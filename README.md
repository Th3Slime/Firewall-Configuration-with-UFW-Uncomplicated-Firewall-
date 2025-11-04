# Firewall-Configuration-with-UFW-Uncomplicated-Firewall-
Goal: Secure your system by blocking unauthorized network access.   

 1. Install UFW:
 
sudo apt install ufw  # Install firewall

2. Deny all incoming traffic by default:

sudo ufw default deny incoming  # Block all incoming connections

3. Allow essential services (SSH/HTTP):

sudo ufw allow ssh  # Allow SSH for remote management
sudo ufw allow http  # Allow web traffic (if hosting a server)

4. Enable the firewall:
   
sudo ufw enable  # Activate firewall

5. Verify rules:

sudo ufw status  # List active rules
