# pointscollector
An mobile app for training my child

This is a project I am working to create a mobile application to help my child do his daily chores.

Functionality

The app will have the following functionality

It will have two users

1. Normal User
2. Admin User

Normal User is basically my child for whom the app would cater. A normal user will be doing the following task(s)

1. Pick a task from the predefined task(s) created by admin. (Voluntary Action) or An Admin Assigns a task to the user.
2. All the task(s) are time bound and are to be completed within the time frame. On Completion the user can click on the running timer to
lodge the completion of the task.

Admin User is the parent/guardian of the child and is responsible for 
1. Creating the task list along with the time for the task.
2. Alloting points for the task(s).
3. Approving the completed task(s).

The system calculates the points to be alloted for successfull completion of task.

Example
If the admin has created a task 

Task Name - Brush your teeth.
Minimum Time - 3 Mins
Maimum Time - 10 Mins
Grace Time - 1 Min(Default)
Total Points - 10
Bonus Points - 5

If the child has voluntarily picked the task and completed the task in 5 mins then the points awarded would be

Additional Time taken = 5-3 Mins = 2 Mins
Minus Grace Time = 2-1 = 1 Min

Total Extra Time = 1/7 
Points Earned = 10 - (1/7)%10 = 9.5 + (1/7)%5 = 13

The Admin can set the number of points required for an activity.

Example 
200 Points in exchange for 1 hr of Video.

The normal user can exchange his points for this activity. When he exchanges his points he gets a code which he can use for his activity.

The app is to promote learning in a fun way for the child to be responsible.

# Technology Planned

- NativeScript for Mobile Development
- Firebase Cloud Store for Database
- Firebase Cloud Functions for API
