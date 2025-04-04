# Portfolio - Wilker J C Pimenta

![Portfolio Preview](assets/img/profile.jpg)

Portfolio website featuring an interactive network background animation with responsive design and modern UI elements.

## Features

- **Interactive Network Background**

  - Particle animation with connection lines
  - Responsive to window resizing
  - Mouse interaction effects

- **Dynamic Content**

  - Typewriter effect for "Desenvolvedor Web" title
  - Bootstrap social media icons (GitHub, LinkedIn, Email)
  - Services section with hover animations

- **Responsive Design**
  - Mobile-friendly layout
  - Adaptive grid for services section
  - Proper scaling of all elements

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- Canvas API for animations

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── assets/
│   └── img/            # Image assets
└── README.md           # This documentation
```

## Installation

No installation required - just open `index.html` in any modern browser.

## Customization

To modify the portfolio:

1. **Change Background Animation**:

   - Edit particle settings in `script.js`:
     ```javascript
     const particleCount = 100;
     const colors = ["#66727a", "#ebe0e6", "#ffffff"];
     const maxDistance = 150;
     ```

2. **Update Personal Information**:

   - Edit the header section in `index.html`:
     ```html
     <h1>Wilker J C Pimenta</h1>
     <h2 id="typewriter-text">Desenvolvedor Web</h2>
     ```

3. **Change Social Links**:

   - Update href attributes in `index.html`:
     ```html
     <a href="https://github.com/wilkerjcpimenta" target="_blank"></a>
     ```

4. **Modify Services**:
   - Edit the services grid in `index.html`:
     ```html
     <div class="service-card">
       <i class="bi bi-globe"></i>
       <h4>Sites</h4>
       <p>Desenvolvimento de sites profissionais e responsivos</p>
     </div>
     ```

## License

This project is open source and available under the [MIT License](LICENSE.md).

---

**Developed by Wilker J C Pimenta**  
[GitHub](https://github.com/wilkerjcpimenta) |
[LinkedIn](https://linkedin.com/in/wilkerjcpimenta) |
[Email](mailto:wilkerjcpimenta@gmail.com)
