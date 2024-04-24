Challenge 1 - How to Run on Windows OS. 
1. Download Docker Desktop and create an account. 
2. Open Windows Powershell/Command prompt. 
3. Use the command wsl --install to install the Ubuntu distribution to the powershell.
4. Once installed, it will prompt you to create a username and password. 
5. Clone the github repository to your prefered coding app. This application was created in Visual Studio Code. 
6. Save the cloned repositiry to your computer. Remember where you saved it. 
7. Return to the powershell, log into Ubuntu. 
8. Use the command sudo docker pull nginx to pull the nginx image from Docker Hub. 
9. To ensure nginx is running and no firewall is in the way, run the commands sudo systemctl start nginx. Followed by
sudo ufw allow 'Nginx Full', then sudo ufw reload. 
10. You will then want to expose your local port to the docker port 8080 using the command sudo docker run -p 8080:80 -d nginx. 
11. Then you can attempt to run the program using the command sudo docker run -p 8080:80 [the file path where you saved the repository] -d nginx. 

Challenge2 - How to Run on Windows OS
1. Download Docker Desktop and create an account. 
2. Open Windows Powershell/Command prompt. 
3. Use the command wsl --install to install the Ubuntu distribution to the powershell.
4. Once installed, it will prompt you to create a username and password. 
5. Clone the github repository to your prefered coding app. This application was created in Visual Studio Code. 
6. Save the cloned repositiry to your computer. Remember where you saved it. 
7. Return to the powershell, log into Ubuntu. 
8. Use the command sudo docker pull nginx to pull the nginx image from Docker Hub. 
9. To ensure nginx is running and no firewall is in the way, run the commands sudo systemctl start nginx. Followed by
sudo ufw allow 'Nginx Full', then sudo ufw reload. 
10. You will then want to expose your local port to the docker port 8080 using the command sudo docker run -p 8080:80 -d nginx. 
11. Then you can attempt to run the program using the command sudo docker run -p 8080:80 [the file path where you saved the repository] -d nginx. 
