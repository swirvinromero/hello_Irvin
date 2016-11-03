# hello_Irvin
one of many




# registration


import requests
import json

url = 'http://challenge.code2040.org/api/register'
payload = { 'token': '' , 'gtihub': 'https://github.com/swirvinromero/hello_Irvin' }

r = requests.post(url, json=payload )
print(r.text)
