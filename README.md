SonarQube Nexus Pipeline

This project shows how to connect SonarQube and Nexus in a DevOps pipeline using Jenkins.
It runs code checks with SonarQube and uploads build files to Nexus automatically.

Tools Used

Jenkins • SonarQube • Nexus • Maven • Docker • GitHub

Steps

Clone the repo

Set up SonarQube and Nexus

Add your project key, token, and Nexus info

Run the Jenkins pipeline

Pipeline Flow

Build → Test → Scan → Publish

Result

Quality-checked code is stored in Nexus and visible in Jenkins and SonarQube.# sonarqube-nexus-pipeline-
