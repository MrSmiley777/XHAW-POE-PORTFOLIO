# XHAW-POE-PORTFOLIO
Group E-Two members
ST10459254 Gesaven Pillay, ST10456980 Arsene Kalala 
Detailed Report and Logging files for both website and mobile application:

Detailed Report:

**Client Requirements:**

A local small-to mid-size enterprise (SME) would like to have a web page and mobile app developed to advertise their business, receive requests for information from potential customers as well as provide quotes to the potential customers for services requested.
The company’s name is “Empowering the Nation”. This company provides a range of courses to assist domestic workers and gardeners in finding new employment with higher payment.

We need to create the website and mobile app with strong images, fonts and colours to reflect the professional image and purpose of the business, create a logo, allow users to select courses, apply discounts, provide descriptions of courses, calculate fees and provide contact details.

**Solution:**

Create a website and mobile application that appeals to the requirements of the company. There must be simple, but fluid navigation, descriptive text, alluring headings and pictures, selection of courses with discounts, and accurate calculations with contact details in case the user needs help. Flawless calculations and directions are important to provide a user experience that is not frustrating or in some way feels unprofessional.

**Data flow diagram:**
![image](https://github.com/user-attachments/assets/3934fb9d-de29-4eeb-956f-2d40d41cf6dd)

**Use Case diagram:**
![image](https://github.com/user-attachments/assets/7b2b7d4a-61d2-49b9-9e6b-e1c3716cd76a)

**Entity Relationship Diagram:**
![image](https://github.com/user-attachments/assets/3ea041c1-d701-4265-a857-e2274021f998)

**In-depth Solution and design:**

**Login**

*Purpose:*

This login page is for users who already have accounts and wish to log back in to see their selected courses, add new courses, or see the details to contact the company, or/and peruse the mobile application and website.

*Design:*
Website-
![image](https://github.com/user-attachments/assets/d339c857-ad98-4bdf-9389-d9f88ace8f84)

Mobile Application-
![loginreal](https://github.com/user-attachments/assets/3b783663-385c-48ef-9f80-6a6543e40b10)

**Registration**

*Purpose:*

This registration page is for users who do not have accounts and wish to make one in order to see the courses, purchase courses, or see the details to contact the company, or/and peruse the mobile application and website.

*Design:*

Website-
![image](https://github.com/user-attachments/assets/568cc31e-43de-47cc-b081-183475b0bd91)

Mobile Application-
![Register](https://github.com/user-attachments/assets/8f01fa90-a942-4ab5-9023-68410143709f)


**Home Page/Screen**

*Purpose:*

The Home Page/Screen serves as the primary landing page for visitors to the website, offering an overview of what the website and mobile application entails. The website contains navigation links to all major sections, such as individual course pages, enrollment options, and contact information. The application has links to the courses. Both the website and mobile application adhere to requirements.

*Design:*
Website-
![image](https://github.com/user-attachments/assets/e19149e4-9ad3-402a-a859-602aaa1b459e)

Mobile Application-
![Homescreen](https://github.com/user-attachments/assets/a041d1d2-27aa-4754-9ad2-92a7ef97360c)

**Courses Pages/Screens**

*Purpose:*

The course pages show short descriptions to tell the user what each course entails, the user can then make a educated guess based on these descriptions, on which course they wish to check out first or even purchase.

*Design:*
Website- (Example using 6 Month Courses Page)
![image](https://github.com/user-attachments/assets/2d342ea9-91ea-407a-a8c6-8283ce46f50d)

Mobile Application- (Example using 6 Month Courses Screen)
![SixMonth](https://github.com/user-attachments/assets/fc2f7853-624d-4cf5-819a-f55e2f06cced)

**Detailed Course Pages/Screens**

*Purpose:*

The detailed course pages show a course overview describing the course in more detail, then a content overview which shows the user what activites are offered by the course, the amount for the course, a button to go back to the previous screen and a button to enrol into the course-takes them to select and purchase the courses they wish.

*Design:*
Website- (Example using First Aid Course Page)
![image](https://github.com/user-attachments/assets/fc68ec25-9399-4bb5-a339-252adc9ed423)

Mobile Application- (Example using Sewing Course Page)
![sewing detailed course](https://github.com/user-attachments/assets/3c66ea36-9cb5-4cc5-9307-2a5be8487294)

**Calculate Fees Page/Screen**

*Purpose:*

This page/screen is for the user to schedule a consultant and, select and purchase courses while seeing the complete fee breakdown, after which they may proceed to checkout, pay for their fee and continue to the contact details page/screen.

*Design:*
Website-
![image](https://github.com/user-attachments/assets/d91cd127-699e-4f5d-b9a4-595119c52f26)

Mobile Application-
![Calculate](https://github.com/user-attachments/assets/67c77f55-f516-4983-bd4e-5881f05d72c6)

**Contact Details Page/Screen**

*Purpose:*

This page/screen is for the user to get the company's contact info and see the venues of the company's offices. They can select an address and get directions to selected venue through a google map. 

*Design:*
Website-
![image](https://github.com/user-attachments/assets/5ec9bce2-2c6b-4965-98b5-f9a5430edc2c)

Mobile Application-
![Contact Details](https://github.com/user-attachments/assets/777a00c7-21eb-421c-ac57-678f6085d792)

**Logging File**

*Application-*


Initial Setup and Project Configuration
Date: 2024-11-16

Action: Initialized the project using Expo and React Native.
Packages Installed:
react-navigation for screen navigation.
react-native-paper for UI components like Checkbox and Picker.
react-navigation-stack and react-navigation-drawer for navigation components.

Login and Registration Screens were implemented and design was chosen to be used throughout the mobile application to show consistency
Date: 2024-11-20

Login Screen:

Created fields for email and password.
Integrated form submission with navigation to the home screen on successful login.
Error handling added for missing fields.
Registration Screen:

Added fields for name, email, and password.
Registration logic implemented with error handling for missing inputs.
3. Home Screen Design
Date: 2024-11-20

Action:
Designed the home screen layout with a "Empowering the Nation" heading and description.
Added buttons leading to Six-Month Courses and Six-Week Courses screens.
Styled the background with light blue color and buttons with purple color and cyan text.
4. Six-Month and Six-Week Courses Screens
Date: 2024-11-20

Action:
Created separate screens for Six-Month Courses and Six-Week Courses with lists of courses.
Each course has a description and a button linking to the detailed course screen.
5. Fees Calculation Screen
Date: 2024-11-21

Action:
Developed the Calculate Fees screen with input fields for name, phone, and email.
Implemented course selection functionality using checkboxes.
Fee calculation logic based on selected courses, with discounts and VAT applied.
Displayed fee breakdown with normal total, discount, VAT, and final total.
6. Contact Details Screen
Date: 2024-11-22

Action:
Created the Contact Details screen with fixed phone number and email.
Displayed 3 physical addresses stored in a Dropbox.
Integrated map functionality that updates based on the selected venue.
Styled the screen with a white background behind the text and adjusted headings.
Included a "Back to Home" button with navigation functionality to return to the home screen.
7. Error Handling and Validation
Date: 2024-11-22

Action:
Implemented form validation to ensure all fields (name, phone, email) are filled before submitting.
Added checks to ensure the correct format for phone numbers and email addresses.
8. Address Selection and Map Update
Date: 2024-11-22

Action:
Implemented a dropdown list for selecting the venue.
Integrated a map below the venue selection that updates with directions when a new venue is selected.
Addressed an issue where selecting a new venue didn’t update the map display.
9. Final Adjustments and UI Styling
Date: 2024-11-23

Action:
Made the final UI adjustments:
Added consistent white background behind text on all relevant screens.
Adjusted heading styles with a gold background, matching the home screen style.
Refined button appearance with proper text and background color contrasts for usability.
10. Cleanup and ESLint Warnings
Date: 2024-11-23

Action:
Removed unused style definitions such as pickerStyles.inputAndroid to clear ESLint warnings.
Ensured no unused styles are present to maintain code quality.
11. App Testing and Debugging
Date: 2024-11-23

Action:
Tested the app on both Android and iOS simulators.
Ensured the map updates properly when a venue is selected and that all fields and buttons are functioning as intended.
Fixed bugs related to the dropdown selection not refreshing the map.
12. Final Review and Deployment
Date: 2024-11-24

Action:
Conducted a final review of the app, ensuring all functionality (navigation, form validation, map updates) works seamlessly.
Prepared the app for deployment to Expo Go for further testing and sharing with stakeholders.
Notes and Future Improvements:
To-Do:
Add error handling for map updates in case the venue address is unavailable.
Implement additional features for payment processing on the checkout page.
Optimize the app for performance on both Android and iOS platforms.

