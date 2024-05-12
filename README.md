# README

Below is a README file template for your Chrome extension project:

---

# Activity Tracker Chrome Extension

The Activity Tracker Chrome Extension is a productivity tool designed to help users track their browsing habits and manage their time effectively on the internet. It allows users to monitor the time spent on each website, set time limits for specific sites, and restrict access to distracting websites.

## Installation

To install the Activity Tracker Chrome Extension, follow these steps:

1. Download the extension files from the GitHub repository or obtain the extension package.
2. Open Google Chrome and navigate to the Extensions page. (You can access this page by typing `chrome://extensions` in the address bar and pressing Enter.)
3. Enable Developer mode by toggling the switch in the top right corner.
4. Click on the "Load unpacked" button and select the directory containing the extension files.
5. The Activity Tracker Chrome Extension should now be installed and visible in your list of extensions.


## Usage

Once the extension is installed, it will start tracking your browsing activity automatically. You can access the extension's features by clicking on its icon in the Chrome toolbar.

### Features:

1. **Track Activity**: The extension tracks the time spent on each website and provides detailed analytics.
2. **Productive Browsing**: Users can add websites to a restricted list and set time limits for them.
3. **Personalized Dashboard**: Access your website usage statistics and analytics in a personalized dashboard.



## Database Schema

The database schema for the Activity Tracker Chrome Extension is as follows:

```
User
- id (Primary Key)
- email (String)
- password_digest (String)

Website
- id (Primary Key)
- url (String)
- category (String)
- user_id (Foreign Key)

Visit
- id (Primary Key)
- website_id (Foreign Key)
- start_time (DateTime)
- end_time (DateTime)
- duration (Integer)
```
---

## Screenshots
![](https://i.ibb.co/ZzVCnMy/Screenshot-2021-10-06-at-23-40-46.png)

![](https://i.ibb.co/SxzVhKn/01.png)

![](https://i.ibb.co/CKWX6sp/03.png)

![](https://i.ibb.co/sRKZcmZ/03.png)

![](https://i.ibb.co/myMRTyJ/Screenshot-2021-10-06-at-23-49-39.png)
