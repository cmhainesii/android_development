# android_development
CS360 Mobile Development - Charles Haines - Southern New Hampshire University

The requirements of this app were a login screen where users can create a new account or log in and a way to display the warehouse inventory as a grid. The application also needed a way for users to edit, add, and delete items within the inventory.
The application was built to accommodate various users such as warehouse workers, managers, and administrators.

The login screen allows users to either log in or create a new account to log in with. The display inventory screen appears after logging in and displays the warehouse's inventory which updates in real-time as the database is updated. There is a screen
for editing an item and an additional screen to add an item to the warehouse inventory. The design was created like this to keep different activities on their own screens and to keep things simple and intuitive for users to navigate.
The design is successful because it allows users to accomplish a variety of tasks without a steep learning curve you might find in a more sophisticated solution.

I approached the coding of this application by trying to keep all of the parts and components that make up the application modular. My strategy was to work on one piece at a time and to test things as often as I could while working on the code to ensure things were working before adding new components and features.
I will apply these techniques in the future by making sure I write code in a modular fashion so that related pieces of code are kept together. This will make the application easier to work with and maintain.

I tested the application manually during this project for the most part, but I do realize that I could have saved a lot of time by writing test cases and automating parts of the testing process. Testing the UI can always be done manually, but testing the logic of the various components can be
done using test cases to make the testing process faster and more efficient. Through testing the app I discovered many small issues that I was then able to fix. For instance, my manual testing revealed that the grid wasn't updating in real-time after adding an item. The results of this test
alerted me to the problem so I could look into what the issue was and fix it.

One part where I had to innovate was writing the Room database code in a way that the database queries were done on a background thread but still allowed the program access to the records used to create Java objects needed by other parts of the application. I used techniques of asynchronous programming
to allow me to keep the database activities on a background thread while still providing access to the records retrieved by database queries. It took me a while to come up with this solution, however, once I implemented it, it worked as intended and allowed the application to function how I wanted it to.

I think the grid of inventory items is a good showcase to demonstrate the skills, knowledge, and experience I gained from working on this project. It is one of the more complicated parts of the program and I'm happy with the way that the final solution looks and functions. The list is able 
to respond to changes in the database and the UI is very responsive. I think this is a good showcase because it includes not only coding elements to function, but UI elements as well.
