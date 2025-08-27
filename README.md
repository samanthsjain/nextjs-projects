# NextJS Projects

A collection of Next.js projects and learning examples to help you master modern web development with React and Next.js.

## 📁 Project Structure

This repository contains various Next.js projects organized by learning progression:

### 01-starting-project
A foundational Next.js application demonstrating core concepts and features.

**Features:**
- 🏠 **Home Page** - Main landing page with header component
- 📄 **About Page** - Simple about section
- 📝 **Blog Section** - Dynamic blog with individual post pages
- 🎨 **Component Architecture** - Reusable header component
- 🔗 **Navigation** - Internal linking between pages
- 📱 **Responsive Design** - Modern CSS styling

**Pages:**
- `/` - Home page with welcome message
- `/about` - About page
- `/blog` - Blog listing page
- `/blog/[slug]` - Dynamic blog post pages

## 🚀 Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd nextjs-projects
   ```

2. **Navigate to a specific project:**
   ```bash
   cd 01-starting-project
   ```

3. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 🛠️ Available Scripts

Each project includes the following npm scripts:

- `npm run dev` - Starts the development server
- `npm run build` - Builds the application for production
- `npm run start` - Starts the production server
- `npm run lint` - Runs ESLint for code quality

## 🏗️ Project Architecture

### App Router Structure
The projects use Next.js 14 with the App Router, featuring:
- **File-based routing** - Pages are created by adding files to the `app` directory
- **Layout components** - Shared layouts across multiple pages
- **Dynamic routes** - Dynamic segments using `[slug]` notation
- **Component organization** - Reusable components in the `components` directory

### Key Technologies
- **Next.js 14.0.3** - React framework for production
- **React 18** - UI library
- **ESLint** - Code linting and quality
- **CSS Modules** - Scoped styling

## 📚 Learning Path

This repository is designed as a progressive learning experience:

1. **01-starting-project** - Basic Next.js concepts and routing
2. *(Future projects will be added here)*

## 🤝 Contributing

Feel free to contribute to this project by:
- Adding new example projects
- Improving existing code
- Adding documentation
- Reporting issues

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Vercel Platform](https://vercel.com) - Deploy your Next.js app

---

**Happy coding! 🚀**
