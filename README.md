# FastAPI-MinIO-Storage

This is a project that uses FastAPI to create a web application for file upload and download, using a MinIO-storage. The project consists of two containers, one for the FastAPI application and another for the MinIO.

### Prerequisites

This project relies on the [Docker](https://www.docker.com/) and the [Docker Compose](https://github.com/docker/compose). You should install them to build and run the project.

### Getting Started
To get started, you need to clone this repository:

``` sh
git clone https://github.com/Ladyk3000/FastAPI-MinIO-Storage.git
```

### Build

To build the project you need to run the build command:

``` sh
docker-compose build
```

### Run

To run the project simply execute the following command:

``` sh
docker-compose up
```

This will start the FastAPI application on port 80 and the mini-storage on port 9000. You can access the application by navigating to the following URL in your web browser:
```
http://localhost:8000/
```

### Usage

Once you have the application running, you can use it to upload and download files from the mini-storage. 
To upload a file, navigate to the upload page: 
```
http://localhost:8000//uploadfile/
```
and click on the "Upload File" button. This will take you to a form where you can select a file to upload. 
After selecting the file, click on the "Upload" button to upload the file to the mini-storage.

To download a file, navigate to the download page:
```
http://localhost:8000//downloadfile/
```
choose file from list of files in bucket and click to filename to download it.
