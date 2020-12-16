## Build the image based python3 
FROM python:3 

## Copy all packages to /app dir
COPY . /app 

## Change the default folder 
WORKDIR  /app 

## Install all packages 
RUN pip install  -r  /app/requirements.txt

## Set default port 
EXPOSE 5000 

## run this command when container started 
CMD ["/bin/sh", "-c", "python /app/app.py"]