# Deployment

The following is how development is recommended for this project :

1. Download and install [MAMP](https://www.mamp.info/en/mac/) which can create localhost on MAC OS as shown below.
![MAMP](./image/mamp.png)

2. Create a local environment WordPress.org as shown below.
![WordPress](./image/wordpress_setup.png)



3. [zip GitHub](cp3402-2022-team1)clone the repository to your desktop or download and unzip the folder if downloaded.
5. Modifications or newly created files on the local host commit to [GitHub](Labyrinth-child-2.0.0/Labyrinth-child/).
6. New developments, edits, and updates should be recorded on the Trello board, and the version name is updated every time. The Trello board effectively manages your project and keeps a historical record of your project.
7. Utilize a code editor such as Visual Code Studio or other IDE and run it as shown below.
![visualcode](./image/visualcode.png)

8. Create a control commit in the IDE the user is using and then push the completed work.
9. Create a relevant pull request for the main branch.
10. After changes are merged in the main branch, users can import the repository into their local environment and upload it to the staging site via a zip file.
11. If the test is successful on the staging website, the user can upload the theme zip folder to the production site.

# Export/Import WordPress

The following is export/import WordPress recommendations for this project :

1. Download and install [FileZila Client](https://filezilla-project.org/download.php?platform=osx) which can connect to your computer and web sever as shown below.

2. Quickconnect with host, username, password and port.
3. FileZila Client allow to download/upload file to web server as shown below.
4. Open **phpMyAdmin** as shown below.
5. Find and open **kzu_users** as shown below.
6. Copy existent ID and put user_login, user_pass, user_nicename, user_email and display_name.
7. Find and open **kzu_usermeta** as shown below.
8. Copy existent kuz_capabilities, rich_editing and screen_layout_tss-sc and put user_id as same as kzu_users's ID. (This 4 usermeta are mandatory)


# Web hosting 

### The staging site used [siteground](http://ruchip.sgedu.site/).
### The production site used [dreamhost](https://jihpar3.dreamhosters.com/).

Dreamhost offers the following:

- Uptime guarantees
- Unlimited Bandwidth & Storage
- Free Email Addresses
- Free SSL Security
- Automated Backups
- Free Privacy Protection

Below is what the Dream host looks like
![dreamhost](./image/dreamhost.png)

# Version Control

Version control is done with GitHub. A way to track, manage, and compare old and new versions of code that each team member has committed to the repository.

# Project Management

- [Staging site](http://ruchip.sgedu.site/)
- [Production site](https://jihpar3.dreamhosters.com/)
- [Project management board](https://trello.com/b/NDg5kUFU/cms-team)
- [Slack](https://app.slack.com/client/T1HPNSNKT/C03LW1D2HM2)
- [GitHub repository](/cp3402-2022-team1)

