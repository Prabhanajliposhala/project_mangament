# Project Management Tool

A modern, full-stack project management application built with React, Redux, and Node.js. This tool helps teams organize projects, track tasks, and collaborate effectively.

![Project Management Tool](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?auto=format&fit=crop&q=80&w=1200)

## Features

- 📊 **Dashboard Overview**: Get quick insights into active projects and task status
- 📝 **Project Management**: Create, update, and track project progress
- ✅ **Task Tracking**: Manage tasks with priorities and due dates
- 👥 **User Authentication**: Secure login and authentication system
- 🎨 **Modern UI**: Clean and responsive design with Tailwind CSS
- 🔄 **Real-time Updates**: State management with Redux for seamless updates

## Tech Stack

### Frontend
- React.js
- Redux Toolkit for state management
- React Router for navigation
- Tailwind CSS for styling
- TypeScript for type safety
- Lucide React for icons

### Backend
- Node.js
- Express.js
- PostgreSQL with Supabase
- JWT for authentication

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL database

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/project-management-tool.git
cd project-management-tool
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Create a `.env` file in the root directory and add:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server
```bash
npm run dev
```

## Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/         # Page components
├── store/         # Redux store and slices
├── types/         # TypeScript type definitions
└── main.tsx       # Application entry point
```

## Features in Detail

### Dashboard
- Overview of active projects
- Task statistics
- Recent activity feed

### Projects
- Create new projects
- Assign team members
- Track project status
- Set project deadlines

### Tasks
- Create and assign tasks
- Set priority levels
- Track task status
- Set due dates

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.com/)
