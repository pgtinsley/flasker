# Flasker - SG2 through Flask

git clone
cd flasker 
conda env create -f flasker\_environment.yml

### To spin up the flask server:
cd stylegan2-ada/
flask run

### To ping endpoint and return encoding:
python test\_post.py

You can change image in test\_post.py... might add as argument/parameters if necessary.

Also, the projector only uses 250 steps currently, instead of default 1000; this is faster and usually gets the job done.

Happy encoding! 

