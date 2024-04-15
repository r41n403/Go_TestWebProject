# Go_TestWebProject

Simple Go web program that displays "Hello Word!" On port 3000

Amazon Linux Setup:

1. `sudo yum install -y golang`
2. copy hello.go to home directory
3. `go build hello.go`
4. Copy hello.service systemd file to /etc/systemd/system/hello.service
5. `sudo systemctl daemon-reload`
6. `sudo systemctl enable hello.service`
7. `sudo systemctl start hello.service`

Go program will run on boot. 
