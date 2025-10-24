# Virtual Meet Reminder Assistant

The "Virtual Meet Reminder Assistant" is a web-based utility created by Syed Ismail N. Its purpose is to streamline the process of sending virtual meeting reminders to multiple colleagues through WhatsApp. It solves the common, repetitive problem of manually copying, pasting, and sending individual reminder messages, reducing the task to just a few clicks.

The application features a clean, two-step interface. In "Step 1," the user provides the essential meeting details: the "Meet Topic", "Date", "Time", and an optional "Meeting Link". In "Step 2," the user inputs all the recipient "WhatsApp Numbers" into a single text area, separated by commas. The tool instructs users to include the country code (e.g., '91' for India) without any '+' or '00' prefixes.

Once the user clicks the "Generate Notification Links" button, the application's built-in JavaScript validates the inputs. It then formats the raw date and time inputs into a user-friendly format (e.g., "Friday, October 24, 2025" and "03:00 PM").

The results are displayed in a new section on the page. This includes a "Message Preview", which shows the exact, formatted message that will be sent, incorporating the topic, date, time, and link. Below this preview, the tool generates a list of "Click to Notify" buttons. Each button corresponds to one of the phone numbers entered.

When the user clicks a specific button (e.g., "Notify 919876543210"), the app opens a wa.me (WhatsApp) link in a new browser tab. This link automatically opens a chat with the specified number and pre-populates the chat box with the complete, URL-encoded reminder message. For security, the user must still manually press "send" within the WhatsApp interface to dispatch the reminder. The project is built entirely with front-end technologies: HTML, vanilla JavaScript, and the Tailwind CSS framework.
