Meeting Demo Project
Author: Traagen, aka Chris Serson
May 2017

Written using ReactJS with Firebase DB.
Uses email/password authentication and Facebook authentication through Firebase.
Uses Material-UI library for front-end styling.

Project objective was to build a scheduling web app for meetings in a conference room.
Users can sign in and see all meetings scheduled in the room and schedule their own meetings.
They can invite other registered users to a meeting.
They can see which meetings they have been invited to and mark whether they are attending.
The meeting creator can delete a meeting.
Validates that a new meeting will not overlap with existing meetings.
General Agenda view that shows all upcoming meetings.
Daily view that shows a chosen day's meetings.
Weekly view that shows all meetings in a given week.

To Do:
Better differentiation of meetings based on whether a user owns or has been invited to a meeting.
Ability to open new meeting view from each Agenda view. New meeting currently has its own tab,
requiring the user to navigate away from what they were looking at.
More fleshed out ability to edit a meeting from each Agenda view and view relevant details of a meeting,
like who is attending.
General Agenda view works by day, rather than time, so if you are part-way through a day,
you will still see meetings from that day that have already passed.

Note:
For the purpose of sharing, I have removed the Firebase API keys I used.
To use this code, you will need to create your own Firebase project and
copy the API keys provided into the firebaseconnect.js file,
in the config constant.
For the Facebook authentication to work, you will also need to create
a Facebook project and add the appropriate keys to the Firebase project.
See Firebase documentation for details.