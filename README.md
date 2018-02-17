# fungcorps
---
Make sure server is on before doing the below.

Check if someone else is on the server:
```
who
```
## 1.0 Instructions to Access Machine Learning Server ##
```
>> ssh *username*@*server.net* (ask barn for your login and pw)
```  
## 2.0 Instructions for fast.ai ##

Activate the fastai anaconda environment:
```
>> cd */directory to fastai local repo*/fastai/
>> source activate fastai 
``` 
Run the jupyter notebook server for DL1:

First, find the local ipv4 address for the machine:
```
>> ifconfig
```
Then activate the notebookserver at a convenient port:
```
>> cd *directory to fastai local repo*/fast_ai/fastai/courses/dl1
>> jupyter notebook --ip *address here* --port *4 digit port*
```
The terminal should output some instruction like this:
```
Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
     
```
Paste the URL into a browser and things should work.
