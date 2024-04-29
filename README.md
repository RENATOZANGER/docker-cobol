## docker-Cobol
Cobol program that displays the "Hello, World!" 

## step by step to run the program
1. Create Docker Image: 
- docker build -t teste .

2. Exec Container from docker image:
- docker run --rm teste

3. If you want to redirect the container's output to a file, you can do so using the following command:
- docker run --rm teste > input.txt