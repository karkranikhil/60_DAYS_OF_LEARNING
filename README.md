# 60_DAYS_OF_LEARNING


## DAY 1 - SSH

<h4>SSH or secure shell is a protocol.SSH is a way for machines to communicate with one another.</h4>

1) For example Hypertext Transfer Protocol allows you to send files over the internet.
just like HTTP SSH is another protocol that allows us to communicate
between two computers over the Internet.
2) It allows users to share files as well as control and modify remote computers over the internet.

3) It was created as a secure way of communication which again encrypts all data so bad actors can't monitor

4) A shell needs a certain protocol to enable data exchange or communication between two devices and not
just a browser and a server and that's why SSH is called secure shell protocol.

5) It's a protocol to use over shell and if you remember a shell unlike a browser allows you to talk to
the operating system yes you've used your command line before right.

6) The significant advantage offer by SSH over its predecessors is the use of encryption to ensure
secure transfer of information between host and the client.The host refers to the remote server you're trying to access while the client is the computer you're
using to access the host.
    
        ssh {user}@{host}
    <p><b>ssh -</b> SSH key command and instruct your system that you want to open an encrypted secure
          shell connection.</p>
    <p><b>user -</b> user represents the account you want to access.For example you may want to access the root user which is basically synonymous for system an administrator.</p>
    <p><b>host -</b> Host refers to the computer you want to access.</p>
    
7) Once you are enter into your ubuntu box . Run below commands
    
        ssh root@ip
        sudo apt-get install git // it will install git
        git clone repo
        sudo apt install curl
        curl -sL https://deb.nodesource.com/setup_6.x | sudo bash -
        sudo apt-get install -y nodejs
        sudo apt-get install -y npm
        exit // to logout of the box
        
8) Sending local folder data to server
        
        cd folderName
        rsync -av . root@ip:~/destinationFolder eg rsync -av . root@167.99.146.57:~/destination
        ssh root@ip
        ls // it will show the folder with the data that you have copied
        