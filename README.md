cd ~/maven-web-app
cat > README.md << EOL
# Maven Web Application

## Project Overview
Simple Maven web application demonstrating basic CI/CD pipeline with Jenkins, GitHub, and Tomcat.

## Technologies
- Maven
- Java 17
- Jenkins
- GitHub

## Setup Instructions
1. Clone the repository
2. Build with Maven: \`mvn clean package\`
3. Deploy to Tomcat

## Jenkins Integration
Configured for automated build and deployment

## Author
Praveen Machani
EOL

git add README.md
git commit -m "Add README.md"
git push origin main
