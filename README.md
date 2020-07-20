# locust-loadtest

Step to run:

Install brew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Install libel
brew install libev

Install python
https://www.python.org/getit/
python3 --version

pip3 install locust
pip install --upgrade pip

Create script locust

Run locust
locust
locust -f locust_files/my_locust_file.py
locust -f locusfile.py --host=http://namadomain
