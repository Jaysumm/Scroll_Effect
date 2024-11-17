Infinite Scroll Posts
This project demonstrates an infinite scroll mechanism using HTML, CSS, and JavaScript. Posts are dynamically fetched from an API and displayed on the page as the user scrolls, mimicking the behavior of social media feeds like Instagram or Twitter.

Features
Infinite Scrolling: Automatically fetch and load more posts as the user reaches the bottom of the page.
Dynamic Content Loading: Posts are fetched from an external API and displayed on the page.
Loading Indicator: A visually appealing loader shows up during data fetching.
Debouncing for Performance: Implements scroll event debouncing to enhance performance and prevent unnecessary API calls.
Technologies Used
HTML5: Structuring the page.
CSS3: Styling the content, including the loader animation.
JavaScript (Vanilla): Handling API requests, DOM manipulation, and infinite scrolling logic.
JSONPlaceholder API: A free fake REST API for testing and prototyping.
Setup Instructions
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/infinite-scroll-posts.git
cd infinite-scroll-posts
Open the project in your preferred code editor.
Open index.html in any browser to view the project.
How It Works
On page load, an initial set of posts is fetched from the API and displayed.
The user scrolls to the bottom of the page, triggering an API call to fetch more posts.
A loader animation is displayed while new posts are being fetched.
Newly fetched posts are dynamically appended to the page.
Debouncing ensures smooth performance during scroll events.
Usage
Modify the number of posts fetched per request by changing the _limit parameter in the API URL:
javascript
Copy code
'https://jsonplaceholder.typicode.com/posts?_limit=5';
Customize styles by editing the style.css file.
Experiment with different APIs by replacing the API endpoint in script.js.
Folder Structure
bash
Copy code
.
├── index.html       # Main HTML file
├── style.css        # Styling for the project
├── script.js        # JavaScript logic for fetching and displaying posts
└── README.md        # Project documentation
Demo
Open index.html in your browser to see the infinite scroll functionality in action.
Future Enhancements
Add error handling to display user-friendly messages when the API request fails.
Implement pagination to handle large datasets more efficiently.
Add unit tests for the JavaScript functionality.
Enhance UI/UX for better user interaction.
Contributing
Feel free to contribute to this project by creating a pull request. Ensure that your code follows best practices and is well-documented.

