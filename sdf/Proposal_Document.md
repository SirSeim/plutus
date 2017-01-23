# 3.0 Proposal Document & Slides

## 3.1 Verbal Description

_Plutus_ is a Stock Tracking Analysis & Prediction service which is an aid to investment in the stock market. Users have the ability to select stocks they wish to track and _Plutus_ will start to analyze the history it has on those stocks and create a schedule for the user to follow along with predictions of gains with associated probabilities of correctness. As a service, most of the software runs on cloud hosted servers that store stock information and analyze it. The user gets a web interface that interacts with this cloud infrastructure. Currently, the backend is a Node server with a Postgres database. This requirement is pending further exploration of the algorithms necessary for Stock analysis. Users of the _Plutus_ service can be analysts looking for another tool to base their models on. Another user could be just common traders that need aids to their investment strategy.

## 3.2 Justification

As this is a data driven anaylsis service, knowledge of data structures and algorithms is crucial. Databases services to help the creation of an efficient database system geared toward the data driven analysis. Operating Systems helps with server architecture, networking techniques, and concurrency. This also builds on my 401 project, _SPY_, as this project follows a similar server architecture, but with a lot of focus on the data driven analysis which _SPY_ lacked. With this, there is an appropriate amount of difficulty, because most of the effort of this project is on the anaylsis algorithm, and less so on the repeated tasks like creating the backend and database architecture. Assuming no major road blocks occur on the anaylsis algorithm, this project should be well within the purview of one semester. 
