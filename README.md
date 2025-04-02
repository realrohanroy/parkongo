# Parkongo

Parkongo is an urban parking marketplace that connects drivers looking for parking with hosts who have available parking spaces.

## Features

- **Authentication System**: Login, signup, and password reset functionality
- **Renter Dashboard**: Find parking, manage bookings, vehicles, and payments
- **Responsive Design**: Mobile-friendly interface for all pages
- **Modern UI**: Built with Material UI and custom styling

## Tech Stack

- **Frontend**: Next.js, TypeScript, Material UI
- **Backend**: Django REST Framework (Python)
- **Authentication**: JWT-based authentication

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Python (v3.8 or higher)
- npm or yarn
- pip

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/parkongo.git
   cd parkongo
   ```

2. Set up the frontend:
   ```
   cd frontend
   npm install
   npm run dev
   ```

3. Set up the backend:
   ```
   cd backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Project Structure

- `frontend/`: Next.js frontend application
  - `src/app/`: Page components and routes
  - `src/components/`: Reusable UI components
  - `src/styles/`: Theme and global styles
- `backend/`: Django backend application
  - `api/`: REST API endpoints
  - `backend/`: Project settings

## Screenshots

[Include screenshots here]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Material UI for providing excellent component library
- Next.js team for the amazing framework 