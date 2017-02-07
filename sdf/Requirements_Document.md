# Requirements Document

## Table of Contents
- [5.1 Introduction](#51-introduction)
- [5.2 Functional Requirements](#52-functional-requirements)
- [5.3 Performance Requirements](#53-performance-requirements)
- [5.4 Environment Requirements](#54-environment-requirements)

## 5.1 Introduction

_Plutus_ is a Stock Tracking Analysis & Prediction service which is an aid to investment in the stock market. Users have the ability to select stocks they wish to track and _Plutus_ will start to analyze the history it has on those stocks and create a schedule for the user to follow along with predictions of gains with associated probabilities of correctness. As a service, most of the software runs on cloud hosted servers that store stock information and analyze it. The user gets a web interface that interacts with this cloud infrastructure. Currently, the backend is a Node server with a Postgres database. This requirement is pending further exploration of the algorithms necessary for Stock analysis. Users of the _Plutus_ service can be analysts looking for another tool to base their models on. Another user could be just common traders that need aids to their investment strategy.

## 5.2 Functional Requirements

- 5.2.1 The Graphical User Interface _(GUI)_ shall include a stocks list
  - 5.2.1.1 The stocks list shall be searchable
  - 5.2.1.2 The stocks list shall allow you to add the stocks to your watchlist
  - 5.2.1.3 The stocks list may show what stocks have already been added
- 5.2.2 The GUI shall include a watchlist of stocks you are following
  - 5.2.2.1 The watchlist shall be searchable
  - 5.2.2.2 The watchlist shall let you view analysis for a specific stocks
  - 5.2.2.3 The watchlist shall let you go to the stocks list to add more stocks
  - 5.2.2.4 The watchlist may show an overview of each stock
- 5.2.3 The GUI shall include a view for a specific stock
  - 5.2.3.1 The view shall show current status of the stock
  - 5.2.3.2 The view shall show past history of the stock
  - 5.2.3.3 The view shall show future projected Performance
  - 5.2.3.4 The view shall show projected risk level and percentage accuracy of prediction
- 5.2.4 The GUI shall show a schedule for interactions with the market
  - 5.2.4.1 The schedule shall show what action to take on a particular stock _(buy, sell, short, cover)_
  - 5.2.4.2 The schedule shall show the projected result and percentage accuracy
- 5.2.5 The server shall populate the database with up to date data on stocks being tracked
  - 5.2.5.1 This population shall occur regularly in accordance with that stock's market operation's times
- 5.2.6 The server shall perform regular analysis on the stocks to update predictions
  - 5.2.6.1 This analysis shall occur after the stock's market operation's times when data collection is no longer performed
  - 5.2.6.1 This analysis may in future be performed in parallel with data collection if that capability can be done without affecting data collection
- 5.2.7 The server may send notifications of when to perform an action on a stock

## 5.3 Performance Requirements

- 5.3.1 The server shall perform data collection on stocks at least once a minute
- 5.3.2 The server shall complete analysis of a stock before the market for that stock opens back up
- 5.3.3 The GUI shall be responsive and indicate if it requires more time to perform an action

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
| web browser | any modern web browser |

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
| web browser | any modern web browser |
