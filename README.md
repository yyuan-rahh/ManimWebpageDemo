# Manim Projects Portfolio

A simple, clean webpage to showcase your Manim projects including videos and interactive websites.

## Structure

- `index.html` - Main HTML file
- `styles.css` - Styling for the webpage
- `videos/` - Place your video files here (create this folder)
- `screenshots/` - Place your project screenshots here (create this folder)

## How to Add Your Projects

### Adding Videos

1. Create a `videos` folder in the project directory
2. Add your video files (MP4 format recommended)
3. In `index.html`, find the video section and add a new project card:

```html
<div class="project-card">
    <div class="video-container">
        <video controls>
            <source src="videos/your-video.mp4" type="video/mp4">
        </video>
    </div>
    <div class="project-info">
        <h3>Your Project Title</h3>
        <p>Your project description.</p>
    </div>
</div>
```

### Adding Interactive Websites

1. Create a `screenshots` folder in the project directory
2. Add screenshots of your interactive projects
3. In `index.html`, find the interactive websites section and add a new project card:

```html
<div class="project-card">
    <div class="screenshot-container">
        <img src="screenshots/your-screenshot.png" alt="Project screenshot">
    </div>
    <div class="project-info">
        <h3>Your Project Title</h3>
        <p>Your project description.</p>
        <a href="https://your-project-url.com" class="project-link" target="_blank">View Project →</a>
    </div>
</div>
```

## Opening the Webpage

Simply open `index.html` in your web browser to view your portfolio.

