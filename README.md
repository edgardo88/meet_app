
**Meet_App**

**Objective**

- The app displays  list of events, which is fetching the events from Google Calendar API, that can be filtered by city or number of events.
- To build a serverless, progressive web application (PWA) with React using a
test-driven development (TDD) technique. The application uses the Google
Calendar API to fetch upcoming events.

**The 5 Ws**
1. Who — The users of your Meet app. They could be you, your friends, your professional
network, or your potential employers.
2. What — A progressive web app with the ability to work offline and a serverless backend
developed using a TDD technique.
3. When — Users of this app will be able to use it whenever they want to view upcoming events
for a specific city. Your recruiter will be able to see your code immediately on GitHub.
4. Where — The server, in this case, is a serverless function hosted by a cloud provider (e.g.,
AWS). The application itself is also hosted online to make it shareable and installable. It can
be used even when the user is offline. As it’s responsive, it displays well on any device.
5. Why — Serverless is the next generation of cloud infrastructure, PWA provides great user
experience and performance, and the TDD technique ensures you have quality code and
adequate test coverage. All of these skills, together with data visualization, will distinguish
you from other web developers.


**Development server**
Run npm run start for a dev server(once done it open url link in new tab with react front end and backend showing its logo spinning). Navigate to http://localhost:3000/meet_app.

**Build Purposes**
Run npm run build to build the project. 

**Meet App and their user stories/features**

**FEATURE 1: FILTER EVENTS BY CITY**

As a user, I should be able to filter events by city. So that I can see a list of events taking place in that city.

Scenario 1: User opens the app and has searched a city.

Assuming the main page with the search option has been opened and the user has entered a city, upcoming events for that city should display to the user



**FEATURE 2: SHOW/HIDE AN EVENT'S DETAILS**

As a user I should be able to show or hide event details, after I have selected a city I wanted to look up the events for.

Scenario 1: An event element is collapsed by default

When a user first opens the app and receives the full list of events, whether specific to a city or all events, it is recommended to have all events collapsed by default. Collapsing the events provides a more streamlined and organized view for the user.

**FEATURE 3: SPECIFY NUMBER OF EVENTS**

As a user, I should be able to specify the number of displayed events, after I have selected the number of displayed events.

Scenario 1: User can change the number of events they want to see.

When the user has events displayed and decides to change the number of events shown, the app should update the display to reflect the user's selection.

**FEATURE 4: USE THE APP WHEN OFFLINE**

As a user, I should be able to get events information when offline, that was fetched while having internet connection.

Scenario 1: Show cached data when there's no internet connection.

-When the user is accessing the app and there is no internet connection available, the app will provide cached data that has been stored locally. This ensures that users can still access and interact with content even when offline.


**FEATURE 5: ADD AN APP SHORTCUT TO THE HOME SCREEN**

As a user I should be able to add a shortcut of the app to the home screen, so I can access the app quicker.

Scenario 1: User can install the meet app as a shortcut on their device home screen.

When a user selects to install the app as a shortcut, a shortcut can be created on the user's homescreen. This allows the user to quickly access the app without having to navigate through other sections of their device

**FEATURE 6: DISPLAY CHARTS VISUALIZING EVENT DETAILS**

As a user, I would like to be able to see a chart showing the upcoming events in each city so that I know what events are organized in which city.

Scenario 1: Show a chart with the number of upcoming events in each city.

Given the user is in the events detail page, when the user clicks the button to see a chart of those events in all the cities as a comparison,  a chart with the number of upcoming events for every city will be shown to the user.

