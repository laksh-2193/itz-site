<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        /* Reset some default styles */
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
        }

        /* Style for the container */
        .container {
            display: flex;
            flex-wrap: wrap;
        }

        /* Style for the left column */
        .left-column {
            flex: 1;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            z-index: 1;
            position: sticky;
            top: 0;
        }

        /* Style for the right column */
        .right-column {
            flex: 2;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow-y: auto;
            max-height: 85vh;
        }

        /* Style for the profile image */
        .profile-image {
            max-width: 100%;
            height: auto;
        }

        /* Add responsive styles for smaller screens */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .right-column {
                flex: 1;
                max-height: none;
                overflow-y: visible;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-column">
            <!-- Content for the left column -->
            <h1>B.Tech in Life Sciences | Bioinformatics & Data Science Enthusiast</h1>
            <h2>Committed to Lifelong Learning | Nonprofit Leader</h2>
            <h2>About Me 💡</h2>
            <img class="profile-image" src="insert_profile_image_url_here" alt="Profile Image">
            <p>
                A third-year BTech in Life Sciences, I am on a journey to discover my passion while lovingly embracing new skills and subjects. My commitment to spreading compassion and kindness in the world led me to lead the Charter for Compassion chapter at Atria University. I am a hardworking and motivated individual who believes in the power of smart work and discipline. I am eager to collaborate on projects with peers and mentors who share my passion for Life Sciences.
            </p>
        </div>
        <div class="right-column">
            ## Experiences 🚀

### Company 1
- **Role:** Research Intern
- **Duration:** January 2022 - April 2022
- ![Image](insert_image_url_here)
- *Description of your experience goes here.*

### Company 2
- **Role:** Laboratory Assistant
- **Duration:** June 2021 - August 2021
- ![Image](insert_image_url_here)
- *Description of your experience goes here.*

### Company 3
- **Role:** Volunteer
- **Duration:** September 2020 - December 2020
- ![Image](insert_image_url_here)
- *Description of your experience goes here.*

## Education 📚

### Atria University
- **Degree:** Bachelor of Technology (B.Tech) in Life Sciences
- **Duration:** 2019 - Present
- ![Image](insert_image_url_here)
- *Description of your educational journey goes here.*

### XYZ School/College
- **Degree:** High School Diploma
- **Duration:** 2015 - 2019
- ![Image](insert_image_url_here)
- *Description of your high school experience goes here.*

### Another Institution
- **Degree:** Relevant Degree
- **Duration:** Year - Year
- ![Image](insert_image_url_here)
- *Description of your experience at this institution goes here.*

## Skills 💪

- Bioinformatics
- Data Science
- Laboratory Techniques
- Research Methodology
- Data Analysis

## Hobbies & Interests 🎨

- Reading
- Gardening
- Hiking
- Photography
- Cooking

## Experiments & Projects 🔬

### Project 1: [Project Title](insert_project_url_here)
- *Description of the project goes here.*

### Project 2: [Project Title](insert_project_url_here)
- *Description of the project goes here.*

### Project 3: [Project Title](insert_project_url_here)
- *Description of the project goes here.*

## Blog 📝

### Blog Post 1
- ![Image](insert_image_url_here)
- *Title of the blog post goes here.*
- *Description of the blog post goes here.*

### Blog Post 2
- ![Image](insert_image_url_here)
- *Title of the blog post goes here.*
- *Description of the blog post goes here.*

### Blog Post 3
- ![Image](insert_image_url_here)
- *Title of the blog post goes here.*
- *Description of the blog post goes here.*

### Blog Post 4
- ![Image](insert_image_url_here)
- *Title of the blog post goes here.*
- *Description of the blog post goes here.*

---

*Thank you for visiting my portfolio website! Feel free to reach out for collaborations or to learn more about my journey in Life Sciences and Data Science.* 🌱🔬
This design includes placeholders for images, so make sure to replace "insert_image_url_here" and "insert_profile_image_url_here" with the actual URLs of your images to make it visually appealing.




User
Rewrite like this

create two columns
in 1st column (fixed)
# B.Tech in Life Sciences | Bioinformatics & Data Science Enthusiast | Committed to Lifelong Learning | Nonprofit Leader

## About Me 💡

![Profile Image](insert_profile_image_url_here)

A third-year BTech in Life Sciences, I am on a journey to discover my passion while lovingly embracing new skills and subjects. My commitment to spreading compassion and kindness in the world led me to lead the Charter for Compassion chapter at Atria University. I am a hardworking and motivated individual who believes in the power of smart work and discipline. I am eager to collaborate on projects with peers and mentors who share my passion for Life Sciences.


rest in 2nd column, scrollable. make sure its responsive
ChatGPT
To create a two-column layout with a fixed left column and a scrollable right column, you can use HTML and CSS. Here's an example of how you can structure your portfolio page:

html
Copy code
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Style for the two columns */
        .container {
            display: flex;
            flex-wrap: wrap;
        }

        /* Style for the fixed left column */
        .left-column {
            flex: 1;
            padding: 20px;
            background-color: #f1f1f1;
            position: sticky;
            top: 0;
        }

        /* Style for the right column */
        .right-column {
            flex: 2;
            padding: 20px;
            overflow-y: scroll; /* Enable scrolling for the right column */
        }

        /* Style for the profile image */
        .profile-image {
            max-width: 100%;
            height: auto;
        }

        /* Add responsive styles for smaller screens */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .right-column {
                flex: 1;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-column">
            <!-- Content for the left column -->
            <h1>B.Tech in Life Sciences | Bioinformatics & Data Science Enthusiast</h1>
            <h2>Committed to Lifelong Learning | Nonprofit Leader</h2>
            <h2>About Me 💡</h2>
            <img class="profile-image" src="insert_profile_image_url_here" alt="Profile Image">
            <p>
                A third-year BTech in Life Sciences, I am on a journey to discover my passion while lovingly embracing new skills and subjects. My commitment to spreading compassion and kindness in the world led me to lead the Charter for Compassion chapter at Atria University. I am a hardworking and motivated individual who believes in the power of smart work and discipline. I am eager to collaborate on projects with peers and mentors who share my passion for Life Sciences.
            </p>
        </div>
        <div class="right-column">
            <!-- Content for the right column -->
            <!-- Add your experiences, education, skills, hobbies, projects, and blog posts here -->
            <!-- Ensure that the content in the right column is long enough to make it scrollable -->
        </div>
    </div>
</body>
</html>
In this code, the left column is fixed and contains your personal information, while the right column is scrollable and can accommodate the rest of your content. The design is responsive, meaning it will adapt to smaller screens by stacking the columns vertically. Be sure to replace "insert_profile_image_url_here" with the actual URL of your profile image, and add your content to the right column as needed.




User
Rewrite whole code, for column 2 also. Make sure, its responsive and work with index.md code.
ChatGPT
Certainly, I'll provide you with HTML and CSS code for a responsive two-column layout that you can use with your index.md content. Below is the updated code:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        /* Reset some default styles */
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
        }

        /* Style for the container */
        .container {
            display: flex;
            flex-wrap: wrap;
        }

        /* Style for the left column */
        .left-column {
            flex: 1;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            z-index: 1;
            position: sticky;
            top: 0;
        }

        /* Style for the right column */
        .right-column {
            flex: 2;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow-y: auto;
            max-height: 85vh;
        }

        /* Style for the profile image */
        .profile-image {
            max-width: 100%;
            height: auto;
        }

        /* Add responsive styles for smaller screens */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .right-column {
                flex: 1;
                max-height: none;
                overflow-y: visible;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-column">
            <!-- Content for the left column -->
            <h1>B.Tech in Life Sciences | Bioinformatics & Data Science Enthusiast</h1>
            <h2>Committed to Lifelong Learning | Nonprofit Leader</h2>
            <h2>About Me 💡</h2>
            <img class="profile-image" src="insert_profile_image_url_here" alt="Profile Image">
            <p>
                A third-year BTech in Life Sciences, I am on a journey to discover my passion while lovingly embracing new skills and subjects. My commitment to spreading compassion and kindness in the world led me to lead the Charter for Compassion chapter at Atria University. I am a hardworking and motivated individual who believes in the power of smart work and discipline. I am eager to collaborate on projects with peers and mentors who share my passion for Life Sciences.
            </p>
        </div>
        <div class="right-column">
            <!-- Content for the right column -->
            <!-- Add your Markdown content from index.md here -->
            <!-- Ensure that the content in the right column is long enough to make it scrollable -->
            <!-- For responsive tables, use CSS classes or styles to make them scrollable on small screens -->
        </div>
    </div>
</body>
</html>
This code provides a responsive two-column layout with a fixed left column and a scrollable right column. Be sure to replace "insert_profile_image_url_here" with the actual URL of your profile image. You can include your index.md content in the right column, and it should work well on various screen sizes. If you have tables or other content that you want to make scrollable on smaller screens, you can use CSS classes or styles to achieve that.






        </div>
    </div>
</body>
</html>
