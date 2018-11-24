<head>
  <!-- Favicon -->
  <link rel="shortcut icon" href="../../favicon.ico">
  <!-- Emojis -->
  <link href="https://afeld.github.io/emoji-css/emoji.css" rel="stylesheet">
  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=UA-129370470-1"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'UA-129370470-1');
  </script>
</head>

<!-- Main Links -->
#### [Home](../../README.md) | [Blog](../main.md) | [Archives](../../archives.md) | [Music](../../music/main.md) | [Art](../../art/main.md) | [Contributors](../../contributors.md) | [Upload](../../upload.md)

- - -

## [<span style="text-decoration: underline; color: #fff;">Blog</span>](../main.md)

- - -

### [How To Push Existing Github](./view.md)

<h4>
  Date: <a href="#">October 7, 2018</a>
  <br />
  Author: <a href="#">Ninté Null</a>
</h4>

This is part **2** of a series I began with [this post](https://poetrique.github.io/blog/09-03-2018_how-poetry-taught-me-to-use-github/view.html). Here, I will be explaining how to push existing code to a new and empty Github repository.

<blockquote>
  "Coding is a beautiful thing. Anyone can learn to code!"
  <br />
  ~ @Usheninte
</blockquote>

#### What you need to do:

* Copy the `HTTPS` link provided.
<img src="http://res.cloudinary.com/poetrique/image/upload/c_scale,w_700/v1536217259/allbuy-i-ng/gallery/github-example.png" />

* Run `git init` in the terminal. This will initialize the folder/repository that you have on your local computer system.

* Run `git add .` in the terminal. This will track any changes made to the folder on your system, since the last commit. As this is the first time you are committing the contents of the folder, it will add everything.

* Run `git commit -m"insert Message here"`. This will prepare the added/tracked changes to the folder on your system for pushing to Github. Here, **_insert Message here_** can be replaced with any relevant commit message of your choice.

* Run `git remote add origin https://github.com/Usheninte/example.git` in the terminal. Here, **_Usheninte_** and **_example_** will be replaced by the values provided in the copied link. This will push the existing folder on you local computer system, to the **newly created** Github repository.

* Run `git remote -v`. This does some **_git pull_** and **_git push_** magic, to ensure that the contents of your new Github repository, and the folder on you local system are the same.

* Run `git push origin master`. Note that the last word in the command **_master_**, is not a fixed entry when running `git push`. It can be replaced with any relevant "branch_name".


##### Note
This is just _Part 2_ in a series. Please reach out, if I have made any error, or if there is any part of this article I could have explained better. My email is at the footer of this page. Thanks! **Code In Peace**

- - -

#### [Back to Blog](../main.md)