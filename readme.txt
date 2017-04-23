##########################SENTIMENTAL ANALYSIS############################

Step 1:- Download and install hadoop in your system, if you dont know how to do it then follow the link - https://www.tutorialspoint.com/hadoop/hadoop_enviornment_setup.htm


Step 2:- Download and install pig in your system, if you dont know how to do it then follow the link - https://www.tutorialspoint.com/apache_pig/apache_pig_installation.htm


Step 3:- start your hadoop, to do that go to your hadoop folder and enter the following command in the terminal
sbin/start-all.sh
Verify that the hadoop is started using jps command

Step 4:- download the tweets from the link - https://drive.google.com/file/d/0ByJLBTmJojjzNkRsZWJiY1VGc28/view and save it in the desired location

Step 5:- download the AFFIN dictionary from the link - https://drive.google.com/file/d/0ByJLBTmJojjzZ0d1RVdBTDVjT28/view and save it in the desired location

Step 6:- Open the sentimental_analysis.pig file and provide the correct path for loading the data,  after doing that save the file

Step 7:- Run the following command - pig -x local sentimental_analysis.pig, and you will see all the positive tweets.

#################################END######################################