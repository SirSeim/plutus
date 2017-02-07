# Requirements Document

## Table of Contents
- [5.1 Introduction](#51-introduction)
- [5.2 Functional Requirements](#52-functional-requirements)
- [5.3 Performance Requirements](#53-performance-requirements)
- [5.4 Environment Requirements](#54-environment-requirements)

## 5.1 Introduction

_Plutus_ is a Stock Tracking Analysis & Prediction service which is an aid to investment in the stock market. Users have the ability to select stocks they wish to track and _Plutus_ will start to analyze the history it has on those stocks and create a schedule for the user to follow along with predictions of gains with associated probabilities of correctness. As a service, most of the software runs on cloud hosted servers that store stock information and analyze it. The user gets a web interface that interacts with this cloud infrastructure. Currently, the backend is a Node server with a Postgres database. This requirement is pending further exploration of the algorithms necessary for Stock analysis. Users of the _Plutus_ service can be analysts looking for another tool to base their models on. Another user could be just common traders that need aids to their investment strategy.

## 5.2 Functional Requirements

## 5.3 Performance Requirements

## 5.4 Environment Requirements

#### 5.4.1 Development Environment Requirements

The following hardware is required for development:

| Category | Requirement |
| --- | --- |
| Processor | relatively recent |
| Hard Drive Space | 5 GB starting |
| RAM | 4 GB for efficient performance |
| Display | must have a display |
| Sound Card | optional |

The following software is required for development:

| Category | Requirement |
| --- | --- |
| Operating System | macOS |
| Text Editor | Atom |
| Run Server | Node |
| Test Database | PostgreSQL |
| Graphics | Adobe Illustrator |

#### 5.4.2 Execution Environment  Requirements

The following hardware is required for execution for the server:

| Category | Requirement |
| --- | --- |
| Processor | relatively recent |
| Hard Drive Space | 5 GB starting |
| RAM | 4 GB for efficient performance |
| Display | optional |
| Sound Card | optional |

The following software is required for execution for the server:

| Category | Requirement |
| --- | --- |
| Operating System | macOS _or_ Linux |
| Run Server | Node |
| Database | PostgreSQL

The following hardware is required for execution for the client:

| Category | Requirement |
| --- | --- |
| Processor | relatively recent |
| Hard Drive Space | none required for online website |
| RAM | sufficient RAM for a web browser |
| Display | must have a display |
| Sound Card | optional |

The following software is required for execution for the client:

| Category | Requirement |
| --- | --- |
| web browser | any |
