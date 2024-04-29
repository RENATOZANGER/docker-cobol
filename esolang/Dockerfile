FROM esolang/cobol

# Copy file COBOL to conteiner
COPY *.cbl /
RUN cobc -x -free -o /hello /hello.cbl

#exec hello.cbl
CMD ["/hello"]
