# Why this ?

You probably need to anyalize/monitor your linkedin network. I personally use this to have a better visualization of my network and run some data analysis on it. 
![graph](/images/graph.png)


# How to use

You have to setup your linkedin API key by creating an app into it
[Linkedin app settings](https://www.linkedin.com/secure/developer)
[Linkedin API documentation](https://developer.linkedin.com/)


```bash
git clone https://github.com/shubs/linkedin_to_neo4j.git
cd linkedin_to_neo4j

pip install oauth2
pip install simplejson
pip install py2neo

chmod +x import.py
Usage:	./import.py consumer_key consumer_secret oauth_token oauth_token_secret
```

You have to make sure that your Neo4j sever is started
[link to Neo4j Guide!](http://neo4j.com/developer/get-started/)


PS : This script is based on [rjbriody](https://github.com/rjbriody/linkedin-neo4j) work