# BUILDING DJANGO NEWSMAGAZINE MULTIAUTHOR NEWS247
https://github.com/gurnitha/2024-dj-newsmag-multiauthor-news247

## 1. SETUP

#### 1. Initial commit

        new file:   .gitignore
        new file:   README.md

#### 2. Modified .gitignore file

        modified:   .gitignore
        modified:   README.md

#### 3. Create remote repository Github and push local repository to it

        modified:   README.md
        https://github.com/gurnitha/2024-dj-newsmag-multiauthor-news247


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