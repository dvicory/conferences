https://www.papercall.io/talks/20313

# Title
Delivering User Value Quickly by Leveraging Existing Responsive Web

# Abstract
*The abstract is the 300 character elevator pitch for this talk.*

You already have a large web app, but now your users want native apps. You don’t want to divide development effort. Worse, your users won’t tolerate a different feature set than your web app. I’ll show you how we were able to leverage our existing responsive web app to quickly deliver a native app.

# Description
*This field supports Markdown. The description will be seen by reviewers during the CFP process and may eventually be seen by the attendees of the event.*

React Native is an amazing technology that lets you create native experiences quickly. But what happens when your users begin to demand a native app from a decade-old and evolving B2B application built for the web? Furthermore, users expect to be able to do anything on the go. Our recent stats show that the top 100 actions in our app are accessed from a mobile device 10% of the time, with an extremely long tail of usage: nearly 75% of our app receives mobile traffic in a given month. Rebuilding the complex functionality offered in just a small segment of our app is a near-impossible task for a small team and would leave many users resorting to mobile web to complete tasks.

Unlike traditional hybrid apps, where you may build an offline-first HTML5 app to live on the device, or include WebViews in limited roles with mostly native experiences, we were faced with going WebView first and progressively enhancing with native technology later. We started with the bare minimal native functionality needed to power the login experience. From there, we began to build a more featured React Native app – adding in redux, redux-saga, and more. We also built out a communication pathway between native app code and our web app, which has allowed us to deliver user value that only native technologies can provide. The native features which we’ve so far built (or under consideration) include:

- Sign on, two factor, auto login
- OS-protected account with fingerprint or PIN
- Native uploads from Gallery and Camera that support a quick workflow
- Location-based service enhancements

In this talk, I will share the technologies and approaches we have used and reveal some of the lessons learned along the way.

# Notes
*This field supports Markdown. Notes will only be seen by reviewers during the CFP process. This is where you should explain things such as technical requirements, why you're the best person to speak on this subject, etc…*

## Why I’m qualified to speak about this

I am a Sr. Software Engineer working at [AppFolio](https://www.appfolioinc.com/) for just over two years. Since joining AppFolio, I’ve been on the team driving the major efforts to create a great mobile experience for our customers. At first much of the work was to overhaul our main layout, create responsive experiences of existing features, promote frontend best-practices and building out a reusable components library.

In late 2015 we set out to build a replacement app for our aging apps created early in AppFolio’s life. We first chose Cordova - believing React Native to not be ready yet - and delivered the app to all customers in early 2016. While the app was a hit with users, the limitations with Cordova were interfering with our ability to deliver greatness. We took a small break from app development after that. Last summer, I led an intern team to create an inspections app with React Native, with the goal of improving our most heavily used feature on mobile. With the knowledge gained from that, we took to upgrading our Cordova app with a React Native one, with the first public release last September. Since then we’ve been iterating to add more native features to improve the mobile experience.

The development of our apps were all done with a single small agile team, with only 2-3 engineers, which has allowed us to gain a swath of knowledge.

## Technical Requirements

The talk will be primarily slides with some interactive demos, so it would be best to be able to use my own laptop for presenting.

# Tags
*Tag your talk to make it easier for event organizers to be able to find. Examples are "ruby, javascript, rails".*

hybrid,responsive,redux,redux-saga,agile,react native

# Bio
*This field supports Markdown. Your bio sells you. Who are you? Why should people listen to you? Who's your favorite member of One Direction? This is your chance to put it all out there.*

Daniel Vicory is a Senior Software Engineer at [AppFolio](https://www.appfolioinc.com/). For the past two years he has focused on delivering awesome mobile experiences and putting smiles on users’ faces. His open-source contributions include [Crosswalk](https://crosswalk-project.org) and co-maintaining [react-native-webview-crosswalk](https://github.com/jordansexton/react-native-webview-crosswalk).

# Additional Information

I have been working with React Native since early-mid 2016, for both work and personal projects. I won a Hack Day in part because of React Native. I've given several talks internally at AppFolio describing the work we've done with our app and other teams have started to consider using it because of our work. I try to closely follow the amazing work that people in the React Native community are doing and would be proud to be able to share how some of that has enabled us to be successful. I'd like to enable all of us to create a better mobile platform without sacrifice.
