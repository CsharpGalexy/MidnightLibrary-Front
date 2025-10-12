# MidnightLibrary-Front 📚

A digital library frontend project built with Next.js, providing a modern and responsive interface for book management and reading.

## Links Usefull

- [Demo](https://midnightlibraryteam.onrender.com/)
- [BackEnd](https://github.com/CsharpGalexy/MidnightLibrary-Back)
- [Old Project](https://github.com/abolfazlshs80/TeamLibrary)


## Project Structure 🗂️

```
MidnightLibrary-Front/
├── app/                      # Main application pages
│   ├── AboutUs/             # About Us page
│   ├── Auth/                # Authentication related pages
│   │   ├── ForgetPassword/  # Password recovery page
│   │   ├── login/          # Login page
│   │   ├── Profile/        # User profile page
│   │   └── signup/         # Registration page
│   ├── dashboard/          # Admin dashboard
│   ├── detail/            # Book details page
│   ├── explore/          # Search and explore page
│   └── Favorite/         # Favorites page
├── assets/               # Static assets
├── components/           # Reusable components
├── context/             # React contexts
├── lib/                 # Libraries and helper functions
├── modal/               # Type definitions and models
└── utils/               # Utility functions
```

## Technologies Used 🛠️

- [Next.js](https://nextjs.org/) - React framework for production
- [TypeScript](https://www.typescriptlang.org/) - Static typing for JavaScript
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Axios](https://axios-http.com/) - Promise based HTTP client

## Installation and Setup 🚀

1. Clone the repository:
```bash
git clone https://github.com/CsharpGalexy/MidnightLibrary-Front.git
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. View in browser:
```
http://localhost:3000
```

## Pages Structure 📄

- `/` - Home page
- `/AboutUs` - About Us page
- `/Auth/login` - Login page
- `/Auth/signup` - Sign Up page
- `/Auth/ForgetPassword` - Password Recovery page
- `/Auth/Profile` - User Profile page
- `/dashboard` - Admin Dashboard
- `/explore` - Search and Explore page
- `/detail/[slug]` - Book Details page
- `/Favorite` - Favorite Books page

## Features ✨

- 🔐 Complete Authentication System
- 📚 Book Management
- 🏷️ Book Categories
- 💖 Favorites System
- 🔍 Advanced Search
- 📱 Responsive UI
- 🌙 Dark/Light Mode
- 📖 Reading Progress Tracking
- 🔖 Bookmarking System

## Contributing 🤝

We welcome contributions to MidnightLibrary! Here's how you can help:

1. Fork the project
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License.
