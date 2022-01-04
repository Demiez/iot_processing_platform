# IoT Processing Platform

## Project Scope

Project includes microservices for IoT Processing that process decomposition into connectors (sensor and publishers) and variables, which form signalSource recieved on one functional part of the platform devices (sensors) and transmitted to targetDestinations (publishers) on other functional parts of the system.<br> 

## Main microservices

Core functionality of the project is formed by services:
- IoT Connection Manager
- IoT DataSource Manager
- IoT Orchestrator

## Protocols

Communication between services is planned in following protocols:
- http
- amqp/mqtt