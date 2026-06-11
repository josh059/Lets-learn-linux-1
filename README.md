# Let's Learn Linux – Episode 1
🛡️ Let's Learn Linux — Episode 1 A DevSecOps Field Assignment | CypherCore Systems Bootcamp

## DevSecOps Bootcamp Assignment

This repository contains my solutions, practical exercises, screenshots, and documentation for **"Let's Learn Linux – Episode 1"**, a hands-on Linux fundamentals assignment from the **ParoCyber DevSecOps Bootcamp** facilitated by **Samuel Nartey**.

The lab simulates real-world DevSecOps tasks performed by a junior engineer, covering Linux command-line navigation, filesystem management, file operations, links and inodes, log handling, data streams, redirection, and automation concepts.

---

## Assignment Objectives

Through this lab, I learned how to:

* Navigate the Linux filesystem
* Identify system and kernel information
* Create and manage directory structures
* Create, read, update, and archive files
* Work with hidden files and permissions
* Understand the Filesystem Hierarchy Standard (FHS)
* Use heredocs for automation and scripting
* Create and manage hard links and symbolic links
* Understand inodes and link counts
* Redirect stdout and stderr streams
* Generate reports from command-line operations

---

## Project Structure

```text
lets-learn-linux-1/
├── answers.md
├── screenshots/
│   ├── screenshots1.png
│   ├── screenshots2.png
│   ├── screenshots3.png
│   ├── screenshots4_tree.png
│   ├── screenshots.png
│   ├── ...
│   └── screenshots...22.png
└── README.md
```

---

## Skills Demonstrated

### Linux Fundamentals

* pwd
* whoami
* uname
* ls
* tree

### File and Directory Management

* mkdir
* touch
* cp
* mv
* rm
* rmdir

### File Reading and Analysis

* cat
* tac
* less
* more
* tail

### Links and Inodes

* ln
* ln -s
* ls -li

### Data Streams and Redirection

* stdin (0)
* stdout (1)
* stderr (2)
* >
* > >
* 2>
* 2>&1

### Automation Techniques

* Heredocs
* Variable expansion
* Bash brace expansion

---

## Key Concepts Learned

### Filesystem Hierarchy Standard (FHS)

Linux systems follow a standardized directory structure that helps administrators, developers, and automation tools consistently locate files, logs, binaries, and configuration data.

### Inodes

An inode stores metadata about a file, including permissions, ownership, timestamps, and references to data blocks. Understanding inodes helped clarify how hard links work and why deleting a filename does not always remove the underlying data.

### Hard Links vs Symbolic Links

| Feature                       | Hard Link | Symbolic Link |
| ----------------------------- | --------- | ------------- |
| Shares inode                  | Yes       | No            |
| Survives deletion of original | Yes       | No            |
| Cross-filesystem support      | No        | Yes           |
| Can link directories          | No        | Yes           |

### Data Streams

Linux processes use three standard streams:

| Stream | Number | Purpose         |
| ------ | ------ | --------------- |
| stdin  | 0      | Input           |
| stdout | 1      | Standard output |
| stderr | 2      | Error output    |

Understanding stream redirection is essential for scripting, automation, logging, and troubleshooting.

---

## Reflection

This assignment helped me move beyond simply memorizing Linux commands and begin understanding how Linux works internally.

The most valuable lessons came from:

* Working with inodes and hard links
* Understanding symbolic links and dangling references
* Learning how stdout and stderr can be managed separately
* Using heredocs to automate file creation

These concepts are fundamental to DevOps, DevSecOps, Cloud Engineering, System Administration, and Cybersecurity.

---

## Repository Contents

* `answers.md` — Detailed answers for all questions (Q1–Q21)
* `screenshots/` — Evidence of command execution and outputs
* `README.md` — Project overview and learning summary

---

## Technologies Used

* Linux
* Bash Shell
* Git
* GitHub

---

## Author

**Joshua Osafo**

Cybersecurity & DevSecOps Enthusiast

---

## Acknowledgements

This assignment is part of the DevSecOps training organised by **ParoCyber** and facilitated by **Samuel Nartey**.

Special thanks to the ParoCyber team for providing practical, real-world Linux and DevSecOps learning experiences.

---

## License

This repository is for educational purposes as part of the ParoCyber DevSecOps Bootcamp.
