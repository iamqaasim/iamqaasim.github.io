
# Github Pages
Github offers free hosting for static website

see https://docs.github.com/en/pages to learn more

# Quick Start

## Clone repo

You need 3 things:
- PAT (personal access token): To gain access to your repo
- Github_username: In my case its "iamqaasim"
- name_of_repo: In my case i gave it the same name as my username


```bash
  git clone https://PAT@github.com/github_username/name_of_repo.github.io
```
    
## Enter repo

Once you enter the repo you need to add your static sites HTML, CSS and/ JS files. For simplicity sake you can use the following command for testing


```bash
  echo "Hello World" > index.html
```

## Push changes and visit site

After you pushed your chnages to github everything should work (it takes a while for changes to take effect). To visit you site simply visit "name_of_repo.github.io." (dont forget the full stop at the end)

in my case the site would be "https://iamqaasim.github.io."
