## Discord Sentiment Analysis Microservices Project

## Motivation 

Monitoring of AI sentiment scores of multiple messaging channels in a server.

## Overview

This project is in the process of being shifted to a microservices architecture. Initially, GCP Language API was used, but message volumes made that approach costly. Testing of TensorflowJS quickly revealed a queue would be needed so as to not overwhelm instances. The new Microservices design is aimed at creating a performant sentiment analysis system using TensorflowJS.

## Tech Stack

DiscordJS
TensorflowJS and/or Google Language API
Express
MongoDB

![Microservices Architecture Map](https://imgur.com/lgicwU5.png)

# Discord Bot

https://github.com/jmsaylor/discord-bot-sentiment

# Backend Gateway

# Frontend Gateway

# Search

https://github.com/jmsaylor/discord-sentiment-api

# Database

# Queue

