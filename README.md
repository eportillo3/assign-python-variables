<h1>Assign Python variables</h1>

<h2>Introduction</h2>

Variables help security analysts to keep track of a variety of security-related information. For example, analysts may need to create Python variables for the users who are allowed to log in, the number of login attempts that they're permitted, and the current number of attempts that a user has made.

In this lab, you'll practice assigning values to variables and determining their data types.

<h2>Scenario</h2>

You are a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, you'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, you'll assign these variables and check the data types of the variables.

<h3>Task 1</h3>

In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is `"72e08x0"`.

In the following code cell, assign this value to a variable named `device_id`. Then, display the contents of the variable and observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

<img src="https://i.imgur.com/1704WXm.png" height="80%" width="80%"/>

<h3>Task 2</h3>

Now that the variable device_id is defined, you can return its data type.

In this task, use a Python function to find the data type of the variable device_id. Store the data type in another variable called device_id_type. Then, display device_id_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/cj02m4c.png" height="80%" width="80%"/>

<h3>Task 3</h3>

As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are "madebowa", "jnguyen", "tbecker", "nhersh", and "redwards".

In this task, create a variable called username_list. Assign a list with the approved usernames to this variable. Then, display the value of the username_list variable.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/1X185cy.png" height="80%" width="80%"/>

<h3>Task 4</h3>

In this task, find the data type of the username_list. Store the type in a variable called username_list_type. Then, display username_list_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/2yUr26O.png" height="80%" width="80%"/>

<h3>Task 5</h3>

Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: "madebowa", "jnguyen", "tbecker", "nhersh", "redwards", and "lpope".

In this task, reassign the variable username_list to the new list. Run the code to display the list before and after it's been updated to observe the difference.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/liTHzU9.png" height="80%" width="80%"/>

<h3>Task 6</h3>

In this task, define a variable called max_logins that represents the maximum number of login attempts allowed per user. Store the value 3 in this variable. Then, store its data type in another variable called max_logins_type. Display max_logins_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/5Ovh6XJ.png" height="80%" width="80%"/>

<h3>Task 7</h3>

In this task, define a variable called login_attempts that represents the current number of login attempts made by a user. Store the value 2 in this variable. Then, store its data type in a variable called login_attempts_type. Display login_attempts_type to observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/IkV1BIc.png" height="80%" width="80%"/>

<h3>Task 8</h3>

In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/jILm6Xo.png" height="80%" width="80%"/>

<h3>Task 9</h3>

This code continues to check for the Boolean value of whether max_logins is less than or equal to login_attempts. In this task, reassign other values to login_attempts. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/BjaW7cQ.png" height="80%" width="80%"/>

<h3>Task 10</h3>

Finally, you can also assign a Boolean value of True or False to a variable.

In this task, you'll create a variable called login_status, which is a Boolean that represents whether a user is logged in. Assign False to this variable and store its data type in a variable called login_status_type and display it.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

<img src="https://i.imgur.com/mY4tF6g.png" height="80%" width="80%"/>
