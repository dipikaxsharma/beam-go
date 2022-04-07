# My commands:

1. Went to your Documents/44-517 folder. Created a new project folder under 44-517. 
2. Made new directory beam-go (no spaces - for the easiest life, never leave spaces in folder/file names!)
3. Changed directory into beam-go. This will be our root project folder for the quick start.
4. In your folder, run go mod init github.com/denisecase/beam-go (use your github profile name)
5. Use code . to open VS Code here.
6. Create the sample hello.go file in your new modules. Customize it. We'll be able to import your hello app from GitHub.
7. When done, use go run . to execute the default file in the folder. 

# Codes:
1. $ go version
2. $ go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
3. $ go install github.com/apache/beam/sdks/v2/go/examples/wordcount
$ wordcount --input sample.txt --output counts

