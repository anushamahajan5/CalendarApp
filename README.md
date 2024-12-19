# CalendarApp
## Overview
The Calendar App is a React-based single-page application that allows users to view and interact with a calendar, add and manage events, and customize event details. The app provides functionalities such as month navigation, event scheduling with time validation, event categorization (e.g., Work, Personal, Others), and real-time updates to the event list.

Deployed URL: https://calendar-app-xit1-dg0k8mzix-anushas-projects-65e5849b.vercel.app/

## Technologies Used
*React.js*

**Why**: React provides a modular and component-based architecture that simplifies the management of the UI state and the rendering process. This is particularly beneficial for dynamic, interactive apps like a calendar.
Usage: The app uses React components (useState for state management) to handle user interactions, manage the app's internal state (e.g., current month/year, events), and render updates dynamically.

*CSS*

**Why**: CSS ensures a visually appealing and responsive design, allowing users to interact seamlessly across devices.
Usage: The app's CSS styles define the layout, colors, typography, and interaction feedback. For example:
The calendar grid (.days, .weekdays) and navigation buttons are styled for clarity and usability.
The event popup uses CSS for a modal-like appearance.

*JavaScript (Core)*

**Why**: Provides the logic for date manipulation, event validation, and application state.
Usage: Functions like prevMonth, nextMonth, and handleDayClick handle user interactions with the calendar. Utilities such as isTimeOverlap and isSameDay ensure event scheduling is logical and error-free.

*Boxicons (Icons)*:

**Why:** Boxicons is a lightweight, scalable icon library, ensuring a consistent aesthetic and easy integration.
How: Icons such as arrows, edit, and delete are integrated to enhance interactivity and visual clarity.

*Google Fonts (Typography):*

**Why:** Google Fonts provide a wide variety of high-quality fonts, improving readability and aesthetic appeal.
How: Custom fonts are used to align with the app's modern design language.

## Key Features:

1. *Date Navigation:*
    1. Navigate through months using arrow buttons.
    2.  Display current month and year.

2. *Event Management*:
    1. Add events with specific start and end times, descriptions, and types (e.g., Work, Personal, Others)
    2. Prevent overlapping events on the same day.
    3. Edit or delete events easily using action icons.
       
3. *UI Enhancements*:
    1. Visually distinguish current day, selected day, and event types using distinct styles.
    2. Popup forms for event creation and editing.

## Future Improvements
1. LocalStorage/Database Integration:
To persist events across sessions, allowing users to retrieve their schedules even after refreshing the page.
Use localStorage or a back-end service with APIs (e.g., Firebase, Node.js).
2. Event Filters/Sorting:
Enable users to sort events by time or filter them by category (e.g., only show Work events).
3. Animations:
Add transitions for better feedback when navigating months or opening/closing the event popup.
preferences.
