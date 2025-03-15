# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## creating the buld binary
We need to clone the repo and execute the below command for generating the build binary.
~~~
go build -o main .
#main is the name of the binary file that will be created 
~~~
To execute the code binary we can use 
~~~
./main
~~~

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)


## Helm installation and Configuration

To install the helm, we can use the below script in ubuntu
~~~
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
~~~
Post instalation,
we can first create a helm chart
~~~
helm create <helm_chart_name>
~~~
