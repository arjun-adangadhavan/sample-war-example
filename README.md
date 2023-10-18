# sparkjava-war-example
Build war with maven and sparkjava framework

Steps:

1. Download a fresh [Tomcat 8 distribution](https://tomcat.apache.org/download-80.cgi)
2. Clone this repository to your local machine
3. Run mvn package
4. Copy the generated `sparkjava-hello-world-1.0.war` to the Tomcat `webapps` folder
5. Start Tomcat by running `bin\startup.bat` (or `bin\startaup.sh` for Linux)
5. Tomcat will automatically deploy the war
6. Open (http://localhost:8080/sparkjava-hello-world-1.0/war) in your browser

1.git clone 

2.mvn clean install

3.wget https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.95/bin/apache-tomcat-8.5.95.zip

4.unzip apache-tomcat-8.5.95.zip

5.cp target/*.war  apache-tomcat-8.5.95/wabapps/

6.cd apache-tomcat-8.5.95/bin/

7.sh calina.sh start
