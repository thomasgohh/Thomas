# Thomas


**Lab 1a-1 – Virtualisation and Linux Setup
**
Learning Points

SHA256 verification: Learned how to verify the integrity of an Ubuntu ISO file using a SHA256 checksum. A matching checksum helps confirm that the downloaded file has not been corrupted or unexpectedly modified.

Hardware virtualisation: Learned that virtualisation needs to be enabled in the BIOS/UEFI so that software such as VirtualBox can use hardware-assisted virtualisation.

Virtual machine configuration: Learned how to allocate CPU, RAM and storage resources to a virtual machine.

Virtualisation benefits: Understood how multiple operating systems can run on one physical computer without requiring separate hardware.

Reflection

This lab helped me understand how virtualisation can be used to create a separate Linux environment on a computer. I learned that checking the ISO file before installation is important because it helps identify possible file corruption. I also understood that allocating the correct amount of CPU and RAM is important because the virtual machine shares resources with the host computer.

One thing I learned is that virtualisation is useful for testing and learning because it allows different operating systems to run in an isolated environment. This is also useful in cybersecurity, where different systems can be set up for testing and practical exercises.

**Lab 1a-2 – Ubuntu Desktop and Command Line Familiarisation
**
Learning Points

Ubuntu GUI: Became familiar with the Ubuntu desktop, Firefox, LibreOffice and file manager.

Linux terminal: Learned how to use the command line to manage files and perform system operations.

Process monitoring: Used ps -e and top to view running processes and monitor system resource usage.

File management: Used commands such as ls, ls -la, touch, cp and mv to create, list, copy and move files.

File viewing and editing: Learned the differences between cat, less, nano and graphical text editors.

Permissions: Gained an introduction to Linux file permissions and how access can be controlled.

Networking: Learned basic networking and DNS-related commands and how to check internet connectivity.

Software installation: Explored different ways to install software in Ubuntu.

GCC compilation: Gained exposure to compiling programs using GCC.

Reflection

This lab helped me become more familiar with Ubuntu and the Linux command line. At first, using the terminal required more attention because commands had to be entered correctly. However, I learned that the command line provides a faster way to perform certain tasks compared with using the graphical interface.

I also learned that commands such as cp and mv have different purposes. The cp command creates a copy of a file, while mv moves or renames it. Learning how to view and edit files using cat, less and nano was also useful, especially when working in a terminal environment.

Overall, I gained more confidence in using Linux commands and understood why command-line knowledge is important when managing servers.

**Lab 1a-3 – Linux Services, Permissions and File Management
**
Learning Points

Service management: Learned how Linux services can be managed using systemctl, including checking service status, starting, stopping and disabling services.

Network ports: Understood that services listen on specific ports, such as HTTP on port 80 and HTTPS on port 443.

Service security: Learned that unused services should be disabled because unnecessary open ports can increase the system's attack surface.

File permissions: Learned how Linux permissions control read, write and execute access for users, groups and others.

Permission commands: Gained experience with commands such as chmod, chown and user or group management.

Access control: Understood the importance of assigning only the permissions required instead of giving unrestricted access.

File searching: Learned how to search and navigate the Linux file system using commands such as find.

Bash scripting and automation: Learned how scripts can automate repeated Linux administration tasks.

Reflection

This lab helped me understand that managing a Linux system involves more than just entering commands. It is also important to control which services are running and who has permission to access files.

I learned that leaving unnecessary services running can expose additional ports and increase security risks. File permissions are also important because incorrect permissions may allow unauthorised users to read, modify or execute files.

I also gained an understanding of how automation can reduce repetitive manual work. For example, Bash scripts can be used to perform regular system administration tasks. This is useful because administrators need to manage systems efficiently while maintaining security.


**Lab 2a-1 – Total Cost of Ownership (TCO) Analysis
**
Learning Points

Total Cost of Ownership: Learned that TCO considers the overall cost of owning and operating equipment over a specific period.

Fixed costs: Identified the initial printer purchase price as a fixed cost.

Variable costs: Considered ink or toner cartridges, paper, electricity and maintenance as operating costs.

Excel formulas: Used Excel to organise cost information and calculate the estimated five-year costs.




Cost comparison: Compared an inkjet printer with a laser printer to understand the differences in initial and running costs.

Printing volume: Learned that the number of pages printed affects consumable costs and the final TCO.

Break-even analysis: Understood that the break-even point occurs when the total costs of two options become equal


**Lab 2b-1 – Cloud Web Server Deployment with Amazon EC2
**
Learning Points

Amazon EC2: Learned how to launch and manage a virtual server using Amazon Elastic Compute Cloud (EC2).

Security groups: Learned how to configure inbound security group rules to allow SSH traffic on port 22 and HTTP traffic on port 80.

SSH connection: Learned how to connect remotely to an Ubuntu EC2 instance using SSH.

Apache installation: Used Linux commands to update the package list and install the Apache web server.

Web server testing: Learned how to test the Apache web server through a web browser using the EC2 instance's public IP address.

HTML customisation: Learned how to edit the default Apache HTML page using the nano text editor.

File downloading: Used the wget command to download an external PDF file from the internet.

Web directory: Learned how to copy files into /var/www/html/ so they can be accessed through the Apache web server.

File hosting: Learned how to create a hyperlink in the HTML page to allow users to access the uploaded PDF file.

Cloud cost monitoring: Gained exposure to AWS Billing and Cost Management and the importance of monitoring cloud resource usage.

Reflection

This lab helped me understand how cloud computing can be used to deploy and host a web server. I learned how to launch an EC2 instance on AWS, configure its security group and connect to the Ubuntu server remotely using SSH.

I also gained practical experience installing Apache and modifying its default webpage. By accessing the website through the public IP address, I could see how a web server makes content available to users through a browser.

Another useful part of the lab was learning how to download and host an external PDF file. Using wget, copying the file into the Apache web directory and adding a hyperlink helped me understand how websites can provide access to different types of content.

I also learned that security and cost management are important when using cloud services. Security group rules need to be configured carefully so that only the required network traffic is allowed. Cloud resources should also be monitored to avoid unnecessary charges.

Overall, this lab gave me a better understanding of cloud infrastructure and how a basic web server can be deployed and managed using AWS. It also helped me connect Linux administration skills from the earlier labs with a practical cloud computing environment.


**Lab 2b-1 – Introduction to Bash Scripting & System Automation
**

Through this lab, I developed a better understanding of Linux command-line operations and Bash scripting using Ubuntu. The practical exercises introduced me to filesystem management, script creation, loops, conditional statements and basic system monitoring.

One of the key learning experiences was working with Linux filesystem commands such as `mkdir`, `cat`, `cp`, `mv` and `rm`. These commands allowed me to create directories, manage files and perform basic file operations directly through the terminal.

I also gained practical experience creating and executing Bash scripts using the `#!/bin/bash` shebang. By applying permissions with `chmod`, I learned how to make scripts executable and run them directly from the terminal.

Another important area was implementing loops and conditional statements. I used `for` loops to perform repeated operations and `if`, `elif` and `else` statements to evaluate user input. The use of `read` also helped me understand how to make scripts interactive and handle different input conditions.

For system monitoring, I explored commands such as `top`, `free -h` and `df -h` to observe CPU activity, memory utilisation and disk space. I combined these commands into a monitoring script and used `sleep` to control the intervals between monitoring cycles. This demonstrated how Bash scripting can automate repetitive system administration tasks.

Throughout the lab, I improved my troubleshooting skills by identifying command syntax errors, understanding file permissions and testing script behaviour. I also learned the importance of validating user input to prevent unexpected script execution.

Overall, this project strengthened my foundational knowledge of Linux and Bash scripting. It demonstrated how simple scripts can improve efficiency by automating everyday administrative tasks. These skills provide a useful foundation for more advanced Linux administration, cybersecurity and system automation activities.


**Lab 3b-1 – Bash Backup Scripting, Cron Jobs & Cloud Export
**
## Reflection

Through this lab, I gained practical experience in using Bash scripting to automate file backup operations in Ubuntu. I learned how to use variables, arithmetic operations, loops and commands to create a script that recursively copies files and directories from the Documents folder into a backup directory.

One of the key learning points was understanding how to automate repetitive tasks using Cron. By configuring the system-wide crontab, I was able to schedule the backup script to execute automatically every hour. I also learned how to verify scheduled execution by checking system logs and comparing backup archive timestamps.

Another important part of this lab was learning how to transfer backup files to a remote AWS Ubuntu server using SCP and SSH key-based authentication. I successfully configured the SSH private key, established a remote connection and transferred the ZIP backup archive to the cloud server. This helped me understand how local backup automation can be extended to remote cloud storage.

During the exercise, I encountered some challenges with command syntax, file permissions, SSH key locations and verifying Cron execution. Troubleshooting these issues helped me improve my understanding of Linux commands and system administration.

Overall, this lab demonstrated how Bash scripting, Cron scheduling and cloud transfer can work together to create an automated backup workflow. I also learned that security is important when handling backup files and SSH credentials. In a production environment, I would improve the solution by using more restrictive file permissions, adding error handling, maintaining multiple backup versions and implementing backup retention policies.
