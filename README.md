Deploy artifact to GitHub maven repository
==========

mvn deploy:deploy-file -Durl=file:///Users/dev/workspace/maven/repositories/xx -Dversion=1.0.0 -DgroupId=xx -DartifactId=xx -Dfile=xx.jar
----------
### Maven

```xml
  <repositories>
    <repository>
      <id>sonatype-nexus-snapshots</id>
      <name>Sonatype Nexus Snapshots</name>
      <url>https://oss.sonatype.org/content/repositories/snapshots</url>
      <releases>
        <enabled>false</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
    <repository>
      <id>maxwe-thirdparty</id>
      <url>https://raw.githubusercontent.com/maxwe/maven/master/repositories/thirdparty/</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
  </repositories>
```
  

1.android-support-v13.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=r13 -DgroupId=com.google.android -DartifactId=support-v4 -Dfile=android-support-v13.jar 

2.android.jar   api:19

mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=4.4.2.3 -DgroupId=com.google.android -DartifactId=android -Dfile=android.jar 

    <dependency>
      <groupId>com.google.android</groupId>
      <artifactId>android</artifactId>
      <version>4.4.2.3</version>
    </dependency>



3.slidingmenu-1.3.SNAPSHOT.aar

4.xUtils-2.6.14.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=xUtils-2.6.14.jar -DgroupId=com.lidroid.xutils -DartifactId=xUtils -Dversion=2.6.14 -Dpackaging=jar

    <dependency>
      <groupId>com.lidroid.xutils</groupId>
      <artifactId>xUtils</artifactId>
      <version>2.6.14</version>
    </dependency>

5.netntv_playercore.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=netntv_playercore.jar -DgroupId=kr.co.netntv -DartifactId=playercore -Dversion=201401223 -Dpackaging=jar

    <dependency>
      <groupId>kr.co.netntv</groupId>
      <artifactId>playercore</artifactId>
      <version>201401223</version>
    </dependency>
    
6.umeng-analytics-v5.2.3.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-analytics-v5.2.3.jar -DgroupId=com.umeng -DartifactId=analytics -Dversion=v5.2.3 -Dpackaging=jar

    <dependency>
      <groupId>com.umeng</groupId>
      <artifactId>analytics</artifactId>
      <version>v5.2.3</version>
    </dependency>

7.umeng-fb-v4.3.2.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-fb-v4.3.2.jar -DgroupId=com.umeng -DartifactId=fb -Dversion=v4.3.2 -Dpackaging=jar

    <dependency>
      <groupId>com.umeng</groupId>
      <artifactId>fb</artifactId>
      <version>v4.3.2</version>
    </dependency>

8.umeng-update-v2.4.2.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-update-v2.4.2.jar -DgroupId=com.umeng -DartifactId=update -Dversion=v2.4.2 -Dpackaging=jar

    <dependency>
      <groupId>com.umeng</groupId>
      <artifactId>update</artifactId>
      <version>v2.4.2</version>
    </dependency>

9.hanmei-book-lib-1.0-SNAPSHOT

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=hanmi-book-lib-1.0-SNAPSHOT.jar -DgroupId=com.hanmi.book -DartifactId=hanmi-book-lib -Dversion=1.0-SNAPSHOT -Dpackaging=jar -Dsources=hanmi-book-lib-1.0-SNAPSHOT-sources.jar

    <dependency>
      <groupId>com.hanmi.book</groupId>
      <artifactId>hanmi-book-lib</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>
