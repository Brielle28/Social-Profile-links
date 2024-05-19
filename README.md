# Social Media Link Profile

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project is a simple HTML and CSS based webpage that displays a developer's profile along with links to their social media profiles. It serves as a digital business card, allowing visitors to easily access the developer's online presence.

## Features
- Display of developer's profile picture, name, location, and occupation
- Buttons linking to various social media profiles
- Responsive design suitable for various screen sizes

## Installation
To set up this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/social-media-link-profile.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd social-media-link-profile
    ```

## Usage
Open the `index.html` file in your web browser to view the webpage.

### HTML Code
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Social Media Links</title>
    <link rel="stylesheet" href="socials.css" />
  </head>
  <body>
    <div class="body">
      <div class="details">
        <div class="image-container"></div>
        <h1 class="name">Nnadozie Chukwuemerie</h1>
        <h5 class="Location">Enugu state, Nigeria</h5>
        <p class="occupation">Frontend Software Developer</p>
      </div>
      <div class="buttons">
        <button>
          <a href="#"> github </a>
        </button>
        <button>
          <a href="#"> Linkedin </a>
        </button>
        <button>
          <a href="#"> Frontend Mentor </a>
        </button>
        <button>
          <a href="#"> Twitter </a>
        </button>
        <button>
          <a href="#"> Instagram </a>
        </button>
      </div>
    </div>
  </body>
</html>
```

### CSS Code
```css
*{
   margin: 0;
   padding: 0;
   background-color: black;
}
body{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
}
.body{
    display: flex;
    background-color: rgb(34, 37, 35);
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 60px;
    padding: 20px 30px;
    border-radius: 10px; 
    box-shadow: 0px 5px 10px rgba(128, 128, 128, 0.5);
}
.details{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: rgb(34, 37, 35);
}
.image-container {
    width: 140px;
    height: 140px;
    border-radius: 600px; 
    margin-bottom: 20px;
    background-image: url("media/picture.jpg"); 
    background-size: cover; 
}
.name{
    margin-top: 10px;
    color: white;
    font-size: 25px;
    font-weight: bold;
    background-color: transparent;
}
.Location{
    color: yellow;
    margin-top: 5px;
    font-size: 19px;
    background-color: rgb(34, 37, 35);
}
.occupation{
    color: aliceblue;
    font-size: 20px;
    padding-top: 6px;
    background-color: rgb(34, 37, 35);
}
.buttons{
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-top: 25px;
    width: 100%;
    background-color: rgb(34, 37, 35);
}
button{
    height: 40px;
    border-radius: 10px;
    outline: none;
}
button:hover{
    background-color: rgb(255, 255, 0);
    color: black;
}
.buttons button a {
    text-decoration: none;
    color: white;
    font-size: 15px;
    background-color: transparent;
}
.buttons button a:hover {
    color: rgb(0, 0, 0);
}
```

## Contributing
We welcome contributions to this project. To contribute, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch:**
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes and commit them:**
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the branch:**
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a pull request.**

Please ensure your changes do not break the existing code and update the documentation if necessary.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact:

- **Name:** Nnadozie Chukwuemerie
- **Email:** cukwuemerieclara@gmail.com

