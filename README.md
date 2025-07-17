# AquaLink
AquaLink is a water supply tracker app.
It's a multi-user app with both admins and users rool.
App is build using a cross-platform Flutter.
App is coonected to the Firebase.
I tried to follow the MVVM architecture for this app as much as possible.
All the CRUD operations had been used in it.
Admin can see how many liters of water to a specific user had been supplied, how much the total cost of water had been supplied till yet, he can delete any order or mark any order as suplied.
User can see it's total bill after making an order, make a new order or cancel previous order.
At the backend both user's and admin's data is storing in real time on Firestore whenever they make any changes on the dashboard.
I also used Cloudinary in it.
