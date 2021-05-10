# admin_site

Commands to get the site up and running
start_postgres
python3 -m pip install psycopg2-binary
wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0251EN-SkillsNetwork/labs/m4_django_app/lab2_template.zip"  
unzip lab2_template.zip
rm lab2_template.zip
cd lab2_template
pip3 install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py 
python3 manage.py createsuperuser
python3 manage.py runserver
