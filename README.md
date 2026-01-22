/* ====== General Reset ====== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

/* ====== Scrollbar ====== */
::-webkit-scrollbar {
    width: 8px;
}
::-webkit-scrollbar-track {
    background-color: #222;
}
::-webkit-scrollbar-thumb {
    background-color: #39d0cb;
    border-radius: 5px;
}

/* ====== Navbar ====== */
nav {
    z-index: 1000;
    background: #131010;
    backdrop-filter: blur(5px);
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.item {
    text-decoration: none;
    border: 1px solid #39d0cb;
    margin: 8px;
    padding: 2px 15px;
    border-radius: 25px;
    background-color: rgba(72, 207, 203, 0.055);
    font-weight: 700;
    color: #39d0cb;
    font-size: 17px;
    transition: all 0.3s ease-in-out;
}

.item:hover {
    border: 1px solid rgba(148, 210, 208, 0.3);
    color: #FFD700;
    box-shadow: 0px 0px 5px 2px #FFD700;
}

/* ====== Hero Section ====== */
.home-section {
    height: 100vh;
    position: relative;
    background: url('https://e0.pxfuel.com/wallpapers/149/259/desktop-wallpaper-web-development.jpg') no-repeat center center;
    background-size: cover;
}

.home-section::before {
    content: "";
    position: absolute;
    top: 0; 
    left: 0;
    width: 100%; 
    height: 100%;
    background: rgba(0, 0, 0, 0.9);
    z-index: -1;
}

.home-content {
    position: relative;
    z-index: 2;
    max-width: 800px;
    text-align: center;
    margin: auto;
    padding-top: 15%;
}

.home-content h1 {
    font-size: 3.5rem;
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 1rem;
    color: #39d0cb;
}

.home-content h2 {
    font-size: 1.8rem;
    color: #FFD700;
    margin-bottom: 1rem;
}

.home-content p {
    font-size: 1.3rem;
    margin-bottom: 2rem;
    color: #F5F5F5;
}

.home-content .btn {
    text-decoration: none;
    background-color: #39d0cb;
    color: #131010;
    padding: 0.6rem 1.9rem;
    font-size: 1.2rem;
    border-radius: 25px;
    transition: all 0.3s ease-in-out;
}

.home-content .btn:hover {
    background-color: #FFD700;
    color: #131010;
}

/* ====== About Section ====== */
.about-section {
    background-color: #131010;
    padding: 60px 15px;
    text-align: center;
}

.section-title {
    font-size: 26px;
    color: #48CFCB;
    margin-bottom: 20px;
}

.about-description {
    font-size: 1.1rem;
    line-height: 1.8;
    margin-bottom: 20px;
    color: #f5f5f5;
}

/* ====== Skills Section ====== */
.skills-section {
    background: linear-gradient(135deg, #131010 50%, #161616 50%);
    padding: 50px 0;
    color: #f5f5f5;
    text-align: center;
}

.skill-heading {
    font-size: 26px;
    color: #48CFCB;
    margin-bottom: 20px;
    text-transform: uppercase;
}

.skill-card {
    background: rgba(72, 207, 203, 0.1);
    border: 1px solid rgba(72, 207, 203, 0.3);
    border-radius: 10px;
    padding: 20px;
    margin: 15px;
    transition: transform 0.3s ease;
}

.skill-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 30px rgba(72, 207, 203, 0.5);
}

.skill-card h4 {
    margin-top: 10px;
    font-size: 20px;
    color: #FFD700;
}

<section class="projects-section" id="projects">
    <h2 class="section-title">Projects</h2>

    <div class="project-item">
        <h4>Meta Ad Performance Analysis Dashboard</h4>

        <!-- Image placeholder (you will upload image here) -->
        <img src="images/meta-ads.png" alt="Meta Ads Dashboard" class="project-image">

        <p>
            An end-to-end data analytics project that analyzes Facebook and Instagram advertising data
            to evaluate campaign performance and optimize marketing decisions.
        </p>

        <p>
            The project focuses on tracking key performance indicators such as CTR, CPC, CPA,
            impressions, reach, and conversions using interactive Power BI dashboards.
        </p>

        <p><strong>Tools Used:</strong> Power BI, SQL, DAX, Excel</p>
    </div>

    <div class="project-item">
        <h4>Attendance Management System</h4>

        <img src="images/attendance.png" alt="Attendance System" class="project-image">

        <p>
            A digital attendance management system developed to automate attendance tracking
            and reporting, reducing manual work and errors.
        </p>

        <p>
            The system stores attendance records in a structured database and generates
            attendance summaries and percentages automatically.
        </p>

        <p><strong>Tools Used:</strong> Python, SQL, HTML, CSS</p>
    </div>

    <div class="project-item">
        <h4>Cake Analyzer – Cost | Quality | Optimization</h4>

        <img src="images/cake-analyzer.png" alt="Cake Analyzer Project" class="project-image">

        <p>
            A machine learning-based application that analyzes cake ingredients to optimize
            production cost while maintaining quality standards.
        </p>

        <p>
            Regression models predict cost and quality, and the results are displayed through
            an interactive Streamlit web application.
        </p>

        <p><strong>Tools Used:</strong> Python, Machine Learning, Pandas, Scikit-learn, Streamlit</p>
    </div>

    <div class="project-item">
        <h4>Machine Learning Models (Regression & Classification)</h4>

        <img src="images/ml-projects.png" alt="Machine Learning Projects" class="project-image">

        <p>
            A collection of machine learning models built to solve real-world regression and
            classification problems using structured datasets.
        </p>

        <p>
            The project includes data preprocessing, feature engineering, model training,
            evaluation, and performance comparison.
        </p>

        <p><strong>Tools Used:</strong> Python, Scikit-learn, Pandas, Matplotlib</p>
    </div>

</section>

/* ====== Achievements Section ====== */
.achievements-section {
    background: #131010;
    padding: 50px 20px;
    color: #f5f5f5;
    text-align: center;
}

.achievement-card {
    background: rgba(72, 207, 203, 0.1);
    border: 1px solid rgba(72, 207, 203, 0.3);
    border-radius: 10px;
    padding: 20px;
    margin: 15px auto;
    max-width: 500px;
    transition: transform 0.3s ease;
}

.achievement-card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 20px rgba(72, 207, 203, 0.4);
}

.achievement-card h4 {
    color: #FFD700;
    margin-bottom: 10px;
}

/* ====== Contact Section ====== */
.contact-section {
    padding: 50px 20px;
    background-color: #131010;
    text-align: center;
}

.contact-item {
    background: rgba(72, 207, 203, 0.1);
    padding: 15px;
    margin: 10px;
    border-radius: 10px;
    display: inline-block;
}

.contact-item a {
    color: #48CFCB;
    text-decoration: none;
    font-size: 18px;
}

.contact-item a:hover {
    color: #FFD700;
}

/* ====== Footer ====== */
footer {
    background-color: #222;
    padding: 20px 0;
    text-align: center;
}

footer p {
    color: #f5f5f5;
    margin: 0;
}

footer a {
    color: #00bcd4;
    text-decoration: none;
}

footer a:hover {
    color: #FFD700;
}
