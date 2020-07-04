# Collaboration Guide for Beginners

![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)
[![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)](https://www.firsttimersonly.com/)
[![HitCount](http://hits.dwyl.io/udit-001/Collaboration-For-Beginners.svg)](http://hits.dwyl.io/udit-001/Collaboration-For-Beginners)



Learning to collaborate can be difficult for the first time contributors, and it may seem tedious to find open source projects to contribute to without adequate knowledge of programming. But fear not, this project is made especially to ease the process of contributing to an open source project for a newcomer. You can learn to contribute to open source projects by contributing to this project, and you wouldn't require any programming knowledge at all, to contribute to this.

>Check out other awesome contributors of this project [here.](https://udit-001.github.io/Collaboration-For-Beginners/Contributors)

Here are the steps to make contributions by making your first successful pull requests:

1. Star this repository
2. Fork this repository.

![Fork & Star the Repository](https://raw.githubusercontent.com/udit-001/Collaboration-For-Beginners/master/img/fork.jpg)

3. Clone the fork you just created on your computer.

![Clone this repository](https://raw.githubusercontent.com/udit-001/Collaboration-For-Beginners/master/img/clone.jpg)

Type the following command on Git bash console:
```git
git clone https://github.com/udit-001/Collaboration-For-Beginners.git
```

Replace the above git repo link with that of the fork you just created.

4. Now before making changes to the files, let's take a different route than the usual tutorials you see on the internet, and let's try to do this in an efficient manner. 

For that, first go to your terminal under the repo you just cloned, run:

```git
git checkout -b add-my-name
```

By running the above command, you just created a new branch called `add-my-name` and checked it out, what this does is that it creates a new branch with the commit history of the master branch or the branch that you were on previously.

5. Now open `Contributors.md` and enter the details in the following format.

```
#### Name: [YOUR NAME](GitHub Link)
- Place: City, Country
- Bio: Who are you?
- GitHub: [Your Name](GitHub Link)
```

6. Enter the following commands into your `terminal`:
```git
git add .
git commit -m "Added myself to Contributors.md"
git push origin add-my-name
```

This will create a new commit with the changes you made in the `Contributors.md` file. Then we pushed these updates on the `add-my-name` branch of your fork.

7. Now create a pull request and add the title as `"Added myself to Contributors.md"`

![Create a Pull Request](https://raw.githubusercontent.com/udit-001/Collaboration-For-Beginners/master/img/PR.jpg)

7. Sit back and relax while your pull request is being reviewed and merged.

## Reference Links

- Syncing a Fork : [https://help.github.com/articles/syncing-a-fork/](https://help.github.com/articles/syncing-a-fork/)
- Merging an upstream repository into your fork : [https://help.github.com/articles/merging-an-upstream-repository-into-your-fork/](https://help.github.com/articles/merging-an-upstream-repository-into-your-fork/)
- Configuring a Remote for a Fork : [https://help.github.com/articles/configuring-a-remote-for-a-fork/](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
- Collaborating with Issues and Pull Requests : [https://help.github.com/categories/collaborating-with-issues-and-pull-requests/](https://help.github.com/categories/collaborating-with-issues-and-pull-requests/)

## Further Instructions to Proceed from here
- [Open Source Guide](https://opensource.guide/)
- [First Contributions](https://github.com/Roshanjossey/first-contributions)
- [Hacktoberfest](https://github.com/AliceWonderland/hacktoberfest)

## How To Choose a License
GitHub License Explained : [https://choosealicense.com](https://choosealicense.com)
