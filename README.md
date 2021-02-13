# ppm-test !! currently unstable !!
Acts as kind of skeleton for ppm as a parallel php processor


## start up
docker-compose.yml is just for testing purposes.

start with 

docker run -v `pwd`:/var/www -p 8080:80 phppm/nginx --bootstrap=symfony --static-directory=public/
