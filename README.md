# integrate-wifi-module-ESP8266-with-Ardunio-and-tempreture-sensor-and-receive-the-data-over-channel
collect data using tempreture sensor and represent the data on ThingSpeak channel .

////IMPORTANT LINE OF THE CODE WHERE YOU SHOULD MAKE CHANGE TO TRANSFER THE DATA TO YOUR CHANNEL BY WRITTING YOUR WRITE API KEY/////////

String uri = "/update?api_key=4QPOEQPENOZDVTST&field1=";

	URI: It stands for Universal Resource Identifier. This Universal identifier allows to access the object available using the potocols.

API KEY:Api key is of two types WRITE API and READ API.

WRITE API key: this key is used when we want to write data to a channel.

READ API key: this key allow other people to view your private channel feeds and charts.

Field 1: Since in this program we use WRITE API KEY so, here by using Field1 we specifies that we are going to write the data on field1 of our channel
