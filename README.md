# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Task 4.1
## Feature 1: Filter Events By City
## Feature 2: Show/Hide Event Details
## Feature 3: Specify Number of Events
## Feature 4: Use the App When Offline
## Feature 5: Add an App Shortcut to the Home Screen
## Feature 6: Display Charts Visualizing Event Details
</br>
Feature 1 Scenario: User can select a city from the suggested list.
•
Given user was typing a city in the city textbox AND the list of suggested cities is showing;
•
When the user selects a city from the list;
•
Then their city should be changed to that city AND the user should receive a list of upcoming
events in that city.
As a user, I should be able to filter events by city so that I can see a list of events taking place in that
city.
</br>
Feature 2 Scenario: User can expand an event to see its details.
•
Given the list of events has been loaded;
•
When user clicks on the “Show details” button for an event;
•
Then the event element will be expanded to show the event details.
As a user, I should be able to expand an event so that I can see that event’s details.
</br>
Feature 3 Scenario: User can specify how many events they would like to see.
•
Given user wants to limit the amount of events they want to see;
•
When the user enters a specific number in the event amount section;
•
Then the user will see only the top events in their desired amount.
As a user, I should be able to specify the number of events I would like to see so that I can see a list
of events not exceeding my desired amount.
</br>
Feature 4 Scenario: User can use the app while they are not connected to the internet.
•
Given user didn’t have an internet connection;
•
When the user logs into the app;
•
Then they are still able to access events.
As a user, I should be able to open the app when not connected to the internet so that I still have
access to it.
</br>
Feature 5 Scenario: User can add a shortcut to the app to their Home Screen.
•
Given user selected “add a shortcut”;
•
When the user selects the shortcut settings;
•
Then a shortcut for the app appears on their home screen.
As a user, I should be able to select “add a shortcut” so that a shortcut link gets added to my home
screen.
</br>
Feature 6 Scenario: User can access a chart that details the events on the app.
•
•
Given the user went to the charts page;
When the user selects the event they would like to see a chart for;
•
Then a chart for that event appears.
As a user, I should be able to access the charts page so that I can find charts for the events I like.
