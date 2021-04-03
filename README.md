# GCP-AppEngine-HelloWorld
Quick demo video of a hello world tutorial for GCP's AppEngine 

(please click on the video below to hear sound.)
![demo](https://user-images.githubusercontent.com/38410965/111926274-97acd500-8a82-11eb-8bd4-17b26185dc00.mp4)

This demo follows a Google Cloud Platform (GCP) quickstart:
- [x] log into Google Cloud https://cloud.google.com
- [x] click *Console* in upper right corner
- [x] in the Console, click *Navigation menu* in upper left corner
- [x] in the Navigation menu, click on *App Engine*
- [x] in the upper right corner of the window click on "Learn" or "Learn Home" 
- [x] under "Recommended for you", click on "App Engine Quickstart" 



#
Demo Video 3
Google App Engine 

Steve Depp
MSDS 434 section 55 


Geewax Chapter 11
- [x] standard / flex
- [x] applications, services, versions
- [x] deploying, scaling





#

GCP app engine hello world tutorial

App Engine Quickstart
Deploy a sample application to App Engine using the gcloud command

https://cloud.google.com/appengine/docs/standard/python3/quickstart

<img width="257" alt="App Engine Quickstart" src="https://user-images.githubusercontent.com/38410965/113491408-92964f80-949e-11eb-932b-fc19a32fa8c7.png">


#

GCP app engine hello world tutorial

1. decide on a language



#

GCP app engine hello world tutorial

2. make a project

- [x] gcloud projects describe PROJECT_ID
- [x] gcloud projects list
- [x] gcloud alpha projects update PROJECT_ID --name=NAME
- [x] gcloud projects delete PROJECT_ID
- [x] gcloud projects undelete PROJECT_ID



#

GCP app engine hello world tutorial

3. gather code



#

GCP app engine hello world tutorial

4. examine the code



#

GCP app engine hello world tutorial

gather and examine code
- [x] git clone
- [x] cat main.py
- [x] cat app.yaml


#

GCP app engine hello world tutorial

5. build and test the app locally




#


GCP app engine hello world tutorial

build and test locally:
- [x] python3 -m venv ~/envs/hello_world
- [x] source ~/envs/hello_world/bin/activate
- [x] pip install -r requirements.txt
- [x] python main.py


#


GCP app engine hello world tutorial

local results
- [x] curl http://127.0.0.1:0000/
- [x] plug and play in browser



#


GCP app engine hello world tutorial

6. create and deploy app to GAE standard —> results




#

GCP app engine hello world tutorial

create and deploy app to GAE standard
- [x] gcloud app create —project depp-gcp-training-20201002
- [x] gcloud app deploy app.yaml --project depp-gcp-training-20201002




#


GCP app engine hello world tutorial

deploy —> results 
- [x] curl https://depp-gcp-training-20201002.ue.r.appspot.com
- [x] gcloud app browse -project=depp-gcp-training-20201002


#

GCP app engine hello world tutorial

7. find and disable the app


#


GCP app engine hello world tutorial

view the app




#



GCP app engine hello world tutorial

disable the app


#




#



