# CSYE 6225
Assignments for CSYE 6225

## Prerequisites

### Github
A fork is made from the organization called kanishkbhatia/ webapp. The repository on the fork is then cloned locally using the 'git clone' command and using SSH.

### Node
Install node and npm by running the following commands:

```
sudo apt install nodejs

sudo apt install npm
```

### MySQL Workbench
Run a MySQL connection on:
```
host: localhost

port: 3306

username: root

password: password
```

Create two schemas after that:
```
userDB

productDB
```

## Running the code
In the git directory, run the following command to install the dependencies and run the code:
```
npm start
```

## Postman
Postman needs to be installed for testing the API calls
```
http://127.0.0.1:8080/{requiredRequest}
```

Depending on the type of API call, change the HTTP requests

Sample to add new user:
```
{
    "username": "login@gmail.com",
    "first_name": "Kanishk",
    "last_name": "Bhatia",
    "password": "12345"
}

Sample to add new product:

{
    "name": "Galaxy S22",
    "description": "Smartphone",
    "sku": "1",
    "manufacturer": "Samsung",
    "quantity": 50
}
```

## Running the test
npm run test

    // inline = [
    //   "aws s3 cp s3://${var.s3_bucket}/${var.s3_key} /tmp/${var.s3_key}",
    //   "sudo mkdir /home/${var.ssh_username}/my_folder",
    //   "sudo unzip /tmp/${var.s3_key} -d /home/${var.ssh_username}/my_folder",
    //   "sudo chown -R ${var.ssh_username}:${var.ssh_username} /home/${var.ssh_username}/my_folder",
    //   "sudo rm /tmp/${var.s3_key}"
    // ]