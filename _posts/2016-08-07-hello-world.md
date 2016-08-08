---
layout: inner
position: right
title: 'CRM for Developers'
date: 2016-08-07 20:20:00
categories: development teamwork
tags: Teamwork
featured_image: 'http://i.imgur.com/bx0DMvv.jpg'
project_link: '/crm-for-developers'
button_icon: 'plane'
button_text: 'Read the post'
lead_text: 'When typing on a keyboard is like flying a jet'
permalink: crm-for-developers
---

Crew Resource Management (CRM) is a popular topic in aviation. It consists of the basic principles that hold a multi-crewed aircraft together during critical phases of flight.

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
