# JavaFileSystem
This project is build using JNA Java Wrapper for Fuse.
This project is build using Netbeans. For best results using Netbeans IDE or any appropriate IDE for Your Conveniance.
These are some variable you have to change according to your file system.
String IndexInode = "Inode-0";

final String filename = "/";
String contents ;
String ContentsToWrite;
int numberOfFiles = 1064;
int FileSize = 1024;
int contentPerFile = 1024;
int inodeReadingBuffer = 40;
int baseFileBlockIndex = 40;
int nodesPerBlock = 25;
String IndexInode = "Inode-0";
String mountPoint = "/home/muhammadqasimhunain/NetBeansProjects/MountFolderV2";   
final static String FILENAME = "/home/muhammadqasimhunain/NetBeansProjects/mainFile2.txt";
final static String FILENAMEInode = "/home/muhammadqasimhunain/NetBeansProjects/mainFile2Inode.txt";
final static String FileDirName = "/home/muhammadqasimhunain/NetBeansProjects/";
    
The code is written keeping in mind the basses of Design Patterns. THe code is effeciently reusable and as much as genric as we can.

For unmounting press Crl + Shift + T.
Command fusermount -u mountPoint.
which in case is "/home/muhammadqasimhunain/NetBeansProjects/MountFolderV2"
