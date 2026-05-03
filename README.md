User Management Screen – UI Specification Document

1: Layout:

The screen consists of a top bar with main actions, an existing users user table on the left side, a user registration form on the right side.

1.a: Initial State:

When the page is first opened:

- "+New User" button and "Hide Disabled Users" checkbox are displayed at the top.
- The user list is displayed on the left.
- The registration form is empty. It doesn't contain placeholders.
- The "Save User" button is unclickable until required fields are filled.

2: Components:

2.a: Top Bar:

- +New User Button: Used to add a new user
- Hide Disabled User Checkbox: When checked, disabled users are hidden from the list
- Save User Button: Saves the current user according to the information filled below

2.b: User Table:

The table displays the list of users with the following columns:
- ID
- Username
- Email
- Enabled (Boolean)

The table should support sorting and basic filtering. Clicking on a row selects that user.

2.c: User Form:

The form is used for creating users.

2.d: Fields:

- Username
- Display Name
- Phone
- Email
- User Roles (Drop-down List)
- Enabled (Checkbox)

3: User Actions:

3.a: Selecting a User:

When a user clicks on a row in the table:
- The form is filled with that user’s data.
- The form switches to edit mode.

3.b: Creating a New User:

When the “New User” button is clicked:

- All form fields are cleared.
- The form is set to create mode.

3.c: Saving a User:

When the “Save User” button is clicked:

- Required fields must not be empty.
- If everything is valid, the user is saved.

- If the required fields are empty the "Save User" button remains unclickable.

3.d: Hide Disabled Users:

- If the checkbox is checked, only enabled users are shown.
- If unchecked, all users are displayed.
