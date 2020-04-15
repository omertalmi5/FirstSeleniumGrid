firstAutomation
Need to find the ip of the machine with ifconfig and put it in the url
Wait afer set up the infrastructure before running the tests
1. set up the grid :
docker-compose --file docker-compose-infra.yml  up

2. Run the tests:
or from terminal :mvn test
or build the image of tests and run it:
docker build -t imagename .
docker run imagename

or docker-compose --file docker-compose-tests.yml up

In the tutorial he uses jar because he wants ude only jre and not jdk
because he wants thinner image as much
