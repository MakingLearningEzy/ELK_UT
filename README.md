## COMMANDS USED

# to start filebeat

filebeat.exe -e -c <FILEBEAT_CONFIG_FILE>

ex.

filebeat.exe -e -c filebeat_test_csv.yml


# to start logstash

logstash.bat -f <LOGSTASH_CONFIG_FILE>

ex.

logstash.bat -f D:\microservices_project\kibana_setup\6.8\logstash\logstash-6.8.0_book\config\logstash_send_s3.yml
