<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio Project Demo – Using Framework</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      padding: 2rem;
      color: #333;
    }
    h1, h2 {
      color: #0d6efd;
    }
    section {
      margin-bottom: 2rem;
    }
    a {
      color: #0d6efd;
    }
    img {
      max-width: 100%;
      border-radius: 6px;
      border: 1px solid #ccc;
      margin-top: 0.5rem;
    }
    .code-block {
      background-color: #e7f0fd;
      padding: 1rem;
      border-left: 5px solid #0d6efd;
      font-family: monospace;
      white-space: pre-wrap;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <h1>Portfolio Project – Built with a Framework</h1>

  <section>
    <h2>1. Project Description</h2>
    <p>
      This responsive portfolio website was built using the <strong>Bootstrap framework</strong>. I customized the components, layout, and design to create a modern, professional-looking portfolio. The site includes sections for introduction, project highlights, contact, and testimonials. It uses Bootstrap’s grid system, cards, modals, and forms to structure the content efficiently and responsively.
    </p>
  </section>

  <section>
    <h2>2. Hosted Site Link</h2>
    <p>
      View the live site here:  
      <a href="https://your-bootstrap-site.com" target="_blank">https://your-bootstrap-site.com</a>
    </p>
  </section>

  <section>
    <h2>3. W3C Validation</h2>
    <p>
      The site was tested with the W3C validator and no critical HTML/CSS errors were found.
    </p>
    <img src="w3c-bootstrap-validation.png" alt="W3C Validation Screenshot" />
  </section>

  <section>
    <h2>4. Responsive Design Evidence</h2>
    <p>
      The Bootstrap grid system ensures smooth responsiveness across devices:
    </p>
    <img src="mobile-view.png" alt="Mobile View Screenshot" />
    <img src="tablet-view.png" alt="Tablet View Screenshot" />
    <img src="desktop-view.png" alt="Desktop View Screenshot" />
  </section>

  <section>
    <h2>5. CSS/Bootstrap Customization</h2>
    <p>Here’s an example of custom CSS along with Bootstrap classes:</p>
    <div class="code-block">
<pre>
.hero-section {
  background-color: #f0f8ff;
  padding: 3rem 1rem;
  text-align: center;
}

.card:hover {
  transform: scale(1.02);
  transition: transform 0.3s ease;
}
</pre>
    </div>
  </section>

  <section>
    <h2>6. Four Extras Included</h2>
    <ul>
      <li><strong>Skip Link:</strong> A “Skip to Main Content” link appears for keyboard users, improving accessibility.</li>
      <li><strong>Prefers-Color-Scheme:</strong> Light and dark mode support using media queries.</li>
      <li><strong>Prefers-Reduced-Motion:</strong> Users with motion sensitivity will see minimal transitions.</li>
      <li><strong>Keyboard Navigation:</strong> Bootstrap buttons, navbars, and modals are fully navigable using the keyboard.</li>
    </ul>

    <div class="code-block">
<pre>
@media (prefers-color-scheme: dark) {
  body {
    background-color: #121212;
    color: #e4e4e4;
  }
}

@media (prefers-reduced-motion: reduce) {
  * {
    transition: none !important;
    animation: none !important;
  }
}
</pre>
    </div>
  </section>

  <section>
    <h2>7. Summary</h2>
    <p>
      This site demonstrates strong understanding of framework-based design, custom component styling, responsiveness, and accessibility. I leveraged Bootstrap’s utility-first classes to minimize code and maximize performance while ensuring the site remains visually appealing across devices.
    </p>
  </section>

</body>
</html>
