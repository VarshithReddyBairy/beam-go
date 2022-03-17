# beam-go
# Varshith Reddy Bairy
## Step By Step Process 
### Download and Install
- Download and Install GO from [Download](https://go.dev/doc/install)
### Check Version
- After Downloading and Installing, Check your GO version using the command  `go version`
### Create a project and a Repository
- Create a project with name beam-go in your local machine.
- Create a git repo with exactly the same name of your project in local machine.
- Create a go.mod file using the command `go mod init github.com/VarshithReddyBairy/beam-go`
### Get the SDK and the examples
- The easiest way to obtain the Apache Beam Go SDK is using the command `go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`
### Run WordCount
- First we need to get the wordcound.go
- We can get it by using the command `go install github.com/apache/beam/sdks/v2/go/examples/wordcount`
- We need to create input file and add some content to it.
- Now we need to run the word count using the command `go run wordcount.go --input sample.txt --output counts`
- I got a error stating to install some additional files using the command ` go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0`
- Now again run the command `go run wordcount.go --input sample.txt --output counts` , then it works and we can see the count of the words in file counts
