# Terraform AWS S3 static website
Terraform configuration for hosting a static website on AWS S3

This repository holds the harshicorp terraform code used to host the static website https://www.mybucket.me/ on AWS S3. The bucket functions as a web server and serves the contents of index.html for any requests to bucket-name/index.html, displaying a "Hello World" message, otherwise serves the 404.html page and displays a "page not found message".
