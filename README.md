Forked from https://github.com/omnicate/yopass to allow uploading larger files.

Default as of March 31st, 2021 - only a 5kb upload file.

This change will allow around a 500kb file.

Building the container
```
go get -u ./...
docker build . -t image-name-here
docker push image-name-here
```