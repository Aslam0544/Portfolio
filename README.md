# Portfolio Template

### A beautiful minimal and accessible portfolio template for Developers ✨.


## Features

- Clean, Simple and Modern UI Design.
- Uses No CSS or JavaScript Frameworks or libraries as dependencies.
- Built with only HTML, CSS and a bit of JavaScript 🔨.
- Well Organized Documentation.
- Keyboard support.
- Fully Responsive.
- Loads fast ⚡.

### Contributions are warmly welcomed ❤️.

## Getting Started 🚀

You'll need [Git](https://git-scm.com) to be installed on your computer. 
```
# Clone this repository
$ git clone https://github.com/Aslam0544/Portfolio.git
```

If you don't have Git installed or you don't like using the terminal then you can download the [zip](https://github.com/Aslam0544/Portfolio/archive/refs/heads/main.zip) and extract that and open the extracted folder in the code editor of your your choice.

## Editing the Template 🔨

Go to `index.html` and fill your information. 

### Header

In all of the places where you're supposed to fill your information you'll find HTML comments. As shown below just replace what is already in the opening and closing tags below the comment with your information.

```html
<div class="header__text-box row">
    <div class="header__text">
        <h1 class="heading-primary">

        <!-- Replace the following name with your name -->

        <span>Shaik Aslam</span>
        </h1>

        <!-- Put a small paragraph about yourself -->

        <p>A Full Stack Developer based in Hyderabad, India.</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
    </div>
</div>
```

### Work Section

Each div with class `work__box` represents a project, replace the contents of the all the tags with the information of your projects.

```html
<div class="work__box">
    <div class="work__text">
    <h3>Portfolio Template</h3>
    <p>
        A free Open Source Portfolio for anyone to use for free.
    </p>
    <ul class="work__list">
        <li>HTML</li>
        <li>SCSS</li>
        <li>JavaScript</li>
        <li>React</li>
    </ul>

    <div class="work__links">
        <a href="#" class="link__text">
        Visit Site <span>&rarr;</span>
        </a> 
        <a href="https://github.com/Aslam0544/Portfolio" target="_blank">
        <img src="./images/github.svg" class="work__code" alt="GitHub">
        </a>
    </div>
    </div>
    <div class="work__image-box">
        <img
            src="./images/first.jpg"
            class="work__image"
            alt="Project 1"
        />
    </div>
</div>
```

For changing the screenshot:
- first place the image in `images/` folder and then in HTML replace the name in `src` with the name of your image.

- Recommended size for project image (1366 x 767px) also make sure the size of all  project images is the same.

```html
<img
    src="./images/name-of-your-image.png"
    class="work__image"
    alt="Project 1"
/>
```

### Clients Section

- Place the logos of the clients and companies that you have worked with in `images/` directory and then replace the name in `src` with the name of your logos accordingly.

- Make sure that you don't have whitespace on either side of the logos.

```html
<img
    src="./images/your-logo.png"
    class="client__logo"
    alt="Your Logo"
/>
```

### About Section

- Replace the contents in the below paragraph with information about yourself.
- Place a nice photo of yourself in the `images/` directory and then change the name in the src with your image name.

```html
<section class="about" id="about">
    <div class="row">
        <h2>About Me</h2>
        <div class="about__content">
            <div class="about__text">

                <!-- Replace the below paragraph with info about yourself -->

                <p>
                   Hi! I am Shaik Aslam. I'm from Hyderabad. I'm a hard-working engineering graduate specialization in Computer Science and Engineering at Bharat Institute of Engineering & Technology under JNTU University, Hyderabad, Telangana with an overall cgpa of 8.0. In addition to my degree, I completed Java Full Stack course through Ihub powered by Quality Thoughts. These various technologies helped me to develop my projects. These projects enhanced my teamwork skills and strengthened my passion for software development and I'm eager to apply my skills and contribute to your ongoing projects. Finally, I'm having 4 months of experience in GIS domain at Tech Mahindra Limited.
                </p>

                <!-- Provide a link to your resume -->

                <a href="#" class="btn">My Resume</a>
            </div>

            <div class="about__photo-container">

                <!-- Add a nice photo of yourself -->

                <img
                class="about__photo"
                src="./images/aslam.jpg"
                alt=""
                />
            </div>
        </div>
    </div>
</section>
```

### Contact Section

- Modify the paragraph to your likings.
- Replace the email with yours in the `href` anchor property and the text also.

```html
<section class="contact" id="contact">
      <div class="row">
        <h2>Get in Touch</h2>
        <div class="contact__info">
          <p>
            Are you looking for a fast-performing and user-friendly website to
            represent your product or business? or looking for any kind of
            consultation? or want to ask questions? or have some advice for me
            or just want to say "Hi 👋" in any case feel free to Let me know. I
            will do my best to respond back. 😊 The quickest way to reach out to
            me is via an email.
          </p>

          <!-- Replace the email with yours -->

          <a href="mailto:shaikaslam1158@gmail.com" class="btn">shaikaslam1158@gmail.com</a>
        </div>
      </div>
</section>
```

### Footer

- Replace the `href` attribute values to your profile URLs for all anchors.
- Remove the div with class `footer__github-buttons`.

```html
<footer role="contentinfo" class="footer">
    <div class="row">

        <!-- Update the links to point to your accounts -->

        <ul class="footer__social-links">
            <li class="footer__social-link-item">
                <a href="https://github.com/Aslam0544">
                    <img src="./images/github.svg" class="footer__social-image" alt="Github">
                </a>
            </li>
            <li class="footer__social-link-item">
                <a href="https://www.linkedin.com/in/shaik2276">
                    <img src="./images/linkedin.svg" class="footer__social-image" alt="Linkedin">
                </a>
            </li>
        </ul>

        <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->

        <p>
          &copy; 2023 - Template designed & developed by Shaik Aslam.
        </p>
        <div class="footer__github-buttons">
          <iframe
            src="https://github.com/Aslam0544/Portfolio" 
            frameborder="0" scrolling="0" width="170" height="20" title="Watch Portfolio Template on GitHub">
          </iframe>
        </div>
    </div>
</footer>
```
