# Animated Headers Kit

![CSS](https://img.shields.io/badge/CSS-Animations-blue)
![HTML](https://img.shields.io/badge/HTML5-Components-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A collection of animated header components for modern web applications. Features smooth CSS transitions, scroll-triggered effects, and customizable styles that work across all major browsers.

## Features

- Multiple animated header styles (fade, slide, parallax, sticky)
- Pure CSS animations with no JavaScript dependency for core effects
- Customizable via CSS custom properties
- Dark theme support with configurable accent colors
- Responsive design for mobile, tablet, and desktop
- Lightweight and performant

## Tech Stack

| Technology | Purpose              |
|------------|----------------------|
| CSS3       | Animations & styling |
| HTML5      | Markup structure     |
| Make       | Build automation     |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/animated-headers-kit.git
cd animated-headers-kit
```

2. Include the theme in your project:

```html
<link rel="stylesheet" href="styles/theme.css" />
```

3. Apply header classes to your markup:

```html
<header class="animated-header fade-in">
  <h1>Your Title</h1>
</header>
```

## Customization

Override theme variables to match your brand:

```css
:root {
  --primary: #00d4aa;
  --background: #1e1e2e;
}
```

## Build

```bash
make build
make test
```

## Project Structure

```
animated-headers-kit/
  styles/
    theme.css       # Base theme and animations
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. New header animation styles and accessibility improvements are especially appreciated.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
