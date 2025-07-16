# Enabling HDFS High Availability

## Steps:
1. Go to **HDFS service** > **Actions > Enable HA**
2. Enter or accept nameservice (e.g., `nameservice1`)
3. Select:
   - Active & Standby NameNode hosts
   - 3 JournalNode hosts (odd number for quorum)
4. Provide JournalNode Edits Directory paths (must be empty).
5. Cloudera Manager handles:
   - Role updates
   - Directory creation
   - Failover setup
   - Restart of services

## Recommendation:
- Place JournalNodes on similar hardware.
- One JournalNode each on Active, Standby, and another strong node.
