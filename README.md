Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal was to build a simple, lightweight inventory tracker that lets users keep track of their items and quantities. It’s primarily designed for small business owners or individuals who need to manage inventory with
minimal setup and complexity. The app also provides users with the option to receive SMS alerts when an item runs out, adding a practical and helpful layer to the experience.


What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app needed a login/signup screen to keep things secure, a home screen to display inventory, and basic actions like add/remove items and adjust quantities. I kept the UI clean and simple, just a grid with all
the items, four main buttons, and easy dialogs that guide the user through every task. The focus was making sure users could get started right away without needing a manual or tutorial.
Everything’s where you’d expect it to be, which makes it intuitive to use.


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I tackled it one screen and one feature at a time. I’d design the UI in XML, get the layout working, and then build the logic behind it in Java. I also made sure to keep things modular by using helper classes
like the authentication and inventory database classes, so that everything stayed clean and easy to debug. I tested as I built each part, which saved a lot of time later.


How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I ran everything on the emulator and manually tested each feature login, item creation, quantity changes, SMS permission, etc. I also tested cases like invalid login or denying permission to make sure
the app didn’t crash. It was important because I wanted the app to be stable no matter what the user does. Testing helped me catch edge cases and fix small issues before they turned into big ones.


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One part that took some extra thinking was keeping the layout consistent when adding a new item to the grid. The card size didn’t match at first, and I had to figure out how to update the layout and spacing
so everything looked clean. Another challenge was handling SMS permission gracefully I made sure the app doesn’t break if the user denies it.


In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I’d say the full flow from authentication to inventory management shows that I’ve got a solid grasp on how to build a functional app from start to finish. The way the app handles different cases
like verifying users, syncing inventory with their account, and managing SMS — really shows what I’ve learned. It’s also clean and easy to use, which is what I was aiming for from the start.

