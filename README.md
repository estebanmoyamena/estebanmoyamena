<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esteban Moya - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
        }
        .header {
            text-align: center;
            padding: 50px;
            background-color: #343a40;
            color: #ffffff;
        }
        .header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .header h1 {
            margin: 20px 0 10px;
            font-size: 2.5rem;
        }
        .header p {
            font-size: 1.2rem;
        }
        .skills {
            padding: 50px 0;
        }
        .skills h2 {
            text-align: center;
            margin-bottom: 40px;
        }
        .skills .row > div {
            text-align: center;
            padding: 20px;
        }
        .skills .row img {
            width: 100px;
            height: 100px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="your-photo.jpg" alt="Esteban Moya">
        <h1>Esteban Moya</h1>
        <p>Java | Spring Boot | HTML | CSS | Bootstrap Developer</p>
    </div>

    <div class="container skills">
        <h2>My Skills</h2>
        <div class="row">
            <div class="col-md-4">
                <img src="java-logo.png" alt="Java">
                <h3>Java</h3>
            </div>
            <div class="col-md-4">
                <img src="spring-boot-logo.png" alt="Spring Boot">
                <h3>Spring Boot</h3>
            </div>
            <div class="col-md-4">
                <img src="html-logo.png" alt="HTML">
                <h3>HTML</h3>
            </div>
            <div class="col-md-4">
                <img src="css-logo.png" alt="CSS">
                <h3>CSS</h3>
            </div>
            <div class="col-md-4">
                <img src="bootstrap-logo.png" alt="Bootstrap">
                <h3>Bootstrap</h3>
            </div>
        </div>
    </div>
</body>
</html>
