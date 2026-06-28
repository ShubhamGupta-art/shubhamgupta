# SG — Developer Portfolio Website

A premium, single-page developer portfolio website designed for a Machine Learning Engineer, Software Engineer, and Computer Vision Researcher.

## Features

- **Video Background**: Smooth, muted looping video background (`video_bloom.mp4`) with a high-fidelity image fallback (`still.jpg`) for iOS Safari compatibility.
- **Glassmorphism Design Theme**: Modern dark aesthetic utilizing tailored CSS variables, semi-transparent overlays (`backdrop-filter: blur(14px)`), and thin glowing borders.
- **Interactive Animations**:
  - Sequential staggered entrance animations on page load for the Hero section.
  - Expanding hover specifications panel in the Research section.
  - Multi-phase staggered hover slide-up overlay on Project Cards.
- **IntersectionObserver reveals**: Scroll-aware reveals that fade and translate sections into view.
- **Responsive Layout**: Designed to dynamically adapt to desktop, tablet, and mobile breakpoints with sticky navigation active trackers and collapsible menus.

## Technologies Used

- **Core**: HTML5, Vanilla JavaScript, CSS3
- **Fonts**: Space Grotesk, Inter, JetBrains Mono (via Google Fonts)
- **Icons**: Inline SVGs

## Project Structure

```
├── index.html         # Main page entrypoint containing all HTML, CSS, and JS
├── video_bloom.mp4    # Dark ambient video background
├── still.jpg          # Video poster fallback image
├── ir.jpg             # Infrared image for research strip
├── visible.jpg        # Visible light image for research strip
├── fused.jpg          # Multi-spectral fused result for research strip
├── proj_ale.jpg       # Project thumbnail (ALE fusion)
├── proj_pipeline.jpg  # Project thumbnail (ML pipeline)
├── proj_analyzer.jpg  # Project thumbnail (LLM analyzer)
├── proj_edusense.jpg  # Project thumbnail (EduSense)
├── proj_smartrail.jpg # Project thumbnail (SmartRail)
└── proj_node.jpg      # Project thumbnail (Backend logger)
```

## Running Locally

Simply open the `index.html` file in any modern web browser, or serve it using a local static file server:

```bash
# Serve using Python
python3 -m http.server 8000

# Or serve using Node (if npx/vite is installed)
npx vite
```
