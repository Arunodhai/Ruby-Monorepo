# README

Online Hostel Management System

* It is a web application through which students can register with their basic details and select the hostel room and mess of their choice by requesting the warden.
* Students can raise any kind of complaints regarding the hostel and mess. Warden can register with his basic details and upload the hostel and mess fee details.
* Warden can verify the students details and allocate the rooms and mess based on the availability.
* Warden can see the complaints made by the students and resolve them .
* Technology: Ruby on Rails, HTML, CSS

Screenshots of Project: <br><br>
<img width="700" alt="homepage" src="https://github.com/user-attachments/assets/fdecc41c-26f8-4790-a56a-d0102a6145ec"><br>
<img width="700" alt="student register" src="https://github.com/user-attachments/assets/cf0c0c91-8c75-45c1-b6a3-5ffd47a117c5"><br>
<img width="700" alt="student login" src="https://github.com/user-attachments/assets/8559db39-d0d5-497c-8bc6-a7cfdf04dbe2"><br>
<img width="700" alt="warden register" src="https://github.com/user-attachments/assets/e925290d-5481-476a-abc3-2f909af60f90"><br>
<img width="700" alt="warden login" src="https://github.com/user-attachments/assets/f2d3de51-ecbf-45c9-bd65-5e01dbe66e1d"><br>
<img width="700" alt="new hostel details" src="https://github.com/user-attachments/assets/44baa91b-d2c4-4e5a-8ab6-35d1ce961852"><br>
<img width="700" alt="new mess details" src="https://github.com/user-attachments/assets/c221fc82-daca-4541-93af-c7f99df16fb3"><br>
<img width="700" alt="list of mess and hostels" src="https://github.com/user-attachments/assets/cea5f4e0-6b8b-4989-8761-ad2cf23048b6"><br>
<img width="700" alt="raise complain" src="https://github.com/user-attachments/assets/8c5e157b-ac4b-42f7-a246-de496e3f2b77"><br>
<img width="700" alt="complain raised dashboard" src="https://github.com/user-attachments/assets/87f93c78-ee49-46f0-81ee-76fae3faa624"><br>


* Try these lines in the console in the project folder:

    gem install bundler
    bundle
    rake db:create && rake db:migrate
    rails s

* These commands will start Rails server at localhost:3000. This project requires DB to be installed. (DB type depends on Gemfile content). Also you should check if config/database.yml file is present.
