# Budget-Tracker
This program is a farily simple budget tracking tool that allows the user to input their monthly income and savings goal, and then add expenses to track where their money is being spent. The program then saves the data in a JSON file, and also generates a bar chart to visually represent the breakdown of expenses. The user can continue to add expenses and the program will update the JSON file and the chart accordingly. This allows the user to keep track of their spending and make adjustments to stay within their budget and reach their savings goal.

The plugins that we utilize are are as follows- <h2>
  
<b>-json<b>
  
<b>-datetime<b>
  
<b>-matplotlib<b>

<h2> Main body<h2>

 ![Screenshot_20230118_020529](https://user-images.githubusercontent.com/112616414/213122673-a1ff76f1-8c79-4fd2-8b2f-87ae5e0af4d6.png)
 
<-b> -Make an empty list so we can prompt the user for income and savings goals then subtracting the savings to give us a budget for the rest of the month <b>

<-b> -We then make a while loop to prompt the user for expenses and save it to a function<b>
  
<-b> -Line 20-24 basically says that if you dont input a subcategory then it will leave it blank<b>
 
