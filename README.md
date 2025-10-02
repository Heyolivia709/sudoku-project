# Kitten Sudoku — Static Mock (v5)

A modern, responsive Sudoku game mockup built with pure HTML and CSS. Features a cute kitten mascot and clean, accessible design.

## 🎮 Features

- **Two Game Modes**: 6×6 (Easy) and 9×9 (Hard) Sudoku boards
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Screen reader friendly with proper ARIA labels
- **Modern UI**: Dark theme with gradient accents and smooth animations
- **No JavaScript**: Pure HTML/CSS implementation as required

## 📁 Project Structure

```text
sudoku-mock-v5/
├── index.html              # Homepage with welcome message
├── game-easy/              # 6×6 Sudoku game
│   └── index.html
├── game-hard/              # 9×9 Sudoku game
│   └── index.html
├── selection/              # Puzzle selection page
│   └── index.html
├── login/                  # User login form
│   └── index.html
├── register/               # User registration form
│   └── index.html
├── rules/                  # Game rules and credits
│   └── index.html
├── high-scores/            # Leaderboard
│   └── index.html
└── assets/
    ├── css/
    │   └── common.css      # All styles and responsive design
    └── kitten.png          # Cute kitten mascot image
```

## 🎯 Pages Overview

| Page | Description | Features |
|------|-------------|----------|
| **Home** | Landing page with kitten mascot | Welcome message, game links, responsive grid |
| **Easy Game** | 6×6 Sudoku board | Timer display, game details sidebar |
| **Hard Game** | 9×9 Sudoku board | Full Sudoku experience, accessibility labels |
| **Selection** | Puzzle picker | Mock puzzle list with creator credits |
| **Login** | User authentication | Centered form, validation patterns |
| **Register** | Account creation | Password verification, form validation |
| **Rules** | Game instructions | How-to-play guide, developer credits |
| **High Scores** | Leaderboard | Mock data table, responsive design |

## 🎨 Design Highlights

### Visual Design
- **Dark Theme**: Modern dark background with cyan/green accent colors
- **Kitten Mascot**: Cute cat logo and hero image throughout the site
- **Gradient Effects**: Subtle radial gradients for depth
- **Smooth Animations**: Hover effects and transitions

### Responsive Features
- **Mobile-First**: Navigation moves to bottom on small screens
- **Flexible Grid**: CSS Grid adapts from 2-column to single-column
- **Touch-Friendly**: Larger tap targets on mobile devices
- **Safe Spacing**: Proper margins to prevent edge touching

### Accessibility
- **Semantic HTML**: Proper header, nav, main, footer structure
- **ARIA Labels**: Screen reader support for game boards
- **Keyboard Navigation**: All interactive elements are focusable
- **High Contrast**: Readable text colors and sufficient contrast

## 🛠️ Technical Implementation

### CSS Architecture
- **CSS Custom Properties**: Centralized color and spacing variables
- **Mobile-First Media Queries**: Responsive breakpoints at 600px and 900px
- **CSS Grid & Flexbox**: Modern layout techniques
- **Pure CSS Sudoku Grid**: Thick subgrid lines created with gradients

### Form Validation
- **HTML5 Patterns**: `pattern="[1-6]"` for easy mode, `pattern="[1-9]"` for hard mode
- **Input Constraints**: `maxlength="1"` and `inputmode="numeric"`
- **Required Fields**: Form validation without JavaScript

### Performance
- **No External Dependencies**: Zero external fonts or libraries
- **Optimized Images**: Single kitten.png asset
- **Minimal CSS**: Efficient, well-organized stylesheet

## 📱 Mobile Responsiveness

The site adapts seamlessly across devices:

- **Desktop (≥900px)**: Full 2-column layout with top navigation
- **Tablet (600-900px)**: Single column with adjusted spacing
- **Mobile (<600px)**: Bottom navigation, stacked layout, touch-optimized

Key mobile features:
- Navigation bar moves to bottom for thumb accessibility
- Sudoku boards scale appropriately with viewport
- Forms remain centered and usable
- Kitten image scales to 50% width on small screens

## 🎮 Game Features

### Sudoku Boards
- **6×6 Easy Mode**: 3×2 subgrids, digits 1-6
- **9×9 Hard Mode**: 3×3 subgrids, digits 1-9
- **Visual Grid Lines**: Thick borders separating subgrids
- **Input Validation**: Pattern-based number restrictions

### User Interface
- **Timer Display**: Mock timer showing elapsed time
- **Game Details**: Sidebar with notes and information
- **Progress Tracking**: Visual feedback for completed sections

## 🚀 Getting Started

1. **Clone or Download** the project files
2. **Open** `index.html` in any modern web browser
3. **Navigate** through the site using the responsive navigation
4. **Try** both easy and hard Sudoku modes
5. **Test** on different screen sizes for responsive behavior

## 📋 Development Notes

### What was the most challenging aspect?
Creating a fully responsive design that works seamlessly across all device sizes. The Sudoku boards needed careful sizing calculations to prevent overflow while maintaining usability.

### Key design decisions:
- **Mobile-first approach**: Started with mobile layout, enhanced for larger screens
- **CSS-only solutions**: Used gradients for Sudoku grid lines instead of images
- **Semantic structure**: Proper HTML5 elements for accessibility and SEO
- **Consistent spacing**: CSS custom properties for maintainable design

### Future enhancements (if JavaScript were allowed):
- Real Sudoku puzzle generation and validation
- Progress saving and resume functionality
- Interactive hints and error highlighting
- Dynamic scoreboard with real user data
- Theme customization options

## 👥 Credits

**Developers**: Qing Wen & Yuwei Ma  
**Project**: Static HTML/CSS Mockup Assignment