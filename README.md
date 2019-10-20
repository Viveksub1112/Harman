#Requirement:
1. Write an ansible playbook to install the HTTPD server. Also, install and configure two virtual servers running on different ports. Install and configure a self-signed certificate.
2. The above role should be integrated with Jenkins i.e. build a Jenkins job to execute your ansible
3. For point 1 write a playbook which will do the following
    - Identify the certificate expiry dates for the 2 virtual servers
    - If the certificate expiry is due with 7 days then perform certificate updates
    - Create new certs
    - Update the certs
    - Validate and verify if the certificates update properly 
