## Instructions

The goal of this exercise is to create a demo calendar application using React & Redux & Routes. We strongly recommend [create-react-app](https://github.com/facebookincubator/create-react-app) to make the bootstrapping of your application really easy.

### The Task

Your app should render a single month view of a calendar for the current month – along with the lines of the below illustration:

![Calendar Image](https://raw.githubusercontent.com/ansal10/calendar-assignments-react-redux/master/calender-screenshot.png)


### Features & Requirements:

* Ability to add a new “reminder” (max 30 chars) for a user entered day and time.
* Display reminders on the calendar view in the correct time order.
* Allow the user to select a color when creating a reminder and display it appropriately.
* Properly handle overflow when multiple reminders appear on the same date.
* Ability to edit reminders – including changing text, day and time & color.
* Ability to delete reminders.
* Expand the calendar to support more than the current month.
* There should be a Previos and Next button that would render next or previous month
* You have to use Redux compulsory, you can also use redux-thunk/redux-saga if required.
* You have to use Routes to render particular months, or details of a particular event. I should be able to navigate to that particular route with Month & Year, that will render the calender for that month & year, or the event details dependeing upon the route & params.


### Notes:

* The data should be retained across different page views, but it’s not necessary to persist it beyond a browser refresh.
* This is a coding activity and not a design activity. That’s not to say we don’t appreciate good design or that we don’t value those skills if you have them! It’s just that it won’t have a high value when scoring this particular project.

