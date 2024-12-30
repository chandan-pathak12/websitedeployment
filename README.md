Aim:- To automate the deployment of a static website to an AWS S3 bucket whenever changes are pushed to the GitHub repository's main branch. The website will be publicly accessible.

Key Components
- S3 bucket
- index.html code
- github action

Automate Deployment:
1. Push or update files in the main branch of the GitHub repository 
2. The GitHub Actions workflow is triggered automatically.
3. The workflow uploads or updates the website files in the S3 bucket.
4. The S3 bucket serves the updated website publicly.


![Alt Text](/website-CICD.png)

