# Corenlp Version 3.7
## Dockerfile for Stanford CoreNLP Server

This Dockerfile builds the [Stanford CoreNLPServer](https://stanfordnlp.github.io/CoreNLP/corenlp-server.html) and exposes the endpoint on port 9000 by default. Requests are made as covered in the documentation.

This version uses the Oracle version of Java.

To run:

docker run -p 9000:9000 --rm unititled99/corenlp
