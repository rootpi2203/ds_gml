# Machine Learning Mini-Challenges FS 2022 

Mini-Challenges for gml FS 2022.


## Set up the ML Trainingcenter

Use the instructions in the
[gml Trainingcenter Repo](https://gitlab.fhnw.ch/ml/courses/gml/gml_trainingcenter) 
to set up the gml Trainingcenter.


## Set up Mini-Challenges Repo locally

### Fork this repository

Fork this repository to your own user space by pressing the fork button on the
upper right.  

Add @michael.graber as **Maintainer** to your fork. Otherwise I won't be able to
see your submissions and they will be considered as **not handed in.**

### Clone your fork to your computer. 

In your fork on GitLab find the address with which you can clone your Repo on
the upper right. Clone into your ml directory (`MY_ML_DIR`, see ML
Trainingcenter Repo) using:

```
$ git clone MY_REPO_FORK
```

Now you'll find this Mini-Challenges Repo in your ML Trainingcenter
JupyterLab-Container.

You can now edit files in the clone of your fork on your local machine.


## Submitting assignments

Whenever you want to upload something to your Repo on GitLab you need to
'commit' and 'push' it:

```
# commit MY_FILE
$ git commit MY_FILE -m 'my commit message'

# push all commits to the server
$ git push
```

**By pushing your commits to your personal fork on GitLab you will submit the Mini-Challenges!**

Your last commit before the deadline will be your submission.


## Fetching new assignments

If you want to fetch new assignments from the main repo do as follows:

```
# add original repo as remote upstream 
$ git remote add upstream git@gitlab.fhnw.ch:ml/courses/gml/gml_minichallenges_fs2022.git 

# now whenever you want to merge the changes from the remote upstream repo, ie
# the one you forked from, you can do:
$ git pull upstream main
```

.. and add some merge message.
