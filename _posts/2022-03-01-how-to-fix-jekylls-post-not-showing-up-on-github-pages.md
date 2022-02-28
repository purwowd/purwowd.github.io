---
title: How to fix Jekyll's post not showing up on Github pages
layout: post
date: '2022-03-01 00:16:12'
categories:
- jekyll
---

Actually, this is a stupid thing, because the issue come up when I missing to add GMT at end of the line on the date property of my new post.

`before` :
{% highlight markdown %}
---
title: My Default settings VSCode for Developments
layout: post
date: '2022-02-28 22:56:02'
categories:
- vscode
---
{% endhighlight %}

`after` :

{% highlight markdown %}
---
title: My Default settings VSCode for Developments
layout: post
date: '2022-02-28 22:56:02 +0700'
categories:
- vscode
---
{% endhighlight %}

and Viola, the issue has been solved :laughing:
