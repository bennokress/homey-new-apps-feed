# 🏠 Homey Apps RSS Feed

[![RSS Feed](https://img.shields.io/badge/RSS-Feed-orange?style=flat-square&logo=rss)](https://raw.githubusercontent.com/DEIN-USERNAME/homey-apps-feed/main/feed.xml)
[![Homey Community](https://img.shields.io/badge/Homey-Community-blue?style=flat-square)](https://community.homey.app/)
[![Automation](https://img.shields.io/badge/Powered%20by-Make.com-blueviolet?style=flat-square)](https://www.make.com)

An automated RSS feed for new apps published in the Homey App Store, sourced from the official [Community Thread](https://community.homey.app/t/list-new-published-app-in-homey-app-store-get-em-while-theyre-hot/100276).

## 📡 Subscribe to the Feed

Copy this URL into your favorite RSS reader:
```
https://raw.githubusercontent.com/bennokress/homey-new-apps-feed/main/feed.xml
```

## 📋 What's Included

Each feed item contains:
- **App Name** - The name of the newly published app
- **Description** - A brief tagline or description
- **Link** - Direct link to the app on homey.app
- **Author** - The community member who posted about the app
- **Publication Date** - When the app was announced

## 🤖 How It Works

This feed is automatically generated through a workflow automation:

1. **Monitoring** - The Community Thread is monitored for new app announcements
2. **Email Notifications** - New posts trigger email notifications
3. **Automation** - A Make.com scenario parses incoming emails and extracts app details
4. **Storage** - App data is stored in `data/apps.json` in this repository
5. **Feed Generation** - The RSS feed (`feed.xml`) is automatically updated with new entries

The entire process is serverless and runs on GitHub + Make.com automation.

## 🔄 Update Frequency

The feed updates automatically whenever it gets a notification mail about a new app posted to the Homey Community Thread. Typically this happens several times per week.

## ⚠️ Disclaimer

This is an unofficial, community-maintained feed. It relies on the Community Thread structure remaining consistent. The official source of truth is always the [Homey App Store](https://homey.app/apps) and the [Community Forum](https://community.homey.app/).

## 🐛 Issues or Suggestions?

If you notice any problems with the feed or have suggestions for improvement, please [open an issue](https://github.com/bennokress/homey-new-apps-feed/issues).

## 📜 License

This project is provided as-is for the Homey community. Feed data is sourced from publicly available Community Forum posts.

---

**Not affiliated with Athom or Homey. Just a community member making it easier to discover new apps!**
