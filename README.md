ASSIGNMENT 1

Installation of Nginx.
Task Description:
This task involves creating a Jenkins Freestyle job that automates the installation of Nginx onan Ubuntu server using the command sudo apt-get install -y nginx. This automation ensures consistent server setup and can be easily repeated, making it ideal for automated environments.

Steps:
1. Update Package List:
*  Run the following command to update the package list:
*  sudo apt update
2. Install Nginx:
*  Install Nginx using the following command:
*  sudo apt-get install -y nginx
3. Verify Installation:
* Check if Nginx is running with the command:
*  systemctl status nginx
4. Create Jenkins Freestyle Job:
*  In Jenkins, click New Item and create a Freestyle project (e.g., Install_Nginx).
5. Configure Job:
 * Add a build step of type Execute shell.
* In the Windows command box
Echo “Hello Jenkins”
6. Save and Run Job:
* Save the job and click Build Now to run it.

7. Check Console Output:
* After the job completes, view the Console Output to confirm the successful
installation of Nginx.

    








 




 
 
