# ATSC_ROUTE

Complete setup and usage guide under the /Doc folder

Summary:
To run this setup on your system:

System requirements
•	Ubuntu Linux 64 bit.
•	Apache with php,
•	Libcurl dev
•	Python

Put the contents of /Work directory under the www-root directory of your Linux Apache2 server.

reminder:
sudo apt install apache2 php mysql-server libapache2-mod-php chromium-browser python-lxml
In openssl source dir:
./config shared

In libcurl source dir:
export OPENSSL_ROOT_DIR=/usr/local/ssl/
cmake ..


Access the Sender UI located at:
http:// 127.0.0.1/Work/Route_Sender/bin/Sender_UI/

Access the Receiver UI located at:
http://127.0.0.1/Work/Route_Receiver/Receiver/

Simply start the service from sender side, and tune into a channel in the receiver.

For any issues, report in the issues section.

Note: The code is provided as-is, and currently, it does not provide reference implementation of any of the standards involved.

Licensing: See "LICENCE" file.
