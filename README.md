https://bitbucket.org/hvisser/bundles の https://bitbucket.org/hvisser/bundles/downloads から jar をダウンロードしてきて、以下のコマンドで maven repository の形で公開しているだけです。

無保証です。
ライセンスはオリジナルのライセンスを参照してください。

```
$ mvn3 deploy:deploy-file -DgroupId=com.neenbedankt.bundles -DartifactId=bundles -Dversion=1.0.3 -Dpackaging=jar -Dfile=/Users/zaki/Downloads/bundles-1.0.3.jar -Durl=file:///Users/zaki/fromgit/bundle_zaki50/maven_repo
$ mvn3 deploy:deploy-file -DgroupId=com.neenbedankt.bundles -DartifactId=argument -Dversion=1.0.3 -Dpackaging=jar -Dfile=/Users/zaki/Downloads/argument-1.0.3.jar -Durl=file:///Users/zaki/fromgit/bundle_zaki50/maven_repo
$ mvn3 deploy:deploy-file -DgroupId=com.neenbedankt.bundles -DartifactId=frozen -Dversion=1.0.3 -Dpackaging=jar -Dfile=/Users/zaki/Downloads/frozen-1.0.3.jar -Durl=file:///Users/zaki/fromgit/bundle_zaki50/maven_repo
```
