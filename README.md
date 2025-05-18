# Interactive 3D Flower Viewer

An interactive web application that displays a beautiful 3D flower model with various interactive features.

## Features

- Interactive 3D flower model with smooth animations
- Wireframe mode toggle
- Zoom in/out functionality
- Progressive drawing animation
- Responsive design for all devices
- Beautiful message display
- Smooth transitions and effects
- Automated deployment with GitHub Actions

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Three.js for 3D rendering
- GLTFLoader for 3D model loading

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Open the project folder:
```bash
cd Roses
```

3. Start a local server (using Python):
```bash
python3 -m http.server 8000
```

4. Open your browser and navigate to:
```
http://localhost:8000/message.html
```

### Deployment

This project can be easily deployed using any of these free hosting services:

#### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings
3. Scroll to "GitHub Pages" section
4. Select "main" branch as source
5. Your site will be available at: `https://YOUR_USERNAME.github.io/interactive-flower-viewer`

#### Netlify
1. Sign up at https://app.netlify.com/
2. Connect your GitHub repository
3. Deploy settings:
   - Build command: leave empty
   - Publish directory: ./
4. Your site will be available at: `https://your-site-name.netlify.app`

#### Vercel
1. Sign up at https://vercel.com/
2. Import your GitHub repository
3. Deploy settings:
   - Framework Preset: Other
   - Build Command: leave empty
   - Output Directory: ./
4. Your site will be available at: `https://your-site-name.vercel.app`

## Project Structure

- `message.html` - Initial welcome page
- `message2.html` - Second message page
- `message3.html` - Third message page
- `message4.html` - Fourth message page
- `flower.html` - Main 3D flower viewer
- `flores gratuito/` - Directory containing 3D model files

## Features in Detail

### 3D Model Viewer
- Smooth camera controls
- Interactive rotation and zoom
- High-quality lighting and shadows
- Responsive design for all screen sizes

### Animation
- Progressive wireframe drawing
- Smooth transitions
- Automatic playback
- Play/pause controls

### UI Elements
- Clean, modern interface
- Responsive controls
- Beautiful typography
- Smooth animations

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Three.js for the 3D rendering capabilities
- The original 3D model creator 