# JP-Morgan-Software-Engineering-Virtual-Experience
![Images](https://github.com/wangyihong-yvonne/JP-Morgan-Software-Engineering-Virtual-Experience/blob/main/Screen%20Shot%202021-06-10%20at%207.23.33%20PM.png)
## Tasks
1. Set up your system by downloading the necessary repository, files, tools and dependencies.
2. Fix the broken client datafeed script in the repository by making the required adjustments to it.
### Task 1 
We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.
### Task 2 
The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application (see Before and After images below) Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.
### Task 3
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor this trading strategy. Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12 month historical average ratio.
