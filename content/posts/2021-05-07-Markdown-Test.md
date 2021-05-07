---
title: "2021 05 07 Markdown Test"
date: 2021-05-07T18:33:30+08:00
description: "文章描述"
tags: [ "tag1", "tag2", "tag3" ]
categories: [ "分类1", "分类2" ]
lastmod : 2021-05-07
draft: true
---

# This is an <h1> tag

## This is an <h2> tag

###### This is an <h6> tag

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

![GitHub Logo](/img/avatar.jpg)

Format: ![Alt Text](#)

As Kanye West said:

> We're living the future so
> the present is our past.

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

```null
def foo():
    if not bar:
        return True
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

Any word wrapped with two tildes (like `~~this~~`) will appear crossed out.