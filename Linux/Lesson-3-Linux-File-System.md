# Lesson 3 - Linux File System

## Objective

Understand how Linux organizes files and directories.

---

## What is a File System?
The method an operating system uses to organize, store, name and retrieve files.

---

## Root Directory
Linux doesn't use drive letters. Instead, everything starts from one place. 
The symbol '/ ' is called: The Root Directory. Think of it as the "mother" of every folder.
Everything in Linux begins here.



---

## Important Directories

### /home
This is where users keep their personal files.

### /root
This one is special. Notice: /root,
This is not the same as: /. Many beginners confuse these.
/ means: The root directory.
/root means: The home directory of the root user (the administrator account).

### /etc
One of the most important directories.
Contains: Configuration files.
Think of it as the computer's settings cabinet.
Examples:
user accounts,
network configuration,
hostname,
system settings.

As a penetration tester or defender, one often inspects configuration files here.

### /bin
Short for: Binary
Contains essential programs.
Examples include commands such as:
ls
cp
mv
cat

Without these basic tools, using the system would be difficult.

### /var
Stands for: Variable.
Contains data that changes frequently.
Examples:
log files,
print queues,
caches.

If you're investigating what happened on a server, /var/log is often one of the first places to examine.

### /tmp
Temporary files.
Programs store temporary data here.
These files may be deleted automatically.

### /boot
Contains files needed to start Linux.
Remember Lesson 1?
This directory contains important boot-related files used during startup.

### /dev
One of the coolest directories.
It represents devices through special files.
Examples include storage devices and terminals.
This is part of what people mean when they say: "Everything is a file."

### /usr
Despite the name, this is not primarily for user home directories.
It contains many applications, libraries, documentation, and shared resources used by the system.

---

## What I Learned

Imagine you're performing an authorized assessment on a Linux server. You want to know:

Where are the logs?
→ /var/log

Where are configuration files?
→ /etc

Where are users' personal files?
→ /home

Where are boot files?
→ /boot

Understanding the file system helps you investigate, troubleshoot, and administer Linux systems effectively.

---


