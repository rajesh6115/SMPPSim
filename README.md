This repo is for self learn.  I modified the origial logging to Slf4j logging which helps me for debugging:)

SMPPSim official website tutorial:
http://www.seleniumsoftware.com/user-guide.htm#quick

REQUIERD SOFTWARE:
1. java environment java 1.6.x or later.
2. maven 2.x or 3.x

QUICK START

How to run?
java -jar smppsim.jar conf/logback.xml conf/smppsim.props

How to change credentials?
All credential information is in the conf/smppsim.props

***attention***:
the smpp-lib may not be downloaded, please get the maven dependency 
in the conf/ folder and put it into your local maven repository:
/.m2/respository/smpp/smpp-lib

***update***:
build: do `mvn clean` first, it will install that attention 3party to local mvn
this needs to be done one time per build env
then do `mvn clean package` as usual
