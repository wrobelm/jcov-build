# jcov-build
As at the official site of JCov the release download doesn't work anymore, and some of the Ant build dependencies were not so easy to download for me, I decided to create this repository with JCov built prerequisite .jars and also jcov.jar built itself, to make it easy for others to try this tool, without having to build it themselves (which I recommend)

You can checkout original JCov sources here: hg clone http://hg.openjdk.java.net/code-tools/jcov

The new version that you can use for Java 17 you can find here: git clone https://github.com/openjdk/jcov.git

For the dependencies you can use maven repository: https://mvnrepository.com/artifact/org.ow2.asm/asm
Jcov for Java 8 was compiled with versions 7.0. Jcov for Java 17 was compiled with version 9.1

I prepared an article about using JCov code coverage tool, you can find it here: http://blog.mwrobel.eu/dynamic-java-e2e-code-coverage/


