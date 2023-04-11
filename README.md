# scheduler-service

WholesaleBackup clients use a scheduling service to kick off automated backups.  Like all WholesaleBackup executables, the scheduling service executable is branded, and in its case, its name ends in a _scheduler.exe and it will be shown in the Microsoft Windows Services Control Panel (Services.msc) with your brand name.

## Backup client scheduler service command line options

Run the scheduling service as ```<your-brand>```_scheduler.exe from the commandline.

```
-e  to end (stop) the service
-i  to install the service, it will run as 'NT AUTHORITY\LocalService'
-i  <user> <pass> to install the service with a specific username/password
-s  to start the service
-u  to remove (uninstall) the service
-x  to reinstall the service, it will run as 'NT AUTHORITY\LocalService'
-x  <user> <pass> to reinstall the service with a specific username/password
```

Of course its much easier to do this from Microsoft Windows Services Control Panel application called Services.MSC.

Screenshot of the WholesaleBackup client scheduler service active in the GUI.
![Screenshot of the WholesaleBackup client scheduler service active in the GUI.](https://support.wholesalebackup.com/hc/article_attachments/360025823153/Screen_Shot_2019-02-07_at_1.26.32_PM.png)


Screenshot of the WholesaleBackup client scheduler service control panel from Services.MSC
![Screenshot of the WholesaleBackup client scheduler service control panel from Services.MSC](https://support.wholesalebackup.com/hc/article_attachments/360024906054/Screen_Shot_2019-02-07_at_1.52.44_PM.png)

WholesaleBackup [Online Backup Software](https://wholesalebackup.com/backup-software/) allows you to configure your backup service using [self-hosted Windows Server](https://wholesalebackup.com/backup-software/wholesalebackup-server/) or using cloud-based object storage from [S3](https://wholesalebackup.com/backup-software/amazon-s3-cloud-backup-client/), [Wasabi](https://wholesalebackup.com/backup-software/wasabi-backup-client/), [Backblaze](https://wholesalebackup.com/backup-software/backblaze-backup-client/), and [GCP](https://wholesalebackup.com/backup-software/google-cloud-backup-client/). 

The backup client can be deployed on [Windows](https://wholesalebackup.com/backup-software/windows-backup-client/) and [macOS](https://wholesalebackup.com/backup-software/wholesalebackup-macos-backup-client/) systems.

#### Need help? 
Connect with [wholesalebackup.com](https://wholesalebackup.com/) if you have any questions.
