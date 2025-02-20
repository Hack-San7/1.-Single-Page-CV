
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    padding: 20px;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* border-bottom: 3px solid black;*/
    padding: 15px 20px;
    font-size: 24px;
}
nav a {
    text-decoration: none;
    margin: 0 10px;
    color: black;
    font-weight: bold;
}

/* Main Title */
.main-title {
    text-align: center;
    margin: 20px 0;
}

/* Grid Layout */
.container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr; /* 3 columns for desktop */
    gap: 20px;
    margin-top: 20px;
}
.box {
    border: 2px solid black;
    padding: 15px;
}

/* Reviews Section */
.reviews-title {
    margin-top: 20px;
}
.reviews {
    display: flex;
    justify-content: space-between;
    gap: 10px;
    margin-top: 20px;
}
.review-box {
    flex: 1;
    border: 2px solid black;
    padding: 10px;
    text-align: center;
}

/* Footer */
footer {
    text-align: center;
    margin-top: 20px;
    padding: 10px;
    /* border-top: 2px solid black;*/
}

/* Mobile Responsive */
@media (max-width: 768px) {
    .container {
        display: flex;
        flex-direction: column;
    }
    header {
        flex-direction: column;
        text-align: center;
    }
    nav {
        margin-top: 10px;
    }
    .reviews {
        flex-direction: column;
        /*https://roadmap.sh/projects/portfolio-website*/
    }
}
