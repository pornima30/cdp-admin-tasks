# Configuring Hue to Work with HDFS HA

## Steps:
1. Add **HttpFS role** in HDFS:
   - HDFS > Instances > Add Role Instances > HttpFS
   - Select a host, continue, start role
2. Go to **Hue > Configuration**
3. Change `HDFS Web Interface Role` to the new HttpFS role
4. Save changes and restart Hue
