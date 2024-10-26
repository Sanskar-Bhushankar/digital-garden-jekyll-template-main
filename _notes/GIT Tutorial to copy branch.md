
##  Step1 : first create a empty folder in desktop and open gitbash in the folder

fir git clone the repo

```
git clone https://github.com/bmentor0321/OptiPrice_Prognosticator_Infosys_Internship_Oct2024.git
```

## Step 2 : then go to to repo folder created inside that empyt folder

```
 cd OptiPrice_Prognosticator_Infosys_Internship_Oct2024
```

or go manually inside the folder and open gitbash there

## Step 3 : then to find out number of branches that repo has do

`git branch -a`

Now the main branch is made by vishal so we checkout vishal 
```
 git checkout vishal
```


## Step 4: then create out branch of any name
```
git checkout -b test1sanskar
```

## Step 5 : then copy vishals branch's content with our branch 

```
git fetch origin
```
then merge
```
git merge origin/vishal
```


## Step 6 : then publish our branch onto github
```
 git push origin test1sanskar
```
