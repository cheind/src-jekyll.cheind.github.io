Install WSL / Ubuntu https://docs.microsoft.com/en-us/windows/wsl/install
```
$ sudo apt-get update -y && sudo apt-get upgrade -y
$ sudo apt-get install ruby-full
$ sudo gem update --system
$ sudo apt-get install build-essential --no-install-recommends
$ sudo apt-get install libmagickcore-dev
$ sudo gem install jekyll bundler
```
Then 
```
$ cd <your-repo-name>
$ sudo bundle install
$ sudo bundle exec jekyll serve --livereload --unpublished --incremental
```
Issues?
```
rm -r .site .jekyll-cache
```
