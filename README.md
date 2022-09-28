# Ambari-Spark3

# Stop the ambari-server

ambari-server stop

Install the mpack in ambari-server

VERSION=hdp-select status hadoop-client | sed 's/hadoop-client - \([0-9]\.[0-9]\).*/\1/'


git clone https://github.com/support-cloud/Ambari-Spark3.git /var/lib/ambari-server/resources/stacks/HDP/$VERSION/services/SPARK3


ambari-server start
