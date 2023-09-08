
gradle명령어 

서버포트 하나 더올리는법 
1. gradlew bootRun --args='--server.port=9003'
   java -jar -Dserver.port=9004 ./build/libs/your-app-name.jar
부트런 하는 gradle명령어
2. gradlew bootRun
compile하는 명령어 
3. gradlew compileJava

