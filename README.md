# CAD Viewer Pro

A modern, web-based 3D CAD viewer built with React and Three.js that allows users to view and interact with STL and OBJ files directly in the browser.


## 🚀 Features

- **File Support**
  - STL file viewing
  - OBJ file viewing
  - Drag and drop file upload

- **Viewing Controls**
  - Interactive 3D model manipulation
  - Zoom slider with precise control
  - Camera position presets (Top, Front, Side views)
  - Reset view option

- **Display Options**
  - Toggle grid display
  - Toggle axis display
  - Wireframe mode
  - Model color customization

- **User Interface**
  - Modern, clean design
  - Collapsible control panel
  - Responsive layout
  - Loading indicators
  - Error handling

## 🛠️ Technologies Used

- **Frontend**
  - React.js
  - Three.js
  - React Three Fiber
  - React Three Drei
  - Framer Motion

- **Backend**
  - Node.js
  - Express.js
  - Multer (file handling)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/kilarimohan/cad-viewer.git
```

2. Navigate to the project directory:
```bash
cd cad-viewer
```

3. Install dependencies for both frontend and backend:
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

4. Start the development servers:
```bash
# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
cd ../frontend
npm start
```

## 🎮 Usage

1. Open your browser and navigate to `http://localhost:3000`

2. Upload a CAD file:
   - Click the "Upload" button or drag and drop a file
   - Supported formats: .stl, .obj

3. Interact with the model:
   - Left click + drag to rotate
   - Right click + drag to pan
   - Scroll to zoom
   - Use the zoom slider for precise zoom control

4. Use the control panel to:
   - Adjust view settings
   - Change model color
   - Toggle grid/axes
   - Switch between different camera views

## 🔧 Configuration

### Backend Configuration
The backend server runs on port 5000 by default. To change this:
1. Create a `.env` file in the backend directory
2. Add: `PORT=your_preferred_port`

### Frontend Configuration
To configure the frontend development server:
1. Create a `.env` file in the frontend directory
2. Add necessary environment variables

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:
```bash
git commit -m 'Add some AmazingFeature'
```
4. Push to the branch:
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Future Improvements

- [ ] Support for more file formats (STEP, IGES)
- [ ] Measurement tools
- [ ] Cross-section view
- [ ] Export capabilities
- [ ] Model annotation features
- [ ] Custom material properties
- [ ] Scene lighting controls

## 🐛 Known Issues

- Please report any bugs in the Issues section

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainer.

## 👤 Author

**Kilari Mohan Sai**
- LinkedIn: [Mohan Kilari](https://www.linkedin.com/in/mohan-kilari-207a131a2/)
- GitHub: [@Mohan-github]([https://github.com/kilarimohan](https://github.com/Mohan-gtihub))

## 🙏 Acknowledgments

- Three.js community
- React Three Fiber team
- All contributors who have helped with the project

---

Made with ❤️ by [Kilari Mohan Sai]
