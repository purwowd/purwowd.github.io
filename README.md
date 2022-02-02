# My simple notes

```bash
# Install rbenv
$ git clone https://github.com/rbenv/rbenv.git ~/.rbenv
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
$ echo 'eval "$(rbenv init -)"' >> ~/.zshrc
$ exec $SHELL

# Install ruby-build
$ git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
$ echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.zshrc
$ exec $SHELL

# Install ruby v2.4.0 with rbenv
$ rbenv install 2.4.0
$ rbenv global 2.4.0
$ ruby -v

# If you get an error when installing `ruby v2.4.0` or install WSL2 (Ubuntu 20.04 LTS)
$ RUBY_CFLAGS=-DUSE_FFI_CLOSURE_ALLOC rbenv install 2.4.0
$ rbenv global 2.4.0
$ ruby -v

# Install the dependencies
$ git clone https://github.com/purwowd/purwowd.github.io.git
$ cd purwowd.github.io/
$ bundle install

# Run app
$ bundle exec jekyll serve
```
