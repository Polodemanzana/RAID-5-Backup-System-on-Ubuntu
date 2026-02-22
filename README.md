🖥️ RAID 5 + Backup System on Ubuntu

Project for the sis57.et domain – Educational Environment
This repository documents the full implementation of a RAID 5 storage system on Ubuntu Server, combined with an automated backup solution using NFS and cron.

The project simulates the infrastructure of a school, where administrative documents, teaching materials, student work, and shared folders must remain available and protected.

“In an educational environment, data availability and protection is essential…”

📌 Project Objectives

Deploy a fully functional RAID 5 array using 4 disks.

Configure a persistent mount point for the RAID.

Move system module folders into the RAID storage.

Prepare a Linux client as a backup destination.

Share storage using NFS.

Perform incremental backups using rsync.

Automate daily backups using cron jobs.

🛠️ Technologies Used

Technology	Purpose
Ubuntu Server	Main server with RAID 5
mdadm	RAID management
NFS	Network file sharing
rsync	Incremental backups
cron	Task automation
VirtualBox	Virtualized environment



📂 Directory Structure

/mnt/raid5
└── Moduls
    ├── BBDD
    ├── MARQUES
    ├── PROGRA
    ├── SSOO
    └── XARXES

/BackUp (NFS client)
└── Moduls
    ├── ...
    └── Moduls_YYYY-MM-DD

🎯 Results

Fully operational RAID 5 array

Persistent and reliable storage

Network-based backup system

Incremental and full backups with timestamps

Automated daily backup routines

Ideal environment for systems administration practice

📜 License

This project is free to use for educational purposes.
