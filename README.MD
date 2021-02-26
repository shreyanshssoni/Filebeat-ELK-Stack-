This is the Demo of FileBeat to get the stream of .log from log files and docker logs and forward it to the Logstash and after into the Elasticsearch for storing.
In filebeat there is a filebeat.yml file for changing the input,output source and any other source.
If you will get the ILM POLIY error in elasticsearch please refer the seconf filebeat.yml file.

Steps:
1)Select the path for input
2)Selectc the output for logstash or elasticsearch and their port numbers
3)Change es template if needed.
4)For run apply comman from filebeat directory:   ./filebeat
