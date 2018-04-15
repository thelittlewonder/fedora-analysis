# Home Screen
## Position of fedora logo
The first thing that greets the user after the opening is the Fedora logo at the centre.  At the first glance, it is not sure if the logo is clickable and does something (It doesn’t). The fact that it is surrounded by 4 clickable elements doesn’t help the case.

<img src="./images/HomeScreenNav.png" height="400px">

According to [Hick’s law](https://en.wikipedia.org/wiki/Hick%27s_law), the time it takes to make a decision increases with the number and complexity of choices. In order to craft a better experience for the users, the application should avoid having too many options with equally perceived hierarchy which ultimately can cause paralysis of analysis.

#### Solution
An obvious solution would be to remove the logo (Keep it simple, stupid). But in case the logo has to stay on the home screen, we can add a navigation bar at the top with the app name and logo. 

However, a **better long term solution** would be to use a **bottom navigation** instead of the current design. Using the bottom navigation will allow the user to make quicker decisions and all the options can be comfortably reached with one-thumb interactions. All the current 4 features can be grouped into separate tabs, but the problem will arrise when we need to add more features.

In order to solve that, we can group similar categories together or introduce a 4+1 tab design (4 core features + One **More** tab).
