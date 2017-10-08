---
layout: post
title:  "Welcome to Jekyll!"
date:   2017-10-08 15:12:29 +0300
categories: tech github jekyll blog
---
#H1
The Idiot's Guide to Github Pages with Jekyll for custom site names
1. jekyll new \<blogname\>. inside that folder, create a folder "docs"
2. jekyll build --destination ./docs 
3. initiate it as a repository 
4. add Gemfile and Gemfile.lock to gitignore. Add all. commit. push.
5. in Github settings, point github pages to docs


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
