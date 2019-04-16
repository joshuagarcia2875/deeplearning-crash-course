# deeplearning-crash-course

# Instructions
This instruction comes from [github help](https://help.github.com/en/articles/fork-a-repo)


# Getting started

1. Sign up for [github account](https://github.com)

![Github](assets/github-signup.png)

Just follow the instructions.

2. Open your terminal and configure your git.

```bash
$ git config --global user.name "Your FirstName LastName"
$ git config --global user.email "your_github_email@gmail.com"
```



3. In the top-right corner of this webpage, click Fork.

It should look like this

![alt-text](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Congratulations! You are able to fork this repo

4. Navigate to your fork repository

You know you are able to fork the repo when you see the ff:

![fork-2](assets/fork2.png)   

5. Clone your fork

Click on the `Clone or download` button, then copy the link

6. Open your terminal

7. type the `git clone` then paste the url. it should look like the ff:

```bash

$ git clone https://github.com/USERNAME/deeplearning-crash-course.git
```

8. Press `Enter`. You should see the ff:

```bash
$ git clone https://github.com/YOUR-USERNAME/deeplearning-crash-course.git
> Cloning into `deeplearning-crash-course`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```


9. Add the **original** repository

```bash
$ git remote add upstream https://github.com/johnanthonyjose/deeplearning-crash-course.git
```


10. Verify your #9

```bash
$ git remote -v
> origin    https://github.com/YOUR_USERNAME/deeplearning-crash-course.git (fetch)
> origin    https://github.com/YOUR_USERNAME/deeplearning-crash-course.git (push)
> upstream  https://github.com/johnanthonyjose/deeplearning-crash-course.git (fetch)
> upstream  https://github.com/johnanthonyjose/deeplearning-crash-course.git (push)
```

11. When you're done. Congratulations. Wait for my instructions.