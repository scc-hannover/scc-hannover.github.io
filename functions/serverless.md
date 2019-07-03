---
author: Patrick Geschinski
title: Serverless
date: Juli 02, 2019
---

## Serverless ein Überblick

## Evolution

![Microservice Evolution](https://cdn-images-1.medium.com/max/2042/1*VD9n01kVn4hqOhyzY9X41w.png)

<sub><sup>*Bild Quelle: https://serverless.zone/abstracting-the-back-end-with-faas-e5e80e837362</sup></sub>


## Vorteile Serverless

- Skalierung

- Schnelle Bereitstellung der Funktion (Sekunden)

- Pay per Use

- Konzentration auf den eigentlichen Business Value

## Nachteile

- Vendor Lock-in

- hohe Komplexität bei sehr vielen Funktionen

## Use Cases - Web Events

- Backend services (Formulare verarbeiten, In die Datenbank schreiben, Externe APIs abfragen)

- Digitale-Assistenten Services (Google Home, Alexa skills)

- Automatisierung in CI/CD Pipelines

- Data Processing

## Use Cases - Event Based

- Event-basierte Integration (Web Request, Neue Datei wurde abgelegt, Neue Exception ist aufgetreten)

- Datei Verarbeitung (Bilder und Videos)

- Verarbeiten von komplexen Events (Monitoring, notifications und alerting)

## Provider

- AWS Lambda
- Google Cloud Functions
- Microsoft Functions
- IBM Openwhisk
- KNative

## Herausforderungen

- Kaltstart
- Authentifizierung
- Integrations Tests
- Function Discovery

## Architektur

![Api Gateway](functions.png)

<sub><sup>*Bild Quelle: https://softwareengineeringdaily.com/2016/08/23/serverless-architecture-with-mike-roberts//sup></sub>

## Api Gateway

- Vereinheitlichter API Zugang für Microservices

- DDoS Schutz und Throttling von Anfragen

- Authentifizierung und Autorisierung

- Pay per Use Geschäftsmodelle

## serverless cli

- abstrahiert das Deployment von Funktionen für aws lambda, azure functions, open whisk, google functions usw.


## serverless installieren

- https://serverless.com/framework/docs/getting-started/

- https://serverless.com/framework/docs/providers/aws/guide/quick-start/
 
- https://serverless.com/framework/docs/providers/aws/events/apigateway/


## links

- https://martinfowler.com/articles/serverless.html
 
- https://itnext.io/build-a-restful-api-using-aws-lambda-api-gateway-dynamodb-and-the-serverless-framework-30fc68e08a42

- https://aws.amazon.com/de/serverless/sam/
