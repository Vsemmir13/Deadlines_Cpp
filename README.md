# Deadlines_Cpp (Joint Deadline Tracker)

## Idea
There's a lot of deadlines and it isn't always easy to keep track of them, so I suggest to make an application that will help the user to not miss the deadline. This tracker will be unique in the way that it will be possible to set deadlines for a group of users. That is, you will be able to select a group of users and set the deadline for every single one of them with their consent. The project will be implemented via a Telegram bot. 

## Features:
1. Creating deadlines: The user can create new tasks and set deadlines for them. For each deadline, you can specify the name, description, completion date. The creator will also be able to set the deadline for other users. 
2. Notifications for each deadline: The user can select several dates on which the application will notify the user about how much time is left before the deadline. 
3. Displaying a list of all deadlines.
4. Tags and priorities: the ability to add priorities and tags to tasks so that deadlines can be filtered and sorted.
5. Beautiful interface.

## Realization:
1. The main language in which the project is written is C++. It is also possible to use the Python language.
2. The user interface will include the following features: creating a new deadline, changing the deadline, displaying the deadline list and completing the deadline.
3. The user can share the deadline with other bot users. To do this, the user will need to specify the list of users with whom the deadline will be shared.
4. The user can set a priority for each deadline on a scale of 1 to 10. If the priority is not set, the deadline will be displayed in the list called "General".
5. The user can receive a notification from the bot when the deadline is overdue or approaching. These deadlines can either be extended or completed.
