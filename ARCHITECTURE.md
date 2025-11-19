| Path                        | Description                                         |
|-----------------------------|-----------------------------------------------------|
| backend/                    | Backend application for API and business logic      |
| node_modules/               | Node.js backend dependencies                        |
| scripts/                    | Utility scripts for automation or data setup        |
| seedRooms.ts                | Seeds initial room data into database               |
| src/                        | Main backend source files                           |
| controllers/                | Controllers for route request handling              |
| bookingsController.ts       | Handles booking-related logic and API requests      |
| roomsController.ts          | Handles room-related logic and API requests         |
| entity/                     | TypeORM database models                             |
| Booking.ts                  | Booking entity/model for ORM                        |
| Room.ts                     | Room entity/model for ORM                           |
| routes/                     | API route definitions                              |
| analyticsRoutes.ts          | Analytics API endpoint routes                       |
| bookingRoutes.ts            | Booking endpoint routes                             |
| roomRoutes.ts               | Room endpoint routes                                |
| app.ts                      | Main Express app configuration                      |
| .env                        | Environment variables for backend config            |
| ormconfig.json              | TypeORM config for database and entities            |
| package-lock.json           | Backend dependency lock file                        |
| package.json                | Backend dependencies and scripts                    |
| tsconfig.json               | TypeScript config for backend compilation           |
| frontend/                   | React-based frontend application                    |
| node_modules/               | Frontend dependencies                              |
| public/                     | Static files/assets for client                      |
| index.html                  | Main frontend HTML entrypoint                       |
| meeting.png                 | Image asset for workspace booking                   |
| src/                        | Main frontend source files                          |
| components/                 | Reusable React UI components                        |
| AdminAnalytics.js           | Admin dashboard analytics UI                        |
| BookingForm.js              | Workspace booking form UI                           |
| RoomList.js                 | Room/workspace listing UI                          |
| UserBookings.js             | User booking history UI                            |
| pages/                      | Main application pages/views                        |
| AdminPage.js                | Admin dashboard page                                |
| HomePage.js                 | Workspace booking home page                         |
| services/                   | API service utilities                               |
| api.js                      | Logic for frontend API requests                     |
| App.css                     | Main stylesheet for frontend app                    |
| App.js                      | Root React component for app bootstrap              |
| index.css                   | Entry point stylesheet for UI                       |
| index.js                    | JavaScript entry point for frontend                 |

User -->|HTTP| Frontend
Frontend -->|API Calls| Backend
Backend -->|ORM Queries| DB


