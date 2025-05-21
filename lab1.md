🖨️ Printable Lab Sheet & Solution Guide

🧪 Lab 1: Build and Run Custom Image

Objective: Build a MySQL container with custom config and verify it initializes properly.

Steps:

Create a Dockerfile using mysql:8 as base.

Add a custom my.cnf file to /etc/mysql/conf.d/.

Add an init.sql script to initialize the DB.

Build with:

docker build -t custom-mysql:8 .

Run the container and verify:

docker run -d --name db1 custom-mysql:8
docker logs db1

🧪 Lab 2: Set Up Offline Registry
