# Please read this first *******

# what we need to create the application 

folder location where CSV will arrive .

filebeat software -> 6.8 , i am  using 

logstash ->  6.8 , i am  using

elastic search ->  6.8 , i am  using

kibana -> 6.8 , i am  using


# NOTE
files and command having paths from my local system so when you use in your system please update paths to your local path .


# ELK Application data flow 

CSV Files --> filebeat --> logstash --> elastic search --> Kibana

# config details 

This branch contains all below configuration files used during demo of CSV data loading to elastic .

logstash_test_csv.yml  -*->  use in your logstash and start logstash with this config file .

filebeat_test_csv.yml   -*-> use in your filebeat and start filebeat with this config file .

test.csv --> this is sample csv data .


#  COMMANDS USED

>> to start logstash

logstash.bat -f D:\microservices_project\kibana_setup\6.8\logstash\logstash-6.8.0_book\config\logstash_test_csv.yml

>> to start filebeat

filebeat.exe -e -c filebeat_test_csv.yml

to start elastic search

>> elasticsearch.bat

to start kibana

>> kibana.bat


