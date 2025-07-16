```markdown
# Enabling YARN ResourceManager HA

## Steps:
1. Go to **YARN service** in Cloudera Manager.
2. Click **Actions > Enable High Availability**.
3. Select a standby ResourceManager host and click **Continue**.

## Notes:
- JobHistory Server (JHS) is stateless.
- To auto-restart JHS:
  - Go to YARN > Configuration.
  - Scope: **JobHistory Server**
  - Category: **Advanced**
  - Search: **Automatically Restart Process**
  - Edit: Select **JobHistory Server Default Group**
  - Restart the JHS role.
