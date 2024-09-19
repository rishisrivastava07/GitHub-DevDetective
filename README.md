Here’s a detailed write-up for your project, **GitHub - DevDetective**:

---

### **GitHub - DevDetective**
**Project Overview**:  
GitHub - DevDetective is a web application that allows users to search for GitHub profiles using a GitHub username. By leveraging the GitHub API, the app fetches key information about the developer and displays it in a user-friendly manner. The search results are presented as visually appealing cards, offering an organized and aesthetic layout of the user’s profile data. Additionally, the app features both dark and light modes, enhancing the user experience and accessibility.

---

### **Key Features**:

1. **GitHub API Integration**:
   - Utilizes the GitHub REST API to fetch real-time user data based on a given GitHub username.
   - Retrieves details such as profile picture, username, bio, repositories, followers, following count, and more.

2. **Profile Details Displayed as Cards**:
   - Each profile search result is displayed in a clean and minimalistic card format, ensuring information is structured and easy to read.
   - Cards include key details like:
     - **Profile Picture**: Fetches the avatar of the GitHub user.
     - **Username**: The developer’s GitHub handle.
     - **Bio**: A short description from the user's profile.
     - **Repositories**: Displays the number of public repositories.
     - **Followers and Following**: Shows the number of followers and following for the developer.
   - The card layout ensures optimal display on different screen sizes, contributing to a responsive design.

3. **Dark and Light Mode**:
   - The app provides a toggle button that allows users to switch between dark mode and light mode for better accessibility and personal preference.
   - **Light Mode**: Offers a bright, clean interface with a white background and darker text for readability in well-lit environments.
   - **Dark Mode**: A sleek, dark-themed interface that reduces eye strain and improves visibility in low-light environments.

4. **Responsive Design**:
   - The layout adapts across different devices, ensuring that the user interface is both mobile and desktop-friendly.
   - Utilizes CSS media queries to enhance the display on various screen sizes.

---

### **Technology Stack**:

- **HTML5**: For structuring the webpage and providing a semantic layout.
- **CSS3**: For styling, including the implementation of dark and light modes, along with responsive design principles.
- **JavaScript**: Handles the dynamic fetching of data from the GitHub API and the rendering of user profiles as cards.
- **GitHub API**: Provides real-time data about GitHub users.

---

### **How It Works**:

1. **User Input**:
   - Users enter a GitHub username into the search bar on the webpage.
   
2. **Fetching Data**:
   - Upon submitting the username, a `fetch` request is sent to the GitHub API, retrieving the user's data.
   
3. **Display Profile**:
   - The fetched details are processed and then displayed within a card structure using JavaScript's DOM manipulation capabilities.

4. **Dark and Light Mode Toggle**:
   - Users can toggle between dark and light modes using a switch button, which dynamically updates the CSS classes for the webpage.

---

### **Challenges and Learnings**:

- **API Rate Limiting**: Handling API rate limits imposed by GitHub to ensure a smooth user experience, even with multiple searches.
- **Error Handling**: Providing clear error messages for invalid or non-existent usernames, enhancing usability.
- **Dynamic Theming**: Implementing an effective toggle between dark and light mode while ensuring smooth transitions across the entire interface.

---

**GitHub - DevDetective** offers a seamless experience for users looking to quickly access developer profiles, all while ensuring a visually appealing and accessible interface.
