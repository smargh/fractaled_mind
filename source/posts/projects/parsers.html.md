---
title: Parsers
date: 2015-05-27
image: projects/parsers.svg
github: https://github.com/smargh/alfred_parsers
tags:
  - code>alfred
summary: Parse any Greek or Latin word lightening quick. This workflow uses the [Perseus Digital Library]() backend to provide parsing info on input text.
---
#### Version: 2.0

#### Download at [Packal](http://www.packal.org/workflow/parsers)

### Introduction

**`Parsers`** is a relatively simple workflow for [Alfred](http://www.alfredapp.com/). It allows you to quickly and easily look up parsing information for Greek *or* Latin words. It gets its parsing information from the powerful [Perseus project](http://www.perseus.tufts.edu/), but presents the results in the clean user-interface of Alfred. To use **`Parsers`**, simply open Alfred and type the keyword `parse`. Follow the keyword with the Latin or Greek word you want to look up:

![alfred_parser](https://www.evernote.com/shard/s41/sh/2c444d67-b4ca-40b3-b914-c20dc5ebbfb6/9d54f19c489deda365c65f1e6b5232e6/deep/0/alfred_parser.png)

**`Parsers`** will display the results for you as quickly as possible.

As you can see, **`Parsers`** displays the parsing information in the main title field for each item. Below that, in the sub-title field, it displays the lemma and a short definition separated by `::`.

Let's say you are reading some Greek or Latin, however, and don't want to have to open Alfred, type `parse`, then type the word you're interested in. Well, **`Parsers`** has thought of that. From within Alfred's Preferences, you can set up a keyboard shortcut to pass the currently selected text on your Mac to **`Parsers`**. I have mine set up as `cmd+fn+->`. This makes using **`Parsers`** even easier.

Once you have found the parsing information that you believe is correct in your reading context, **`Parsers`** can do 2 things for you:

+ copy the parsing information to the clipboard in a nicely formatted way (`cmd+return`)
+ copy the dictionary entry for that lemma to the clipboard (`shift+return`)

If, for instance, you were to choose the Nominative Singular Feminine form of `aura` (with `cmd+return`), **`Parsers`** would copy this to the clipboard:

~~~
Type: noun
Number: sg
Gender: fem
Case: voc

Definition: the air (in motion), a breeze, breath of air, wind, blast:
Lemma:  aura

Lexicon Links:
  + [Lewis & Short](http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3Atext%3A1999.04.0059%3Aentry%3Daura)
  + [Elem. Lewis](http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3Atext%3A1999.04.0060%3Aentry%3Daura)
~~~

Alternatively, you can use `shift+return` to view a HUD of the lexicon entry for that parsing term, and this lexicon data will also be copied to the clipboard (*NOTE*: Parsers will attempt to display the lexicon entry from the most concise lexicon available for the chosen term or allow you to choose out of the available dictionaries).

All you should need to read your Greek and/or Latin with ease.
