# GCP-AppEngine-HelloWorld
Quick demo video of a hello world tutorial for Google Cloud Platform's AppEngine 

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

> Hello everyone this is steve. Thank you for watching my video. This week i really enjoyed working in Geewax chapter 11. Their coded examples do an excellent job with Google App Engine, but after the intense detail I wanted some simpler takeaways ... 

**Demo Video 3**  
### Google App Engine   

**Steve Depp**  
**MSDS 434 section 55**   

**Geewax Chapter 11**  
- [x] standard / flex  
- [x] applications, services, versions  
- [x] deploying, scaling  

#

> ... which i found in a google tutorial attached to the Cloud Console.  In 7 steps, this quickstart ...

### GCP app engine hello world tutorial  

**App Engine Quickstart**  
Deploy a sample application to App Engine using the gcloud command  

https://cloud.google.com/appengine/docs/standard/python3/quickstart

<img width="257" alt="App Engine Quickstart" src="https://user-images.githubusercontent.com/38410965/113491408-92964f80-949e-11eb-932b-fc19a32fa8c7.png">

#

> ... asks us to pick a language,  

### GCP app engine hello world tutorial    

**1. decide on a language**    

<img width="273" alt="Hello World" src="https://user-images.githubusercontent.com/38410965/113491812-86f85800-94a1-11eb-89e8-f1cc13834556.png">

<img width="277" alt="Hello World" src="https://user-images.githubusercontent.com/38410965/113491816-89f34880-94a1-11eb-8c7c-0ea9c11011f6.png">

#

> ... make a project,  

### GCP app engine hello world tutorial  

**2. make a project**  

- [x] gcloud projects describe PROJECT_ID  
- [x] gcloud projects list  
- [x] gcloud alpha projects update PROJECT_ID --name=NAME  
- [x] gcloud projects delete PROJECT_ID  
- [x] gcloud projects undelete PROJECT_ID  

<img width="251" alt="Project setup" src="https://user-images.githubusercontent.com/38410965/113491839-a7c0ad80-94a1-11eb-99c5-2922ee861580.png">

#

> ... gather and ...


### GCP app engine hello world tutorial  

**3. gather code**  

<img width="257" alt="Tutorial" src="https://user-images.githubusercontent.com/38410965/113491853-bb6c1400-94a1-11eb-806c-01540eff848f.png">

#

> ... examine code, 

### GCP app engine hello world tutorial  

**4. examine the code**  

<img width="259" alt="Tutorial" src="https://user-images.githubusercontent.com/38410965/113491861-c9ba3000-94a1-11eb-9cf7-8fa394023a13.png">

#

> [pause]  

### GCP app engine hello world tutorial  

**gather and examine code**  
- [x] `git clone`  
- [x] `cat main.py`  
- [x] `cat app.yaml`    

<img width="682" alt="gcp _tutorial git clone" src="https://user-images.githubusercontent.com/38410965/113491873-e8b8c200-94a1-11eb-8d67-c59bf40be539.png">

#

> ... build and test the app locally, ...  

### GCP app engine hello world tutorial  

**5. build and test the app locally**    

<img width="255" alt="Testing your app" src="https://user-images.githubusercontent.com/38410965/113491883-fcfcbf00-94a1-11eb-80ea-099313d6cba8.png">

#

> [pause]  

### GCP app engine hello world tutorial  

**build and test locally:**  
- [x] `python3 -m venv ~/envs/hello_world`  
- [x] `source ~/envs/hello_world/bin/activate`  
- [x] `pip install -r requirements.txt`  
- [x] `python main.py`  

<img width="682" alt="hello world" src="https://user-images.githubusercontent.com/38410965/113491893-1140bc00-94a2-11eb-83a8-7b23f4ab30e2.png">

#

> ... and look at the results.   

### GCP app engine hello world tutorial  

**local results**  
- [x] `curl http://127.0.0.1:0000/`  
- [x] plug and play in browser  

<img width="682" alt="stevedepp" src="https://user-images.githubusercontent.com/38410965/113491905-274e7c80-94a2-11eb-9544-1b9438250a20.png">

<img width="317" alt="127 0 0 18080" src="https://user-images.githubusercontent.com/38410965/113491909-2a496d00-94a2-11eb-9e9e-d4e05fb63e3f.png">  

#

> Then, we simply create and deploy the app, ... 

### GCP app engine hello world tutorial  

**6. create and deploy app to GAE standard —> results**  

<img width="257" alt="Deploying to App Engine" src="https://user-images.githubusercontent.com/38410965/113491917-39c8b600-94a2-11eb-994f-b4eb5c0b6945.png">

#

> [pause]  

### GCP app engine hello world tutorial  

**create and deploy app to GAE standard**  
- [x] `gcloud app create —project depp-gcp-training-20201002`  
- [x] `gcloud app deploy app.yaml --project depp-gcp-training-20201002`  

<img width="682" alt="cannot be changed  More information about regions 1" src="https://user-images.githubusercontent.com/38410965/113491924-45b47800-94a2-11eb-88a3-f6b4c1c67567.png">

#

> ... and wait to see the results.

### GCP app engine hello world tutorial  

**deploy —> results**   
- [x] `curl https://depp-gcp-training-20201002.ue.r.appspot.com`  
- [x] `gcloud app browse -project=depp-gcp-training-20201002`  

<img width="697" alt="Hello Workd!" src="https://user-images.githubusercontent.com/38410965/113491935-5cf36580-94a2-11eb-809d-2ae2f56e10f2.png">

<img width="682" alt="geload app logs tail -s default" src="https://user-images.githubusercontent.com/38410965/113491934-59f87500-94a2-11eb-9580-a860e763ee69.png">

#

> Finally, just find your app, ...

### GCP app engine hello world tutorial  

**7. find and disable the app**  

<img width="263" alt="Tutorial" src="https://user-images.githubusercontent.com/38410965/113491947-75fc1680-94a2-11eb-9ebd-757a1f2a2a73.png">

<img width="270" alt="Tutorial" src="https://user-images.githubusercontent.com/38410965/113491948-78f70700-94a2-11eb-8d3f-8b3babd24219.png">

#

> [pause]  

### GCP app engine hello world tutorial  

**view the app**  

<img width="1134" alt="Google Cloud Platform" src="https://user-images.githubusercontent.com/38410965/113491952-8613f600-94a2-11eb-83cd-643c44694f33.png">

#

> ... and disable it to save money

### GCP app engine hello world tutorial  

**disable the app**  

<img width="666" alt="Search products and r" src="https://user-images.githubusercontent.com/38410965/113491963-94faa880-94a2-11eb-9e28-987b3eb06776.png">

<img width="705" alt="Disable depp-gcp-training-20201002" src="https://user-images.githubusercontent.com/38410965/113491969-975d0280-94a2-11eb-8520-98e216c6ebb2.png">

> Thank you for watching. 

