# Christmas Tree Animation 🎄
This project is a festive animation of a Christmas tree with sparkling effects and a "Merry Christmas" message. The animation is created using HTML, CSS, and JavaScript, with the help of the GSAP (GreenSock Animation Platform) library for smooth animations and SVG manipulation.

## 🎥 Demo
You can view the live demo of the project [[here](https://codepen.io/MahdiDevSec/full/PwYagPp)]

---

## 🕠️ Files Overview

### 1. index.html
The main HTML file that structures the content and includes the SVG elements for the Christmas tree, stars, and other decorative elements.

#### Key Features:
- SVG elements for the tree, stars, and particles.
- Links to external GSAP libraries for animation.
- A `foreignObject` element to display the "Merry Christmas" message.

### 2. script.js
The JavaScript file that handles the animation logic using GSAP.

#### Key Features:
- Animates particles and sparkles around the tree.
- Uses GSAP's `MotionPathPlugin` to move particles along the tree's path.
- Controls the timing and sequencing of animations, including the appearance of the tree and the final message.

### 3. style.css
The CSS file that styles the project, including the background, font, and SVG elements.

#### Key Features:
- Custom font `mountains_of_christmasregular` for the "Merry Christmas" message.
- Background color and layout settings for the body and SVG elements.
- Visibility and opacity controls for the SVG and `foreignObject` elements.

---

## 🚀 How to Run the Project

### Method 1:
You can view the live demo of the project [[here](https://codepen.io/MahdiDevSec/full/PwYagPp)]

### Method 2:

### Clone the Repository:
```bash
git clone https://github.com/MahdiDevSec/Christmas.git
cd Christmas
```

### Open the Project:
Open the `index.html` file in your web browser to view the animation.

### Customize:
You can modify the `index.html`, `script.js`, and `style.css` files to customize the animation, colors, or text.

---

## 📦 Dependencies

- **GSAP (GreenSock Animation Platform):** Used for creating smooth and complex animations. Included via CDN in the `index.html` file.
- **MorphSVGPlugin:** A GSAP plugin for morphing SVG shapes.
- **DrawSVGPlugin:** A GSAP plugin for animating SVG strokes.
- **MotionPathPlugin:** A GSAP plugin for animating objects along a path.
- **Physics2DPlugin:** A GSAP plugin for adding physics-based animations.

---

## 🎨 Custom Font
The project uses a custom font called `mountains_of_christmasregular`, which is loaded via the `@font-face` rule in the `style.css` file.

---

## 📽️ Animation Details

- **Particle Animation:** Small particles (stars, circles, crosses, and hearts) are animated around the tree using GSAP's physics and motion path plugins.
- **Tree Drawing Animation:** The tree is drawn using the `DrawSVGPlugin`, which animates the SVG path to create a drawing effect.
- **Sparkle Effect:** A sparkle effect is created using a radial gradient and GSAP's opacity animation.
- **Final Message:** The "Merry Christmas" message fades in at the end of the animation sequence.

---

## 📜 License
This project is open-source and available under the MIT License. Feel free to use and modify it for your own projects.

---

Enjoy the festive animation and feel free to contribute or customize it further! 🎄

## 🔗 Links
- [GSAP Documentation](https://greensock.com/docs/)
- [GitHub Repository](https://github.com/MahdiDevSec/Christmas)

