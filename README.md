# Hosting-a-Static-Website-on-Google-Cloud-VM-with-Apache
In this project, I deployed a static website to the Google Cloud Platform (GCP) using a Compute Engine Virtual Machine (VM) and Apache Web Server. This demonstrates skills in cloud infrastructure, Linux server management, and web hosting.

Steps I Followed
	1.	I Created a Virtual Machine Instance
	•	Used Google Compute Engine.
	•	Chose OS: Ubuntu (20.04 LTS).
	•	Configured firewall to allow HTTP traffic.
  
	2.	Connected to the VM via SSH
	•	Used GCP’s in-browser SSH tool.

  	3.	Installed Apache Web Server
  MY CODE; sudo apt update
sudo apt install apache2 -y

	4.	Uploaded Website Files
	•	Uploaded HTML, CSS, and image files using the SSH file upload option.

  	5.	Moved Files to Apache’s Root Directory
    sudo mv * /var/www/html/
     I then 	Ensured correct permissions: 
     sudo chown -R www-data:www-data /var/www/html
sudo chmod -R 755 /var/www/html

	6.	Accessed Website Live
	•	Opened the external IP address in a browser.
	•	The deployed static website loaded successfully.

   Outcome
	•	Successfully hosted a static website on GCP using Compute Engine and Apache.
	•	Learned how to:
	•	Launch and configure VM instances.
	•	Install and configure web servers.
	•	Upload and manage web files on Linux servers.
	•	Expose a website to the internet with an external IP.

  

  
