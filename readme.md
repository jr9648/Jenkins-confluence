# Confluence API Automation with Jenkins Pipeline
This repository contains code for automating tasks related to Confluence using Python, Jenkins Pipeline, and GitHub.

## Features
- Integration with Confluence API to retrieve and analyze data from a specific page.
- Jenkins Pipeline setup to trigger builds based on changes detected in the Confluence page.
- Python script for parsing HTML content and extracting relevant data.
- Automated commit and push to GitHub repository based on detected changes.
# Requirements
- Python 3.11 or higher
- Jenkins Pipeline
- GitHub repository for version control
# Files
- test.py: Python script for interacting with the Confluence API and parsing HTML content.
- config.json: JSON file containing configuration data.
- trigger.json: JSON file used to trigger Jenkins Pipeline based on detected changes.
- Jenkinsfile: Jenkins Pipeline configuration file.
# Instructions
1. Clone the repository to your local machine.
2. Set up a Jenkins Pipeline with the provided Jenkinsfile.
3. Configure the config.json file with your Confluence site URL, page ID, and base64-encoded token.
4. Execute the Jenkins Pipeline to automate tasks related to Confluence.
# Usage
- Run the Jenkins Pipeline with the specified environment parameter ('dev' or 'prod') to trigger the appropriate deployment pipeline.
- View the console output of the Jenkins Pipeline for status and error messages.