# Why automate WordPress setup on Ubuntu?
## 1️⃣ Saves time ⏱️

Without automation:

Install Ubuntu

Install Apache

Install MySQL

Install PHP

Download WordPress

Configure files manually

This can take hours.

With automation:

Run one command

Everything installs automatically in minutes

## 2️⃣ No manual mistakes ❌

Manual setup can cause:

Missed steps

Wrong commands

Wrong permissions

Config errors

Automation:

Does the same steps every time

Reduces human errors

## 3️⃣ Same setup on every system 🔁

Automation ensures:

Same WordPress setup on all machines

Works the same on:

Laptop

Team member’s system

Test server

# WordPress Setup using Vagrant

This project automatically sets up a **WordPress website** on an **Ubuntu virtual machine** using **Vagrant**.

Everything (server, database, and WordPress) is installed **automatically** when you run one command.

---

## What this project does (in simple words)

When you start Vagrant:

- Creates an Ubuntu virtual machine
- Installs Apache (web server)
- Installs MySQL (database)
- Installs PHP
- Downloads and configures WordPress
- Creates a WordPress database and user
- Starts the website automatically

No manual setup is needed.

---

## Requirements

You need to have these installed on your system:

- VirtualBox
- Vagrant
- Internet connection

---

## How to run this project

1. Clone this repository
   ```bash
   git clone <your-repo-url>
