# OPEN-SOURCE-EX-1

## NAME: NITHIYANERANJAN S
## REGNO: 212223040146  
## DEPT: CSE

## AIM:
To create a local repository file for RHEL 9 using AppStream and BaseOS URLs and verify the repository setup using DNF commands.

## PROCEDURE:

### **STEP 1:**  
Navigate to the repository directory  
```bash
cd /etc/yum.repos.d/
```

### **STEP 2:**  
Create and open a repo file  
```bash
sudo vi classroom.repo
```

### **STEP 3:**  
Add the following repository configurations  
```ini
[AppStream]
name=AppStream Repository
baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/AppStream
enabled=1
gpgcheck=0

[BaseOS]
name=BaseOS Repository
baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/BaseOS
enabled=1
gpgcheck=0
```

### **STEP 4:**  
Clear the DNF cache  
```bash
dnf clean all
```

### **STEP 5:**  
Verify the repositories  
```bash
dnf repolist
```

## OUTPUT:
![Screenshot](https://github.com/user-attachments/assets/5b61bf74-0cdd-4109-b79e-abef310d6b70)

## RESULT:
The AppStream and BaseOS repositories were successfully configured, cleaned, and verified using DNF commands in the Red Hat Linux environment.
