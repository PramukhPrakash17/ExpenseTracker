Overview
The Expense Tracker is a robust tool designed to help users effectively manage their finances by tracking daily, weekly, and monthly expenses. It offers features such as secure authentication, detailed reporting, and intuitive expense management. Developed collaboratively by a team, the project focuses on modularity and user-centric functionality.

Features

The Expense Tracker allows users to securely sign up and log in, ensuring data privacy. Users can manage their expenses by adding, editing, deleting, and categorizing them. The system validates inputs to prevent invalid or empty entries. A search and filter functionality enables users to look up expenses based on specific details, dates, or categories. Users can track their daily spending activity with a dedicated section highlighting "Today's Expenses." A streak management feature motivates consistent usage by maintaining a daily streak when expenses are added regularly.

The system generates comprehensive expense reports, categorized for better analysis. Users can also download these reports for offline use. Recent activities are highlighted, keeping users informed about their most recent spending patterns.

The interface is designed for a seamless user experience with smooth navigation, proper error handling, and loading overlays to ensure consistent functionality. Navigation errors and UI inconsistencies have been resolved to improve overall flow.

Technologies Used : 
Vue.js , HTML5, CSS3 , JSON Server (DB).

Development Setup
This project is built with Vue 3 and uses json-server for handling mock APIs.

Running the Project
Clone the repository and navigate to the project directory:

git clone [repository_url]
cd [project_directory]
Install dependencies:

npm install
Start the development server for the Vue 3 application:

npm run dev
Run the mock API server using the following command:

npm run db
The json-server will serve data from db.json and start on port 5001, dynamically updating based on changes in the file.
