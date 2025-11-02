# MS-DOS Commands - Interactive Learning Platform

An interactive web-based platform for learning and practicing MS-DOS commands. This project combines an educational website with a functional command prompt emulator to help users understand and experiment with DOS commands in a safe, browser-based environment.

![MS-DOS Commands](https://img.shields.io/badge/MS--DOS-Commands-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Features

### Educational Website
- **Interactive Landing Page**: Modern, responsive design built with HTML5 UP's Hyperspace template
- **Comprehensive DOS Guide**: Learn about MS-DOS commands and their usage
- **Command Reference**: Detailed list of available DOS commands with explanations
- **Smooth Navigation**: Single-page application with smooth scrolling between sections

### Command Prompt Emulator
- **Real-time Command Execution**: Practice DOS commands in a safe, simulated environment
- **Authentic Interface**: Mimics the classic Windows command prompt appearance
- **Supported Commands**: Includes help, date, time, cls, dir, ver, exit, echo, ping, ipconfig, systeminfo, cd, attrib, break, tree, chkdsk, and more
- **Interactive Learning**: Type commands and see instant feedback

## 📋 Supported DOS Commands

The emulator supports the following commands:
- `help` - Display available commands
- `date` - Show current date
- `time` - Show current time
- `cls` - Clear the screen
- `dir` - Display directory contents
- `ver` - Show system version
- `exit` - Close the command prompt
- `echo` - Display messages
- `ping` - Network connectivity test
- `ipconfig` - Display network configuration
- `systeminfo` - Show system information
- `cd` - Change directory
- `attrib` - Display/modify file attributes
- `break` - Set break checking
- `tree` - Display directory structure
- `chkdsk` - Check disk for errors
- And more...

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/alfredmagat23/MSDOS.git
   cd MSDOS
   ```

2. **Open the project**
   - Open `index.html` in your web browser for the main educational site
   - Navigate to the CMD emulator folder and open `aaa.html` for the command prompt emulator

3. **No build process required!**
   - This is a static website - just open the HTML files in any modern web browser

## 📁 Project Structure

```
MSDOS/
├── index.html                  # Main landing page
├── elements.html              # UI elements reference
├── generic.html               # Generic page template
├── assets/                    # Website assets
│   ├── css/                   # Stylesheets
│   ├── js/                    # JavaScript files
│   ├── sass/                  # SASS source files
│   └── webfonts/              # Font files
├── images/                    # Image assets
└── ito yung cmd emulator/     # CMD Emulator
    ├── aaa.html               # Emulator interface
    ├── script.js              # Command handling logic
    └── style.css              # Emulator styles
```

## 💻 Usage

### Main Website
1. Open `index.html` in your browser
2. Navigate through the sections:
   - **Welcome**: Introduction to MS-DOS commands
   - **What is MS-DOS**: Learn about DOS and its importance
   - **List of Commands**: Browse available commands
   - **Get in Touch**: Contact information

### Command Prompt Emulator
1. Open `ito yung cmd emulator edit niyo nalang yung js nito ako na bahala mag connect/aaa.html`
2. Type commands in the input field
3. Press Enter to execute
4. Type `help` to see available commands
5. Type `cls` to clear the screen

## 🎨 Customization

### Modifying the Emulator
The command logic is located in `script.js`. To add new commands:

```javascript
case 'yourcommand':
case 'YourCommand':
case 'YOURCOMMAND':
    yourCommandFunction();
    break;
```

### Styling
- Website styles: `assets/css/main.css` or modify SASS files in `assets/sass/`
- Emulator styles: `ito yung cmd emulator/style.css`

## 👥 Authors

- **Fritz Catalan**
- **Alfred Magat**
- **Justin Morales**

## 📝 License

This project is free for personal and commercial use under the CCA 3.0 license.

### Template Credits
The main website uses the Hyperspace template by HTML5 UP:
- Template: [HTML5 UP](https://html5up.net)
- Design by [@ajlkn](https://twitter.com/ajlkn)

### Additional Credits
- Icons: [Font Awesome](http://fontawesome.io)
- jQuery: [jquery.com](http://jquery.com)
- Scrollex: [github.com/ajlkn/jquery.scrollex](https://github.com/ajlkn/jquery.scrollex)
- Demo Images: [Unsplash](http://unsplash.com)

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

If you encounter any bugs or issues, please open an issue on the GitHub repository with:
- A clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 🔮 Future Enhancements

- [ ] Add more DOS commands to the emulator
- [ ] Implement file system simulation
- [ ] Add command history navigation (up/down arrows)
- [ ] Create interactive tutorials for each command
- [ ] Add dark/light theme toggle
- [ ] Backend integration for advanced features

## 📧 Contact

For questions or suggestions, please reach out to the development team through the website's contact section.

---

Made with ❤️ for MS-DOS enthusiasts and learners everywhere!