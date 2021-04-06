## Overview

Comparison of sentiment analysis with Google Cloud Platform's Natural Language API against a self-hosted TensorFlowJS pretrained model in test scenarios revealed that system requirements and available resources should be considered. For example, a system with low peak messaging frequency will see lower costs selecting a self-hosted sentiment model, but scaling up can be a challenge. Preprocessing and queuing strategies must be employed for instances running the model not to get inundated and miss messages. GCP's Natural Language API can easily scale and handle high frequencies of messaging, but costs can also exceed those of a self-hosted sentiment analysis model. 

https://github.com/jmsaylor/discord-bot-sentiment

https://github.com/jmsaylor/discord-sentiment-api

