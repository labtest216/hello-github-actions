# set base image (host OS)
FROM python:3.8
# set the working directory in the container
#WORKDIR ./
# copy the dependencies file to the working directory
COPY requirements.txt .
# copy the content of the local src directory to the working directory
#COPY ./StudDeploy /opt/StudDeploy
#WORKDIR /
# install dependencies
RUN pip install -r requirements.txt
WORKDIR /opt/StudDeploy
#RUN chmod -R 744 ./Deploy_app.py

# command to run on container start
CMD [ "python", "./test.py.py" ]
