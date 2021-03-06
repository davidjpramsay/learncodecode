
# Learn Code Code

> David Ramsay

## System Setup

![](https://raw.githubusercontent.com/davidjpramsay/learncodecode/master/images/zorin-logomark-blue.png =65x)
[Zorin OS](https://zorin.com/os/)


### Git & GitHub

#### Install Git
1.	Install
	```bash
	apt install git
	```
1.	Setting your Git username for _every_ repository on your computer
	```bash
	git config --global user.name "davidjpramsay"
	```

1.	Setting your commit email address in Git
	```bash
	git config --global user.email "david.jp.ramsay@me.com"
	```
#### Connect to GitHub

1.	Generate a new SSH key
	```bash
	ssh-keygen -t ed25519 -C "david.jp.ramsay@me.com"
	```

2.	Start the ssh-agent in the background.
	```bash
	eval "$(ssh-agent -s)"
	```
3.	Add your SSH private key to the ssh-agent
	```bash
	ssh-add ~/.ssh/id_ed25519
	```
4.	Add public SSH to GitHub in the account settings menu.

5.	Clone  a repository on GitHub locally.
	```bash
	git clone git@github.com:davidjpramsay/learncodecode.git
	```

#### Using Git

1.	Add & Commit
	You can propose changes (add it to the **Index**) using  
	```bash
	git add <filename>
	```
	or
	```bash
	git add *
	```  
	To commit these changes use  
	```bash
	git commit -m "Commit message"
	```
	Now the file is committed to the **HEAD**, but not in your remote repository yet.

2.	Pushing Changes
	Your changes are now in the **HEAD** of your local working copy. To send those changes to your remote repository, execute
	```bash
	git push origin master
	```
3.	Check status.
	```bash
	git status

4. Pull remote changes to local.

	```bash
	git pull
	```


### Miniconda

#### Install Miniconda

1.	Download [Miniconda](https://docs.conda.io/en/latest/miniconda.html#linux-installers)

2.	Bash the installer
	```bash
	bash Miniconda3-latest-Linux-x86_64.sh
	```
	
3.	Update
	```bash
	conda update conda
	```

#### Managing Environments

1.	Create a new environment.
	```bash
	conda create --name my_enviroment_name
	```
2.	Activate environment
	```bash
	source activate my_enviroment_name
	```
3.	List all environments
	```bash
	conda info --envs
	```
4.	Change back to base.
	```bash
	conda activate
	```
5.	Install packages.
	```bash
	conda install python numpy pandas jupyterlab
	```
6.	List packages in environment.
	```bash
	conda list
	```
7.	Delete environment.
	```bash
	conda remove --name my_environment_name --all
	```

### Jupyter

1.	Launch JupyterLab
	```bash
	jupyter-lab
	```

## Documentation

### Git Page
https://davidjpramsay.github.io/learncodecode/

### Git Repository
https://github.com/davidjpramsay/learncodecode

### Process

The markdown file [Learn Code Code.md](https://github.com/davidjpramsay/learncodecode/blob/master/Learn%20Code%20Code.md) and [index.html](https://github.com/davidjpramsay/learncodecode/blob/master/index.html) are written with StackEdit.

*Note: There is currently an error with StackEdit authenticating with GitHub work around posted here:* https://github.com/benweet/stackedit/issues/1755



## Terminal Commands

### Delete folder and sub-folders without asking.

```bash
rm -rf "folder_name"
```


## Learn Python

1.	[Learn Python - Full Course for Beginners [Tutorial]](https://www.youtube.com/watch?v=rfscVS0vtbw&t=0s)
2.	[Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)

## Pandas Course

1. [Daniel Chen: Cleaning and Tidying Data in Pandas](https://www.youtube.com/watch?v=iYie42M1ZyU&t=853s)

## SwiftUI

1. [Apple - SwiftUI Essentials](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation)
1. [2021 SwiftUI Tutorial for Beginners](https://www.youtube.com/watch?v=F2ojC6TNwws&t=6859s)
1. [Paths vs shapes in SwiftUI](https://www.youtube.com/watch?v=xTRhYKjp5nk)
## ML Courses

1.	[Coursera - Machine Learning](https://www.coursera.org/learn/machine-learning)
2.	[Coursera - Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)
3.	[Practical Deep Learning for Coders](https://course.fast.ai/)
4.	[Part 2: Deep Learning from the Foundations](https://course19.fast.ai/part2)

## Resources

1.	[arXiv](https://arxiv.org/)
3.	[Mathematics for Machine Learning](https://mml-book.github.io/book/mml-book.pdf)
4.	[Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
5.	[Deep Learning](https://www.deeplearningbook.org/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNTE3NzY3MTgsLTE2NTQwMDM4MjksMT
UzNzU2NzEyNCwtMTk1NDc2NTYwOSw2OTIyNjQwNjksLTE1OTY2
OTMwODAsLTE4MjUxMzI5MjEsLTQwMjIzODY3NiwtNjc0MzE1OD
IxLC0xOTE5NTc2ODk3LC0xOTE5NTc2ODk3LDE2NzU1NzUwOTAs
LTY1OTk2OTc2MCwtMjczNDcxNzcsLTE1NTE1NjU5NTYsLTIwMT
YyMTYyMjgsMTg0MTcyMjA3OCwxMDU0ODIyMDIyLC05MTkxNjY0
NzgsLTIyNTYzNzI2Nl19
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU0MTUwODQ4MCwxMDI4NDU3MDQ1LDE1MT
I2MDA4MCwtMTA2MDA4NjEzNCwtMTE4MDAyNzc5XX0=
-->