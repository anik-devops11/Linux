# 📖Linux-Basic

<img align = "center" alt = "Linux" hight="400" width="400" src = "https://github.com/anik-devops11/Linux/blob/main/images/Linux%20Logo.png"> </br>


A foundational guide to understanding what Linux is, why it is widely used, and essential theoretical concepts that are important for Linux users.

## 📝 Table of Contents

1. [Introduction to Linux](#introduction-to-linux)
   - [What is Linux Operating System?](#what-is-linux-operating-system)
   - [History of Linux](#history-of-linux)
   - [Linux vs Other Operating Systems](#linux-vs-other-operating-systems)
   
2. [Why Use Linux?](#why-use-linux)
   - [Advantages of Using Linux](#advantages-of-using-linux)
   - [Linux in DevOps and Cloud](#Linux-in-DevOps-and-Cloud)

3. [Linux Distributions (Distros)](#linux-distributions-distros)
   - [What is a Distribution?](#what-is-a-distribution)
   - [Popular Linux Distros](#popular-linux-distros)
   - [Choosing the Right Distro](#choosing-the-right-distro)

4. [Linux File System Basics](#Linux-File-System-Basics)
   - [Linux Directory Structure](#Linux-Directory-Structure)
   - [Understanding File Permissions](#Understanding-File-Permissions)
   - [File Types in Linux](#File-Types-in-Linux)
---

## 🐧Introduction to Linux🐧

### What is Linux Operating System?

The Linux Operating System is a Unix-like operating system built upon the Linux Kernel, which serves as its core component. The Linux Kernel is responsible for managing interactions between the computer's hardware and software resources, ensuring efficient and smooth operation. However, the Kernel alone does not constitute a complete operating system. To form a fully functional system, it is integrated with various software packages and utilities, collectively known as Linux distributions. These distributions provide users with a secure and effective environment for running applications and performing tasks. Each distribution is designed to meet specific user needs and preferences.

### History of Linux
Linux was created by Linus Torvalds in 1991 while he was a student. He aimed to develop a free and open-source version of the MINIX operating system. Over time, it has grown with contributions from developers all around the world.

### Linux vs Other Operating Systems
Linux offers unique advantages over proprietary operating systems like Windows and macOS. Its open-source nature means it can be modified freely, and it is less prone to malware.

## 👀Why Use Linux?

Because it is free, open-source, and extremely flexible, Linux is widely utilized. For servers and developers, it is the ideal option because it offers strong security, stability, and performance. Generally interoperable hardware, a broad software library, and a vibrant community that offers support and regular updates are the many benefits of Linux. Due to its adaptability, users can customize the operating system according to their own needs, whether they become for personal or large enterprise use.

### Advantages of Using Linux

- **Open Source**: Linux is free to use, modify, and distribute.
- **Customizability**: Users have full control over the environment.
- **Security and Stability**: Linux is known for fewer vulnerabilities compared to other operating systems.
- **Community Support**: Linux has a large, active community that offers support through forums, online resources, and documentation. Users can often find help and solutions quickly.
- **Cost-Effective**:Linux is free to use, reducing software licensing costs. This makes it an attractive option for businesses and individuals alike.

### Linux in DevOps and Cloud

Linux is the preferred choice for servers, cloud computing, and DevOps tools like Docker and Kubernetes due to its stability, security, and efficiency. Its open-source nature allows for customization and cost savings, while its performance and resource management capabilities make it ideal for high-demand environments. Linux natively supports containerization, which is essential for tools like Docker and Kubernetes, providing a lightweight and consistent environment for deploying applications. With strong community support and integration with cloud platforms, Linux is a reliable and scalable solution for modern IT infrastructure.

## 🔎 Linux Distributions (Distros)

### What is a Distribution?
A Linux distribution is an operating system composed of a collection of software built around the Linux kernel. It includes the kernel itself, along with supporting libraries and applications. Users can obtain a Linux-based operating system by downloading one of the many available distributions, which are designed for various types of devices, including embedded systems and personal computers. Currently, there are over **600 Linux distributions available**, each tailored to meet different user needs and preferences.

### Popular Linux Distros

- **Ubuntu**: A user-friendly distribution that is great for beginners and offers extensive community support.

- **Fedora**: A cutting-edge distribution that provides the latest software and technologies for users and developers.

- **Debian**: Renowned for its stability and reliability, often used as a base for servers and critical applications.

- **MX Linux**: A midweight distribution that combines a simple and efficient desktop with a user-friendly interface.

- **Manjaro**: A user-friendly distribution based on Arch Linux, offering a rolling release model and a wide selection of software.

- **Linux Mint**: A beginner-friendly distribution based on Ubuntu, known for its simplicity and ease of use, particularly for new users.

- **Elementary OS**: A visually appealing distribution that emphasizes a clean, user-friendly interface and simplicity.

- **Solus**: A modern and independent distribution designed for home computing, offering an easy-to-use desktop environment.

- **openSUSE**: A versatile distribution known for its powerful configuration tools and strong support for developers and system administrators.

- **Deepin**: A visually stunning distribution that focuses on an elegant user experience, making it suitable for everyday computing.

## Linux File System Basics

The Linux file system is structured like a tree, starting from the root directory `/`, which serves as the base for everything else. In Linux, all items—such as files, directories, and even hardware devices—are represented as files, making interactions with the system consistent and straightforward. Permissions are set to control who can read, write, or execute a file, and are applied to the file owner, a group, and others. Paths are used to navigate the system: an **absolute path** starts from the root (e.g., `/home/user/documents/report.txt`), while a **relative path** starts from your current directory (e.g., `./report.txt`). To access external devices like USB drives, they are "mounted" into the file system, usually in directories like `/media` or `/mnt`. This design makes Linux well-organized, efficient, and secure for both users and the system.

### Linux Directory Structure

The Linux directory structure follows a hierarchical, tree-like structure that starts from the root directory, represented by `/` . Each directory under the root has a specific purpose, allowing users and system processes to easily locate files and resources. Here is an overview of the most common directories.
<br>

![logo](https://github.com/anik-devops11/Linux/blob/main/images/Linux%20Directory%20Structure.png) <br>

# Linux Directory Structure

| Directory    |    Description    |
|--------------|:---------------------------------------------------------------------------------------------|
| `/`          | The root directory, which is the base of the entire Linux file system.                       |
| `/dev`       | Contains device files representing hardware components like hard drives, printers, etc.      |
| `/usr`       | Stores user system resources, including:                                                     |
|              | - **`/usr/bin`**: Executable files available for all users.                                  |
|              | - **`/usr/local`**: User-specific software or scripts.                                       |
|              | - **`/usr/man`**: Manual (help) pages for commands.                                          |
|              | - **`/usr/share`**: Shared data like icons or documentation.                                 |
|              | - **`/usr/lib`**: Libraries needed by programs.                                              |
| `/bin`       | Contains essential user commands for booting and basic system operations (e.g., `ls`, `cp`).|
| `/lib`       | Stores essential shared libraries for system commands and programs in `/bin` and `/sbin`.   |
| `/home`      | Contains user home directories (e.g., `/home/user1`, `/home/user2`).                         |
| `/tmp`       | Temporary files generated by applications or during installations.                          |
| `/var`       | Stores files that grow in size, such as logs and caches:                                     |
|              | - **`/var/log`**: System and application log files.                                          |
|              | - **`/var/lock`**: Lock files for resources used by processes.                               |
|              | - **`/var/temp`**: Temporary files used by running services.                                 |
| `/sbin`      | Contains essential system binaries for system administration (e.g., `reboot`, `ifconfig`).  |


### Understanding File Permissions

### File Types in Linux