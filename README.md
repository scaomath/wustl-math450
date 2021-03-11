# Math 450 Optimization Methods in Machine Learning at WUSTL
Browsing every coding lecture's notebook on github you will see a button of running it in Google Colab cloud. 

## Tentative material
[https://scaomath.github.io/teaching/sp2021-math450](https://scaomath.github.io/teaching/sp2021-math450)

## Primer on Python 3
[https://www.kaggle.com/learn/python](https://www.kaggle.com/learn/python)

## Structure of this repo
```bash
├── Homework
│   ├── imports needed
│  
├── Lectures
│   ├── notebooks for lecture

```

## How to keep your local copy up-to-date
First use either terminal on Mac or Windows powershell to navigate to the folder of your current copy of this repo
then do the following
```bash
git remote add upstream git://github.com/scaomath/wustl-math450.git
git fetch upstream
```
The git will tell your there is new upstream. Now do 
```bash
git pull --rebase upstream master
```
This will keep the version history even for your edited local copies.
