# Visual Changelog Component

A modern and responsive changelog component built with HTML and CSS, featuring a timeline-based layout to showcase product updates, new features, and bug fixes.

## 🎯 Project Goals

This project implements a changelog component with the following features:
- Responsive timeline layout
- Visual indicators for different update types (features, fixes, updates)
- Clean and modern design inspired by Apple's aesthetic
- Mobile-friendly interface

## 🛠️ Technologies Used

- HTML5
- CSS3
- Modern CSS Features:
  - Flexbox
  - CSS Variables
  - Media Queries
  - Pseudo-elements
  - Box-shadow
  - Border-radius

## ✨ Features

- Timeline-based layout with dots and connecting lines
- Color-coded badges for different update types:
  - 🟢 Feature badges (green)
  - 🔴 Fix badges (red)
  - 🔵 Update badges (blue)
- Responsive design that adapts to mobile devices
- Clean typography using system fonts
- Subtle animations and hover effects
- Card-based container with modern shadow effects

## 📱 Responsive Behavior

The component is fully responsive and includes:
- Flexible container width
- Stacked layout on mobile devices
- Adjusted spacing and typography for smaller screens
- Breakpoint at 600px for mobile optimization

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/changelog-component.git
```

2. Navigate to the project directory:
```bash
cd changelog-component
```

3. Open `index.html` in your browser or use a local server.

## 📂 Project Structure

```
changelog-component/
├── index.html
├── styles.css
└── README.md
```

## 🎨 Customization

You can customize the component by modifying these CSS variables:
- Colors
- Spacing
- Typography
- Shadow effects
- Timeline appearance

## 📝 Usage

To add new changelog entries, follow this HTML structure:

```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-date">Date Here</div>
    <div class="timeline-content">
        <h3>Title Here <span class="badge badge-feature">Type</span></h3>
        <p>Description here</p>
    </div>
</div>
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by [roadmap.sh](https://roadmap.sh/projects/changelog-component) project guidelines
- Design inspiration from modern UI practices