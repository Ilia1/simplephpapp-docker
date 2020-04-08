[SimplePhpApp] (https://github.com/Saritasa/simplephpapp) in Docker
======================

## Building the images in this repository

You can build the images with the build command
```
sudo docker build -t simplephpapp .
```
## First run

You need generate application key by run command
```
sudo docker run --rm --network host -v $PWD/.env:/simplephpapp/.env -t simplephpapp php artisan key:generate
```
## Example run command

```
sudo docker run --rm --network host -v $PWD/.env:/simplephpapp/.env -t simplephpapp
```
