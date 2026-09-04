<div align="center">

# 💗 ForCouple

An interactive digital love letter with a simple heart animation, created to share a personal message with someone special.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/github/license/DzarelDeveloper/ForCouple?style=for-the-badge)

</div>

## About the Project

ForCouple is a lightweight, single-page website that presents a heartfelt message through an interactive envelope-like experience. Click the heart to reveal the letter, then click it again to close the message.

The project runs entirely in the browser and does not require a backend, database, package manager, or build process.

## Features

- Interactive heart button to open and close the message
- Smooth letter-opening and heart-moving animations
- Beating-heart hover and active effects
- Soft romantic color palette
- Easy-to-customize message and styling
- Runs as a simple static website

## Built With

- **HTML5** — page structure and message content
- **CSS3** — layout, colors, shadows, and animations
- **JavaScript** — interaction logic
- **jQuery 3.6.0** — event handling and background transitions

## Getting Started

### Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/DzarelDeveloper/ForCouple.git
   ```

2. Open the project directory:

   ```bash
   cd ForCouple
   ```

3. Open `index.html` in your browser.

You can also use a local development server, such as the **Live Server** extension in Visual Studio Code.

## Customization

### Change the Message

Open `index.html`, then replace the text inside:

```html
<div class="message">
    <h1>Untuk Kamuu</h1>
    <p>Your personal message...</p>
</div>
```

### Change the Heart Image

Replace the image URL in the following element:

```html
<img src="https://raw.githubusercontent.com/DzarelDeveloper/Img/main/Lope.png">
```

### Change the Colors

Edit the background colors used in the JavaScript section:

```javascript
$(".container").stop().animate({"backgroundColor": "#f48fb1"}, 2000);
$(".container").stop().animate({"backgroundColor": "#fce4ec"}, 2000);
```

## Project Structure

```text
ForCouple/
├── index.html
├── LICENSE
└── README.md
```

## Deployment

Because this is a static website, it can be deployed easily using:

- GitHub Pages
- Netlify
- Vercel
- Any static web hosting service

For GitHub Pages, open the repository settings, select **Pages**, choose the `main` branch as the source, and save the configuration.

## License

This project is available under the [MIT License](LICENSE).

## Author

Created by [DzarelDeveloper](https://github.com/DzarelDeveloper).

If you find this project useful, consider giving the repository a ⭐.

---

<div align="center">

Made with ❤️ for someone special.

</div>
