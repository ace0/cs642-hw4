# CS 642: Computer Security - Homework Four

This homework assignment covers topics in network security. You must work with a partner. There are four parts; all are required; there is no extra credit portion for this assignment.

It is due **May 2, 2016** by 11:59 PM local time. 

## Background
In this repository you will find four packet traces (pcap files) that can be read by the WireShark tool (among other tools). You will need to investigate these traces to answer the questions below. To get started you will want to understand how to use WireShark's filtering capabilities. Your solution will be a file `solutions.txt` with answers to the questions below.

## Trace 1: HTTP
1. Give three websites (domain name and IP addresses) visited from source IP address `192.168.0.100`.

1. Give three search queries and the domain of the site for each query made from source IP address `192.168.0.100`.


### Trace 2: FTP
FTP is the file transport protocol. There is a lot of information about it on the internet.

1. What is the user name and password used to connect to the FTP server?

1. List any (and all) files that were downloaded from the FTP server.

1. List the full path for two files (in different directories) on the FTP server that were NOT downloaded.


### Trace 3: Traceroute
`traceroute` is a tool used to determine the route between two IP addresses. You can find information about on the internet.
Wikipedia has a nice introduction: https://en.wikipedia.org/wiki/Traceroute.

1. Briefly describe how the traceroute tool works including which network protocols are in use.

1. Give the source IP address that issued the traceroute command and the destination IP address.

1. List the IP addresses on the route between source and destination.


## Trace 4: POP
The post-office protocol (POP) is used for email.

1. What is the POP username and password?

1. How many emails are in the user’s mailbox?

1. Give the contents of `from`, `to`, `subject`, and `date` for one email message.

1. What email client (application) and operating system is this person using to send and receive email?

## Deliverables
No need to make a tar files for this assignment. Ensure that your `solutions.txt` file includes your group members names and UW ID #s and upload it to the hw-4 folder on the Desire2Learn website for this course:
https://uwmad.courses.wisconsin.edu/d2l/home/3199130

Use Assignments > Dropbox to find the hw-4 submission folder.

## Grading
Each subquestion is worth up to 1 point for a total of 12 points for this assignment. There is no extra credit for this assignment.

## Collaboration Policy
You are encouraged to use the internet, the Piazza discussion board for this class, and classmates for information about tools and setup. Please help your fellow classmates with tools setup and understanding how to use WireShark, but don't discuss solution specifics with anyone beyond your project partner.
