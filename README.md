This project was created by BASH students to participate in the Software Development competition of the PA-TSA (Pennsylvania Technology Student Association)'s Regional 9 event.

We followed directions to build the app from a blog post:
https://read.acloud.guru/build-your-own-multi-user-photo-album-app-with-react-graphql-and-aws-amplify-18d9cfe27f60

### Problem this project tries to address:

Students and teachers participating in TSA events at either the Regional, State or National level, often need to share photos taken during the events or during the activities preceding the events. TSA events can be very competitive, so it is typically desirable that the photos been share can be accessed only by student members of the team and their advisors.
Some of the options currently available for that purpose include:
•	Attach the photos to an email sent to the team members, which can be slow when sending multiple photos, and is limited by the attachment capacity set by the email service, and besides, the user has to add each recipient each time photos are been sent, which may be very cumbersome
•	Use regular chat/messaging apps widely used in all mobile platforms, after creating a group, but this option can also limit the number of photos that can be shared on a single message, and the user may need to send multiple messages, which takes more time. Another disadvantage of this method is that photos are stored on the app’s storage space, and this rapidly can take a lot of storage on the device and make it slower.
•	Use social media apps such as Facebook or Instagram, which requires all group members to have accounts, and the photos are stored in the servers from those companies, to which the users have little control.
•	Use dedicated photo sharing services such as those by Google, Amazon and other companies, after creating an album. This option also takes a lot of space on the device, and it requires all the group members to have an account with the company, which has several information privacy implications.

The solution we propose for the problem described above is a PWA (Progressive Web App) titled “TSA Shared Photo Albums”, which TSA students and teachers can use to share photo albums among a project team or across a larger group such as a specific class or even the entire school, while keeping peace of mind that members of competing teams or schools won’t be able to access those photos.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

