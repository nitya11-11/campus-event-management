EventHive - Campus Event Management Portal

EventHive is a lightweight, single-page web application designed for managing campus events, technical workshops, cultural fests, and competitions.
Built using vanilla HTML5, CSS3, and JavaScript, it provides an intuitive interface for both students and campus event organizers without requiring 
external frameworks or backend setup.

Key Features

For Students
- Event Directory: Browse upcoming campus events with real-time seat tracking.
- Search & Filter: Easily search events by title, venue, or keywords, and filter by categories (College Fest, Workshop, Seminar, Competition).
- Instant Registration: Register for events using student details with built-in seat validation to prevent overbooking.
- Digital Event Pass: Automatically generate printable confirmation tickets with unique ticket IDs.
- My Tickets View: Easily access and review all your registered event passes in one place.

For Organizers / Admins
- Event Creation: Publish new events with custom capacity limits, schedules, venues, and eligibility rules.
- Seat Management: Track live registration numbers and seat availability.
- Participant Rosters: View the complete directory of registered students across all events.
- Event Moderation: Remove or update past and canceled events from the directory.

User Interface & Experience
- Dark Mode Support: Toggle between light and dark visual themes.
- Responsive Design: Optimized layout for desktops, tablets, and mobile screens.
- Local Persistence: Uses browser `localStorage` to save events and student registrations locally.

Built With

- HTML5: Semantic structure and accessible modal overlays.
- CSS3: Custom properties (CSS variables), CSS Grid, Flexbox, and printable media styles.
- JavaScript (ES6): State management, DOM manipulation, and dynamic filters.

Getting Started

Since EventHive is built as a self-contained web application, running it is simple:

1. Clone or Download the project repository.
2. Open `scampus.html` directly in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).
3. No server installation, Node.js packages, or database setup required!

Data Storage

The application operates entirely on the client side using the browser's `localStorage` engine:
- `campus_events`: Stores custom and default event entries.
- `campus_registrations`: Stores generated student tickets and enrollment records.
