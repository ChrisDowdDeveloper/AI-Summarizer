AI Summarizer
AI Summarizer is a React application that leverages the OpenAI GPT-4 model to summarize web pages, making it easier to digest lengthy articles. The application utilizes a Redux Toolkit for state management and interacts with a RapidAPI to fetch and summarize articles.

Features
URL Input for Article Summarization: Users can input a URL, and the application fetches the article, returning a concise summary.
Local Storage History: Summarized articles are saved in local storage, allowing users to revisit previous summaries.
Copy to Clipboard: Users can easily copy the article URL or summary to the clipboard.
Responsive Design: The application is designed to be responsive, ensuring a good user experience across various devices.
Technologies Used
React.js for the frontend.
Redux Toolkit for state management.
RapidAPI for article fetching and summarization.
Local Storage for persisting article summaries.
Setup and Installation
To get the project up and running on your local machine, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/ChrisDowdDeveloper/AI-Summarizer.git
Navigate to the project directory:
bash
Copy code
cd AI-Summarizer
Install the necessary dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm run dev
Open http://localhost:3000 to view the application in your browser.
Environment Variables
Before starting the application, you will need to add your RapidAPI key to an .env file at the root of your project:

makefile
Copy code
VITE_RAPID_API_ARTICLE_KEY=your_rapidapi_key_here
Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request.

License
This project is open source and available under the MIT License.
