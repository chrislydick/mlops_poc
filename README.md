# mlops_poc

### Description: 
======
The idea here is to setup a server and client setup for MLFlow (mlflow.org) with a prepared prediction model and a streamlit app served on the server. Retraining should occur on the clients, with an automatic update to the server. 


### Criteria:
====== 
* Use reference names wherever available, instead of guid or computer-generated URLs for models or productionlized models. 
* Have a seperated instance of server and client. 
* Server exists in AWS EC2. 
* Client can exist within VPN. 
