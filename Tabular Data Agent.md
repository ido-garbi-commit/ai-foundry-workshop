# Gather Insights from Tabular Data
You are given a task - create an agent that can get tabular data and come up with answers based on that data. 
Since we always try to narrow the task, let's focus the agent on analyzing on one task. 
You can use any table with data that you would like, and I also provided here some CSV tables with financial data - table with profit and loss data, and a table with financial report. 

# Those are the things to accomplish
* Create an agent that enables you to ask questions about the data in the tables you chose. For example - asking "what is the overall profit" andd get an answer. 
* Then, tune the agent so you will be able to ask questions that require iterating over multiple tables. For example - "is the company financially healthy". 
You will encounter various issues—one of them will be that the model "stops". 
* Then, make the agent return a consistent output that can be used. 
* Then, handle a situation where the user hasn't uploaded anything. 