# Cloud-linux-livewire
[ec2-user@ip-172-31-45-175 ~]$ sudo su
[root@ip-172-31-45-175 ec2-user]# ls

[root@ip-172-31-45-175 ec2-user]# ls -la
[root@ip-172-31-45-175 ec2-user]# mkdir cloud
[root@ip-172-31-45-175 ec2-user]# touch aws.text
[root@ip-172-31-45-175 ec2-user]# echo "cloud computing">aws.text
[root@ip-172-31-45-175 ec2-user]# cat aws.text
cloud computing
[root@ip-172-31-45-175 ec2-user]# echo "welcome to cloud computing">aws.text
[root@ip-172-31-45-175 ec2-user]# cat aws.text
welcome to cloud computing
[root@ip-172-31-45-175 ec2-user]# yum install httpd
[root@ip-172-31-45-175 ec2-user]# systemctl start httpd
[root@ip-172-31-45-175 ec2-user]# systemctl enable httpd

[root@ip-172-31-45-175 ec2-user]# echo "<html><body><h1>My First Heading</h1><p>My first paragraph.</p</body></html>">/var/www/html/index.html
