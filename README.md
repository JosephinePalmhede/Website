# Josephine Palmhede – Personal Webpage

This is the source code for my personal portfolio website, built with HTML, CSS, and Bootstrap. The site serves as a simple webpage showcasing my name, title, and links to contact me.

## Live Webpage

[View the site](https://josephinepalmhede.com/)  

## Hosting and Deployment (AWS Amplify + S3)

This site is deployed using **AWS Amplify**, which is connected to a GitHub repository. The static files are hosted in an **Amazon S3 bucket**.

1. **GitHub Integration**: AWS Amplify is connected to the GitHub repository.
2. **CI/CD Pipeline**: On every push to the `main` branch, Amplify automatically:
   - Pulls the latest code
   - Deploys the updated files to an S3 bucket
   - Serves the site via a public URL or custom domain

## Tools Used

- **HTML5** & **CSS3**
- **[Bootstrap 5](https://getbootstrap.com/)** - responsive layout framework
- **[Font Awesome](https://fontawesome.com/)** - For social icons
- **[Google Fonts](https://fonts.google.com/)** - Roboto & Playfair Display
- **[AWS Amplify](https://aws.amazon.com/amplify/)** - CI/CD pipeline
- **[Amazon S3](https://aws.amazon.com/s3/)** - static site hosting