---
layout: guide
title:  "Installing Ocaml on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/ocaml.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Ocaml Compiler on Raspberry Pi. 

## Installation


{% highlight shell %}
sudo apt-get install ocaml
{% endhighlight %}

## Usage

Sample program:


```
print_string "Hello this is OCaml!";
```

To run this Program enter the following command in command line.
{% highlight shell %}
 ocaml filename.ml
{% endhighlight %}

</section>
