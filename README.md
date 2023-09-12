<h1 align='center'> 
  BookIT App
</h1>

This app was created with the purpose to service small business owners in the hair salon industry to store data about their customers, appointments and staff.  

### How to setup and start the containers
**Important** - you need Docker Desktop installed

1. Clone this repository.  
1. Change the password in the file named `db_root_password.txt` in the `secrets/` folder and put inside of it the root password for MySQL. 
1. Change the password in the file named `db_password.txt` in the `secrets/` folder and put inside of it the password you want to use for the `webapp` user. 
1. In a terminal or command prompt, navigate to the folder with the `docker-compose.yml` file.  
1. Build the images with `docker compose build`
1. Start the containers with `docker compose up`.  To run in detached mode, run `docker compose up -d`. 

### For setting up a Conda Web-Dev environment:

1. `conda create -n webdev python=3.9`
1. `conda activate webdev`
1. `pip install flask flask-mysql flask-restful cryptography flask-login`

### Link to Demo:
https://drive.google.com/file/d/1mYm_mGXBU-tMCUjnyEuMUWFhAjeF8lB1/view?usp=sharing 

### Demo Owner Login Page Info:

Username: teamquattro_owner
<br>
Password: quattropass

### Demo Admin Login Page Info:

Username: teamquattro_admin
<br>
Password: quattropass



