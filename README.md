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

- Interactive Brokers is the undisputed leader in providing discount brokerage services to traders around the world.
- If you’re a rookie trader, looking to graduate to serious trading / investing, IB is a good choice because it tends to be the broker of choice for day traders, small firms and some serious traders, so you’ll be in good company.
- IB lets you trade in a variety of products across a variety of markets.
- To open an account on Interactive Brokers, you can either open a local account or a global account - these two accounts need to be opened separately, and you cannot move money between them.
- Everything is different for these two accounts, such as the Funding and the Accounting.
- So both these accounts will need to be opened separately, but you will be able to see them both tagged to your name.
- The Global Account lets, for example, someone sitting in Asia, trade across different markets like the US market, the UK market, and other European and Asian markets.
- In terms of the Trading Platforms offered by IB, you will need to get the Desktop TWS tool - that is required to implement API strategies.
- When we discuss the API infrastructure of Interactive Brokers, it will become apparent why downloading the Desktop AWS tool is important.
- But to implement an API-based solution, one more thing we will need to download is the IBKR API.
- TWS can be downloaded for macOS directly on the page - the stable, time-tested version is recommended, but for macOS there’s a warning that there may be stability issues on Monterey and higher versions (not shown in the pic below).

<img src="https://drive.google.com/uc?export=view&id=1q1XkkexHLeV8-sVnDLm2QMdkeot6to9g">

- We will also need to download the API software for macOS in a similar manner, by going to the [TWS API page](https://interactivebrokers.github.io/), and installing the stable version for macOS.

<img src="https://drive.google.com/uc?export=view&id=1PRy_6j0KIG1TC7lDU28m0Dv21ZwuaMPP">

