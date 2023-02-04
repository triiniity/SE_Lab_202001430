# Lab 1: Identifying Functional and Non-Functional Requirements
202001430
Aryan Shah

## Question 1

***Functional Requirements:***
1) Search: Any user (without logging in) should have the ability to search the library's various reading material using different criteria like title, writer/author, ISBN number, genre, etc. 
2) Issue Status: If all the copies of that reading material have been issued by other people, the system should not permit the user to borrow it and instead inform them of its status.
3) Issue and Return: Before issuing or returning a book or any ohter reading material like magazine or publication, the system should ask the user for their username and password and proces the issue/return request and verify that the credentials belong to a valid LIS user/member.
4) Access: As discussed in the above points browsing should be allowed to everyone but issuing and returning should only be allowed for valid LIS members.
5) Alerts and Reminders: The system should notify the user of books that are going to be overdue shortly and the fine if it becomes overdue.
6) Profile: A user should be able to view all the reading material he/she has issued and returned with the respective dates; which books are still left to be returned and their due date. It should also show any pending penalty charges against the user.
7) Admin priviliges/Librarian: 
  i) The librarian should be able to view the status of all books, the users who have issued a paricular reading material and the fines that are due for all users. 
  ii) The librarian should be able to add, update and remove book records as and when new books are purchased and removed from the shelf.


***Non-functional Requirements:***
1) Security: Access to the LIS should only be allowed with appropriate credentials that students,
2) Privacy: The login credentials should be stored in a encrypted format and not in a plain text format.
3) Maintainability: The LIS software should be designed in such a way that it is for new changes and updates to be incorporated.
4) Usability: The software should have a good UI/UX an it should be convinient for the user to use and interact.
5) Performance: The software should handle user requests in a speedy manner.
6) Storage: The data about different reading material like books, magazines, publications, etc, different users like students, employees, professors, admin, etc and what reading material has been issued and returned should be stored in a 


## Question 2

***Scope:***
The scope of the application should be the people in the world that suffer from hearing loss (~466 million people)

***Features:***
1) AI-based sound recognition: The app should have the capability to identify key sound events, such as car horns and babies, based on machine learning algorithms
2) Accuracy: Reliability of sound event recognition to ensure the correct sounds are detected and reported to the user
3) Immediate alerts for key sound events: Notifications should be sent to the user in real-time to alert them to the presence of important sounds
4) Customisability: Ability to configure alert settings, such as volume, vibration, and tone, to meet individual needs
5) Continual logging of recognized events: There should be a record of all sound events recognized by the application over time, stored locally or in the cloud. Also the user should have the ability to view, sort, and analyze the logged events to understand patterns and trends.
6) Multilingual support: The app should support various world languages since the scope is the world population.
7) Optimized for Android devices: Performance and usability optimized for Android devices to provide a smooth and seamless user experience
8) Low latency for real-time use: Minimal processing time to ensure that sound events are recognized and alerts are sent in real-time

***Non-functional aspects:***

1) Performance
* Processing speed and efficiency to ensure real-time recognition of sound events
* Scalability to accommodate growth in user numbers and usage

2) Usability
* User-friendly interface to allow individuals with hearing loss to easily use the application
* Compliance with accessibility standards to ensure that the application is accessible to a wide range of users

3) Reliability
* Robustness and resilience of the AI sound recognition system to ensure consistent performance and minimize errors
* Data storage and management to ensure the security and privacy of user data

4) Security
* Encryption and secure storage of sensitive user data, such as personal information and logged sound events
* Protection against unauthorized access to the application and user data

5) Accessibility
* Compliance with accessibility standards to ensure that the application is accessible to individuals with disabilities, including those with hearing loss
* Customization options to meet individual needs and preferences, such as language and font size.
