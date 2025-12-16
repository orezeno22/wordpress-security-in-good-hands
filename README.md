# WordPress Security in Good Hands

## About this handbook

Hi, I've been a WordPress enthusiast since 2007, and this handbook is the result of my research into WordPress security since 2020. The handbook guides you through WordPress security by covering its foundations, current threats, practical hardening techniques, and real-world examples. The goal is to give you the essential knowledge to understand risks while equipping you with the tools needed to keep WordPress sites secure and reliable in an ever-changing world. I won’t tell you which plugins to install for “maximum security.” Instead, I aim to build your understanding from the core outward, giving you the insight to make your own decisions, whether you prefer handling everything manually or using a third-party tool.

The full content of the handbook is available [here](https://taihoang.com/articles/wordpress-security-in-good-hands/).

I greatly appreciate any feedback that can help improve this handbook and make it even more valuable to the web dev community. Please share your thoughts or suggestions by creating an Issue or emailing me at hello@taihoang.com. Thank you!

## Table of Contents

### CHAPTER 1: INTRODUCTION—HOW SECURE IS WORDPRESS?

- About WordPress Security
- Understanding the Security Model of WordPress
- From Browser to Server: The Journey of a Web Request
- The Real Problem

### CHAPTER 2: THE STATE OF WORDPRESS SECURITY IN 2025

- The State of WordPress Security in 2025
- Popular Websites Powered by WordPress

### CHAPTER 3: BEST PRACTICES FOR HARDENING WORDPRESS SECURITY

- Choose a Reliable Hosting Provider
- Reduce the Attack Surface
- Control Access and Permissions
- Disable Unnecessary Features
- Why I Don’t Use Security Plugins
- Monitoring, Logging, and Early Detection
- Backup, Backup, Backup
- Prepare for Incidents Before They Happen
- Build a Long-Term Security Culture

### CHAPTER 4: WORDPRESS SECURITY IN ACTION

- How to Hack a WordPress site
- Secure Your WordPress site
	1. Hide PHP version and Nginx version
	2. Enforce Automatic TLS/SSL Certificate
	3. Block Direct IP Access to Prevent Cloudflare Bypass
 	4. Set the Security Permissions for WordPress files and folders
  5. Secure your wp-config.php file
  6. Hide all errors from being printed on the front-end
  7. Disable WP-Cron
  8. Disable the WordPress File Editor
  9. Change the default login URL to dodge ‘dumb’ bots
  10. Limit Login Attempts, Hide WordPress Version, etc.
  11. Hide your real username
  12. Avoid Using the Username “admin”
  13. Integrate two-factor authentication
  14. Remove Unused Plugins and Themes
  15. Wisely Manage User Accounts
  16. Don’t Forget “Must-Use Plugins”
  17. Other Security Measures in Nginx
  18. Useful Cloudflare Rules

### CHAPTER 5: WHAT TO DO NEXT

- The Official Sources
- Security Intelligence
- Communities
