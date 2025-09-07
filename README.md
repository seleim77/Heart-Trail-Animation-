# ❤️ Heart Trail Animation

A beautiful and interactive heart trail animation that follows your mouse cursor with colorful animated hearts floating upward.

## 🌟 Features

- **Interactive Mouse Following**: Hearts spawn wherever you move your mouse
- **Dynamic Animation**: Hearts float upward while rotating through different colors
- **Random Sizing**: Each heart has a random size for visual variety
- **Smooth Performance**: Automatic cleanup prevents memory issues
- **Responsive Design**: Works on all screen sizes

## 🚀 Demo

Move your mouse around the screen and watch as colorful hearts trail behind your cursor, floating upward with a beautiful animation effect!

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and visual effects
- **Vanilla JavaScript**: Interactive functionality and DOM manipulation

## 📁 Project Structure

```
Heart-Trail-Animation/
├── index.html          # Main HTML structure
├── style.css           # Styling and animations
├── main.js             # JavaScript functionality
└── README.md           # Project documentation
```

## 🎯 How It Works

1. **Mouse Detection**: JavaScript listens for mouse movement events across the entire page
2. **Heart Creation**: For each mouse movement, a new heart element is dynamically created
3. **Positioning**: Hearts are positioned at the exact mouse coordinates
4. **Animation**: CSS animations make hearts float upward while changing colors
5. **Cleanup**: Hearts automatically remove themselves after 3 seconds to prevent memory buildup

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heart-trail-animation.git
   ```

2. Navigate to the project directory:
   ```bash
   cd heart-trail-animation
   ```

3. Open `index.html` in your web browser:
   ```bash
   # On Linux/Mac
   open index.html
   
   # On Windows
   start index.html
   
   # Or simply double-click the file
   ```

### Usage

Simply open the HTML file in your browser and start moving your mouse around the screen. Enjoy the heart trail animation!

## 🎨 Customization

You can easily customize the animation by modifying:

- **Heart Image**: Change the background image URL in `style.css` (line 15)
- **Animation Duration**: Adjust the timeout value in `main.js` (line 15)
- **Colors**: Modify the `hue-rotate` values in the CSS animation
- **Size Range**: Change the random size calculation in `main.js` (line 10)
- **Animation Speed**: Adjust the animation duration in `style.css` (line 26)

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🤝 Contributing

Feel free to contribute to this project! Here's how:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Selim** - [Your GitHub Profile](https://github.com/yourusername)

## 🎉 Acknowledgments

- Heart icon from [Iconfinder](https://www.iconfinder.com/)
- Inspiration from interactive web animations
- Thanks to the JavaScript and CSS animation community

---

⭐ Star this repository if you found it helpful!
