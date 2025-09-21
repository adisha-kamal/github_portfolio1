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

/* ====== Projects Section ====== */
.projects-section {
    background: linear-gradient(135deg, #131010 45%, #161616 55%);
    padding: 40px 20px;
    color: #f5f5f5;
}

.projects-section .section-title {
    font-size: 28px;
    color: #48CFCB;
    margin-bottom: 20px;
}

.project-item {
    background: rgba(72, 207, 203, 0.1);
    border: 1px solid rgba(72, 207, 203, 0.3);
    border-radius: 10px;
    padding: 20px;
    margin: 10px;
    transition: transform 0.3s ease;
}

.project-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 30px rgba(72, 207, 203, 0.5);
}

.project-item h4 {
    font-size: 19px;
    font-weight: 600;
    color: #48CFCB;
}

.project-item p {
    font-size: 14px;
    color: #f5f5f5;
}

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
