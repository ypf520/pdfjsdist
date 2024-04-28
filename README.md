> 如果你的PDF文件mykichen.pdf和viewer.html放在同一个目录下,那么在URL中指定file参数的写法是:
> http://localhost:8000/viewer.html?file=mykichen.pdf

注意几点:
你只需要写文件名mykichen.pdf,因为viewer.html和pdf文件在同一路径,不需要额外的路径部分。
?file=mykichen.pdf这一部分是一个URL查询参数,告诉viewer.html需要加载哪个PDF文件。

> 所以只要保证viewer.html和mykichen.pdf在同一目录,然后正确构造带有file参数的URL,就可以用viewer.html直接打开并展示你的PDF文件了。
