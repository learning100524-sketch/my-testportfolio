# My Portfolio Website

A professional portfolio website showcasing my work, skills, and projects. Built with clean HTML, CSS, and JavaScript for a modern, responsive experience.

## How to Access the Portfolio

### Option 1: Open Directly in Browser (Simplest)

1. Clone or download this repository
2. Navigate to the project folder
3. Double-click on `index.html` to open it in your default web browser

### Option 2: Using a Local Server (Recommended)

For the best experience, run a local web server:

#### Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open http://localhost:8000 in your browser

#### Using Node.js:
```bash
# Install http-server globally (one-time)
npm install -g http-server

# Run server
http-server -p 8000
```
Then open http://localhost:8000 in your browser

#### Using VS Code:
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Deploy Online

Deploy to a hosting platform to make your portfolio accessible on the internet:

- **GitHub Pages**: Enable GitHub Pages in repository settings, select the main branch
- **Netlify**: Drag and drop the project folder to https://app.netlify.com/drop
- **Vercel**: Connect your GitHub repository at https://vercel.com

## Project Structure

```
my-testportfolio/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript for interactions
└── README.md       # This file
```

## Features

- 📱 Fully responsive design
- 🎨 Modern and clean UI
- 🔗 Smooth scrolling navigation
- 📋 Sections: Home, About, Skills, Projects, Contact
- 🍔 Mobile-friendly hamburger menu

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

## Customization

To personalize this portfolio:
1. Edit `index.html` to update your name, bio, projects, and contact info
2. Modify `style.css` to change colors, fonts, and layout
3. Customize `script.js` for additional interactivity

## License

MIT License - Feel free to use this portfolio template for your own projects.