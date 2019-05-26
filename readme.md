https://idratherbewriting.com/documentation-theme-jekyll/

# Use Bundler to install all the needed Ruby gems:
bundle update

# use this command to build & serve Jekyll:
bundle exec jekyll serve


# On a new machine without Ruby
curl -L https://get.rvm.io | bash -s stable  # get RVM
rvm install ruby-[version]						# install desired ruby v (eg 2.6.3)
rvm --default use 2.6.3							# if you want to


{% include image.html file="jekyll.png" url="http://jekyllrb.com" alt="Jekyll" caption="This is a sample caption" %}

<img style="float: right; border: 30px solid white" src="Images/InTheWild/jo_perold.png">


| Level | Description |
|-------|--------|
| **Needs** |  |
| **Values** |  |
| **Principles** |  |
| **Practices** |  |
| **Tools** |  |


{% include note.html content="This is my note." %}
{% include tip.html content="This is my tip." %}
{% include warning.html content="This is my warning." %}
{% include important.html content="This is my important info." %}

{% include callout.html content="This is my **danger** type callout. It has a border on the left whose color you define by passing a type parameter." type="danger" %}

{% include callout.html content="This is my **default** type callout. It has a border on the left whose color you define by passing a type parameter." type="default" %}

{% include callout.html content="This is my **primary** type callout. It has a border on the left whose color you define by passing a type parameter." type="primary" %}

{% include callout.html content="This is my **success** type callout. It has a border on the left whose color you define by passing a type parameter." type="success" %}

{% include callout.html content="This is my **info** type callout. It has a border on the left whose color you define by passing a type parameter." type="info" %}

{% include callout.html content="This is my **warning** type callout. It has a border on the left whose color you define by passing a type parameter." type="warning" %}
