




Установка jar -файла как зависимости в локальный .m2:

mvn install:install-file -Dfile=C:/Users/user/IdeaProjects/project-maven/lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar   

Запуск jar-файла:

java -jar "C:\Users\user\IdeaProjects\project-maven\target\project-maven-1.0.jar"

запускать с SDK Full (со встроенным Java FX)
