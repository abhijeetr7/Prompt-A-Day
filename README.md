# Prompt-A-Day
📓 Prompt-A-Day: Daily Reflection Journal
💡 Concept
Prompt-A-Day is a web application designed to encourage daily journaling, creativity, and mindful reflection. It presents users with a unique reflective writing prompt each day, providing a dedicated space to capture their thoughts and build a personal archive of their insights.

🛠 Features
Daily Reflective Prompt: A new thought-provoking prompt is presented every day, rotating from a preset list and user-added custom prompts.

Inspirational Quote: Each daily prompt is accompanied by a random inspirational quote to spark further reflection.

Answer Box: A dedicated text area for users to write their daily journal entries.

Automatic Saving: Entries are automatically saved to the user's private journal archive in real-time as they type.

Journal Archive: A scrollable list of all past entries, grouped by month and year for easy navigation.

Search Functionality: Users can search through their journal entries (prompts and answers) to quickly find specific reflections.

Favorite Entries: Option to "favorite" important or meaningful entries for quick access.

Filter by Favorites: Toggle to display only favorited entries in the archive.

Prompt Management: Users can add and delete their own custom prompts, which will be included in the daily rotation.

Export Journal: Ability to export the entire journal as a PDF document.

🔧 Technologies
Frontend:

HTML5: Structure of the web application.

Tailwind CSS: For rapid and responsive styling, ensuring a clean and modern user interface across various devices.

JavaScript (ES6+): Core logic for application functionality, including date-based prompt rotation, data handling, and UI interactions.

Font Awesome: For various icons used throughout the application (e.g., star, export, plus, trash).

jsPDF Library: Used for client-side generation and export of journal entries into PDF format.

Backend/Data Storage:

Firebase Firestore: A NoSQL cloud database used for securely saving and synchronizing user journal entries and custom prompts in real-time. Each user's data is stored privately.

Firebase Authentication: Handles anonymous user authentication to provide a unique userId for data storage without requiring explicit sign-up.

🚀 How to Use
Access the Application: Open the index.html file in your web browser or deploy it to a web server.

Daily Prompt: Upon loading, you will see "Today's Prompt" and an answer box.

Write Your Entry: Type your reflections into the answer box. Your entry will be automatically saved.

View Archive: Scroll down to the "Journal Archive" section to see all your past entries.

Search Entries: Use the "Search entries..." input field to filter your entries by keywords in the prompt or your answer.

Favorite Entries: Click the star icon next to any entry in the archive to mark it as a favorite. Click again to unfavorite.

Filter Favorites: Click the "Show Favorites" button to toggle between viewing all entries and only your favorited ones.

Export Journal: Click the "Export" button to download your entire journal as a PDF file.

Manage Custom Prompts: In the "Manage Custom Prompts" section:

Enter a new prompt into the input field and click "Add Prompt" to add it to your rotation.

Click the trash icon next to any custom prompt to delete it.

Optional Enhancements (Future Considerations)
Markdown Support: Allow Markdown formatting within the answer box.

Image/Media Embedding: Enable users to embed images or other media into their entries.

Reminders/Notifications: Implement a system for daily journaling reminders.

Theming Options: Allow users to customize the application's visual theme.

Advanced Export Options: Offer more export formats or customizable PDF layouts.
