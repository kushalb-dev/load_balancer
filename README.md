# <u> Simple Load Balancer in Golang </u>

This project is a tutorial-project that I coded alongside the go youtuber Akhil Sharma. This project is a very simple load balancer that redirects server requests in a round robin fashion. 

This doesn't take into account the usage capacity of the servers, it just takes in the request and forwards it to the next available server.

This project helped me learn about http server proxies and reverse proxy, what are they really used for and how do client and servers talk to each other. 

There are no requirements for this project, everything is available in the go standard library. You just need a running version of go. 

`go run main.go` should do the job if you want to demo this project. 

![GO_Image](https://blog.logrocket.com/wp-content/uploads/2020/06/creating-a-web-server-with-golang.png)

Thanks for checking out!