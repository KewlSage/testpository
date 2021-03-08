# testpository
This shows you how to make your css file importable easily from github.

As seen above, there is a file callled demo.css, should it be imported in to discord your home icon will instead of its normal white, become black on hover or if the home icon is active.

you may think that `@import url("https://github.com/KewlSage/testpository/demo.css")` would work but that is not true, after all if you visit that link it will say not found.

To import this properly your repository must be public and you will need to use github pages, this however does NOT require that you have this in a user.github.io repository, nor does it reqire that you have one in the first place. You need only go to you repository settings and just above the dangerzone if your repository is public you will see a section by the name "GitHub Pages" and it should look like this.

![Hithub pages settings](https://user-images.githubusercontent.com/46802123/110390589-d62aa480-802b-11eb-9478-017b015ce701.png)

Under source you will select the branch of the repository you want to be use for github pages, main is my branch so now it looks like this.

![branch selection](https://user-images.githubusercontent.com/46802123/110390984-72ed4200-802c-11eb-9e71-659f5be8366c.png)

Leaving the second option as /root is what I will choose to do and that, once saved, will as shown below make it available at https://user.github.io/repo.

![image](https://user-images.githubusercontent.com/46802123/110391306-ebec9980-802c-11eb-8c6c-58f09268be01.png)

using that kind of link you will be able to import css successfully, for example you can use `@import url("https://kewlsage.github.io/testpository/demo.css")`
