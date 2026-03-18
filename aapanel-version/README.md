# GLPI Deployment using aaPanel

## Overview
This deployment aimed to install GLPI using a traditional web hosting stack (Nginx, PHP, MySQL) via aaPanel.

## Challenges Encountered
- Web server misconfiguration errors
- Issues with GLPI's `/public` directory structure
- PHP restrictions (open_basedir)
- Missing PHP extensions (mbstring, fileinfo)
- Permission errors on system files
- Database access control issues
- Routing problems after authentication

## Actions Taken
- Adjusted Nginx configuration
- Modified PHP settings and permissions
- Installed missing extensions
- Switched to CLI installation for database setup
- Tested multiple configurations

## Result
- GLPI installation completed via CLI
- Web interface partially functional
- Some routing issues remained unresolved

## Key Takeaway
Traditional deployments can introduce unexpected complexity, especially when dealing with modern PHP applications.

