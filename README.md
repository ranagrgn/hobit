**Hobit – Habit Tracking and Reminder Mobile Application**

About the Project
Hobit is a mobile application designed to help users build and maintain healthy daily routines. The application allows users to create personal habits, schedule reminders, record daily completions and monitor their progress.
The main target audience is university students who want to organize their daily activities and maintain consistent routines through a simple and user-friendly mobile application.

Project Objectives
The main objectives of Hobit are:

* To make habit creation and management simple.
* To help users maintain consistent daily routines.
* To provide customizable reminders for planned habits.
* To record daily habit completion.
* To visualize progress through calendar and statistics features.
* To support offline usage and cloud synchronization.

Planned Features

1. User Authentication

* Login using email and password.
* Google sign-in integration.
* Password recovery.

2. Habit Management

* Create new habits.
* Edit existing habits.
* Select a starting date.
* Configure repetition frequency (daily, weekly or one-time).
* Archive habits.

3. Daily Habit Tracking

* View daily habits.
* Mark habits as completed.
* Store dated completion records.

4. Reminders and Notifications

* Set reminder times for habits.
* Schedule local notifications.
* Modify or cancel reminders.

5. Calendar and Statistics

* View completed habits on a calendar.
* Track consecutive completion days.
* Display weekly completion rates and progress statistics.

6. Data Synchronization

* Store habit records locally.
* Support offline access.
* Synchronize user data with Firebase Cloud Firestore when online.

Screens
The planned application includes the following main screens:

* Login Screen
* Home Screen
* Add/Edit Habit Screen
* Calendar Screen
* Statistics Screen
* Settings Screen

<img width="1280" height="523" alt="image" src="https://github.com/user-attachments/assets/7c0565c6-01e2-4240-9beb-76551065d520" />

The habit creation process is divided into two steps. Users first enter the habit name and starting date, then configure the repetition frequency and reminder time.

Technology Stack
The planned technologies for the project include:

| Technology / Tool | Purpose |
| --- | --- |
| Flutter | Cross-platform mobile application development framework |
| Dart | Application programming language |
| Provider & ChangeNotifier | State management and UI state change notifications |
| Inter (Typeface) | Clean and readable primary typography family supporting visual hierarchy |
| Firebase Authentication | User authentication (Email/password and Google Sign-In) |
| Cloud Firestore | Cloud data storage and synchronization for online states |
| Local Database | Offline data access and local record storage |
| Local Notifications | Scheduled reminder notifications for habits |

Software Architecture
Hobit follows the Model–View–ViewModel (MVVM) architectural pattern, ensuring a clear separation of concerns across its components:

* **View**: Flutter screens, form components, card-based layout structures, and user interface elements. Designed with a soft green-based color palette (#2C6658 primary color, #E9F1E9 secondary color, #EDF4EE background, #FCFCFA form cards, and #F3F7F1 input fields) to ensure a unified visual hierarchy and a calm user experience.
* **ViewModel**: Manages screen state, input validation, loading states, the two-step habit creation workflow, and user actions.
* **Model**: Represents application entities such as User, Habit, and Completion.
* **Repository**: Coordinates data operations between the application and local storage or cloud Firestore.
* **Notification Service**: Manages notification permissions, scheduling, and cancellations.
* **State Management**: Utilizes Provider and ChangeNotifier to manage and propagate UI state changes effectively.

Data Model
The main planned entities are:

* **User**: Stores user information such as UID, email and display name.
* **Habit**: Stores habit details, repetition days, reminder time and archive status.
* **Completion**: Stores daily habit completion records.
* **SyncMetadata**: Tracks pending changes and synchronization information.

Project Team

| Team Member | Main Responsibilities |
| --- | --- |
| Rana Girgin | Flutter interface, navigation, forms, calendar and statistics |
| Leyla Gülnur Gür | Data models, local database, Firebase authentication, Firestore synchronization and iOS integration |
| Duygu Eroğlu | Habit completion logic, notification scheduling and Android integration |

Development Status
Hobit is currently in the project planning and interface design stage.
The initial project proposal defines the application features, technical architecture, data models and development responsibilities. The interface design process includes the authentication screen, two-step habit creation process and habit tracking screen.
Implementation and integration will follow the planned development schedule.

Future Improvements
If the core application is completed successfully, additional improvements may include:

* More detailed progress insights.
* Improved habit suggestions.
* Additional customization options.
* Enhanced synchronization and user experience.

## Figma Design & Prototype

Our wireframes, high-fidelity mockups, and interactive prototype are available in Figma.

- **Wireframes & Mockups:** [View Figma Design](https://www.figma.com/design/kRzndoG4m3cEAJG7Kzudgz/Untitled?node-id=0-1&p=f&t=PKOoVD4r48VvKteB-0)
- **Interactive Prototype:** [Open Figma Prototype](https://www.figma.com/proto/kRzndoG4m3cEAJG7Kzudgz/Untitled?node-id=2-752&p=f&t=PKOoVD4r48VvKteB-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=2%3A752&show-proto-sidebar=1)

License
This project is developed for academic purposes as part of the MTM4681 Mobile Programming course.
