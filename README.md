# AWS-AICV-Demo

User data for EC2

    #!/bin/bash
    yum -y install httpd git 
    systemctl enable httpd
    systemctl start httpd
    # Download Lab files
    git clone https://github.com/petamind/AWS-AICV-Demo.git
    cp -R AWS-AICV-Demo/* /var/www/html/


Implement on S3, you must use CloudFront for HTTPS
