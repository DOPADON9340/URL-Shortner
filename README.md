# URL Shortener

A full-stack URL shortener application built with React, Redux Toolkit, Vite, and Node.js. Easily shorten long URLs, track link analytics, manage your links, and access a user-friendly dashboard with authentication. Modern UI, secure and efficient.

## Features

- Shorten long URLs instantly  
- Track link clicks and analytics  
- User registration and authentication  
- Link management dashboard  
- Responsive and modern UI  
- Built with React (Vite), Redux Toolkit, and Node.js backend  

## Tech Stack

- Frontend: React, Redux Toolkit, Vite  
- Backend: Node.js, Express (assumed, adjust if different)  
- Routing: @tanstack/react-router  
- State Management: Redux Toolkit  
- HTTP Client: axios  

## Installation

1. Clone the repo:
git clone [https://github.com/yourusername/your-repo.git](https://github.com/DOPADON9340/URL-Shortner)
cd your-repo

text

2. Install dependencies (frontend and backend):
npm install

text

3. Start the development server:
npm run dev # For frontend

and/or
npm start # For backend (if separate)

text

4. Open your browser and navigate to `http://localhost:3000` (or your specified port).

## Usage

- Register or login to create and manage your shortened URLs.  
- Paste any long URL in the input box to get a shortened link.  
- View stats and analytics for your URLs in the dashboard.

## Troubleshooting

- If you get errors like "**Failed to resolve import '@tanstack/react-router'**," make sure to install all dependencies:
npm install @tanstack/react-router @reduxjs/toolkit react-redux axios

text
- Fix any import paths such as changing `..utils/axiosInstance` to `../utils/axiosInstance`.

- After installing new packages, restart your dev server:
npm run dev

text

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.


---
**Note:** Replace URLs, scripts, and backend instructions as per your actual setup.

Let me know if you want me to add example code snippets, API usage, or deployment instructions!
