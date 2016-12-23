---
layout: post
title:  "Use Materialbox in the Carousel"
date:   2016-10-29 16:26:30 -0700
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

<div class="carousel">
  <a class="carousel-item" href="#one!"><img class="materialboxed" src="http://lorempixel.com/250/250/nature/1"></a>
  <a class="carousel-item" href="#two!"><img class="materialboxed" src="http://lorempixel.com/250/250/nature/2"></a>
  <a class="carousel-item" href="#three!"><img class="materialboxed" src="http://lorempixel.com/250/250/nature/3"></a>
  <a class="carousel-item" href="#four!"><img class="materialboxed" src="http://lorempixel.com/250/250/nature/4"></a>
  <a class="carousel-item" href="#five!"><img class="materialboxed" src="http://lorempixel.com/250/250/nature/5"></a>
</div>




Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/


<!-- Custom Javascript -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.8/js/materialize.min.js"></script>
<script type="text/javascript">
  (function($){
    $(function(){
      $('.carousel').carousel({
        dist: 0,
        padding: 10
      });
    }); // end of document ready
  })(jQuery); // end of jQuery name space
</script>
