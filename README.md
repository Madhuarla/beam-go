# beam-go
# Madhu Babu Arla

Here are some steps to follow

1. Firstly, visit this [Link](https://beam.apache.org/get-started/quickstart-go/#run-wordcount) and install ```go1.18.windows-amd64.msi``` on to your system.
2. After successfull download, install the setup file.
3. Create a folder named beam-go.
4. right click and run the powershall as admin from the beam-go folder. And execute the follow commands
> ```go mod init github.com/Madhuarla/beam-go```
5. steps to run the project.
> ```go version``` - To check the go version
  
> ```go get -u github.com/apache/beam/sdks/v2/go/pkg/beam``` - To get the Apache Beam Go SDK
  
> ```go install github.com/apache/beam/sdks/v2/go/examples/wordcount``` - To install the wordcount program
  
> ```wordcount --input madhusample.txt --output madhuarla_counts``` - to generate the program
  
6. The output file will be generated
