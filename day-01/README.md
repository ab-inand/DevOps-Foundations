
# Day 1: Filesystem Navigation - My Linux Journey

Today, I learned the fundamental skill of navigating the Linux filesystem using the command line. This feels like learning how to walk in a new world!

## 📝 Key Concepts

* **Filesystem Tree**: The Linux filesystem is a hierarchical structure that starts from a single point called **root (`/`)**. All other directories and files branch out from there.
* **Path**: A "path" is the address of a file or directory. For example, `/home/myuser/Documents` is the path to the `Documents` directory.

## 💻 Core Commands Learned

| Command | Description | Example |
| :--- | :--- | :--- |
| `pwd` | **P**rint **W**orking **D**irectory (shows my current location). | `pwd` |
| `ls` | **L**i**s**t files and directories in the current location. | `ls -la` |
| `cd` | **C**hange **D**irectory (moves me to a different location). | `cd /etc` |

### Important `cd` Shortcuts

* `cd /` ➔ Go to the root directory.
* `cd ~` or just `cd` ➔ Go to my home directory.
* `cd ..` ➔ Go up one directory level (to the parent).

## 🚀 Today's Practical Task

I successfully completed the task of navigating to three different directories and confirming my location in each one.

**1. Navigated to `/etc`**

```bash
$ cd /etc
$ pwd
/etc
````

**2. Navigated to `/var/log`**

```bash
$ cd /var/log
$ pwd
/var/log
```

**3. Navigated to `/home`**

```bash
$ cd /home
$ pwd
/home
```

**4. Returned to my home directory**

```bash
$ cd ~
$ pwd
/home/myusername
```
