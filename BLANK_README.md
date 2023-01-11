
<!-- ABOUT THE PROJECT -->
## About Git for beginners 

[![Product Name Screen Shot][product-screenshot]](https://example.com)

I will  explain to you what a developper needs as basic Git commands.


### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

### Git config

* git config username

This is an example of how to list things you need to use the software and how to install them.
  ```
  git config –global user.name <votre_nom_d''utilisateur>
  ```


* git config email

  ```
  git config –global user.email <votre_adresse_email>
  ```


### Git init

```
git init <le_nom_de_votre_repo_git>
```

### Git clone 

```
git clone <url_du_depot_git>
```

### Git add

```
git add <nom_du_ou_des_fichier(s)>
```
To add all file to stage you need to run thoses commands 
```
git add *
```
* or
```
git add .
```

### Git commit

```
git commit -m <votre_message_de_commit>
```
Tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected

```
git commit -a
```

### Git diff

Show changes between commits, commit and working tree, etc of files wich are not yet staged. 

```
git diff 
```
or for staged files.

```
git diff –staged
```
### Git diff deux branches

In order to compare two branches easily, you have to use the “git diff” command and provide the branch names separated by dots.

```
git diff <branche_une> <branche_deux>
```
### git reset

The git reset command is a complex and versatile tool for undoing changes. It has three primary forms of invocation. These forms correspond to command line arguments --soft, --mixed, --hard. The three arguments each correspond to Git's three internal state management mechanism's, The Commit Tree (HEAD), The Staging Index, and The Working Directory.
Basically to  remove the staging file, but preserve its contents.

<img src="images/reset.png"  width="80" height="40>

```
git reset <fichier>
```

