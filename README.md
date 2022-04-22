# Send Data Through API  👋

```bash
import requests

# defining the api-link
API = "http://127.0.0.1:8000/"

# data to be sent to api
data = {'title':"raju",
		'desc':'rangila'}

try:
    r = requests.post(url = API, data = data)
except:
    print("false")
```
# Get Data Through API  👋

```bash
import requests

# Making a get request
response = requests.get('https://reqres.in/api/unknown')

# print response
print(response)

# print json content
a = response.json()
print(a)

# print specific json content
print(a['data'][0]['name'])
```
