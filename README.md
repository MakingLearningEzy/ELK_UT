#### please read this first #####

This branch contains all below configuration files used during logstash mutate filter demo.


logstash_test_mutation.yml  -*->  use in your logstash and start logstash with this config file .

filebeat_test.yml   -*-> use in your filebeat and start filebeat with this config file .

log.log --> this is sample log which you can also use but it is optional .




######  commands used  ######

# to start logstash

logstash.bat -f D:\microservices_project\kibana_setup\6.8\logstash\logstash-6.8.0_book\config\logstash_test_mutation.yml

# to start filebeat

filebeat.exe -e -c filebeat_test.yml

