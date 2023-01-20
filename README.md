# Confluent Kafka Project at Ineuron.ai

This repository contains the implementation of Confluent Kafka, a powerful and scalable streaming platform that we used to process, store, and analyze streams of data in real-time for a big data project at Ineuron.ai as a remote data scientist.

Getting Started <br>
Prerequisites<br>
Python 3.8 or later<br>
Confluent-kafka-python library<br>
[Confluent Platform](https://confluent.cloud)<br>
Installation:<br>
Clone the repository:<br> 
Navigate to the project directory :<br> cd confluent-kafka-implementation <br>

Install the required libraries using pip<br>: pip install -r requirements.txt<br>
Usage<br>
Start the Kafka producer: python producer.py to stream data from Ineuron.ai's datalake<br>
Start the Kafka consumer: python consumer.py to process and analyze the streamed data<br>
Additional Resources<br>
[Confluent Platform documentation](https://confluent.cloud/learn)<br>

Note<br>
Please check the confluent documentation for more information on how to configure and run confluent platform and kafka using python. You will need access to a datalake to run the project.

Contributing<br>
If you would like to contribute to this repository, please submit a pull request with a detailed explanation of your changes.<br>

License<br>
This project is licensed under the MIT License 2.0 - see the LICENSE file for details.
