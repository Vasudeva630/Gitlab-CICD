# Gitlab-CICD
This is a Gitlab CICD of Java-springboot-application. 
This has 3 stages which are:
    1.Build
    2.Unit-test
    3.Code-quality
1. In the fist stage using maven command :- 
     mvn clean package
2. In the unit-test using maven:
     mvn test 
3. For the code quality using soanrqube
     mvn sonar:sonar -Dsonar.host.url=${SONAR_HOST_URL} -Dsonar.login=${SONAR_LOGIN}

![Gitlab1]("C:\Users\ASUS\Downloads\Gitlab1.png"
"C:\Users\ASUS\Downloads\GitHubDesktopSetup-x64.exe"Gitlab1.png)
