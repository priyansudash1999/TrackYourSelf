# Making PRD of To-do app

> App name:- **TrackYourSelf**

## Objective

The purpose of this app is to help you track everything you aim to accomplish throughout the day, from the moment you wake up to the time you go to bed. The app is designed to focus solely on planning for the next day, keeping things simple and efficient. You can add tasks, edit them, delete them, or update their status by marking them as completed or uncompleted.

## Scope

- Build its Design with Figma
- Frontend with React for now

## Features

### P1(Necessary)

- To complete the task of waking up before sunrise, users must upload a photo of the sunrise with the time and date clearly visible in the image.
- For the goal of walking 10,000 steps in a day, users are required to upload a screenshot of their step counter app showing 10,000 steps, along with the date.
- If users want to write a blog, they must submit the blog URL in our app to mark the task as completed.
- Users can also specify the time frame during which they plan to complete a task. A reminder will be sent 3 minutes before the scheduled start time to help them stay on track.
- Our app functions like a digital well-being tracker, helping users monitor their daily habits.
- Before midnight, you can review how much time was spent on distractions versus productive activities.

> These advanced features are available exclusively for premium members.
> Free members can manage their tasks by marking them as completed or uncompleted.

### P2(Preferred)

Our default tasks include:

- Waking up early between 5:00 AM and 6:00 AM.
- Learning a new skill every day.
- Spending 1 hour on daily exercise (e.g., swimming, running, gym, pranayama, or yoga).
- Sitting for 15 minutes for meditation.
- Walking for 30 minutes in nature (either at sunrise or just before sunset).
- Reading 10 pages of a book daily.

It is up to the user to decide whether they want to add these tasks to their personal list.

> This is my personal to-do preference. However, if others find it useful, they are welcome to adapt and add these tasks to their own list.

## User Stories and Use cases

- As a user, I want to be able to add tasks to my to-do list.
- As a user, I want to be able to edit,delete, and update tasks in my to-do list.
- As a user, I want to be able to mark tasks as completed or uncompleted.
- As a user, I want to be able to set reminders for tasks.
- As a user, I want to be able to view the tasks in my to-do list.
- As a user, I want to view the total tasks in my to-do list as a widget on my home screen.(For mobile apps only)
- As a user, I want to be able to filter tasks based on their status.
- As a user, I want to be able to search for tasks in my to-do list by name or description.

## Technical Requirements

- Use Figma for design
- Use React for web app
- Use Python as backend

## Design Requirements

### Sign-up page

When user open the app for the first time he has to signup to create his account.

- User can signup using email and password.
- User can signup using phone number and password.
- User can signup using google.
- User can signup using linkedin.

### Login page

- A motivational line displays before login that is Are you happy with your bank balance ?
- User can login using email and password.
- User can login using phone number and password.
- User can login using google.
- User can login using linkedin.

### Home page

#### Header

- User can see the name of the user in the header.
- User can see the number of tasks in the header.
- User can see the searchbar in the header.
- User can see the logout button in the header.

#### Body

- User can see the list of tasks in the body.
- An add button in the body to add a new task.
- At right side of every task there is a edit and delete button.
- At left side of every task there is a checkbar box for marking completed or uncompleted.
- User can see total number of uncompleted task out of total number of tasks in the body.
- User can delete all todos at a time by clicking on delete all button.
- User can mark all todos completed at a time by clicking on mark all completed button.(for basic users only)
- When the user clicks on "New Task," a form pops up containing a date field, a time frame selector, and an input field to create a new task.
- When the user clicks on "Edit Task," the same form pops up, but instead of the "Add" button, an "Update" button is displayed.
- There is also a section for default tasks. If the user wants to add a default task, they can click on it, and the same form pops up. This form is pre-filled with the date, but users can apply their own time frame, and input values from the selected default task, allowing the user to either keep or modify these values before adding the task.

#### Footer

- User can see the privacy policy link in the footer.
- User can see the terms and conditions link in the footer.
- User can see the contact us link in the footer.

## Success Metrics

- A user can add more than 20 tasks in a week.
- More than 1000+ basic users
- More than 20+ premium users.

## Timeline

| Works                 |     Timeline     |
| :-------------------- | :--------------: |
| Requirement Gathering |     1st week     |
| Figma design          |   2nd-4th week   |
| Frontend Design       |  5th - 7th week  |
| Backend Design        | 8th - 10th week  |
| Testing               | 11th - 12th week |
| If errors             | 13th - 14th week |
| Deployment            | 15th - 16th week |
| Launch                |    17th week     |
