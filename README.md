JUZAWEB CMS version 5.0.7 is vulnerable to Remote code execution through the media upload feature. An authenticated user with media upload permission can upload a PHP web-shell that is disguised as a image, which bypasses the MIME type check and executes commands on the server

## Vulnerability Details
- **Software:** Juzaweb CMS
- **Version:** 5.0.7
- **CVE:** Pending
- **Severity:** Critical
- **Authentication Required:** Yes (admin or media upload role)
- **Vulnerable File:** vendor/juzaweb/core/src/FileManager/MediaUploader.php



