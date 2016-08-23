# hello_Irvin
one of many




# registration


import requests
import json

url = 'http://challenge.code2040.org/api/register'
payload = { 'token': 'a8faea3d0da1899e8a9d19c9cfbcd05a' , 'gtihub': 'https://github.com/swirvinromero/hello_Irvin' }

r = requests.post(url, json=payload )
print(r.text)
