---
layout: post
category : lessons
tagline: "Adding Blog Posts in Jekyll"
tags : [intro, beginner, jekyll, tutorial]
---
{% include JB/setup %}

This Jekyll introduction will outline specifically  what Jekyll is and why you would want to use it.
Directly following the intro we'll learn exactly _how_ Jekyll does what it does.

## Overview

### What is Jekyll?

Jekyll is a parsing engine bundled as a ruby gem used to build static websites from
dynamic components such as templates, partials, liquid code, markdown, etc. Jekyll is known as "a simple, blog aware, static site generator".

### Examples

This website is created with Jekyll. [Other Jekyll websites](https://github.com/mojombo/jekyll/wiki/Sites).

```C#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Web;
using System.Web.Mvc;

namespace Bootstrap31WebApp.Controllers
{
    public class HomeController : Controller
    {
        public ActionResult Index()
        {
            return View();
        }

        public ActionResult About()
        {
            ViewBag.Message = "Your application description page.";

            return View();
        }

        public ActionResult Contact()
        {
            ViewBag.Message = "Your contact page.";

            return View();
        }
    }
}
```

<div class="hlcode">
<div class="syntax">
{% highlight csharp %}
using System;
using System.Collections.Generic;
using System.Linq;
using System.Web;
using System.Web.Mvc;

namespace Bootstrap31WebApp.Controllers
{
    public class HomeController : Controller
    {
        public ActionResult Index()
        {
            return View();
        }

        public ActionResult About()
        {
            ViewBag.Message = "Your application description page.";

            return View();
        }

        public ActionResult Contact()
        {
            ViewBag.Message = "Your contact page.";

            return View();
        }
    }
}
{% endhighlight %}
</div>
</div>


