# Dockerfile Build Failure: Missing requirements.txt

This repository demonstrates a common error in Dockerfiles: a failure to build due to missing dependencies specified in a requirements.txt file. The original Dockerfile assumes the presence of a `requirements.txt` file which is missing, causing the build to fail.

The solution demonstrates how to handle this scenario gracefully by checking for the presence of the file before attempting to install dependencies. 