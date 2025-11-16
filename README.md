# OPEN-SOURCE-EX-1
Create a repository file  http://classroom.example.com/content/rhel9.0/x86_64/dvd/AppStream http://classroom.example.com/content/rhel9.0/x86_64/dvd/BaseOS
# Name : NITHIYANERANJAN S
# Reg No : 212223040136
# Dept : CSE
# Steps involved:
## Step 1 : cd /etc/yum.repos.d/
## Step 2 : sudo vi classroom.repo
## Step 3 : 
### [AppStream]
### name=AppStream Repository
### baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/AppStream
### enabled=1
### gpgcheck=0

### [BaseOS]
### name=BaseOS Repository
### baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/BaseOS
### enabled=1
### gpgcheck=0
## Step 4 : dnf clean all
## Step 5 :dnf repolist

# Output:
<img width="1256" height="752" alt="Screenshot 2025-11-09 153717" src="https://github.com/user-attachments/assets/5b61bf74-0cdd-4109-b79e-abef310d6b70" />

# Result :
## Thus the steps worked in Red hat lab (Terminal) 
