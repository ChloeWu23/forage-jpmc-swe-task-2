# JPMC Task 2
## Set Up: 

1. fork and clone the starter repo
2. create virtual enviroment:

 * create: `python3 -m venv env`
 * activate: `source env/bin/activate`

3. install all dependencies: listed in requirement.txt `pip install -r datafeed/requirements.txt`

4. Working with JS and Python: 
* check node version `node -v` ; nvm can be used to correct version

* intall dependencies with npm: `npm install`

5. Start the python server: run from  the root of project repo: `python datafeed/server3.py`

6. start the client: `npm start`



## Create patch files:
    * single commit: `git format-patch -1 HEAD`
    * multiple commit: `git format-patch -4 --stdout > multi_commit.patch`


## Update Graph Automatically
