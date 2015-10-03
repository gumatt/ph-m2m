# Powerhouse Mark-to-Market Project

## Environment Description

This project is being developed to deploy to Heroku using Mongodb on MongoLab.  Development (_dev_) will be done on a 
local development box.  Stage (_stage_) will be on Heroku; and, eventually, Production (_prod_) will be on Heroku. 

There is a gitHub repository for this project at [https://github.com/gumatt/ph-m2m.git](https://github.com/gumatt/ph-m2m.git)

My idiosyncratic configuration:

##### from heroku CLI
```
heroku create --remote stage 
Creating warm-fortress-6041... done, stack is cedar-14
https://warm-fortress-6041.herokuapp.com/ | https://git.heroku.com/warm-fortress-6041.git

git remote add stage git@heroku.com:warm-fortress-6041.git
git remote add origin https://github.com/ph-m2m.git
```