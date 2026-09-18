<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Course Syllabus Tracker</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>Digital Course Syllabus Tracker</h1>
        <p>Track your course subjects and syllabus completion.</p>

        <div class="course">
            <h2>Web Development</h2>

            <label>
                <input type="checkbox" onchange="updateProgress()">
                HTML Basics
            </label>

            <label>
                <input type="checkbox" onchange="updateProgress()">
                CSS & Tailwind CSS
            </label>

            <label>
                <input type="checkbox" onchange="updateProgress()">
                JavaScript
            </label>

            <label>
                <input type="checkbox" onchange="updateProgress()">
                Responsive Design
            </label>

            <label>
                <input type="checkbox" onchange="updateProgress()">
                Web Project
            </label>

            <div class="progress">
                <div id="progressBar"></div>
            </div>

            <p id="progressText">Progress: 0%</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
