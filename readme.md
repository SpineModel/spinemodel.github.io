https://idratherbewriting.com/documentation-theme-jekyll/

# Use Bundler to install all the needed Ruby gems:
bundle update

# use this command to build & serve Jekyll:
bundle exec jekyll serve


# On a new machine without Ruby
curl -L https://get.rvm.io | bash -s stable  # get RVM
rvm install ruby-[version]						# install desired ruby v (eg 2.6.3)
rvm --default use 2.6.3							# if you want to
