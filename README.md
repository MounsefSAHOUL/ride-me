##Full Stack app

⚙️ Tech Stack
React Native
Expo
Stripe
PostgreSQL
Google Maps
zustand
Clerk
Tailwind CSS

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/JavaScript-Mastery-Pro/uber.git
cd uber
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=

EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=

DATABASE_URL=

EXPO_PUBLIC_SERVER_URL=https://uber.dev/

EXPO_PUBLIC_GEOAPIFY_API_KEY=

EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
Replace the placeholder values with your actual Clerk, Stripe, NeonDB, Google Maps, andgeoapify credentials. You can obtain these credentials by signing up on the Clerk, Stripe, NeonDB, Google Maps and geoapify websites respectively.

Running the Project

npx expo start
Download the Expo Go app and Scan the QR code on your respective device to view the project.
