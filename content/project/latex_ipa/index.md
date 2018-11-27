+++
# Project title.
title = "LaTeX IPA"

# Date this page was created.
date = "2016-04-27"

# Project summary to display on homepage.
summary = "A collection of snippets for SublimeText that simplify the process of using IPA in LaTeX."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["latex", "ipa", "sublimetext", "linguistics"]

# Optional external URL for project (replaces project detail page).
# external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Does the project detail page use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "LaTeX-IPA"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Top"
+++

<iframe src="http://ghbtns.com/github-btn.html?user=jvcasillas&repo=LaTeX-IPA&type=watch&count=true&size=large" height="30" width="170" frameborder="0" scrolling="0" style="width:130px; height: 30px;" allowTransparency="true"></iframe>
<iframe src="http://ghbtns.com/github-btn.html?user=jvcasillas&repo=LaTeX-IPA&type=fork&count=true&size=large" height="30" width="170" frameborder="0" scrolling="0" style="width:130px; height: 30px;" allowTransparency="true"></iframe>
<iframe src="http://ghbtns.com/github-btn.html?user=jvcasillas&type=follow&count=true&size=large" height="30" width="240" frameborder="0" scrolling="0" style="width:240px; height: 30px;" allowTransparency="true"></iframe>

<p></p>

I made this repository to simplify the process of using IPA in $\LaTeX$. It is merely a collection of snippets for the package [TIPA][TIPA]. To install LaTeX-IPA see the [package control][package control LaTeX-IPA] page.


### File naming  

Consonants are labeled in the following way:  

- voicing -> point of articulation -> mode of articulation  
Ex. voiceless-bilabial-aprox.sublime-snippet = [&beta;]


Vowels are labeled in the following way:  

- vowel -> tense/lax -> height -> frontedness -> rounding  
Ex. vowel-tense-high-front-unrounded.sublime-snippet = [i]


### Tab triggers

There are 6 main groups:  

- **Diacritics**: type "diac" + tab  
- **Vowels**: type "vowel" + tab  

Consonants are divided into four subcategories:  

- **Fricatives** type "fric" + tab  
- **Affricates** type "affr" + tab  
- **Liquids**: type "liquid" + tab  
- **Nasals**: type "nasal" + tab

### Notes  

As of now (10/19/2013), I have only included the symbols that I use the most in English and Spanish. I will continue adding to the repository over time. It should be noted that the consonants do not include all categories (i.e. stops). This is because they are not represented by unsual symbols in IPA. 

[project page]: http://www.jvcasillas.com/LaTeX-IPA


[TIPA]: http://www.ctan.org/pkg/tipa
[package control LaTeX-IPA]: https://sublime.wbond.net/packages/LaTeX-IPA

