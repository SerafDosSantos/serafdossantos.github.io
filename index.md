---
layout: home
title: Seraf's Blog
---

## Welcome to my sitebook!

You'll find diverse articles about different subjects but most being about IT, computer science and web 2.0 & 3.0.

### Latest stuff

* Translation of _Mastering Bitcoin_ 2nd Open Edition in French (Canada)
  * 👉 [bitcoin.maitriser.ca](https://bitcoin.maitriser.ca)

### Interesting Links

| link | description |
| --- | --- |
| [cv.seraf.me](https://cv.seraf.me) | My Curriculum Vitae |
| [www.seraf.me/MasteringBitcoinBook/](https://www.seraf.me/MasteringBitcoinBook/) | Free _Mastering Bitcoin_ (en) book |
| [www.seraf.me/MasteringEthereumBook/](https://www.seraf.me/MasteringEthereumBook/) | Free _Mastering Ethereum_ (en) book |
| [www.seraf.me/ComputerScienceBooks/](https://www.seraf.me/ComputerScienceBooks/) | Free Computer Science books (many languages) |
| [www.seraf.me/public-apis/](https://www.seraf.me/public-apis/) | Public APIs list |
| [www.seraf.me/MesBlocNotes/](https://www.seraf.me/MesBlocNotes/) | Notebooks on web 3.0 (fr) |
| [astrotarot.ca](https://astrotarot.ca/) | Little Tarot & Oracle web app |

### Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>