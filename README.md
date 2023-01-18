# Budget-Tracker
This program is a farily simple budget tracking tool that allows the user to input their monthly income and savings goal, and then add expenses to track where their money is being spent. The program then saves the data in a JSON file, and also generates a bar chart to visually represent the breakdown of expenses. The user can continue to add expenses and the program will update the JSON file and the chart accordingly. This allows the user to keep track of their spending and make adjustments to stay within their budget and reach their savings goal.

The plugins that we utilize are are as follows- <h2>
  
<b>-json<b>
  
<b>-datetime<b>
  
<b>-matplotlib<b>

<h2> Main body<h2>

 ![Screenshot_20230118_020529](https://user-images.githubusercontent.com/112616414/213122673-a1ff76f1-8c79-4fd2-8b2f-87ae5e0af4d6.png)
 
  -Make an empty list so we can prompt the user for income and savings goals then subtracting the savings to give us a budget for the rest of the month <b>
   
  -We then make a while loop to prompt the user for expenses and save it to a function<b>
  
  -Line 20-24 basically says that if you dont input a subcategory then it will leave it blank<b>
 
![Screenshot_20230118_020557](https://user-images.githubusercontent.com/112616414/213126736-e4683bbb-6529-4dc0-883f-bcbcee8972de.png)

  - 27-28 set the date and naming format including date

  - 29-30 set the lists
  
  - We then say that we want a bar graph with the lists we made
  - Then we name the bars in the graph and pick the formatting for the chart
  - 43-44 is saying to open a the .json file and dump all the stored data in it into the program
  - This allows us to come back later with another code to continually add expenses into this file
  
  
<h2> Running the program
  
![Screenshot_20230118_015933](https://user-images.githubusercontent.com/112616414/213130442-ee0ad18b-7a24-44eb-98d2-1ad40bcefc5b.png)

  Go through the prompts
  
  ![Screenshot_20230118_020024](https://user-images.githubusercontent.com/112616414/213130919-fd9dd1d7-a30f-4b4d-9957-16957b48b2a5.png)

![Screenshot_20230118_020229](https://user-images.githubusercontent.com/112616414/213131153-d84023a1-3a30-4d84-a7dc-5d26d967a570.png)
  
  - Once finished, the program will generate a .jason file (which stores the budget and expense information that was inputed)
  
  - It will also generate a .png file which will be the expense chart
  
  ![Screenshot_20230118_020410](https://user-images.githubusercontent.com/112616414/213131316-1f0c2d51-d99a-4dab-af3a-45c36af364ff.png)

![Screenshot_20230118_020439](https://user-images.githubusercontent.com/112616414/213132736-c333077d-e6f4-4784-a799-a3012ed7fe9f.png)
  
  <b> Closing this out, I hope you can understand what is happening with this code and more importantly how it can be used in many different situations. This project opened my eyes to many possibilities with data tracking and input.
    
    
