Hybrid Automation Framework

Project Overview:

This project automates end-to-end functional validation of Oracle’s Customer Reference and Support workflow — from login to submitting a Customer Success form — using Java, Selenium WebDriver, and the Page Object Model (POM) design pattern.

It validates critical UI flows, navigation, and form submission functionalities through data-driven and modular automation design.

Tech Stack

Language: Java

Frameworks: Selenium WebDriver, TestNG

Design Pattern: Page Object Model (POM)

Build Tool: Maven

Data Handling: Apache POI (Excel)

Testing Types: Functional, Smoke, Sanity, Data-Driven, and UI Validation.

Functionalities Automated:
Basic Navigation & Login Flows:

Clicking “Sign in to My Account” on the homepage

Validating redirection to Oracle’s Login page

Fetching credentials from Excel (Data-Driven Login)

Verifying successful login and page navigation

Testing Types: Functional, Data-Driven, UI Validation.

Page Validations:

Validation of page URL and page title post-login

Ensures redirection to the expected Oracle Help Center page

Testing Types: Smoke, Sanity, Navigation Validation

Account & Support Access

Accessing user account settings

Navigating to Oracle Premier Support → Customer Reference page

Validating end-to-end navigation flow

Testing Types: Functional Flow, Link Validation, Navigation Testing

Reference Page Interaction:

Handling pop-ups (e.g., “No Thanks” button)

Scrolling and clicking on “Share your success story” link

Verifying redirection to Innovation Story page

Testing Types: UI Interaction, Pop-up Handling, Functional Navigation

Form Submission Functionality:

Selecting radio buttons (e.g., An Oracle Customer)

Filling form fields: Company, Name, Job Title, Email, etc.

Selecting Country, Checkboxes, and Oracle Solutions options

Entering text in “Other” field and submitting the form

Testing Types: Functional, Data-Driven, Dropdown, Checkbox & UI Testing

Confirmation & Completion Validation:

Capturing and validating Thank You / Confirmation message

Ensures successful end-to-end workflow completion

Testing Types: Validation, Confirmation, Functional Completion

Key Highlights:

Built using Hybrid Automation Framework integrating Data-Driven and POM approaches.

Enhances reusability, maintainability, and scalability of test scripts.

Leverages Excel-based test data and custom reporting for validation insights.

Demonstrates strong understanding of UI automation principles and framework design.
