Login to remote server
ssh -i key.pem ubuntu@public IP
![Screenshot from 2023-04-18 10-06-38](https://user-images.githubusercontent.com/35652615/232716321-683cddf5-d4a4-416b-8171-1361d91bdba9.png)
first time using apt, we have to update 
sudo apt update
then install nginx
sudo apt install nginx
when promted cick Y to continue
![Screenshot from 2023-04-18 10-22-30](https://user-images.githubusercontent.com/35652615/232717480-4e3012a2-223a-4f26-9b8d-f3fc65e0cdf7.png)
Nginx server runnig now!!
![Screenshot from 2023-04-18 11-41-06](https://user-images.githubusercontent.com/35652615/232738160-20ac74c6-04e5-4f34-ab0e-88fd004ad216.png)
However, I will be creating another EC2 instance, had some glitches with port here
created another ec2 instance 
setup nginx server
![Screenshot from 2023-04-18 12-21-11](https://user-images.githubusercontent.com/35652615/232748808-42776433-5712-4d7f-a41a-1fa5607403b3.png)
![Screenshot from 2023-04-18 12-21-26](https://user-images.githubusercontent.com/35652615/232748847-01ff10c5-dec2-4513-abb3-e5094870da11.png)
and running locally @ local host
![Screenshot from 2023-04-18 12-52-07](https://user-images.githubusercontent.com/35652615/232755691-9ff460d3-05bb-48ec-8ed1-7ed222720d03.png)
Hurray!!
Now is time to set up a datababse manager (mysql)
Again i use apt to install
![Screenshot from 2023-04-18 13-00-56](https://user-images.githubusercontent.com/35652615/232797377-8a087f7c-9204-47fb-a8a0-d2461959fd43.png)
Done!
SOme security patch with Mysql
![Screenshot from 2023-04-18 13-02-13](https://user-images.githubusercontent.com/35652615/232797540-33ca3418-17be-4871-b093-bdaa520bae7e.png)
![Screenshot from 2023-04-18 13-05-37](https://user-images.githubusercontent.com/35652615/232797605-25b1c12b-631e-47e0-bcba-5acf16340f24.png)


Now, over to setting up PHP
Id,be instaling 2 packages at once using 
sudo apt install php-fpm php-mysql
![Screenshot from 2023-04-18 15-49-51](https://user-images.githubusercontent.com/35652615/232798274-9890692c-4899-480f-8584-0c6620395559.png)


