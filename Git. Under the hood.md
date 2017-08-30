autoscale: true  
slidenumbers: true  
theme: Next, 3

# [fit] Git
# [fit] Under the Hood[^*]

<br/>

```swift
let author = "Konstantin Portnov"
let github = "github.com/x0000ff"
```

![inline 60%](./img/logo.png)

![right](./img/bear-cavalry.png)

[^*]: https://octodex.github.com/bear-cavalry

---

# ¿Git?

![inline 100%](./img/i-am-out.png)

---

![inline 140%](./img/xkcd-git.png)

---

# Hello, Empty World

![inline](./img/init-ls.png)

> Install tree command[^0]

[^0]: On Mac : http://bit.ly/2xKh0PX

---

# [fit] ".git"?

---

![left](./img/tree-left.png)
![right](./img/tree-right.png)

---

# `"config"` it is a...
# config 😮


![inline](./img/config.png)

---

# Captain Hook!


![inline](./img/hooks.png)

---

# 🙈🙉🙊

![inline](./img/exclude.png)

Explicit repository excludes[^1]

[^1]: http://bit.ly/1Poywz1

---

# `"HEAD"`

## It's simple text file!

![inline](./img/head.png)


---

# On `"master"`?


![inline](./img/status.png)

---

# But `"master" doesn't exist`
# Paradox!

![inline](./img/refs.png)

---

# " In the beginning was the Word..."

![inline](./img/echo.png)

---

![left](./img/tree-left-2.png)
![right](./img/tree-right-2.png)

---

# No one change! 😭

Because Git doesn't know about our file

---

# `"add"`

![inline](./img/git-add.png)

---

# `"add"`

![inline](./img/status-2.png)

---

![left](./img/tree-left-3.png)
![right](./img/tree-right-3.png)

---

# Who are you "9f" and "401348"?

![inline](./img/hash-god.png)

> Folder "9f" and file "401348f69b894744b309b1090ed6e05fa257f8"[^2]

[^2]: 10.2 Git Internals - Git Objects: http://bit.ly/2xK9Hb1

---

# But if we add another file with the same content?
# 🤔

---

## Hash doesn't depend of time, OS, localization and so on.
## 😬

---

# And inside we have...

![inline](./img/cat-file.png)

---

# Swiss knife "cat-file"

![inline](./img/cat-file-2.png)

---

# ¿Blob?

![inline](./img/blob.jpg)

> Blob: "an object, especially a large one,
> having no distinct shape or definition:"[^3]

[^3] Blob: http://bit.ly/2xKtirG

---

# Pfff... First commit...

![inline](./img/first-commit.png)

---

![left](./img/tree-left-4.png)
![right](./img/tree-right-4.png)

---

# 2 new Object? Why? 😮

![inline](./img/after-first-commit.png)

---

![inline](./img/first-commit-content.png)

---

![inline](./img/first-commit-content-2.png)

---

![inline](./img/first-commit-content-3.png)

---

# And what about `"master"`?

![inline](./img/cat-master.png)

---

# And all together

![inline](./img/first-commit-all-with-marks.png)

---

# And all together

![inline](./img/tree-left-5.png)

---

# And all together

![inline](./img/first-commit-scheme.png)

---

# Add more files

![inline](./img/second-commit-files.png)

---

![left](./img/tree-left-5.png)
![right](./img/tree-right-5.png)

---

# Who are you `"80b5f2"`?

![inline](./img/80b5f2.png)

---

# 2nd commit


![inline](./img/second-commit.png)

---

![left](./img/tree-left-6.png)
![right](./img/tree-right-6.png)

---

# And all together

![inline](./img/second-commit-scheme.png)

---

# Where am I ?

![inline](./img/source-tree.png)
![120% inline](./img/head-2.png)

---

# And how?

- 😱 Change HEAD of a branch?
- 🤔 Jump ("`checkout`") to another branch?
- 🙃 Edit manually a commit message?
- 😮 Edit manually a commit content?
- ...

---

# What next?

- Repeat all the steps
- `git` ...
    - `amend`
    - `reset`
    - `rebase`
- Pro Git: http://bit.ly/1MRoX7u
- This presentation: https://github.com/x0000ff/git-under-the-hood

---

# Questions? 🙂

![inline](./img/Brace-yourselves-For-a-few-questions.jpg)

---

# Thanks a lot!
# ¡Muchas gracias!
# ¡Moltes gràcies!
# Большое спасибо!

☺️

![30% right fit](./img/thanks.jpg)

---

# **Me...**

![right 50%](./img/me.jpeg)

- ![:inline:](./img/me.jpeg) Konstantin Portnov 

- ![:inline:](./img/favicon.ico) [http://about.me/x0000ff](http://about.me/x0000ff)

- ![:inline:](./img/github.png) [https://github.com/x0000ff](https://github.com/x0000ff)

- ![:inline:](./img/twitter.png) [https://twitter.com/x0000ff](https://twitter.com/x0000ff)

- ![:inline:](./img/linkedin.png) [https://www.linkedin.com/in/KonstantinPortnov](https://www.linkedin.com/in/KonstantinPortnov)

---

# This Presentation
# 🙂
# http://bit.ly/2vHPoJS

---

# EOF
# 🍻