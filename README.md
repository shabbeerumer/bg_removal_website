# Background Remover Pro

A modern, professional web application that removes backgrounds from images using AI technology. Built with HTML, CSS, and JavaScript, featuring a clean and intuitive user interface.

![Background Remover Pro](https://github.com/user-attachments/assets/bb144a9f-818d-4236-9da2-1326d7e80f62)
 <!-- You can add a screenshot of your application here -->

## Features

- 🎯 One-click background removal
- 🖼️ Support for JPG and PNG images
- 📱 Fully responsive design
- ⚡ Real-time preview
- 💾 Easy download of processed images
- 🎨 Modern UI with smooth animations
- 📤 Drag and drop file upload
- 🔄 Loading states and error handling

## Technologies Used

- HTML5
- CSS3 (with modern features like CSS Variables)
- JavaScript (ES6+)
- Bootstrap 5.3.3
- [Remove.bg API](https://www.remove.bg/api)
- Google Fonts (Inter)

## Getting Started

### Prerequisites

- A modern web browser
- An API key from [Remove.bg](https://www.remove.bg/api)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/shabbeerumer/background-remover-pro.git
cd background-remover-pro
```

2. Replace the API key in `index.html` (`REMOVE_BG_API_KEY`):
```javascript
const REMOVE_BG_API_KEY = "your-api-key-here";
```
> **Security Note:** For production deployments, proxy Remove.bg API calls through a backend server or serverless function so your API key is not exposed in client-side code.

3. Open `index.html` in your web browser or serve it using a local development server.

## Usage

1. Click the upload area or drag and drop an image file
2. Click the "Remove Background" button
3. Wait for the processing to complete
4. View the before/after comparison
5. Click "Download Result" to save your processed image

## Project Structure

```
background-remover-pro/
├── index.html        # Main HTML file & client logic
├── styles.css        # Styles and animations
└── README.md         # Documentation
```

## Features in Detail

### Modern UI Components

- Gradient hero section
- Drag and drop upload zone
- Interactive buttons with hover states
- Side-by-side image comparison
- Loading indicators
- Responsive design for all screen sizes

### Error Handling

- File type validation
- Size limit checks
- API error handling
- User feedback for all actions

### Animations

- Smooth hover effects
- Loading spinners
- Fade-in animations for results
- Interactive state changes

## API Usage

This project uses the Remove.bg API for background removal. The free API has the following limitations:

- 50 API calls per month
- Maximum image size: 10MB
- Output image resolution: 0.25 megapixels
- PNG output format

For higher limits and resolution, consider upgrading to a paid API plan.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Remove.bg](https://www.remove.bg) for the background removal API
- [Bootstrap](https://getbootstrap.com) for the CSS framework
- [Google Fonts](https://fonts.google.com) for the Inter font family
