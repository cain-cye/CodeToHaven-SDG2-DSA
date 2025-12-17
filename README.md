# CodeToHaven-SDG2-DSA

# SDG 2 - FOOD DISTRIBUTION NETWORK
- This app assists barangays in distributing food fairly to post-disaster areas and low-income neighborhoods. The project addresses United Nations Sustainable Development Goal 2: Zero Hunger. The system collects family information, identifies vulnerable households, monitors food stock, and organizes delivery routes. Barangay staff apply a ranking system that prioritizes the most vulnerable families first. Food sources include both community donations and government assistance. Distribution begins immediately upon food arrival, with consideration for expiration dates.

# Installation/Setup: Instructions on how to clone the repository and compile the code.
Step 1: Clone the Repository
- Open your terminal or command prompt and navigate to the folder where you want to store the project. Copy the repository URL from GitHub and run the clone command: git clone https://github.com/your-username/zero-hunger.git

- Replace your-username with your GitHub username. This command downloads all project files to your computer.

Step 2: Navigate to Project Folder
- Move into the project directory: cd zero-hunger

Step 3: Start a Local Server
- The application requires a web server to run. You can use Python's built-in HTTP server. First, check if Python is installed: python --version
- If Python 3.x is installed, run this command in the project folder: python -m http.server 8000
- If you have Python 2.x, use: python -m SimpleHTTPServer 8000

Step 4: Open in Web Browser
- Open your web browser and navigate to: http://localhost:8000
- You should see the login page. The application is now ready to use!

Alternative: No Server Setup
- You can also open HTML files directly in your browser by double-clicking them. However, some features may not work without a server. Using a local server is recommended.

# Usage Instructions: Step-by-step guide on how to run the application and use its main features.
Login to the System
- When you first open the application, you will see the login page. Enter your username and password. For testing, use "admin" as username to access the admin dashboard. Any other username will take you to the user dashboard.

User Dashboard
- The user dashboard displays available food items and provides quick access to main features. You can search for beneficiaries or food items using the search bar. The main sections are:

Eligibility Check: Click to check if a household qualifies for food assistance based on income.

Inventory Logging: View current food inventory and stock levels.

Delivery Queue: See pending deliveries waiting to be processed.

Available Food Items: Browse all registered food with expiry dates. Sort by expiry to prioritize items expiring soon.

Admin Dashboard
- The admin dashboard provides comprehensive control. Click on admin tools to manage:

Managing Beneficiaries
- Go to Beneficiaries section.
- Enter household name, number of family members, and location.
- Click "REGISTER" to add the beneficiary.
- The system displays all registered beneficiaries in a list.
- You can add multiple beneficiaries one at a time.
  
Managing Inventory
- Go to Inventory section (Inventory Logging).
- Fill in food name, quantity, and expiry date.
- Click "REGISTER FOOD" to add the item.
- All registered items appear in alphabetical order automatically.
- The system shows total stock (sum of all quantities).
- Items with earlier expiry dates should be distributed first to reduce waste.
  
Checking Eligibility
- Go to Eligible Households section.
- Enter household name and monthly income.
- Click "Check Eligibility".
- Households with monthly income of 15,000 or less are eligible.
- Eligible households are added to the list.
- Ineligible households are rejected and not added to the list.
  
Managing Delivery Queue
- Go to Delivery Queue section.
- Enter household name or item to be delivered.
- Click "Add to Delivery" to enqueue the item.
- Items are added to the end of the queue (FIFO order).
- Click "Deliver Next" to process the first item in the queue.
- When an item is delivered, it is removed from the queue.
- The system alerts you when delivery is complete.
  
Viewing Distribution Records
- Go to Distribution Records section.
- Enter household name or item that was distributed.
- Click "Add Record" to log the distribution.
- All records are displayed in a numbered list.
- This creates an audit trail showing what was given to whom and when.
  
Logout
- Click the "LOG OUT" button in the top right corner of any page to return to the login page.


# Contributors: 

Caday, Ismael Haven R.
- Planning, Sorting Concept, Testing, Documentation

Ebuenga, Caryl Yasmin P.
- Planning, Documentation, Array Concept, Manage the Repository

Opilac, John Martin T.
- Planning, Array Concept, Queues Concept, Manage the Repository

Ramirez, Jay Darrius G.
- Planning, Documentation, Queues Concept

Sipin, Stephen Joshua B.
- Planning, Sorting Concept, Testing, Documentation

Alpas, Lee Endrey A.
- Shadow Member
