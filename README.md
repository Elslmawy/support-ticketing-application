Description
This is a basic text-based (non-GUI) technical support ticketing application. The application allows users to create and manage support tickets for different types of issues. The issue types are organized in categories and defined outside of the program in an external JSON file.

Features
External Configuration: Issue categories and types are defined in a JSON file (categories.json), making it easy to update or add new categories and issues without modifying the code.
Ticket Creation: Users can create a new support ticket by selecting a category and an issue type, and then providing a description of the issue.
View Tickets: Users can view all the created tickets along with their details

File Structure
categories.json: This file contains the predefined categories and issue types.
ticketing_system.py: This is the main script that runs the ticketing system.

Create a new ticket:
Select a category (e.g., Network Issues).
Select an issue type (e.g., Internet Down).
Provide a description of the issue.
View all tickets to see the created tickets along with their details.
