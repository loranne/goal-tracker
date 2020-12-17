## Prompt

Build a goal tracking app. It should allow users to view, save, and edit goals. Users should only be able to see their own goals. Use Firebase as your database, but all other technology is up to you. Given that this will have private user data, security is important.

## My assumptions

For security, our biggest concern is user login credentials.

Schema: User object with ID, email, password, and name. Goal object with ID, text of goal, and user ID.

Starting by reading documentation for Firebase, because that's completely new to me.