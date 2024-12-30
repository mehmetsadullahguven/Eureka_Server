http://localhost:8761/

Eureka örneğidir. pom.xml dosyasına eklemesi yapılabilir.

<!-- for maven target 17: SonarQube 11 veya 17 yapmalısınız -->
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-compiler-plugin</artifactId>
    <version>3.5.1</version>
    <configuration>
        <source>17</source>
        <target>17</target>
    </configuration>
</plugin>