# **Algorithmic Trading using Interactive Brokers’ Python API** 

**[Udemy](https://www.udemy.com/course/algorithmic-trading-using-interactive-brokers-python-api)**

**Mayank Rasu - VP of Quant Research, Barclays Investment Bank**

***Notes by Vishnu Subramanian***

## ***Section 1: Introduction to Interactive Brokers and its API***

### ***1. IBAPI Courses***

- At the end of 2022, Mayank Rasu had 4 courses related to the Interactive Brokers API.
- The correct order for these 4 courses is:
  
1. Algorithmic Trading using Interactive Brokers’ Python API (this one)
2. Advanced Concepts in Algorithmic Trading using Interactive Brokers’ Python API
3. Algorithmic Options Trading on the Interactive Brokers Platform
4. Quantitative Bond Trading on the Interactive Brokers Platform

- The second course - Advanced Concepts with Interactive Brokers, deals with slightly more complex IB API topics, such as the Execution API, the Scanner API, using IB API events to extract data more efficiently, and other such things.
- With some programming background and after completing the first two courses, we should be able to build fairly complex trading applications using Interactive Brokers API tools.
- There are also some product-specific courses - for ex: the course on Algorithmic Options Trading deals exclusively on how to implement derivative-based strategies, particularly Options, on the IB platform.
- Finally, there’s one more product-specific course called Quantitative Bond Trading on the IB platform, where we use IB API algo trading tools on the arcane world of bond trading.
- Bond trading has traditionally been run very conventionally with a lot of manual intervention.
- But things are beginning to change and IB has a decent platform to automate a lot of bond-trading strategies.
- So depending on where we are in our IB API learning curve, which specific product we’re interested in, one of these 4 courses may be a good fit.
- Interactive Brokers actually has a number of API-based applications, and all the courses so far are on the Trader Workstation (TWS). 
- TWS is IBKR’s proprietary, open-source API, which has been there for a long time, and hence has an exhaustive documentation and a large number of users.
- However, there may soon be a course on the Client Portal API from IBKR as well, which is the new, upcoming API technology provided by IBKR.
- The best thing about the Client Portal API is that it’s based on the REST API, which is much easier to work with and navigate.
- However, at the end of 2022, there were still a number of loose ends with the documentation of the Client Portal API that IBKR needed to address before it was suitable to move trading applications from TWS to Client Portal.

### ***2. IB TWS Introduction***

- 
