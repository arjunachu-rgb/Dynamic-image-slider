Dynamic Image Slider

The Dynamic Image Slider is a responsive, user-friendly web component designed to display a series of images with smooth transitions and interactive controls. It allows users to view images in a sliding format, either automatically or manually, providing an elegant and engaging way to showcase visual content on a website.

🚀 Overview

This project demonstrates how to create a fully functional image slider using HTML, CSS, and JavaScript. It supports both static and dynamic image loading, meaning images can be added directly in the code or fetched from an external source (like a JSON file or API).

✨ Features

🔄 Automatic and manual sliding options

🎨 Smooth transitions and animations

📱 Fully responsive design for all screen sizes

🧭 Navigation controls (arrows and indicator dots)

🖼️ Dynamic image loading from JSON or API

⏸️ Pause on hover and resume on mouse leave

♾️ Infinite loop functionality

🧰 Technologies Used

HTML5 – Structure and layout

CSS3 – Styling, transitions, and responsiveness

JavaScript (ES6) – Logic and interactivity

📁 Folder Structure
dynamic-image-slider/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Styles and animations
├── js/
│   └── script.js       # Slider functionality
├── images/
│   └── ...             # Image assets
└── data/
    └── images.json     # JSON file for dynamic image loading (optional)

⚙️ Installation & Usage

Clone the repository

git clone https://github.com/yourusername/dynamic-image-slider.git


Open the project folder

cd dynamic-image-slider


Run the project

Open the index.html file in any modern web browser.

The image slider will start automatically.

🧠 How It Works

The slider is initialized when the webpage loads.

JavaScript controls image transitions, navigation buttons, and autoplay settings.

Images can be loaded dynamically from a JSON file or API for flexible content management.

CSS animations ensure smooth and visually appealing slide effects.

🛠️ Customization

You can easily customize the slider according to your needs:

Adjust autoplay speed and transition duration in script.js.

Modify colors, fonts, and layout in style.css.

Replace existing images or update images.json for new content.

📄 Example JSON Format
[
  {
    "url": "images/slider1.jpg",
    "caption": "Beautiful Sunset"
  },
  {
    "url": "images/slider2.jpg",
    "caption": "Mountain View"
  },
  {
    "url": "images/slider3.jpg",
    "caption": "Ocean Breeze"
  }
]

👨‍💻 Author

Arjun.S.S

📧 arjunanandhuachu@gmail.com

📝 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it with proper attribution.
