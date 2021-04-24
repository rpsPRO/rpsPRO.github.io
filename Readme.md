# MARKDOWN 

## Command line instructions

You can also upload existing files from your computer using the instructions below.
Git global setup

```bash
git config --global user.name "Juan Gualberto"
git config --global user.email "jgutierrez@iesvirgendelcarmen.com"
```

Create a new repository:

```bash
git clone https://gitlab.iesvirgendelcarmen.com/juangu/tecnoweb_profesor.git
cd tecnoweb_profesor
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

Push an existing folder:

```bash
cd existing_folder
git init
git remote add origin https://gitlab.iesvirgendelcarmen.com/juangu/tecnoweb_profesor.git
git add .
git commit -m "Initial commit"
git push -u origin master
```

Push an existing Git repository:

```bash
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.iesvirgendelcarmen.com/juangu/tecnoweb_profesor.git
git push -u origin --all
git push -u origin --tags
```

```css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```#   r e s u m e n t e m a 5  
 