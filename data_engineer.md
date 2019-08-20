# Data Engineer Assignment

The goal of this test is to evaluate your ability to:

- Design a simple but reliable crawler
- Process data and compute metrics
- Build a JSON API delivering these metrics

## 🗒 Instructions

You need to build an app that computes the number of monthly new contributors for each [Facebook's public repositories](https://github.com/facebook), from the month of their creation until now.
A new contributor is someone who did a commit for the first time in a repository.

To ease our review, you also need to build a web server that provides a JSON API delivering the metrics you computed.

You can access the GitHub API using your personal account. There are many ways to retrieve the needed data, choose the most simple one, you do not need to handle more than what is required for the app.

### 🖥 Backend

Build a **straightforward** crawler able to fetch data from GitHub API in a reliable and efficient way. The crawler needs to handle API errors and rate limit so that API calls are retried properly. Parallelize the work when it's possible.

The crawler needs to produce a dataset like this:

[Copy of Untitled](https://www.notion.so/56a6ba6075414bb1934936a0a56faa22)

You can use any technology for this as long as it's reliable, fault tolerant, efficient and scalable.
Imagine you are building Aircall new data platform, do not use hacky solutions. Don't design the solution as a Backend Engineer but as a Data Engineer

The subject is just a pretext to a future discussion during the debriefing.

### 📱 API

Build a simple web server that provide a JSON API delivering the results you previously stored. You are free to design the API the way you want.

## 🖊 Evaluation Criteria

Please push your code to a public or private repository on GitHub and give access to:

- [kmatrah](https://github.com/kmatrah/)
- [flomarin88](https://github.com/flomarin88)

We'll evaluate:

- the usage of the GitHub API,
- the code quality of your crawler and API and engineering practices,
- the developer experience, ease of running and documentation.
- Data Architecture, even more Infra
- Data Modeling

If feasible, make sure that you put the instructions on how to preview your application and run it. So that we can easily see the result.

When finished, we will planned together a quick presentation by Hangout or in our offices to review your work and talk about design and code.

## 🆒 Bonus points

We welcome any feature or addition to your project that you think
makes it better and gives you more chances.

Things like tests, tooling and attention to detail are much appreciated but not mandatory.

## 🤔 Questions

You can ask any questions by sending an email to [florian@aircall.io](mailto:florian@aircall.io) and [karim@aircall.io](mailto:karim@aircall.io) or by creating issues on the repo you use.

🙋‍♀️ Good luck!