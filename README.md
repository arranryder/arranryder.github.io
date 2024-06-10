# Arran Ryder Personal Portfolio Website

Welcome to the repository for Arran Ryder's personal portfolio website. This website is designed to showcase my skills and projects as a Business Data Analyst. Below you will find information on how to set up and customize this website.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo

Check out the live demo [here](https://arranryder.github.io/#portfolio).

## Features

- Responsive design
- Smooth scrolling navigation
- Downloadable CV
- Portfolio section
- Contact form with spam protection

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/arran-ryder-portfolio.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd arran-ryder-portfolio
    ```
3. **Open `index.html` in your web browser to view the site:**
    ```bash
    open index.html
    ```

## Usage

### Customization

- **Change the Title and Meta Description:**
    Modify the content within the `<head>` section of `index.html`:
    ```html
    <title>Arran Ryder</title>
    <meta name="description" content="Start your development with arranryder landing page.">
    ```

- **Update Contact Form:**
    Replace the `access_key` in the contact form with your own from [Web3Forms](https://web3forms.com/):
    ```html
    <input type="hidden" name="access_key" value="your-access-key">
    ```

- **Add Portfolio Items:**
    Update the portfolio section with your own projects:
    ```html
    <div class="col-md-4">
        <a href="" class="portfolio-card">
            <img src="assets/imgs/your-image.jpg" class="portfolio-card-img" alt="Project Title">
            <span class="portfolio-card-overlay">
                <span class="portfolio-card-caption">
                    <h4>Project Title</h4>
                    <p class="font-weight-normal">Category: Description</p>
                </span>
            </span>
        </a>
    </div>
    ```

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contact me if you have any questions or suggestions. Thank you for checking out my portfolio!
