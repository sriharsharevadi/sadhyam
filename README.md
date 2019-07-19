# sadhyam
online exam platform

Installation steps:

#Database configuration

#Run the following commands
git clone https://github.com/sriharsharevadi/sadhyam.git
cd sadhyam
sudo apt install python3-pip
sudo apt-get install python3-venv
python3 -m venv sadhyam_env
source sadhyam_env/bin/activate
cd back-end
pip install -r requirements.txt

cd ~/sadhyam/back-end/sadhyam
python manage.py runserver
