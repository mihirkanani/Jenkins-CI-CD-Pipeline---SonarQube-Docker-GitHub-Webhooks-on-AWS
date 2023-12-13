<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jenkins CI/CD Pipeline Project</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 20px;
        }

        h1 {
            color: #0066cc;
        }

        h2 {
            color: #009933;
        }

        p {
            margin-bottom: 15px;
        }

        ol {
            margin-bottom: 15px;
        }

        code {
            background-color: #f4f4f4;
            padding: 3px 5px;
            border-radius: 3px;
            font-family: 'Courier New', Courier, monospace;
        }

        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }

        a {
            color: #0066cc;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <h1>Jenkins CI/CD Pipeline - SonarQube, Docker, GitHub Webhooks on AWS</h1>

    <h2>📝 Project Steps:</h2>

    <ol>
        <li><strong>Code Repository in GitHub:</strong> Pushing my code repository into GitHub to kickstart the automation
            process.</li>
        <li><strong>EC2 Instances Galore:</strong> Setting up three EC2 instances for Jenkins server, SonarQube server,
            and Docker server to build a resilient infrastructure.</li>
        <li><strong>GitHub + Jenkins Webhook Magic:</strong> Integrating GitHub Webhooks with the Jenkins server for
            seamless automation triggered by code pushes.</li>
        <li><strong>Code Analysis Nirvana:</strong> Connecting SonarQube with Jenkins to perform in-depth code analysis
            and maintain code quality.</li>
        <li><strong>Dockerizing the Game:</strong> After a successful SonarQube integration, installing Docker desktop
            on an EC2 instance to containerize the application.</li>
        <li><strong>Jenkins + Docker Harmony:</strong> Copying Jenkins project files into Docker and crafting a
            Dockerfile to encapsulate the project.</li>
        <li><strong>Containerizing Excellence:</strong> Running the Docker package and initiating the container,
            ensuring a smooth deployment.</li>
        <li><strong>Web Application Awesomeness:</strong> Voila! Accessing the web application by navigating to the
            Docker instance on your browser, making the results of your hard work tangible.</li>
    </ol>

    <p><strong>💡 Key Takeaway:</strong> This project not only streamlines the development and deployment process but
        also enhances code quality with SonarQube integration. A hands-on journey into the world of DevOps, and this is
        just the beginning! 🚀</p>

</body>

</html>
