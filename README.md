# 🐉 Kali Linux Commands 

Kali Linux commands follow this structure:
```
command [options] [arguments]
```

Example:
```
ls -la /home
```

```ls``` → command

```-la``` → options/flags

```/home``` → target argument

### 🖥️ 1️⃣ Navigation Commands (Detailed)
🔹``` pwd```

Prints working directory — shows your current location in filesystem.
```
pwd
```

Useful when scripting or navigating complex paths.

🔹 ```ls```

Lists directory contents.

Common options:

### Option	        Meaning

```-l```        -    Long format

```-a```	      -   Hidden files

```-h```	      -    Human readable size

```-R```	      -   Recursive

Example:
```
ls -lah
```
🔹 ```cd```

Changes directory.

Examples:
```
cd /etc
cd ~
cd ..
cd -
```

```~``` → home directory

```..``` → parent

```-``` → previous directory

📁 2️⃣ File Management (Detailed)
🔹 ```mkdir```

Creates directories.
```
mkdir project
mkdir -p a/b/c
```

```-p``` → create nested paths

🔹 ```rm```

Deletes files/directories.
```
rm file.txt
rm -r folder
rm -rf folder
```

```-r``` recursive

```-f``` force

⚠️ Dangerous — irreversible.

🔹 ```cp```

Copies files.
```
cp file backup/
cp -r dir1 dir2
```
🔹 ```mv```

Moves or renames.
```
mv old new
mv file dir/
```
🔹 ```cat```

Displays file content.
```
cat file.txt
```

Combine files:
```
cat a b > c
```
🔹 ```nano```

Terminal text editor.
```
nano file.txt
```

Basic keys:

CTRL+O → save

CTRL+X → exit

🔐 3️⃣ Permissions & Users
🔹 ```chmod```

Changes file permissions.

Numeric model:

### Value	    |       Permission

7	            |         rwx        |

6             | 	      rw         |

5	            |         r-x        |

Example:
```
chmod 755 script.sh
```
🔹 ```chown```

Changes ownership.
```
chown user:file file.txt
```
🔹 ```sudo```

Runs command with elevated privilege.
```
sudo apt update
```

Essential in Kali admin tasks.

📦 4️⃣ Package Management
🔹 ```apt update```

Refresh repository list.

🔹 ```apt upgrade```

Upgrade installed packages.

🔹 ```apt install```

Install software.
```
sudo apt install toolname
```
🌐 5️⃣ Networking Commands
🔹 ```ip a```

Shows interfaces and IPs.

🔹 ```ping```

Tests connectivity.
```
ping google.com
```

Shows latency and packet loss.

🔹```netstat```

Shows active connections.
```
netstat -tuln
```

```t``` TCP

```u``` UDP

```l``` Listening

```n``` Numeric

🔹 ```ss```

Modern alternative to netstat.

🔎 6️⃣ Process Monitoring
🔹 ```ps```

Process snapshot.
```
ps aux
```
🔹 ```top``` / ```htop```

Live CPU/memory usage.

🔹 ```kill```

Terminates processes.
```
kill PID
```
📊 7️⃣ System Information
🔹 ```df```

Disk usage.
```
df -h
```
🔹 ```free```

Memory stats.
```
free -h
```
🔹 ```uname```

Kernel/system info.
```
uname -a
```
