# Portfolio Website Using AI in 10min

This is the repository for your reference for the youtube video where I teach you how you can build you portfolio website in 10min using AI.

## Click to Watch Youtube Video
[![Thumbnail](./Thumbnail.jpeg)](https://youtu.be/eiCjbOQL8fE "Click to Play Video Demonstration")

## Live Link

[Click Here For Live Link](https://halcyon-past.github.io/Portfolio-Using-AI-VeriPyed/)

## Setup

### Prerequisites

- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white): Download Visual Studio Code from [here](https://code.visualstudio.com/).
- ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white): If you want to host your website in github you need to have a github account.

### Instructions

1. **Download The Repository**:

2. **Copy the Contents from 'Get Started With' Folder to the root directory**:

3. **Delete All The Other Files Which are present**
   The Final List of Files Would be (all from Get Started With):
   - index.html 
   - me.jpeg
   - project1.jpg 
   - project2.jpg
   - project3.jpg

3. **Modify The Images and use your image name and update the image name in the HTML code**
   - For Your own image (Make sure it is horizontal)
      - Modify This Code snippet:
         ```css
         .hero {
            background-image: url('me.jpeg'); /* Add Your Image Here */
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-top: 60px;
        }
         ```
      - To
         ```css
         .hero {
            background-image: url('<your_image_name>'); /* Add Your Image Here */
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-top: 60px;
        }
         ```
   - For Each Project
      - Modify This Code snippet:
         ```html
         <div class="project-card">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>A web app built with React and Node.js.</p>
            <a href="#">View Project</a>
         </div>
         ```
      - To
         ```html
         <div class="project-card">
            <img src="<Your_Project_Image_File>" alt="Project 1">
            <h3>Project 1</h3>
            <p>A web app built with React and Node.js.</p>
            <a href="#">View Project</a>
         </div>
         ```

4. **Install Live Server in VSCODE**:

5. **Update code using Claude with the given prompt**:
   ```
   Design this Portfolio use gsap for scroll animations in all sections The design should be a blue pink neon cyberpunk theme design there should be glitch effects and also use a fonts library to add icons to the website make the education and work section in a timeline design from start to finish make sure to keep the background image in the hero section and make sure the items are centered in their respective divs make sure to make th project cards using the images given and the navbar should be responsive with a hamburger menu
   ```

6. **Deploy in Github Pages**:

Follow the Youtube Video to Understand in Full Details how to perform each step

## Contact

Made with ❤️ by Aritro Saha  
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/halcyon-past)      [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aritro-saha/)    [![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)](https://aritro.tech/)    [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@veripyed)