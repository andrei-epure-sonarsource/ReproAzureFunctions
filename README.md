If you want to fork this to repro in your own account:
- fork the repo
- change the `main.yml` workflow to have a different SonarCloud organization (`/o:"andrei-epure-sonarsource-github"`)
- eventually update the project name
- go to Settings -> Secrets -> Action -> New Repository Secret -> add name `SONAR_TOKEN` and value - a token created with your personal SonarCloud organization (https://sonarcloud.io/account/security/ -> generate a token)

![image](https://user-images.githubusercontent.com/38876598/183081147-1d7abd62-3736-4dc8-978e-45b303bb945e.png)
