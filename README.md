# Budgeting Mobile
**Contributors:** Brandon Lam, Hamzah Bemat, Jed Rendo Magracia, Talike Bennett

## Summary
Our group has designed a budgeting app that organizes the user’s expenses. Items added to the app can be edited or removed at any time. We have created a modern design that users will find visually appealing. With all expenses in one place, we hope users will find it easier to organize their finances, analyze spending patterns, pay bills on time, and more.

## Detailed Design
### Features
- Track spending: All transactions are stored in a local database which can be fetched and displayed.
- Spending categories: This feature of the app shows the person where their money goes in different expense categories such as housing, transportation, food, utilities, etc. This will allow a person to understand where their money goes and pinpoint categories where they can reduce spending.
- Charts: Tracks and displays a graphical representation of how spending is allocated across different categories.

### Look and Feel
We designed our app to look minimal and modern. Our activity layouts have a simple design so that the user can, at a glance, easily find the information they're looking for. The user interface was made to be responsive and intuitive for the user. There is a smooth and seamless navigation between the different pages and menus in our app. The application has multiple scenes for each of its features.

<p align="center">
  <img src="https://user-images.githubusercontent.com/70542819/211239619-d94cdb14-0d07-4a03-a891-6a56730c3a3f.jpg" width="200">
  <img src="https://user-images.githubusercontent.com/70542819/211239668-c4b2cd19-2711-49d9-b23e-a9e49539f884.jpg" width="200">
  <img src="https://user-images.githubusercontent.com/70542819/211239644-338fa537-49f9-4aa6-90d0-1ac1f2f98d64.jpg" width="200">
</p>

### Architecture
Our group decided that we would need to store transactions and other important data (such as specific information about the transaction themselves) in an SQLite3 database. SQL is a technology that some of the group members are familiar with, so it was a great choice for storing the relevant data that we need. We built the app using Model-View-ViewModel(MVVM) design principles to keep the code organized and have a separation of concerns when developing the application.
