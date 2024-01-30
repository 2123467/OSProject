# OSProject Running Containers for Application Development

Group Name: Hello

Section: 2 

Team Mates:
1. MUHAMMAD NUR FIKRI BIN AZARI 2112161
2. ARMAN NURI ANUAR 2119279
3. UMAIR BIN MOHD YAZIZ 2123467	


***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** (https://github.com/2123467/OSProject)
2. How many files and folders are in this repository. ***(1 mark)*** 1 folder with 6 png and 1 readme file.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** Linux.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 2 course, 8GB RAM and 32GB storage, up to 32 course, 64GB RAM and 128GB storage.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** As a record of what we have done and to ensure synchronization of the code.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
2. Run the command **cat /etc/passwd** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
3. Run the command **df** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 13636836  17516748  44% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 23016248   7265544  77% /vscode
/dev/sda1       46127956      268  43752112   1% /tmp
/dev/loop3      32847680 13636836  17516748  44% /workspaces
4. Run the command **du** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ du
64      ./.git/hooks
4       ./.git/branches
8       ./.git/info
8       ./.git/objects/ab
12      ./.git/objects/0b
8       ./.git/objects/52
8       ./.git/objects/0d
8       ./.git/objects/71
8       ./.git/objects/b2
12      ./.git/objects/70
8       ./.git/objects/cd
8       ./.git/objects/4b
8       ./.git/objects/3f
8       ./.git/objects/74
8       ./.git/objects/81
8       ./.git/objects/49
1820    ./.git/objects/pack
8       ./.git/objects/fd
8       ./.git/objects/04
12      ./.git/objects/ff
12      ./.git/objects/72
12      ./.git/objects/d2
8       ./.git/objects/93
8       ./.git/objects/e9
12      ./.git/objects/2e
8       ./.git/objects/86
8       ./.git/objects/cb
8       ./.git/objects/d8
4       ./.git/objects/info
12      ./.git/objects/e5
8       ./.git/objects/fe
12      ./.git/objects/44
8       ./.git/objects/91
8       ./.git/objects/83
8       ./.git/objects/a3
12      ./.git/objects/62
12      ./.git/objects/3d
8       ./.git/objects/f2
12      ./.git/objects/17
8       ./.git/objects/b9
8       ./.git/objects/60
8       ./.git/objects/c4
8       ./.git/objects/c5
8       ./.git/objects/47
8       ./.git/objects/fc
8       ./.git/objects/20
16      ./.git/objects/fb
8       ./.git/objects/b6
8       ./.git/objects/7b
12      ./.git/objects/1c
8       ./.git/objects/fa
8       ./.git/objects/4f
8       ./.git/objects/4a
12      ./.git/objects/b5
12      ./.git/objects/64
8       ./.git/objects/eb
12      ./.git/objects/af
8       ./.git/objects/f7
12      ./.git/objects/73
8       ./.git/objects/e7
8       ./.git/objects/1b
12      ./.git/objects/14
8       ./.git/objects/24
8       ./.git/objects/59
8       ./.git/objects/e6
8       ./.git/objects/f6
8       ./.git/objects/c6
8       ./.git/objects/96
8       ./.git/objects/a6
8       ./.git/objects/c3
8       ./.git/objects/58
2432    ./.git/objects
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
8       ./.git/refs/heads
32      ./.git/refs
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
8       ./.git/logs/refs/heads
28      ./.git/logs/refs
36      ./.git/logs
2612    ./.git
1972    ./images
4600    .
5. Run the command **ls** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ ls
README.md  images
6. Run the command **ls -asl** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 Jan 30 12:43 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 30 12:43 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 30 12:44 .git
16 -rw-rw-rw-  1 codespace root 14550 Jan 30 13:02 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jan 30 12:43 images.2
7. Run the command **free -h** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.6Gi       130Mi       1.0Mi       6.0Gi       5.8Gi
Swap:            0B          0B          0B
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3242.841
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
9. Run the command **top** and type **q** to quit. ***(1 mark)*** processor : 1 vendor_id : AuthenticAMD cpu family : 25 model : 1 model name : AMD EPYC 7763 64-Core Processor stepping : 1 microcode : 0xffffffff cpu MHz : 2804.556 cache size : 512 KB physical id : 0 siblings : 2 core id : 0 cpu cores : 1 apicid : 1 initial apicid : 1 top - 15:54:33 up 3:08, 0 users, load average: 0.22, 0.20, 0.22 Tasks: 20 total, 1 running, 19 sleeping, 0 stopped, 0 zombie top - 15:55:19 up 3:09, 0 users, load average: 0.09, 0.17, 0.20 Tasks: 20 total, 1 running, 19 sleeping, 0 stopped, 0 zombie %Cpu(s): 4.4 us, 7.4 sy, 0.0 ni, 88.2 id, 0.0 wa, 0.0 hi, 0.0 si, 0.0 st MiB Mem : 7930.0 total, 152.2 free, 1716.2 used, 6061.5 buff/cache MiB Swap: 0.0 total, 0.0 free, 0.0 used. 5897.6 avail Mem

PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                      
2343 codespa+ 20 0 21.1g 343112 46464 S 4.0 4.2 0:35.88 node
2134 codespa+ 20 0 975860 116312 42496 S 0.3 1.4 0:06.28 node
1 codespa+ 20 0 1136 640 640 S 0.0 0.0 0:00.04 docker-init
8 codespa+ 20 0 7236 1792 1792 S 0.0 0.0 0:00.01 sleep
49 root 20 0 12192 3480 2560 S 0.0 0.0 0:00.00 sshd
781 root 20 0 1463336 84448 49664 S 0.0 1.0 0:00.19 dockerd
788 root 20 0 1282676 51312 30336 S 0.0 0.6 0:00.25 containerd
1514 codespa+ 20 0 2616 1408 1408 S 0.0 0.0 0:00.01 sh
1598 root 20 0 2616 1664 1664 S 0.0 0.0 0:00.00 sh
2103 codespa+ 20 0 2624 1664 1664 S 0.0 0.0 0:00.00 sh
2398 codespa+ 20 0 849444 56696 38528 S 0.0 0.7 0:00.27 node
2616 codespa+ 20 0 2616 1408 1408 S 0.0 0.0 0:00.00 sh
2692 root 20 0 2616 1408 1408 S 0.0 0.0 0:00.00 sh
3416 codespa+ 20 0 668096 62504 39040 S 0.0 0.8 0:01.41 node
3837 codespa+ 20 0 618320 71204 38400 S 0.0 0.9 0:01.80 node
10. Run the command **uname -a**. ***(1 mark)*** @2123467 ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-72cb68 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
11. What is the available free memory in the system. ***(1 mark)*** 177Mi
12. What is the available disk space mounted on /workspace. ***(1 mark)*** 5Gi.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** Linux codespaces-10daca 6.2.0-1018-azure #18-22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** ls' is the basic command that simply lists the name of the files and directories meanwhile 'ls -asl' is a customized option command that provides a more detailed listing, such as hidden files, sizes in blocks, and additional information about each file
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 2560 4K pages.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 2877.951MHz.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 14:32:54 up 49 min, 0 users, load average: 0.03, 0.16, 0.35.
## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** No, files in containers are not persistent by default.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** Yes

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** @2123467 ➜ /workspaces/OSProject/myroot (main) $ docker run --rm -it -v /workspaces/OSProject/myroot:/root debian bash -c 'echo "Hello, world!" > /root/myfile.txt'
@2123467 ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 root root 32 Jan 30 11:14 myfile.txt
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
@2123467 ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/OSProject/myroot
@2123467 ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 codespace codespace 32 Jan 30 11:14 myfile.txt

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** htdocs folder is owned by the root user and root group, with permissions set to 755 (rwxr-xr-x)
2. What port is the apache web server running. The Apache web server is running on port 80 within the container.
3. What port is open for http protocol on the host machine? The port open for the HTTP protocol on the host machine is 8080. This means that any HTTP requests sent to port 8080 on the host machine will be forwarded to port 80 within the container, where the Apache web server is listening.

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***31 January, 2024***
