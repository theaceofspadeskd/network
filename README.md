# network

Twitter-like social network website for making posts and following users.

Deployed on: https://taoskd.pythonanywhere.com/

All requirements and specification can be viewed here: https://cs50.harvard.edu/web/2020/projects/4/network/


Run in Docker:

1. Pull image
 ```
 docker pull theaceofspadeskd/network:v1 
 ```
2. Run container  
 ```
 docker run -p 8000:8000 theaceofspadeskd/network:v1
 ```   

Installation:

1. Download this project
    ```
    git clone https://github.com/theaceofspadeskd/network.git
    ```
2. Install all necessary dependencies
    ```
    pip install -r requirements.txt
    ```
3. Make migrations
    ```
    python manage.py makemigrations
    ```
4. Migrate
    ```
    python manage.py migrate
