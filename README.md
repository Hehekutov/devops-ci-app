# devops-ci-app

Учебное приложение Flask с маршрутами / и /health. Конвейер выполняет Pylint, pytest, сборку Docker-образа и smoke-test. Main публикует теги по SHA и latest. Git-теги вида v1.1.0 публикуют тег 1.1.0. В Pull Request выполняются проверки.
