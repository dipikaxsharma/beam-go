# My process:

1. Went to your Documents/44-517 folder. Created a new project folder under 44-517. 
2. Made new directory beam-go (no spaces - for the easiest life, never leave spaces in folder/file names!)
3. Changed directory into beam-go. This will be our root project folder for the quick start.
4. In our folder, ran go mod init github.com/dipikaxsharma/beam-go
5. Used code . to open VS Code here.
6. Created the sample hello.go file in my new modules. Customized it.

# My Commands:
1. $ go version
2. $ go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
3. $ go install github.com/apache/beam/sdks/v2/go/examples/wordcount
$ wordcount --input sample.txt --output counts

