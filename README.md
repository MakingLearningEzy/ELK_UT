# read this 

Grok Filter in logstash

to parse the unstructureed data like text ,log etc . 
grok filter uses GROK pattern to do the parsing .


data flow 

log file --> filebeat --> logstash --> console


#  COMMANDS USED

>> to start filebeat

filebeat.exe -e -c FILEBEAT_CONFIG_FILE

for mine

filebeat.exe -e -c filebeat_test_grok.yml

>> to start logstash

logstash.bat -f _LOGSTASH_CONFIG_FILE

for mine -

logstash.bat -f D:\microservices_project\kibana_setup\6.8\logstash\logstash-6.8.0_book\config\logstash_test_mutation.yml


