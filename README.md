# WordPress Security in Good Hands

## About this handbook

Hello, this handbook is the result of my ongoing research into WordPress security over the years. In which I explain about WordPress security, its current threats and how to harden the whole system. The goal is to give you the essential knowledge to understand WordPress security as well as keep it’s under control. I won’t tell you which plugin to install for “maximum security.” Instead, I aim to build your understanding from the core outward, giving you the insight to make your own decisions.

The full content of the handbook is available [here](https://taiht.dev/articles/wordpress-security-in-good-hands/).

I greatly appreciate any feedback that can help improve this handbook and make it even more valuable to the web dev community. Please share your thoughts or suggestions by creating an Issue or emailing me at hello@taiht.dev. Thank you!

## Table of Contents

### CHAPTER 1: INTRODUCTION—HOW SECURE IS WORDPRESS?

- About WordPress Security
- Understanding the Security Model of WordPress
- From Browser to Server: The Journey of a Web Request
- The Real Problem

### CHAPTER 2: THE STATE OF WORDPRESS SECURITY IN 2025

- Key Figures
- Popular Websites Powered by WordPress

### CHAPTER 3: BEST PRACTICES FOR HARDENING WORDPRESS SECURITY

- Choose a Reliable Hosting Provider
- Reduce the Attack Surface
- Control Access and Permissions
- Disable Unnecessary Features
- Why I Don’t Use Security Plugins
- Monitoring, Logging, and Early Detection
- Backup, Backup, and Backup
- Prepare for Incidents Before They Happen
- Build a Long-Term Security Culture

### CHAPTER 4: WORDPRESS SECURITY IN ACTION

- How to Hack a WordPress site
- Secure Your WordPress site
	1. Hide PHP Version and Nginx Version
	2. Enforcing Automatic TLS/SSL Certificate
	3. Block Direct IP Access to Prevent Cloudflare Bypass
	4. Set the Security Permissions for WordPress Files and Folders
	5. Secure Your wp-config.php File
	6. Hide All Errors from Being Printed on the Front-end
	7. Disable WP-Cron
	8. Disable the WordPress File Editor
	9. Change the Default Login URL to Dodge ‘Dumb’ Bots
	10. Limit Login Attempts, Hide WordPress Version, etc.
	11. Hide Your Real Username
	12. Avoid Using the Username “admin”
	13. Integrate Two-Factor Authentication
	14. Remove Unused Plugins and Themes
	15. Wisely Manage User Accounts
	16. Don’t Forget “Must-Use (MU) Plugins”
	17. Disabling Concatenated Script Loading
	18. Blocking OPML Links
	19. Preventing WP’s “Application Passwords” from Being Abused
	20. Useful Cloudflare Rules
	21. Other Security Measures in Nginx

### CHAPTER 5: WHAT TO DO NEXT

- The Official Sources
- Security Intelligence
- Communities
