# Software Development Plan

## Table of Contents
- [4.1 Introduction](#41-introduction)
- [4.2 Project Resources](#42-project-resources)
- [4.3 Project Organization](#43-project-organization)
- [4.4 Project Schedule](#44-project-schedule)

## 4.1 Introduction

This Software Development Plan provides details about the development planned for the _Plutus_ service. _Plutus_ analyzes the history of stocks and then uses the analysis to predict possible future values of the stock.

### 4.1.1 Project Deliverables
- Server & Database setup **DUE**:
  - This is the foundation of what is needed to build this application
  - On top of this base needs to be client pages and code as well as business logic for handling data and passing along analysis and predictions
- Data Collection and Visualization **DUE**:
  - This is the base functionality of the application, to store and visualize current stock Data
  - Data collection occurs by querying openly facing API's for stock data and storing it in our own database for analysis
  - Visualization will be done in D3 and allow for future addition of predictive model overlay
- Hookup to analytics **DUE**:
  - Stored stock data needs to be periodically sent to _AWS's Machine Learning library_ to update its model for the stock
  - Service needs to query _AWS's Machine Learning library_ for predictions on futures of a stock

## 4.2 Project Resources

### 4.2.1 Hardware Resources
#### Development Machine
An Apple laptop is to be used for development of the service with the following attributes:
- MacBook Pro (15-inch, 2016)
- 2.9 GHz Intel Core i7
- 16 GB RAM

#### Online Application Host
Development of the user-facing features of the service will be done for a web application.
- HTML 5 Support
- Chrome, Safari, Firefox

### 4.2.2 Software Resources
| Use | Program |
| -- | -- |
| Text Editor | [Atom v1.16.0](https://atom.io) |
| Executor | [Node v7.7.3](https://nodejs.org/en/) |
| Version Control | git v2.11.0 |
| Version Control | [GitHub](https://github.com) |
| Server Framework | [Hapi](https://hapijs.com) |
| Database | [PostgreSQL](https://www.postgresql.org) |
| Analysis | [AWS Machine Learning](https://aws.amazon.com/machine-learning/) |
| Visualization | [D3](https://d3js.org) |

## 4.3 Project Organization

## 4.4 Project Schedule

### 4.4.3 Class Schedule
- Class Meets Mondays `4:20` - `7:20` in the Keck Lab
- [Full schedule here](http://myweb.lmu.edu/bjohnson/cmsi402web2/classnotes.html)
