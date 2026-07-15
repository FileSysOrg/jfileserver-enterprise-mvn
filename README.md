# jfileserver-enterprise-mvn
Maven repository for jfileserver-enterprise artefacts

To access the repository in your pom.xml add the following sections :-

    <dependencies>
        <dependency>
            <groupId>org.filesys</groupId>
            <artifactId>jfileserver-enterprise</artifactId>
            <version>1.3.1</version>
        </dependency>
    </dependencies>

    <repositories>
        <!-- jfileserver-enterprise GitHub Maven repository -->
        <repository>
            <id>jfileserver-enterprise-mvn-repo</id>
            <url>https://github.com/FileSysOrg/jfileserver-enterprise-mvn/raw/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
