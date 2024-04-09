# Linux Cheatsheet 

1. id - This is used to find out user and group names and numeric ID’s (UID or group ID) of the current user or any other user in the server.
Example: id -u root

2. cd - Change Directory: Navigate to a different directory.
Example:cd /home/user/documents

3. pwd - Print Working Directory: Display the current directory's full path. Example: pwd

4. mkdir - Make Directory: Create a new directory.
Example: mkdir new_folder

5. rm - Remove: Delete files or directories.
Example: rm file.txt

6. cp - Copy: Copy files or directories.
Example: cp file.txt /backup

7. mv - Move: Move files or directories.
Example: mv file.txt /new_location

8. touch - Create Empty File: Create a new empty file.
Example: touch new_file.txt

9. cat - Concatenate and Display: View the content of a file.
Example: cat file.txt

10. nano - Text Editor: Open a text file for editing.
Example: nano file.txt

11. grep - Search Text: Search for text patterns in files.
Example: grep "pattern" file.txt

12. find - Search Files and Directories: Search for files and directories. Example: find /path/to/search -name "file_name"

13. chmod - Change File Permissions: Modify file permissions.
Example: chmod 755 file.sh

14. chown - Change Ownership: Change the owner and group of a file or directory.
Example: chown user:group file.txt

15. ps - Process Status: Display running processes.
Example: ps aux

16. top - Monitor System Activity: Monitor system processes in real-time. Example: top

17. kill - Terminate Processes: Terminate a process using its ID.
Example: kill PID

18. wget - Download Files: Download files from the internet.
Example: wget https://example.com/file.zip

19. curl - Transfer Data with URLs: Transfer data to or from a server. Example: curl -O https://example.com/file.txt

20. tar - Archive and Extract: Create or extract compressed archive files. Example: tar -czvf archive.tar.gz folder

21. ssh - Secure Shell: Connect to a remote server securely.
Example: ssh user@remote_host

22. scp - Securely Copy Files: Copy files between local and remote systems using SSH.
Example: scp file.txt user@remote_host:/path

23. rsync - Remote Sync: Synchronize files and directories between systems.
Example: rsync -avz local_folder/ user@remote_host:remote_folder/

24. df - Disk Free Space: Display disk space usage.
Example: df -h

25. du - Disk Usage: Show the size of files and directories.
Example: du -sh /path/to/directory

26. ifconfig - Network Configuration: Display or configure network interfaces (deprecated, use ip).
Example: ifconfig

27. ip - IP Configuration: Manage IP addresses and network settings. Example: ip addr show

28. netstat - Network Statistics: Display network connections and statistics (deprecated, use ss).
Example: netstat -tuln

29. systemctl - System Control: Manage system services using systemd. Example: systemctl start service_name

30. journalctl - Systemd Journal: View system logs using systemd's journal.
Example: journalctl -u service_name


