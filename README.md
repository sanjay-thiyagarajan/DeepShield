# Deep Shield

<img src="https://github.com/Mayukhdeb/deep-shield-temp/blob/main/images/banner_large_font.png" width=800>

## Instructions to setup

0. Make sure that you have `Python 3`, `python-3-devel`, `gcc`, `virtualenv`, and `pip` installed.     
1. Clone the repository

    ```bash
        $ git clone https://github.com/Mayukhdeb/deep-shield-temp.git
        $ git checkout django
        $ cd deep-shield-temp
    ```  
2. 
    a. Docker image (First option)  
  
    ```bash  
        $ docker-compose build  
        $ docker-compose up  
    ```  

    b. Create a python 3 virtualenv, activate the environment and Install the project dependencies. (Second option)  

    ```bash
        $ virtualenv -p python3
        $ source bin/activate
        $ pip3 install -r requirements.txt
    ```   

You have now successfully set up the project on your environment. 

---

### After Setting Up
From now when you start your work, run ``source bin/activate`` inside the project repository and you can work with the django application as usual - 

* `python3 manage.py makemigrations` - Prepare the models for migrations
* `python3 manage.py migrate` - Migrate the models
* `python3 manage.py runserver`  - run the project locally

*Make sure you pull new changes from remote regularly.*

---  

### Contributors  
- [Mainak Deb](https://github.com/Mainakdeb)
- [Mayukh Deb](https://github.com/Mayukhdeb)
- [Sanjay Thiyagarajan](https://github.com/sanjay-thiyagarajan)
