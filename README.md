# To Do List
This is a fullstack project built with HTML/CSS frontend and Golang backend. A simple To-Do app where one can create, edit and delete tasks.

https://todo.mobenh.com

## Technologies Used
* Golang
* HTML
* CSS
* MongoDB

## Dependencies

* Install Go - https://go.dev/doc/install
* Install MongoDB - https://www.mongodb.com/docs/manual/administration/install-community

## Executing program

* Download the repository to your computer and go to project file
```
git clone https://github.com/mobenh/go-todo
cd go-todo
```
* View the project locally
```
go mod init github.com/mobenh/go-todo
go build
go run main.go
```

## Deploying to AWS
* Launch an Amazon Linux 2 EC2 instance
* Install git on the instance - https://www.how2shout.com/linux/how-to-install-git-on-aws-ec2-amazon-linux-2
* Install Go on the instance - https://medium.com/cloud-security/go-get-go-download-install-8b48a0425717
* Install MongoDB on the instance - https://techviewleo.com/how-to-install-mongodb-on-amazon-linux
* Repeat the "Executing program" section of this README.md
* Detach terminal to allow the app to work in th background - https://linuxize.com/post/how-to-use-linux-screen
* Create an Application Load Balancer, aquire certs, and create host record - https://www.youtube.com/watch?v=bWPTq8z1vFY&t=714s&ab_channel=NKTStudios

### AWS Technologies used
* EC2 Amazon Linux 2 (for servering the app)
* Application Load Balancer (to allow secure cert assignment)
* Route 53 (for domain registration and DNS record creation)
* Certificate Manager (for acquiring certificates)

