<center><h1 id="gameauth">GameAuth</h1></center>
<center><h2 id="how-to-start-the-gameauth-application">How to start the GameAuth application</h2></center>
<ol>
    <li>Run <code>mvn clean install</code> to build your application </li>
    <li>Start application with <code>java -jar target/gameauth-0.0.1-SNAPSHOT.jar server config.yml</code>
    </li>
    <li>To check that your application is running enter url <code>http://localhost:8080</code>
    </li>
</ol>
<h2 id="health-check">Health Check</h2>
<p>To see your applications health enter url <code>http://localhost:8081/healthcheck</code>
</p>
