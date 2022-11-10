# DNS-practice

## Name of purchased domain
- mengyao36.tech

## A copy of the 'A' record settings that needed to write (name, value, TTL)
- Host name: left blank or type @
- Value: 34.71.249.106
- TTL: 7200

## Cloud vendor selected
- GCP

## Brief instructions if replication needed
- Create own vm and get the IP address ready
- Create own domain name (e.g. XXX.tech)
- Under 'Manage Orders' - 'List/Search orders', find domain name and click on it
- Go to 'DNS Management' and click 'Manage DNS'
- Under 'A Records', click 'Add A Record'
- Put vm IP address under 'Value'
- Set own TTL (min is 7200)
- Go back to vm terminal and connect to git repo
- Locate the flask app file and connect to it

## Commands used in vm terminal
- `sudo apt-get update`
- `sudo apt install python3-pip`
- `pip3 install flask` or `sudo apt get install python3-flask`
- `git clone git-repo-link`
- `sudo python3 file_name.py`
- to edit python file, use `nano file_name.py`
