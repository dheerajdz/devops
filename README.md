# Week 1 – DevOps Fundamentals

## Linux Commands
### File & Directory Commands

- `ls` – Lists files and directories in the current directory
- `pwd` – Displays the current working directory
- `cd` – Changes the current directory
- `ls -l` – Lists files with detailed information including permissions
- `touch` – Creates an empty file
- `mkdir` – Creates a new directory
- `cp` – Copies files or directories
- `mv` – Moves or renames files or directories
- `rm` – Deletes files or directories

### Permissions & Ownership

- `chmod` – Modifies file or directory permissions for users, groups, and others  
- `chown` – Changes file or directory ownership, including user and group

### Privilege Management

- `sudo` – Allows a permitted user to execute commands with elevated (root) privileges

### User & Group Management

- `useradd` – Creates a new user account on the system  
- `groupadd` – Creates a new group  
- `groupdel` – Deletes an existing group

### Processes & Services
- `ps` – Lists running processes
- `top` – Displays real-time system processes
- `htop` – Interactive process viewer
- `systemctl` – Controls system services (start, stop, enable)


## Git Workflow

1. **Initialize a repository**  
   - `git init` – Creates a new local Git repository

2. **Check repository status**  
   - `git status` – Shows changes in the working directory and staging area

3. **Track changes**  
   - `git add <file>` – Adds file(s) to the staging area  
   - `git commit -m "message"` – Commits staged changes with a descriptive message

4. **Branching and switching**  
   - `git branch <branch>` – Creates a new branch  
   - `git checkout <branch>` – Switches to the specified branch

5. **Merging changes**  
   - `git merge <branch>` – Merges another branch into the current branch

6. **Remote repositories (GitHub)**  
   - `git push` – Pushes local commits to a remote repository  
   - `git pull` – Pulls the latest changes from a remote repository  
   - `git clone <url>` – Clones a remote repository to the local machine


### Networking & Utilities
- `ping` – Tests network connectivity to a host  
- `curl` – Transfers data to or from a server, often used for API requests  
- `wget` – Downloads files from the web  
- `netstat` – Shows active network connections and listening ports  
- `ss` – Displays detailed socket statistics  
- `df` – Shows disk space usage for mounted filesystems  
- `du` – Shows the size of directories and files  
- `free` – Displays memory usage and available system memory  
- `tail` – Views the end of a file, often used for logs  
- `less` – Views file content one page at a time, with scrollable navigation  
- `grep` – Searches for patterns in text or files

## Week 2 – Cloud & Containers Foundations

### Day 8 – Cloud Computing Fundamentals

**Cloud Computing:**  
Cloud computing provides on-demand access to computing resources (servers, storage, networking, applications) over the internet, allowing applications to run continuously without relying on local hardware.

**Cloud Service Models:**
- **IaaS (Infrastructure as a Service)** – Provides virtualized computing resources like virtual machines, storage, and networking.  
- **PaaS (Platform as a Service)** – Provides a platform with runtime, libraries, and tools to develop, test, and deploy applications without managing infrastructure.  
- **SaaS (Software as a Service)** – Provides ready-to-use software applications over the internet without managing infrastructure or platforms.

**Regions & Availability Zones:**
- **Region:** A geographical area containing multiple data centers.  
- **Availability Zone (AZ):** A physically separate data center within a region for high availability and fault tolerance.

**Shared Responsibility Model:**
- **Cloud Provider:** Responsible for the security and operation of the cloud infrastructure itself.  
- **User:** Responsible for securing and managing their applications, data, and access controls within the cloud.

