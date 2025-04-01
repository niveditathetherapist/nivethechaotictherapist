<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags for character set and responsive design -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Title of the webpage -->
    <title>Your Website Title</title>

    <!-- Link to the CSS file (Add this line within the <head> tag) -->
    <link rel="stylesheet" href="style.css">  <!-- Correct link to your CSS file -->

</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    
    <nav>
        <!-- Your navigation content here -->
    </nav>
    
    <section>
        <h2>Services</h2>
        <p>Details about your services...</p>
    </section>

    <footer>
        <p>© 2025 Your Website</p>
    </footer>
</body>
</html>

- 👋 Hi, I’m @thechaotictherapist
- 👀 I’m interested in providing Counseling and Therapy services virtually
- 🌱 I’m currently learning different kinds of therapies
- 💞️ I’m looking to collaborate on mental health awareness, one to one counseling, group sessions and support groups
- 📫 How to reach me ndkulk97@gmail.com
- www.linkedin.com/in/nivedita-kulkarni-86085515b
- 😄 Pronouns: She/Her
- ⚡ Fun fact: I am big time foodie but still a vegetarian

<!---
niveditathetherapist/niveditathetherapist is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Nivedita Kulkarni, a mental health professional 5+ years of experience helping individuals, children, adolscents and adults navigate life's challenges. My approach is grounded with a integrative aporoach towards counseling [mainly a cobination of person centered therapy with a combination of Cognitive Behaviour Therapy and Transactional Analysis, etc.].</p>
    <p>I'm passionate about providing a safe and supportive space for growth and healing. Whether you're dealing with anxiety, depression, stress, or other life challenges, I’m here to help.</p>
</section>
body {
    background-color: #f1f1f1; /* Light gray background */
    color: #333333; /* Dark text */
}

header {
    background-color: #0066cc; /* Blue header */
}

nav {
    background-color: #333333; /* Dark gray for navigation */
}

footer {
    background-color: #0066cc; /* Matching footer */
}

body {
    font-family: 'Roboto', sans-serif; /* Smooth and clean font */
}

h1, h2 {
    font-family: 'Lora', serif; /* Serif fonts for headings */
}

/* Button Style */
input[type="submit"] {
    background-color: #4CAF50; /* Green background */
    color: white;
    padding: 15px 20px;
    border-radius: 5px;
    cursor: pointer;
    border: none;
    font-size: 16px;
}

input[type="submit"]:hover {
    background-color: #45a049; /* Slightly darker green on hover */
}

/* Links Styling */
a {
    color: #4CAF50; /* Green link color */
    text-decoration: none;
}

a:hover {
    color: #45a049; /* Darker green when hovered */
}

section {
    display: flex;
    flex-direction: column; /* Stacks elements vertically */
    padding: 20px;
    margin: 20px 0;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

/* For Services Section with Flexbox */
#services ul {
    display: flex;
    flex-wrap: wrap; /* Wrap items onto the next line if needed */
    gap: 20px; /* Space between items */
}

#services li {
    flex: 1 1 250px; /* Items grow, shrink, and have a base width */
    padding: 15px;
    background-color: #e7f7e7;
    border-radius: 8px;
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}

#hero {
    position: relative;
    width: 100%;
    height: 400px; /* Set the height of the hero section */
    overflow: hidden;
}

.hero-image {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures the image covers the area */
    opacity: 0.7; /* Slight transparency */
}

.hero-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-align: center;
}

.hero-text h1 {
    font-size: 36px;
}

.hero-text p {
    font-size: 18px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer a {
    color: #4CAF50; /* Green links */
    text-decoration: none;
}

footer a:hover {
    color: #45a049; /* Hover effect */
}

/* Responsive Design */
@media screen and (max-width: 768px) {
    nav {
        display: block;
        text-align: center;
    }

    #services ul {
        flex-direction: column;
    }
}

<section id="services">
    <h2>Services</h2>
    <ul>
        <li>Individual Counseling</li>
        <li>Group Counseling</li>
        <li>Psychotherapy</li>
      <li>Support group</li>
      <li>Career Counseling</li>
    </ul>
</section>
<section id="book">
    <h2>Book a Session</h2>
    <p>Click the link below to schedule an appointment with me:</p>
    <iframe src="https://calendly.com/yourusername" width="100%" height="600" frameborder="0"></iframe>
</section>
