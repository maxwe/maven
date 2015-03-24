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

9.hanmei-book-lib-1.0-SNAPSHOT.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=hanmi-book-lib-1.0-SNAPSHOT.jar -DgroupId=com.hanmi.book -DartifactId=hanmi-book-lib -Dversion=1.0-SNAPSHOT -Dpackaging=jar -Dsources=hanmi-book-lib-1.0-SNAPSHOT-sources.jar

    <dependency>
      <groupId>com.hanmi.book</groupId>
      <artifactId>hanmi-book-lib</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>

10.util-eventbus-1.0-SNAPSHOT.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=util-eventbus-1.0-SNAPSHOT.jar -DgroupId=org.maxwe.util -DartifactId=util-eventbus -Dversion=1.0-SNAPSHOT -Dpackaging=jar -Dsources=util-eventbus-1.0-SNAPSHOT-sources.jar

    <dependency>
      <groupId>org.maxwe.util</groupId>
      <artifactId>util-eventbus</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>

11.util-json-1.0-SNAPSHOT.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=util-json-1.0-SNAPSHOT.jar -DgroupId=org.maxwe.util -DartifactId=util-json -Dversion=1.0-SNAPSHOT -Dpackaging=jar -Dsources=util-json-1.0-SNAPSHOT-sources.jar

    <dependency>
      <groupId>org.maxwe.util</groupId>
      <artifactId>util-json</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>

12.android-support-v4-19.1.+.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=support-v4-19.1.0.jar -DgroupId=com.android.support -DartifactId=support-v4 -Dversion=19.1.+ -Dpackaging=jar -Dsources=support-v4-19.1.0-sources.jar -Djavadoc=support-v4-19.1.0-javadoc.jar

    <dependency>
      <groupId>com.android.support</groupId>
      <artifactId>support-v4</artifactId>
      <version>19.1.+</version>
    </dependency>

13.BaiduLBS_Android.jar

mvn deploy:deploy-file -Durl=file:///home/glm/dev/workspaces/maven/repositories/thirdparty -Dversion=5.0 -DgroupId=com.baidu.location -DartifactId=baidulbs -Dfile=BaiduLBS_Android.jar

    <dependency>
      <groupId>com.baidu.location</groupId>
      <artifactId>baidulbs</artifactId>
      <version>5.0</version>
    </dependency>

14.playercore.jar 20150211

mvn deploy:deploy-file -Durl=file:///Users/danhantao/dev/workspaces/maxwe/maven/repositories/thirdparty -DgroupId=kr.co.netntv.playercore -DartifactId=playercore -Dversion=1.0 -Dpackaging=jar -Dfile=playercore.jar


      <dependency>
            <groupId>kr.co.netntv.playercore</groupId>
            <artifactId>playercore</artifactId>
            <version>1.0</version>
      </dependency>

15.libGoogleAnalyticServices.jar
mvn deploy:deploy-file -Durl=file:///Users/danhantao/dev/workspaces/maxwe/maven/repositories/thirdparty -Dfile=libGoogleAnalyticsServices.jar -DgroupId=com.google.android -DartifactId=googleAnalytics -Dversion=1.0 -Dpackaging=jar 

        <dependency>
            <groupId>com.google.android</groupId>
            <artifactId>googleAnalytics</artifactId>
            <version>1.0</version>
        </dependency>

16.super-sdk
mvn deploy:deploy-file -Durl=file:///Users/danhantao/dev/workspaces/maxwe/maven/repositories/thirdparty -Dfile=super-sdk.aar -DgroupId=com.retechcorp.android -DartifactId=super-sdk -Dversion=1.0-SNAPSHOT -Dpackaging=aar

        <dependency>
            <groupId>com.retechcorp.android</groupId>
            <artifactId>super-sdk</artifactId>
            <version>1.0-SNAPSHOT</version>
            <type>aar</type>
        </dependency>
        
