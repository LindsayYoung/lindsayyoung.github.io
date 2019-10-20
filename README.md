# GitHub pages site for [my resume site](https://lindsayyoung.github.io)

### Local set up
Dependencies
 - Ruby
 - RubyGems
 - GCC and Make
 
 See [Jekyll instlation docs](https://jekyllrb.com/docs/installation/) for details.

Update Ruby as needed. 
I use rbenv. I update rbenv, I list the ruby versions availale, pick the latest stable version for the install command and to set that version locally.
```
  rbenv install -l
  rbenv install <latest stable version>
  rbenv global <latest stable version>
  rbenv init
```
Install packages
```
  gem update --system 
  gem install
```
Run locally
```
  jekyll serve
```  
### Deployment

Push to the `master` branch via git.
