# Upgrading Hive Metastore for HDFS HA

## Steps:
1. Go to **Hive service**
2. Stop the Hive service
   - (Optional) Stop Hue, Oozie, Impala first
3. Backup Hive Metastore DB
4. Click **Actions > Update Hive Metastore NameNodes**
5. Start Hive service
6. Restart any dependent services (Hue, Oozie, Impala)
