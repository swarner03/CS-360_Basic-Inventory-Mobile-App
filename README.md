# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
---
I developed an inventory management system designed to simplify the tracking and management of inventory. It addresses the need for an organized and straightforward method to monitor items and quantities, as well as to receive notifications when stock levels are low. The app allows users to add, edit, and delete items and provides alerts when quantities fall below a predetermined threshold. The objective was to create an efficient tool for individuals or businesses to manage inventory effectively, without the complications of more complex systems.
---
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
---
To meet user needs, I have incorporated several essential screens:
-	Login Screen: Provides secure access for users.
-	Data Display Screen: A dashboard that showcases the inventory items, displaying names, quantities, and unique item IDs. This screen includes a search bar and facilitates the straightforward addition of new items.
-	Add/Edit Dialogs: User-friendly forms for entering or updating item names and quantities, ensuring a seamless workflow for inventory management.
-	Delete Confirmation: A clear confirmation prompt to prevent accidental deletions.
The UI designs emphasize simplicity and intuitiveness, aiming to minimize the steps required to complete actions. For example, I utilized clear input hints and positioned buttons for easy accessibility. The introduction of a floating action button (FAB) streamlined the process of adding items. These design choices have proven effective, making the app easy to navigate and enabling users to perform actions quickly.
---
How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
---
I approached the coding process by initially structuring the app's core features, specifically focusing on data management and UI flow, before incorporating additional functionalities like SMS notifications. Adopting a modular approach allowed me to keep the UI distinct from the backend logic, which assisted in easier debugging and enhanced code maintainability. I adhered to best practices in Android development, such as utilizing RecyclerView for item listings and AlertDialog for user interactions. This strategy of separating concerns and prioritizing scalability will prove valuable in future projects, especially for larger applications that demand maintainable and scalable code.
---
How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
---
I thoroughly tested the app using the emulator. This comprehensive approach involved evaluating each feature individually, such as adding and editing items, as well as verifying the response for low inventory SMS notifications. The testing process was particularly valuable in identifying usability issues, including layout problems and user input errors. Testing is always essential, as it uncovers minor bugs, like the improper handling of empty fields, which could adversely affect the user experience. Ensuring the app's functionality prior to deployment is crucial to prevent errors in the production environment.
---
Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
---
One area where I needed to innovate was in the real-time management of the inventory list. During development, I encountered challenges in ensuring that any updates to the inventory—whether it was adding, removing, or editing items—reflected immediately on the UI without requiring a full refresh. To address this, I implemented an Adapter for the RecyclerView and utilized notifyDataSetChanged() to update the list efficiently. This approach allowed the app to maintain synchronization between the inventory data and the UI in real time, significantly enhancing both functionality and user experience.
---
In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
---
I successfully showcased my knowledge in database management while implementing a user-friendly interface. By utilizing RecyclerView to display items and ensuring seamless interaction with the database through DatabaseHelper, I created an app that is both functional and efficient. The database management system facilitated easy retrieval and updating of inventory items, which was crucial for the app's objectives. Additionally, the user interface was designed with simplicity in mind, allowing users to navigate the app effortlessly while ensuring a high-quality experience. I believe this quality is particularly evident in this application.

