Deploy artifact to GitHub maven repository
==========

mvn deploy:deploy-file -Durl=file:///Users/dev/workspace/maven/repositories/xx -Dversion=1.0.0 -DgroupId=xx -DartifactId=xx -Dfile=xx.jar

----------

1.android-support-v13.jar
mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=r13 -DgroupId=com.google.android -DartifactId=support-v4 -Dfile=android-support-v13.jar 

2.android.jar   api:19
mvn deploy:deploy-file -Durl=file:///home/dan/dev/workspace/maven/repositories/thirdparty -Dversion=4.4.2.3 -DgroupId=com.google.android -DartifactId=android -Dfile=android.jar 

3.slidingmenu-1.3.SNAPSHOT.aar
