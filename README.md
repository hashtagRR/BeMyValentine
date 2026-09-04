# Valentine's Proposal Website

An interactive Valentine's proposal webpage built with HTML, CSS, and vanilla JavaScript.

The page displays an animated flower, followed by a Valentine's proposal with interactive Yes and No buttons. Selecting Yes triggers an animated "I Love You" message with hearts.

## Features

* Animated flower blooming sequence
* Floating flower background animation
* Interactive Valentine's proposal
* No button moves when hovered or touched
* Animated "I Love You" message
* Animated hearts after selecting Yes
* Mouse and touch interaction
* No external libraries or frameworks required

## Technologies

* HTML5
* CSS3
* JavaScript

## Project Structure

```text
valentine-proposal/
├── index.html
└── README.md
```

The project is contained in a single `index.html` file.

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project

Navigate to the project directory:

```bash
cd valentine-proposal
```

### 3. Run the website

Open `index.html` in a modern web browser.

No dependencies, build tools, or development server are required.

## How It Works

### Flower Animation

When the page loads, JavaScript dynamically creates the flower petals and floating flowers.

The main flower appears through a sequence of animations:

1. The flower container appears.
2. The stem grows.
3. The leaves appear.
4. The petals bloom individually.
5. The flower center appears.
6. The proposal message fades in.

### Floating Flowers

The background contains dynamically generated flowers. Their size, position, animation delay, and animation duration are randomized to create a continuously moving effect.

### No Button

The No button moves to a random position when the user hovers over it or touches it on a mobile device.

### Yes Button

When the Yes button is clicked:

1. The proposal message fades out.
2. The flower fades out.
3. An "I Love You" animation is created.
4. Three animated hearts appear below the text.

## Customization

### Change the Proposal Message

In `index.html`, find:

```html
<h1>Will you be my Valentine?</h1>
```

Replace it with your preferred message.

### Change the Final Message

The final "I Love You" animation is generated dynamically in JavaScript. The individual letters can be changed to create a different message.

### Change the Number of Floating Flowers

Find:

```javascript
for (let i = 0; i < 20; i++)
```

Change `20` to increase or decrease the number of floating flowers.

### Change Animation Timing

The flower animation uses JavaScript `setTimeout()` calls. These values can be adjusted to make the animation faster or slower.

## Browser Support

The project is designed to work in modern browsers, including:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari

JavaScript must be enabled.

## Possible Improvements

* Add personalized names or messages
* Add background music
* Add a photo section
* Add a confetti animation
* Improve mobile responsiveness
* Separate the HTML, CSS, and JavaScript into individual files
* Add additional flower animations
* Deploy the project using GitHub Pages, Netlify, or Vercel

## Acknowledgements

This project was created with assistance from large language models (LLMs).

I would also like to acknowledge and thank the original authors, developers, and open-source contributors whose code, documentation, examples, and ideas have contributed to the wider software ecosystem and helped make AI-assisted development possible.

Where existing code or ideas have been used or adapted, credit belongs to their respective original authors and contributors.

This project is a small example of how human-written software, open-source collaboration, and AI-assisted development can work together.
