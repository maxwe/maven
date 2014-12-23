Deploy artifact to GitHub maven repository
==========

mvn deploy:deploy-file -Durl=file:///Users/dev/workspace/maven/repositories/xx -Dversion=1.0.0 -DgroupId=xx -DartifactId=xx -Dfile=xx.jar
----------

1.android-support-v13.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=r13 -DgroupId=com.google.android -DartifactId=support-v4 -Dfile=android-support-v13.jar 

2.android.jar   api:19

mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=4.4.2.3 -DgroupId=com.google.android -DartifactId=android -Dfile=android.jar 

3.slidingmenu-1.3.SNAPSHOT.aar

4.xUtils-2.6.14.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=xUtils-2.6.14.jar -DgroupId=com.lidroid.xutils -DartifactId=xUtils -Dversion=2.6.14 -Dpackaging=jar

5.netntv_playercore.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=netntv_playercore.jar -DgroupId=kr.co.netntv -DartifactId=playercore -Dversion=201401223 -Dpackaging=jar

6.umeng-analytics-v5.2.3.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-analytics-v5.2.3.jar -DgroupId=com.umeng -DartifactId=analytics -Dversion=v5.2.3 -Dpackaging=jar

7.umeng-fb-v4.3.2.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-fb-v4.3.2.jar -DgroupId=com.umeng -DartifactId=fb -Dversion=v4.3.2 -Dpackaging=jar

8.umeng-update-v2.4.2.jar

mvn deploy:deploy-file -Durl=file:///home/dan/dev/retech/maven/repositories/thirdparty -Dfile=umeng-update-v2.4.2.jar -DgroupId=com.umeng -DartifactId=update -Dversion=v2.4.2 -Dpackaging=jar
