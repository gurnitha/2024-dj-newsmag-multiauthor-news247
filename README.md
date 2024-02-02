# BUILDING DJANGO NEWSMAGAZINE MULTIAUTHOR NEWS247
https://github.com/gurnitha/2024-dj-newsmag-multiauthor-news247

## 1. SETUP

#### 1. Initial commit

        new file:   .gitignore
        new file:   README.md

        E:\_WORKSPACE\2024\django\BLOG-MULTI-AUTHOR\2024-dj-newsmag-multiauthor-news247
        λ git init
        λ git add .
        λ git status
        On branch master

        No commits yet

        Changes to be committed:
          (use "git rm --cached <file>..." to unstage)
                new file:   .gitignore
                new file:   README.md
        λ git commit -am "1. Initial commit"
        [master (root-commit) 12762ce] 1. Initial commit
         2 files changed, 10 insertions(+)
         create mode 100644 .gitignore
         create mode 100644 README.md

#### 2. Modified .gitignore file

        modified:   .gitignore
        modified:   README.md

#### 3. Create remote repository Github and push local repository to it

        modified:   README.md
        https://github.com/gurnitha/2024-dj-newsmag-multiauthor-news247

        (dj-newsmag) λ git commit -am "3. Create remote repository Github and push local repository to it"
        [master a59efa5] 3. Create remote repository Github and push local repository to it
         1 file changed, 6 insertions(+), 1 deletion(-)
        (dj-newsmag) λ git remote add origin git@github.com:gurnitha/2024-dj-newsmag-multiauthor-news247.git
        (dj-newsmag) λ git branch -M main


## 2. CREATE DJANGO PROJECT AND APPS

#### 1. Membuat lingkungan virtual

        modified:   README.md
        (dj-newsmag) λ python -m venv venv312501 --prompt dj-multiauthor

#### 2. Mengaktifkan venv312501

        modified:   README.md
        (dj-newsmag) λ venv312501\Scripts\activate.bat

#### 3. Menginstal Django versi 5.0.1

        (dj-multiauthor) λ pip install django==5.0.1
        Collecting django==5.0.1
        ...
        Successfully installed asgiref-3.7.2 django-5.0.1 sqlparse-0.4.4 tzdata-2023.4

        [notice] A new release of pip is available: 23.2.1 -> 23.3.2
        [notice] To update, run: python.exe -m pip install --upgrade pip

#### 4. Meng-upgrade pip

        (dj-multiauthor) λ python.exe -m pip install --upgrade pip
        ...
        Successfully installed pip-23.3.2