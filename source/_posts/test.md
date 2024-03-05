---
title:  hello-world 🌷
date: 2024-02-22 17:03:18
updated: 2024-02-23 11:00:00
tags: 
  - 
categories: 
---
{% codeblock %}
class Person
  include ActiveModel::Conversion
  <font color=#6b8e23>軍綠色is me</font> include ActiveModel::Validations

  validates_presence_of :name

  attr_accessor :name

  def initialize(attributes = {})
    @name = attributes[:name]
  end

  def persist
    @persisted = true
  end

  def persisted?
    @persisted
  end
end

person1 = Person.new(:name => "matz")
p person1.valid?
{% endcodeblock %}

{% codeblock %}
More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
hexo new "My New Post"
{% endcodeblock %}

>Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. 
>If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).
 
 <!-- more -->

## Quick Start
```
More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
bash
hexo new "My New Post"
```

### Create a new post

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

```bash
$ 你好
```

# 123

- awe
- dv
- web

## 456

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
``` bash
$ hexo new "My New Post"
