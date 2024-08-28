
# Marathon Handbook Articles Widget

This project is a meticulously crafted conversion of a Figma design into a responsive and pixel-perfect HTML, CSS, and JavaScript website. The design focuses on a clean, modern layout that enhances readability and user engagement, making it ideal for showcasing articles, news, and updates related to marathon running. The project follows best practices in web development, ensuring a smooth and consistent experience across various devices.

## Project Overview

The **Marathon Handbook Articles Widget** features a dynamic homepage layout that highlights key articles in a visually appealing manner. The main content area includes a large featured article section, alongside a well-organized list of other important articles, categorized for easy navigation. The top navigation bar offers quick access to different sections of the site, with a responsive design that adapts gracefully to mobile, tablet, and desktop devices.

### Figma Design Reference

This project was created based on the following Figma design:

[**Test Task Figma Design**](https://www.figma.com/design/xUKdOzSL8zqpxzka7TomwB/Test-Task?node-id=1-469&t=vd5AfJ0QmDGgpePK-0)

![Belov marathon handbook HTML page from figma](https://raw.githubusercontent.com/ndegwamoche/belov-figma/main/belov-figma.png)

The design served as the foundation for the layout, styling, and overall structure of the website. Every detail has been meticulously translated from the Figma file to ensure a high level of accuracy and fidelity in the final product.

## Getting Started

These instructions will help you set up and run the project on your local machine, whether you are a developer looking to customize the design or a user who simply wants to view the website in action.

### Prerequisites

Before getting started, ensure that you have the following software installed on your local machine:

-   **Web Browser:** A modern web browser such as Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari.
-   **Text Editor (Optional):** If you plan to modify the code, a text editor like Visual Studio Code, Sublime Text, or Atom will be helpful.

### Installation

Follow these steps to get the project running locally:

1.  **Clone the Repository:** Clone the project repository from GitHub to your local machine using the following command:
    
    `git clone https://github.com/yourusername/marathon-handbook-widget.git` 
    
    Navigate into the project directory:
    
	`cd marathon-handbook-widget`
 
2.  **Open the Project:** Locate the `index.html` file in the project directory and open it in your preferred web browser. This will load the homepage and display the fully responsive design.
    
3.  **Viewing the Project:**
    
    -   To view the site in different device modes (mobile, tablet, desktop), you can use the developer tools in your browser. For example, in Chrome, right-click anywhere on the page, select "Inspect," and then toggle the device toolbar to simulate different screen sizes.
    -   The design is optimized for performance and should load quickly and render correctly on all supported devices.

### Media Queries and Responsive Design

The project includes custom media queries to ensure that the layout is responsive and adapts smoothly to various screen sizes:

-   **Mobile Devices (up to 767px):**
    
    -   The layout adjusts to a single-column format for better readability on smaller screens.
    -   The navigation menu collapses into a hamburger icon, which can be toggled to reveal the menu options.
    -   Images and text resize appropriately to maintain visual clarity.
-   **Tablets (768px to 1024px):**
    
    -   The layout expands to a two-column format, offering a balanced view that makes use of the additional screen space.
    -   The navigation bar remains visible at the top, but elements may shift to maintain an organized appearance.
    -   Padding and margins are adjusted for a more spacious layout.
-   **Laptops/Desktops (above 1024px):**
    
    -   The full-width layout is utilized, with the featured article and other articles displayed in a multi-column grid.
    -   The navigation bar is fully expanded, and the content is centered to provide an optimal viewing experience.
    -   Hover effects and transitions are added to enhance interactivity.

### Project Structure

-   **index.html:** The main HTML file that contains the structure of the homepage.
-   **style.css:** The CSS file responsible for the styling of the website, including layout, colors, typography, and responsive design.
-   **main.js:** The JavaScript file used for adding interactivity, such as toggling the mobile menu.
-   **images/**: A directory containing all image assets used in the project, optimized for web use.

### Running the Tests

Currently, the project does not include automated tests. However, you can manually test the responsiveness and functionality of the website by following these steps:

1.  **Cross-Browser Testing:**
    
    -   Open the website in different browsers to ensure that the design renders consistently.
    -   Test all interactive elements, such as navigation links and the mobile menu, to confirm they work as expected.
2.  **Device Testing:**
    
    -   Use the developer tools in your browser to simulate different device sizes and orientations.
    -   Check the layout, text size, and image quality on mobile, tablet, and desktop views.

### Deployment

To deploy the project on a live server, follow these steps:

1.  **Upload Files to Server:**
    
    -   Use an FTP client or a web hosting control panel to upload all project files (including `index.html`, `style.css`, `main.js`, and the `images` directory) to your web server.
2.  **Set Up Domain:**
    
    -   Ensure that your domain is correctly pointed to your web hosting server.
    -   Once the files are uploaded, your website should be accessible via your domain.
3.  **Test Deployment:**
    
    -   After deployment, test the website on the live server to ensure all elements are functioning as expected.
    -   Perform another round of cross-browser and device testing to catch any issues that may arise in the live environment.

### Built With

-   **HTML5:** For structuring the content and ensuring semantic markup.
-   **CSS3:** For styling the layout, implementing responsive design, and adding transitions and animations.
-   **JavaScript (ES6+):** For adding interactivity and dynamic features to the website.

### Contributing

If you would like to contribute to this project, please fork the repository, create a new branch, and submit a pull request with your changes. Ensure that your code follows the established coding standards and includes appropriate comments.

### Versioning

This project uses semantic versioning (SemVer) to manage version numbers. For more information about available versions, please refer to the tags section of this repository.

### Authors

-   **Martin Ndegwa moche** - _Initial work_ - [GitHub Profile](https://github.com/ndegwamoche)

See also the list of contributors who participated in this project.

### Acknowledgments

-   **Figma Community:** Special thanks for the design inspiration and resources that made this project possible.
-   **Web Development Community:** For the wealth of resources, tutorials, and tools that facilitated the creation of this project.
-   **You:** For taking the time to explore and potentially contribute to this project.
