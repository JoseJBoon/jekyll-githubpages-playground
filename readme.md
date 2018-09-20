## Github pages w/ blank jekyll:

1. Create Jekyll

```bash
jekyll new site-name --blank
cd site-name
```

2. Add GEMFILE

```
#GEMFILE
source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins
```

3. Execute bundle

```bash
bundle install
```

4. Add _config.yml

```yml
title: Project-name
baseurl: "/site-name"
theme: minima
```

5. Git actions

Make sure your are within the project folder
```bash
git init
```

```
# .gitignore
_site
.sass-cache
.jekyll-metadata
```

```bash
git add .
git commit -m 'init commit'
```

If not done yet create a remote repository on github and add the remote.

```bash
git remote add origin https://github.com/username/site-name.git
git push -u origin master
```

6. Activate Github pages through the settings.

7. Goto: https://username.github.io/repository-name/



