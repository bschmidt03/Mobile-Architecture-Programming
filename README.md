# Mobile-Architecture-Programming 
Requirements and Goals:
The main goal of the app was to let users easily log and track their weight while staying motivated toward their fitness goals. It needed to be simple, fast, and reliable, while offering an optional SMS feature that sends a text alert when the user reaches their goal. The app focuses on users who want something straightforward without unnecessary clutter or ads.

User Needs and UI Design:
To support user needs, the app includes a clean login screen, a grid display of entries, and a simple floating “+” button to add new weigh-ins. Each screen was built to be quick to navigate and easy to understand, even for new users. The interface uses clear buttons, readable fonts, and consistent colors to keep it visually balanced. Keeping things intuitive was a big part of the design—users can see their progress at a glance without digging through menus.

Coding Approach:
I focused on clean structure and testing often. I built the app step by step—starting with the database, then adding login, and finally connecting it all with the UI. I used techniques like modular coding, frequent emulator testing, and small, testable changes to make debugging easier. These habits helped avoid major crashes and will carry over to any future mobile or desktop projects I build.

Testing and Functionality:
I used the Android Emulator to test every feature, from logging in to sending SMS alerts. Testing helped catch layout issues, permission errors, and database bugs early on. It’s a crucial part of making sure the app runs smoothly and doesn’t break when users deny permissions or close and reopen the app.

Innovation and Challenges:
One of the hardest parts was implementing the SMS alert system correctly under Android’s strict permission rules. I had to balance functionality with security while keeping the app lightweight. That challenge made me think more like a real developer—solving practical problems, not just writing code.

Key Success:
The most successful part of the app was the combination of the persistent SQLite database and SMS alert feature. It showed that I can connect backend logic with front-end design to create a complete, working product that feels professional and user-centered.
