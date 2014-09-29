---
layout: post
title: "Just setting up my Octo."
date: 2014-09-29 16:39:35 +0200
comments: true
categories: 
---

# Use Gosu

Actually, I am only using this to show code embedding, and `Gosu.rb` was the only Ruby file I had lying around. Text.

{% highlight ruby linenos %}
require 'rubygems' # only necessary in Ruby 1.8
require 'gosu'
action!

class MyWindow < Gosu::Window
  def initialize
   super(640, 480, false)
   self.caption = 'Hello World!'
  end
end

window = MyWindow.new
window.show

{% endhighlight %}

Here be text.