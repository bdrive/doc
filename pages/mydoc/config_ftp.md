---
title: FTP
keywords:
sidebar: netdrive_sidebar
permalink: config_ftp.html
toc: false
hide_sidebar: true
---

# CONNECT

Select FTP in STORAGE TYPE and then click CONNECT.

{% include inline_image.html file="ftp_1.jpg" max-width="200" %}

{% include inline_image.html file="ftp_2.jpg" max-width="200" %}

You will find above FTP window to type in connection information.

Type in ftp server address and port number correctly.

Check "**Use SSL/TLS**" for SSL/TLS use.

Check "**Use Active Mode**" for Active Mode.

Type in FTP User account and Password.

Check "**Anonymous**" for anonymous account.

Uncheck "**Save user and password**" if you do not want to save FTP User account and Password. In this case you need to type these information each time you connect to the drive.

# OPTIONS

{% include inline_image.html file="ftp_3.jpg" max-width="200" %}

- **Charset** : Set encoding information of file name.

  - **Autodetect** : Detect whether FTP server supports UTF-8 or not.
  - **Force UTF-8** : Force to use UTF-8 when transferring file name with FTP server.
  - **Local charset** : Use charset of local PC when transferring file name with FTP server.

- **Use server time for files/folders** : Use the time set of files/folders saved in the server instead of local PC timezone.

- Max sessions : Limit the number of sessions. (NetDrive uses multiple simultaneous sessions to enhance performance when transferring data.)

- Bandwidth : Control bandwidth settings.

{% include links.html %}
