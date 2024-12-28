# PokedexLite
PokedexLite is a responsive web app built with React.js, allowing users to search and browse Pokémon by name or type. It displays stats, abilities, and types with a clean design optimized for all devices. Hosted on Vercel, it ensures fast performance while showcasing modern web development practices.

Installation Instructions:

markdown
Copy code
## Installation Instructions

1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Install dependencies:
npm install
Run the development server:
npm start
Open the app at:
http://localhost:3000

Technologies Used:
- **React.js**: For building dynamic, reusable UI components.
- **CSS Modules**: For scoped and modular styling.
- **JavaScript (ES6+)**: For handling app logic.
- **Vercel**: For hosting and deployment.
- **REST API** (if applicable): For fetching Pokémon data in real-time.

Challenges Faced:

- API Integration**: Managing asynchronous API calls efficiently.
  - Solution**: Used React’s `useState` and `useEffect` hooks to manage state and lifecycle methods.
- Responsive Design: Ensuring the app worked well on all screen sizes.
  - Solution: Implemented CSS media queries for a responsive layout.
- **Deployment Issues**: Encountered issues with environment variables during deployment.
  - **Solution**: Adjusted `.env` files and fine-tuned Vercel deployment settings.
