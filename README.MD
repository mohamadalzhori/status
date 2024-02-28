# Student Status Tracker

The Student Status Tracker offers students a convenient method to assess their progress in various courses quickly.

# Motivation

Initially, I began managing this concept through an Excel sheet. However, as I continued, I realized the potential for greater utility by transforming it into a program. This transition allows me to seamlessly integrate it into my window manager's status bar, ensuring constant visibility of my academic progress.

## 2. Glossary of Terms

- **Course:** An academic subject being studied.
- **Assignment:** A task, activity, or lecture already assigned or presented in class.
- **Due:** An assignment that has already been assigned.
- **Advanced:** An assignment that has been studied or prepared for, although not yet due.
- **Status:** An overall assessment of the student's progress, indicated by "In Danger," "Okay," or "Great."

## 3. Overall Description

### 3.1 Functionality:

- Track the number of Due and Advanced assignments for each course.
- Display a status message ("In Danger," "Okay," or "Great") based on specific logic.
- Add new entries to the Due category for a specified course by default.
- Add entries to the Advanced category for a specified course (optional).
- Remove entries (mark as completed) from either Due or Advanced categories for a specified course. This will completely remove the entry from the database.

### 3.2 Target Users:

This application is intended for students who want to:

- Track their academic workload effectively.
- Monitor their progress in different courses.
- Receive visual cues and motivational messages.

### 3.3 User Interface:

The application will use a text-based command-line interface (CLI) for user interaction.

## 4. Specific Requirements

### 4.1 Functional Requirements

#### 4.1.1 Checking Status:

The application shall display one of the following messages:

- "In Danger": If there are one or more Due assignments.
- "Okay": If there are no Due assignments.
- "Great": If there are no Due assignments and at least one Advanced assignment.

#### 4.1.2 Adding Entries:

The application shall allow users to select a course.

- Users can add new entries as "Due" or "Advanced."

#### 4.1.3 Checking Off Assignments:

The application shall allow users to select a course.

- Users shall be able to choose whether to remove an assignment from the "Due" or "Advanced" category.
- Removing an assignment shall completely delete it from the database.

### 4.2 Non-Functional Requirements

#### 4.2.1 Usability:

- The CLI shall be user-friendly and easy to navigate.
- Clear and concise instructions shall be provided for each command.
- Error handling shall be implemented to provide informative messages for invalid user input.

#### 4.2.2 Performance:

- The application should respond to user commands promptly.

#### 4.2.3 Reliability:

- The application should function reliably without unexpected crashes or errors.

## 7. Future Considerations

- Incorporating logging functionality to track changes and progress over time.
- Introduce functionality that allows users to edit or update existing course information.
