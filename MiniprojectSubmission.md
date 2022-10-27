<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 1 - IceCream</td></tr>
<tr><td> <em>Student: </em> Gayathri Valmiki (gpv)</td></tr>
<tr><td> <em>Generated: </em> 10/25/2022 7:29:12 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-1-icecream/grade/gpv" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216">https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder IcecreamMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197890993-61545c81-dd6a-41cd-b125-d8ba956a93d9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Comment with my UCID and Date<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197890993-61545c81-dd6a-41cd-b125-d8ba956a93d9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Calculated the total cost/proper value of the inprogress_icecream array. <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197891287-32b32687-47f1-412b-bc76-6c1e03ff38b8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The costs are defined as part of the given data and are NOT<br>modified<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197890993-61545c81-dd6a-41cd-b125-d8ba956a93d9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The calculated value is returned from the function<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197891149-a1334dfc-e3fd-4152-bb45-2c0c484e436d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The input() message is properly displaying the value in currency format <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197891436-c38711d9-16ef-4c70-a930-8d2376c8f817.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The output cost showing in currency format (optional screenshot)<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <p><b>1. The total cost </b>is calculated by using <b>for loop </b>and visiting the<br>items that are invoked by the <b>inprogress_icecream array :</b><div><ul><li><b>&nbsp;</b>Inside the for loop ,<br>the expected cost is <b>incremented to n.cost</b>&nbsp;by considering the sum of all the<br>items in the array.</li><li>&nbsp;Then the function is <b>returned</b>&nbsp;to make it print it out<br>to the user .</li><li>&nbsp;While writing the<b> input() message, </b>the &quot;$&quot; symbol is given<br>so as to print the total cost in the <b>currency format</b></li></ul><div><b>2. Currency formatting<br>:</b></div></div><div><ul><li>Currency was handled by inserting <b>&quot;{:.2f}&quot;. format(expectedcost) </b>in the<b> return function </b>so as<br>to make it print in 2 decimal float value and moreover inserted a<br>dollar symbol inside the input() message.</li><li>This made the total cost to print in<br>currency format in the output.</li></ul></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Exception Handling </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of adjusted code to handle exceptions</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197892002-37db2a46-b489-49ba-8675-5389be86c597.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Shows how the OutOfStockException is handled with proper user feedback and continued program<br>flow<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197893389-072d2deb-3c82-40d1-b9c7-1813fcd900a4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Shows how the NeedsCleaningException is handled with proper user feedback and continued program<br>flow <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197893389-072d2deb-3c82-40d1-b9c7-1813fcd900a4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>A new input() process is required by considering continue message and self.reset() function.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197892253-5df82ddd-b9d6-43f6-a5b2-747a70a7eab6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Invalid choice for Container selected : Shows how the various InvalidChoiceExceptions are handled<br>with proper user feedback and continued program flow <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197892789-c749fccc-f0e7-4389-8714-d354437b8611.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Invalid choice for Flavor selected : Shows how the various InvalidChoiceExceptions are handled<br>with proper user feedback and continued program flow <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197892832-28f833ee-9508-4145-a97b-0f623b769bd0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Invalid choice for Toppings selected : Shows how the various InvalidChoiceExceptions are handled<br>with proper user feedback and continued program flow <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197892921-a80ceee5-f026-48c9-a69b-3e1be7c0d5f4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Exceeded flavor limit : Shows how the various ExceededRemainingChoicesExceptions are handled with proper<br>user feedback and continued program flow<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197893005-45846040-f202-473e-b6fa-211aa0e08bec.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Exceeded toppings limit : Shows how the various ExceededRemainingChoicesExceptions are handled with proper<br>user feedback and continued program flow<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197893048-3fd495e5-9022-403f-b877-be3128dcffb8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Shows how the InvalidPaymentException is handled with proper user feedback and continued program<br>flow.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each exception handling process</td></tr>
<tr><td> <em>Response:</em> <ul><li><span style="font-size: 13px;"><b><u>OutOfStockException</u> : </b>This exception is raised when the quantity of any<br>item is less than 0. In this project, the quantity of container is<br>set to 10. And the quantities of flavor and toppings are set seperately<br>in values. Ex : 100. When the <b>self.quantity </b>becomes 0 or less than<br>0, the out of stock exception is raised. The error is handled by<br>using <b>try and except </b>statments where in the error is handled by giving<br>using <b>except </b>as per the above code snippet .</span><br></li><li><span style="font-size: 13px;"><b><u>NeedsCleaningException </u>:&nbsp;</b>This exception<br>is raised when the<b> self.remaning_uses</b> is less than 0.&nbsp;</span>In this project, the number<br>of uses is set 100. When the<span style="font-size: 13px;">&nbsp;<b>USES_UNTIL_CLEANING</b></span><b style="font-size: 13px;">&nbsp;</b><span style="font-size: 13px;">becomes<br>0 or less than 0, the NeedsCleaning exception is raised. The error is<br>handled by using</span><span style="font-size: 13px;">&nbsp;</span><b style="font-size: 13px;">try and except&nbsp;</b><span style="font-size: 13px;">statments where in<br>the error is handled by giving using</span><span style="font-size: 13px;">&nbsp;</span><b style="font-size: 13px;">except&nbsp;</b><span style="font-size: 13px;">as</span><span<br>style="font-size: 13px;">&nbsp;</span><span style="font-size: 13px;">per the above code snippet . A new <b>input() message<br>is given </b>by asking user to whether continue or quit. <b>if continue </b>is<br>selected, the machine will clean successfully and continues operation using <b>self.reset()</b> function.</span></li><li><b style="font-size:<br>13px;"><u>InvalidChoiceException:</u> </b><span style="font-size: 13px;">This exception is raised&nbsp;when the choice selected does not match<br>any of the item. Firstly if there is&nbsp;<b>Invalid choice for Container selected</b></span><b style="font-size:<br>13px;">&nbsp;</b><span style="font-size: 13px;">, the message displays to the user by using except .<br>Same applies for&nbsp;</span><b>Invalid choice for Flavor selected</b><b style="font-size: 13px;">&nbsp;</b><span style="font-size: 13px;">&nbsp;as well as&nbsp;<b>Invalid<br>choice for Toppings selected.</b></span><br></li><li><b style="font-size: 13px;"><u>ExceededRemainingChoicesException </u>: </b><span style="font-size: 13px;">T</span><span style="font-size: 13px; font-weight:<br>400;">his exception is raised</span><span style="font-size: 13px; font-weight: 400;">&nbsp;when the maximum scoops selected are<br>more than 3. That means </span><span style="font-size: 13px;"><b>self.remaining_scoops &lt;0.</b></span><span style="font-size: 13px; font-weight: 400;">Firstly,<br>if there is&nbsp;</span><span style="font-size: 13px;"><b>Exceeded flavor limit&nbsp;</b></span>&nbsp;the message displays to the user by<br>using except. Now the current selection value becomes toppings. Same applies for exceeded<br>limit for <b>toppings.</b>&nbsp;When toppings are exceeded, the exception is handled and printed out<br>to the user and then the current selection will proceed to payment.<br></li><li><b>&nbsp;</b><u style="font-weight:<br>bold;">InvalidPaymentException</u><b> :&nbsp;</b><span style="font-size: 13px;">T</span><span style="font-weight: 400; font-size: 13px;">his exception is raised</span><span style="font-weight: 400;<br>font-size: 13px;">&nbsp;when the </span><span style="font-size: 13px;"><b>total cost != expected cost</b></span><span style="font-weight: 400; font-size:<br>13px;">. This means that the user has entered wrong payment value, which doesn't<br>match the cost calculated. This exception is </span><span style="font-size: 13px;"><b>handled </b>by using except<br>statement. Further ,current status again prints the total cost and asks the user<br>to enter the same exact value.</span><br></li></ul><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197894978-055549c4-2067-43cc-9b26-e795b55152c9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Container is the first selection (can&#39;t add flavors/toppings without a container choice)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895176-e8337e81-55a2-47d8-b94f-c9da8eeb8e84.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Can only add flavors if they&#39;re in stock<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895243-4943476e-cd4e-44cf-9f4c-7c529660f910.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Can only add toppings if they&#39;re in stock<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895307-39a5172a-9d80-435c-aa5f-0492977f6306.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Can add up to 3 flavors/scoops<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895446-a9697fe9-5508-4864-b44b-142daa1f6546.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Can add up to 3 toppings<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895490-dc05768d-ef44-4022-8ca7-5a8c28e54edd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Cost is calculated properly based on the choices . In currency format.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895539-de7ea060-a24a-4d81-b79c-99ff02f0942e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Total Sales (sum of costs) is calculated properly (test case included a few<br>icecream combinations/purchases)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197895736-216a5a62-7dec-4d27-9eb1-ee126ee3e701.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Total icecreams properly incremented for each purchase<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <ul><li><b><u>Test case 1</u></b> : Container will be the first selection. It is done<br>by asserting <b>machine.currently_selecting.name == STAGE.Container.name</b> , here <b>assert() function </b>is used to test<br>the if the condition is true. If it turns out to be true<br>it passes the test.</li><li><b><u>Test case 2</u></b> : Adding flavors only when they're in<br>stock. Flavors are added when the exception of out of stock is <b>false.<br></b>This is done through <b>assert False</b> under except. And in try block ,<br>the quantity is set to 1 , <b>machine.flavors[0].quantity = 1</b>. This test has<br>passed since the out of stock exception turned out to be false when<br>quantity is set to 1.<br></li><li><b><u>Test case 3</u> </b>: Adding toppings only when they're<br>in stock . Toppings are added when the exception of out of stock<br>is&nbsp;<b>false.&nbsp;</b>This is done through&nbsp;<b>assert False</b>&nbsp;under except. And in try block , the quantity<br>is set to 1,&nbsp;&nbsp;<b>machine.toppings[0].quantity = 1</b>. This test has passed since the out<br>of stock exception turned out to be false when quantity is set to<br>1.<br></li><li><b><u>Test case 4</u></b>:&nbsp;Can add up to 3 flavors/scoops. Initially, the container is considered,<br>and when<b> for() loop</b> is considered in range <b>machine.MAX_SCOOPS -1</b>. Inside this loop,<br>there is flavor selected , and then try block is executed to <b>assert</b>&nbsp;<b>machine.remaning_scoops<br>==0. </b>This means that max scoops test has passed when the <b>exception</b> turns<br>out to be <b>false.</b><br></li><li><b><u>Test case 5</u></b>:&nbsp;Can add up to 3 toppings.Initially, the container<br>is considered, and flavor is "next",&nbsp; when<b>&nbsp;for() loop</b>&nbsp;is considered in range&nbsp;<b>machine.MAX_TOPPINGS -1</b>. Inside<br>this loop, there is toppings selected , and then try block is executed<br>to&nbsp;<b>assert</b>&nbsp;<b>machine.remaning_toppings ==0.&nbsp;</b>This means that max toppings test has passed when the&nbsp;<b>exception</b>&nbsp;turns out to<br>be&nbsp;<b>false.</b></li><li><b><u>Test case 6</u></b>: Cost is calculated properly based on the choices . In<br>currency format. Few combinations of purchases are considered and <b>assert machine1.calculated_cost()=='3.75 ', </b>is<br>given. ( 3.75 is given randomnly). And the test has passed .</li><li><b><u>Test case<br>7</u>:</b>&nbsp;Total Sales (sum of costs) is calculated properly (test case should included a<br>few icecream combinations/purchases). Here, first purchase is considered by taking few combinations and<br><b>iceCreamCost1</b> is calculated. Then second purchase is considered and&nbsp;<b>iceCreamCost2</b>&nbsp;is calculated. Finally assert the<br>sum of&nbsp;<b>iceCreamCost1 +&nbsp;</b><b>iceCreamCost2 </b>which increments the total sales.</li><li><b><u>Test case 8</u> </b>:&nbsp;Total icecreams is<br>properly incremented for each purchase. Here, first purchase is considered by taking few<br>combinations and&nbsp;<b>iceCreamCost1</b>&nbsp;is calculated. Then second purchase is considered and&nbsp;<b>iceCreamCost2</b>&nbsp;is calculated. As well as<b><br>iceCreamCost3</b>&nbsp;<b>is </b>defined.Finally assert&nbsp;&nbsp;<b>iceCreamCost1 +&nbsp;</b><b>iceCreamCost2&nbsp;</b>which increments&nbsp;the total icecreams to 2 and also&nbsp;<b>iceCreamCost3 is incremented<br></b>to 3.</li></ul><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Gayathrivalmiki/IS601-007/pull/8">https://github.com/Gayathrivalmiki/IS601-007/pull/8</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <ul><li>I had issues <b>handling exceptions</b> and as well as <b>testcases.</b></li><li>I have handled <b>exceptions</b><br>by using try and catch statements.</li><li>I have learned how to use test cases<br>and apply them as required.</li><li>This project was challenging as test cases were challenging.<br>And using <b>pytest fixtures, </b>which installs pytest and applies for the project ,<br>has really been challenging and advanced by solving test cases .</li><li><b>Icecream machine</b> is<br>quite interesting though! I'm grateful that I have learned certain things while solving<br>the code.</li></ul><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of successful output</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197899660-66138f30-6fcd-47cb-a922-7e08d62f3c9a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Executed : Container -waffle cone is selected by the user.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197899726-6adf6375-5a0f-49f2-9ba8-92a60f1c7dd0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Executed : Flavors : vanilla and chocolate is selected by the user.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197899819-3385deac-aba3-4bbe-aa97-1142b2828b44.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Executed : Toppings : Chocolate chips is selected by the user.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197899903-c72fa2af-272e-41b1-aa1f-77665539c63e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Final cost is calculated and displayed to the user.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197899963-46ca2fe6-2975-4390-9a8b-b69f5f8111dd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Executed sucessfully.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113643423/197900029-f936ef0d-040e-4ab0-8125-db35d53120ae.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Executed IceCreamMachine sucessfully.<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-1-icecream/grade/gpv" target="_blank">Grading</a></td></tr></table>
