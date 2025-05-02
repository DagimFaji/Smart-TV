# Smart-TV
Smart TV Menu Interface
A responsive, TV-optimized user interface built for large-screen displays, showcasing pixel-perfect UI development with focus navigation, WebGL animations, and modular design. This project demonstrates skills in translating Figma designs into a Smart TV frontend using Next.js, Tailwind CSS, and Pixi.js, tailored for a Frontend Developer role.
Features

Pixel-Perfect UI: Responsive menu interface optimized for Smart TV displays.
Focus Navigation: TV remote-compatible navigation using arrow keys and Enter key.
Interactive Popup: Dynamic popup triggered by menu item selection.
WebGL Animations: Smooth, rotating square animation using Pixi.js for engaging visuals.
Modular Design: Reusable React components styled with Tailwind CSS for scalability.

Technologies Used

Next.js: React framework for server-side rendering and scalable frontend development.
Tailwind CSS: Utility-first CSS framework for rapid, responsive styling.
Pixi.js: WebGL library for high-performance 2D animations.
React: Component-based UI development.

Getting Started
Prerequisites

Node.js (v16 or higher)
npm or yarn

Installation

Clone the repository:
git clone https://github.com/dagimfaji/smart-tv-menu.git
cd smart-tv-menu


Install dependencies:
npm install


Run the development server:
npm run dev


Open http://localhost:3000 in your browser to view the app.


Project Structure
smart-tv-menu/
├── components/
│   ├── MenuItem.js        # Menu item component with focus navigation
│   ├── Popup.js           # Popup component for menu interactions
│   └── WebGLAnimation.js  # Pixi.js animation component
├── pages/
│   └── index.js           # Main page with menu and navigation logic
├── styles/
│   └── globals.css        # Tailwind CSS and global styles
├── package.json           # Project dependencies and scripts
├── next.config.js         # Next.js configuration
├── tailwind.config.js     # Tailwind CSS configuration
└── README.md              # Project documentation

Usage

Navigation: Use the left and right arrow keys to navigate between menu items (Home, Movies, Series, Live TV). The focused item is highlighted with a blue background and scale effect.
Selection: Press the Enter key or click a menu item to open a popup displaying the selected item's content.
Animation: A rotating square animation powered by Pixi.js runs above the menu, demonstrating WebGL capabilities.
Responsive Design: The UI is optimized for large screens with clear typography and spacing, adhering to Smart TV UX principles.

Deployment
To deploy the app, use a platform like Vercel:

Push the repository to GitHub.
Connect the repository to Vercel via the Vercel dashboard.
Deploy with default settings for Next.js.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
License
This project is licensed under the MIT License.
Contact

Name: Dagim Faji
Email: dagimfaji@gmail.com
GitHub: github.com/dagimfaji
LinkedIn: linkedin.com/in/dagimfaji


This project was built to demonstrate expertise in Figma-to-code workflows, Smart TV UI design, and WebGL animations for a Frontend Developer role.
