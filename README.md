## COMMANDS USED 

-->  run command in the base folder of metricbeat .

# to start metricbeat 

metricbeat -e -c <metricbeat config file>

ex.

metricbeat -e -c metricbeat_test.yml


# to find all modules

metricbeat modules list

# to enable module in metricbeat

metricbeat modules enable <modulename>


# to disable module in metricbeat

metricbeat modules disable <modulename>