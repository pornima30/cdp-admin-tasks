# HiveServer2 Fix

## Problem:
HiveServer2 fails due to default Tez session initialization.

## Solution:
- Go to **Hive on Tez**
- Edit `hive-site.xml`:
  ```xml
  <property>
    <name>hive.server2.tez.initialize.default.sessions</name>
    <value>false</value>
  </property>
