# qa-ci-cd-pipeline
End-to-end CI/CD pipeline for automated mobile and performance testing using Appium, JMeter, and Allure.

Project Overview

Each time new code is pushed to the repository, the pipeline automatically:
1. Runs **Appium functional tests** (UI & mobile flows).
2. Executes **JMeter performance tests**.
3. Generates **Allure test reports**.
4. Uploads results as artifacts (downloadable from the GitHub Actions page).
