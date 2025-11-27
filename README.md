# 🐧 Linux Basic Command

Learning Linux commands.  
These commands work on **Kali Linux, Ubuntu, Debian, Fedora, and other Linux distros**.  
Use this guide as a quick reference while practicing. 🚀

---

## 1️⃣ Navigation (Move around the system)
```bash
pwd                # Show current directory (Print Working Directory)
ls                 # List files/folders in current directory
ls -la             # Show hidden files with details
cd Desktop         # Move into Desktop folder
cd ..              # Go one step back
```

---

## 2️⃣ Directory Handling (Folders)
```bash
mkdir test         # Create a new folder named test
cd test            # Go inside the folder
```

---

## 3️⃣ File Handling (Create, Read, Write, Append, Multiple files)
```bash
touch file1.txt    # Create an empty file
ls                 # Verify file creation

# 🟢 cat use cases
cat file1.txt      # Read file content

cat > file1.txt    # Create + Write content
Hello Kali Linux
CTRL + D           # Save & exit

cat file1.txt      # Read file again

cat >> file1.txt   # Append content in existing file
This is my first command practice
CTRL + D           # Save & exit

cat file1.txt      # Read updated file

cat file1.txt file2.txt  # Read multiple files at once
```

---

## 4️⃣ File Editing (Interactive Editor)
```bash
nano file1.txt     # Open file in nano editor (write & edit)
```

---

## 5️⃣ Delete Files & Folders
```bash
rm file1.txt       # Delete a file
rm -r test         # Delete folder + its contents
```

---

## 6️⃣ User & System Info
```bash
whoami             # Show current logged in user
hostname           # Show system hostname
uname -a           # Kernel + OS details
```

---

## 7️⃣ Networking Basics
```bash
ifconfig           # Show network interfaces (needs net-tools)
ip addr            # Alternative to ifconfig (modern Linux)
ping google.com    # Test connectivity
curl ifconfig.me   # Show your public IP
```

---

## 8️⃣ Package Management (Install/Update Tools)
```bash
sudo apt update            # Update repositories
sudo apt upgrade           # Upgrade all packages
sudo apt install nmap      # Install a tool (e.g., Nmap)
nmap -v google.com         # Simple port scan
```

---

## 9️⃣ Process Management (Monitor & Kill)
```bash
ps aux              # Show running processes
top                 # Live process monitoring
kill -9 <PID>       # Kill a process by its ID
```

---

## 🔟 Permissions & Ownership
```bash
ls -l               # Show file permissions
chmod 755 file1.txt # Change file permissions
chown user:user file1.txt  # Change file ownership
```

---

## 1️⃣1️⃣ Search & History
```bash
history             # Show previously used commands
grep "keyword" file1.txt   # Search for a word inside a file
man ls              # Manual/help for ls command
```

---

## ✅ Why These Commands?
These are **must-know Linux commands** for anyone starting in **Cyber Security & Ethical Hacking**.  
Without Linux basics, you cannot effectively use tools like **Nmap, Hydra, Metasploit, Aircrack-ng**, etc.  

---

Happy Hacking! 💻🔐
