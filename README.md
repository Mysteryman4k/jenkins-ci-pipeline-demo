# Jenkins CI/CD Pipeline Demo

A continuous integration and deployment pipeline built with Jenkins, completed for SIT223 at Deakin University.

## What it covers

- A declarative Jenkins pipeline defined in a Jenkinsfile
- Build, test and deploy stages triggered automatically on commit
- Integration with a GitHub repository as the pipeline source
- Build status reporting and artefact handling between stages

## Running it

1. Install Jenkins and start the service.
2. Create a new Pipeline job and point it at this repository.
3. Select Pipeline script from SCM so Jenkins reads the Jenkinsfile from the repo.
4. Trigger a build, or push a commit to run the pipeline automatically.

## Notes

This was coursework rather than a production pipeline, built to understand how the stages of a CI/CD workflow fit together. The same ideas carry into the GitHub Actions pipeline running on Trackademic (github.com/Mysteryman4k/lifeplanner), which tests across multiple Python versions and operating systems and publishes a packaged release.
