# ssl-implentation

------------------------------
THis is a quick way to secure apache based webapp using certbot
1.Install Apache (Skip if already installed)

sudo apt update
sudo apt install apache2 -y

2.Install Certbot and Apache Plugin

sudo apt install certbot python3-certbot-apache -y

3.Run Certbot to Get and Install SSL Certificate
Replace yourdomain.com with your actual domain that points to this EC2 instance:

sudo certbot --apache -d yourdomain.com -d www.yourdomain.com

Verify HTTPS is Working-----------
