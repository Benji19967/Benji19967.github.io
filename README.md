# Personal website

## Previewing locally

- https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll

### Install Jekyll

- https://jekyllrb.com/docs/installation/macos/

```bash
brew install chruby ruby-install xz
ruby-install ruby-3.1.3
echo 'export PATH="${HOME}/.rubies/ruby-3.1.3/bin:$PATH"' >> ~/.zprofile
# restart terminal or source ~/.zprofile
which ruby
# ${HOME}/.rubies/ruby-3.1.3/bin/ruby
gem install jekyll
```

### Server website using Jekyll

```bash
jekyll serve
```
