# Linux Structures

Welcome to the Linux Structures course repository.

This repository contains:

- Course modules
- Practice exercises
- Scripts
- Lab materials
- Course resources

Throughout the semester, new materials will be added to this repository. Students should regularly update their local copy to receive the latest files.

---

# Prerequisites

Before using this repository, make sure Git is installed.

Check whether Git is installed:

```bash
git --version
```

If Git is installed, you will see output similar to:

```bash
git version 2.x.x
```

If you receive a "command not found" message, contact your instructor or install Git using your Linux distribution's package manager.

---

# First Time Setup

Create a directory to store GitHub repositories:

```bash
mkdir -p ~/GitHub
```

Move into the directory:

```bash
cd ~/GitHub
```

Clone the course repository:

```bash
git clone https://github.com/ethicalhackingnwtc/linux_structure.git
```

Move into the repository:

```bash
cd linux_structure
```

View the files:

```bash
ls
```

View all folders and files:

```bash
tree
```

---

# Accessing Course Materials

Open the repository directory:

```bash
cd ~/GitHub/linux_structure
```

Display the repository contents:

```bash
ls
```

Move into a module folder:

```bash
cd modules/module1
```

Display the contents of the folder:

```bash
ls
```

View a text file:

```bash
cat filename.txt
```

---

# Getting Updates

The instructor will add new files throughout the semester.

Before each class or lab, update your repository:

```bash
cd ~/GitHub/linux_structure
git pull
```

If updates are available, Git will download the newest version of the repository.

Example:

```bash
Updating 12ab34c..56de78f
Fast-forward
```

If the repository is already current, you may see:

```bash
Already up to date.
```

---

# Checking Repository Status

To see the current status of your repository:

```bash
git status
```

This command will show:

- Modified files
- New files
- Whether your repository is up to date

---

# Viewing Recent Changes

To view recent updates made by the instructor:

```bash
git log --oneline
```

Example:

```bash
a1b2c3d Added Module 2 materials
d4e5f6g Updated Module 1 instructions
```

---

# Running Scripts

Some scripts may need executable permissions before they can run.

Grant execute permissions:

```bash
chmod +x script.sh
```

Run the script:

```bash
./script.sh
```

Always review scripts before executing them.

---

# Troubleshooting

## Git Command Not Found

If you receive:

```bash
git: command not found
```

Git is not installed. Contact your instructor or install Git using your Linux distribution's package manager.

## Repository Not Found

Verify that:

- You typed the repository URL correctly.
- You have internet access.
- You have permission to access the repository.

## Permission Denied

Verify file permissions:

```bash
ls -l
```

Grant execute permissions if needed:

```bash
chmod +x filename.sh
```

---

# Important

Students should treat this repository as a source of course materials.

If you need to modify files for an assignment, copy them to another location before making changes.

Before every lab, run:

```bash
cd ~/GitHub/linux_structure
git pull
```

to ensure you have the latest course materials.
