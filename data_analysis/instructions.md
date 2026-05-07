# As an experimenter
- share your repo with your friends via the discussion forum: https://odtuclass2025s.metu.edu.tr/mod/forum/discuss.php?d=7531
- provide a short description and share the pavlovia or gitlab link for your experiment (make sure it is public)
- **NOTE** please do this before this friday (08.05 midnight), so that others can participate
# As a participant
1. go to the gitlab repo of the experiment
	- see: https://pavlovia.org/alaz/stroop_group and click "view code"
	- or if the direct link is shared use it: https://gitlab.pavlovia.org/alaz/stroop_group
	- fork the repo to your account (use the fork button at top-right)
2. go to your pavlovia account > dashboard > experiments > forked experiment
3. set status to "piloting", click "pilot" to run
4. complete the experiment and you should see that your responses are saved to a csv file
5. share the .csv file with your friend via their folder in: https://drive.google.com/drive/folders/1b_zX4o0qL-bFPA6psYLG80mau_RlAdra?usp=drive_link
6. **DEDLINE:** you should be finished with participating to your friends' experiments and share your data by the end of this saturday (09.05) midnight. please don't be late since your friends will analyze the data after you finish.
# Analysis
1. setup your environment
	- install vscode
	- install extensions (jupyter: for running the notebook, data wrangler: to preview dataframes)
	- install conda
		1. `conda create --name cogs508`
		2. `conda activate cogs508`
		3. `conda install python=3.12`
		4. `conda install -c conda-forge pandas`
		5. `conda install seaborn -c conda-forge`
		6. `pip install notebook`
		7. Select ipynotebook kernel (cogs508) from top-right.
2. reconsider your experimental design
	- which variables are dependent
	- which variables are independent
	- goal: visualize dependents in terms of independents' contrasts
	- see the `intro.ipynb` for an example
3. combine the dataset into a tidy format, based on the experimental design
	- see the `intro.ipynb`
	- see the paper: https://www.jstatsoft.org/article/view/v059i10 and the code in python: https://github.com/alazaydin/tidy-data/
	- save the tidy dataframe to a .csv (or any other format you like)
4. plot
	- use seaborn for easy plotting
	- make categorical (if applicable) contrasts or show the relation between your independent and dependent variables
	- write a short paragraph explaining your interpretation of the plots
	- BONUS: try to fit the data to a statistical model (e.g. linear regression, see the last section of tidy-data paper code notebook, or if you know statistical test apply them). if this is new to you we will consider this next week
5. share your results
	- open a github account
	- install git to your machine
	- initialize a git repo on the local folder
	- commit and push to the remote repo
	- share the link to your repo by replying to the forum where you first shared your experiment link
	- if you're unfamiliar with above steps you can also share your analysis folder through google drive (open a new folder under your name). it's strongly suggested to try using git first.
	- **DEDLINE:** next week before class (14.05 before noon (12:00PM))
