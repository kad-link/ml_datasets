# ml_datasets
url based datasets


13 mar : working on my first ever ML project ie. titanic . so i am loading my csv local file to the github so that i can use it via a URL anytime and anywhere. would like to make this a practise. by the was, the code snippet to use do this , this way is : 

`import requests
from io import StringIO

url=""
headers= {"User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.14; rv:66.0) Gecko/20100101. Firefox/66.0"}
req = requests.get(url,headers=headers)
data = StringIO(req.text)

df = pd.read_csv(data)`
