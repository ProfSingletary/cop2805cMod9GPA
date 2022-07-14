COP2805C Module 5 Programming Assignment

Write a JSP application that prompts the user to enter a capital for a state, as shown in the figure below. Upon receiving the user input, the program should report whether the answer is correct and provide a Next button to display another question. A 2D array is provided below to copy and paste in your Java code; you should create a list from the array and apply the Shuffle method to reorder the list so the questions appear in random order.

Create two JSP scripts and an associated Java class; one script handles the question and provides the text input field, the other script displays the result and provides the Next button (hint: look at the DisplayTime application in the module source code repo and note how the DisplayTime.jsp file content is called from the index.jsp file). Use the Collections.shuffle method to randomize the order of states when the questions are displayed to the user for the first time (e.g. put the  call to  shuffle in your constructor)..

```
String[][] statecapital = {
	{"Alabama", "Montgomery"}, {"Alaska", "Juneau"},
	{"Arizona", "Phoenix"}, {"Arkansas", "Little Rock"}, 
	{"California", "Sacramento"}, {"Colorado", "Denver"}, 
	{"Connecticut", "Hartford"}, {"Delaware", "Dover"}, 
	{"Florida", "Tallahassee"}, {"Georgia", "Atlanta"}, 
	{"Hawaii", "Honolulu"}, {"Idaho", "Boise"}, 
	{"Illinois", "Springfield"}, {"Maryland", "Annapolis"}, 
	{"Minnesota", "Saint Paul"}, {"Iowa", "Des Moines"}, 
	{"Maine", "Augusta"}, {"Kentucky", "Frankfort"}, 
	{"Indiana", "Indianapolis"}, {"Kansas", "Topeka"}, 
	{"Louisiana", "Baton Rouge"}, {"Oregon", "Salem"}, 
	{"Oklahoma", "Oklahoma City"}, {"Ohio", "Columbus"}, 
	{"North Dakota", "Bismark"}, {"New York", "Albany"}, 
	{"New Mexico", "Santa Fe"}, {"New Jersey", "Trenton"}, 
	{"New Hampshire", "Concord"}, {"Nevada", "Carson City"}, 
	{"Nebraska", "Lincoln"}, {"Montana", "Helena"},    
	{"Missouri", "Jefferson City"}, {"Mississippi", "Jackson"},    
	{"Massachusettes", "Boston"}, {"Michigan", "Lansing"}, 
	{"Pennslyvania", "Harrisburg"}, {"Rhode Island", "Providence"},
	{"North Carolina", "Raleigh"}, {"South Carolina", "Columbia"}, 
	{"South Dakota", "Pierre"}, {"Tennessee", "Nashville"},    
	{"Texas", "Austin"}, {"Utah", "Salt Lake City"}, 
	{"Vermont", "Montpelier"}, {"Virginia", "Richmond"}, 
	{"Washington", "Olympia"}, {"West Virginia", "Charleston"}, 
	{"Wisconsin", "Madison"}, {"Wyoming", "Cheyenne"}};
```

![](/images/jsp1.JPG)
![](/images/jsp2.JPG)
![](/images/jsp3.JPG)