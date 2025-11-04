# Charging Station — Frontend

Simple React + Vite + TypeScript frontend for the Charging Station dashboard.
- Used Tailwind CSS for UI
- Homepage conists of Charging station cards if uploaded from admin through the create station form.
- Navbar has Login button which directs to admin dashboard after valid admin credentials.
- All the data added from frontend UI gets stored into postgre sql database.
- Used NestJS in Backend to Implement a RESTful API with endpoints that perform CRUD operations for the station records.
- You can find admin credentials added inisde file auth.service.ts file in backend application for admin login through frontend which are added static.Later we can hide that credentials by adding .env file.
- Before running the project need to do yarn install for all necessary packages and node modules as I have deleted node module before      uploading file here.
- You can Find all other details about project structure and ho to run project below.

## Prerequisites

- Node.js v18+ and npm
- A backend API (optional) — update endpoints in `src/api` if needed

## Setup and run (development)

1. Open PowerShell in the project root (`d:\ChargingStation\charging_station_fe`).
2. Install dependencies:

   ```cmd
   yarn install
   ```

3. Start dev server:

   ```cmd
   yarn run dev
   ```

4. Open `http://localhost:5173` in your browser.

## Build for production

1. Build:

   ```bash
   yarn run build
   ```


## Notes

- To change the API base URL, edit files in `src/api/`.
- If the navbar still shows Login after logging in, make sure the app state updates `isAdmin` and that `Navbar` receives the `isAdmin` prop.

## Project structure

- `src/` — source code
- `src/components` — UI components
- `src/api` — API helpers
- `public/` — static assets
- `package.json` — scripts & deps


