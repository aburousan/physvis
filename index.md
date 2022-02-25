@def title = "Physvis"
@def tags = ["syntax", "code"]

# Idea behind this website
<!-- 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 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-->
<!-- \tableofcontents -->
<!-- you can use \toc as well -->
**Physics!**\\
*Physics* is something we all have heard about.

But _what is it?_

In **Feynman's** terms it is:
> Understanding the nature

An example can be helpful.\\
**Suppose we do not know the rules of chess but are allowed to watch the moves of the players. If we watch the games for a long time (few hundred years!), we may make out some of the rules. With the knowlegde of these rules we may try to understand why a player played a particular move.**

It is exactly what we do in physics.\\
We *notice what happens in real world*, we *study things* and then we try to *find what are the rules this whole world follows*.\\
**This is what 
~~~
<span style="color:magenta;">PHYSICS</span>
~~~
 really is!**

The goal of this website is do give you guys those **OBSERVATION** and then tell you guys what are the possible **Rules** are.\\
For this reason we need **Mathematics**, because **Maths is the language of the universe**.

Like Galilio said,
@@colbox-blue
The universe cannot be read until we have learnt the language and become familiar with the characters in which it is written. It is written in **MATHEMATICAL LANGUAGE**...
@@

For this reason, we will not only see the **explanation of physical phenomenon** but also it's underlying reasons both **visually** and also **mathematically**.

In modern times, we don't always need labs to perform experiments. We can study physical systems using **Computers**. So, we will also see many **stimulations** and **codes** in this website. I will mainly use **Python** and **Julia** for this purpose.

Hope you will be enjoying this website.

## About myself
@@row
@@container
@@center ![](/assets/Austin.jpg) @@
@@
Me with International Doggo.
~~~
<div style="clear: both"></div>
~~~
@@
I am **Kazi Abu Rousan**, a student of **University of Kalyani**, doing my master's degree in Physics. I also teach
 **Maths** and **Physics** for olympiad in [**Cheenta Ganit Kendra**](https://www.cheenta.com/).\\
Ohh and here is my catto! **Mr. Gino!**
~~~
<div class="row"><div class="container"><div class="center"><img src="/assets/Gino.jpg" height = "305" alt="" /></div></div>
~~~

## Few of my works
I have many articles written all over web. Few of them are listed.

1. [**What is Fourier Series? and It’s Beauty**] (https://medium.com/swlh/what-is-fourier-series-and-its-beauty-ce2410012329).
~~~
<div class="row"><div class="container"><div class="center"><img src="/assets/joker_fou.png" height = "230" alt="" /></div></div>
<div style="clear: both"></div></div>
<p>Joaquin Phoenix Joker using 6000 epicycles</p>
~~~
2. [**Trapezoidal Rule: A Method of Numerical Integration**](https://medium.com/cantors-paradise/trapezoidal-rule-a-method-of-numerical-integration-5772838657b3).
~~~
<div class="row"><div class="container"><div class="center"><img src="/assets/tra.png" height = "230" alt="" /></div></div>
<div style="clear: both"></div></div>
<p>Visualization of the Trapezoidal rule</p>
~~~
3. [**Diffraction patterns by different orientation of rectangular Apertures: Intuitive understanding of Optical Transformations**](https://www.researchgate.net/publication/356142815_Diffraction_patterns_by_different_orientation_of_rectangular_Apertures_Intuitive_understanding_of_Optical_Transformations).
~~~
<div class="row"><div class="container"><div class="center"><img src="/assets/diffraction.png" height = "405" alt="" /></div></div>
<div style="clear: both"></div></div>
<p>Diffraction Pattern for a Snowfla aperture</p>
~~~
4. [**Introduction to Anyons and Generalized distribution function**](https://www.researchgate.net/publication/352641643_Introduction_to_Anyons_and_generalized_distribution_function).
@@row
@@container
@@center ![](/assets/anyons.png) @@
@@
~~~
<div style="clear: both"></div>
~~~
@@

~~~
<div style="clear: both"></div></div>
<div class="row"><div class="container"><div class="center"><img src="/assets/any" height = "365" alt="" /></div></div>
~~~

There are many more.
5. [For **_youtube_** vidoes visit this playlist.](https://youtube.com/playlist?list=PLTDTcDkWcXuzwI6M1bGzNh6dDPCB9qZiu)
~~~
<iframe width="410" height="270" src="https://www.youtube.com/embed/videoseries?list=PLTDTcDkWcXuzwI6M1bGzNh6dDPCB9qZiu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
~~~

6. [For my **upcoming book on Using Python in Number-Theory** visit here(Draft)](https://www.researchgate.net/project/Number-Theory-with-Python)
~~~
<p><img src="/assets/book.jpg" height = "400" alt="Cover of the Book" /></p>
~~~

We will sometimes use **codes** for solving problems.\\
As an example, consider the birthday problem ([see detailed discussion](https://www.cheenta.com/a-probability-birthday-with-coding/))
```julia:/assets/scripts/ex1
arr = [2,6,2,10]
arr.==2
sum(arr.==2)
begin
  function prob(n::Int)
    favour = 0
    for ex_num=1:n
      months = rand(1:12,20)
      nums = [sum(months.==i) for i=1:12]
      if sum(nums.==3)==4 && sum(nums.==2)==4
        favour += 1
      end
    end
    probability = favour/n
  end
end
println("The output, probability is = ",prob(10_000_000))
```
The output is 
\show{/assets/scripts/ex1}

So, **Have Fun** learning!

## Contact
You can follow me in :
* ~~~
<a href="https://twitter.com/austinrousan?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @austinrousan</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>~~~
* ~~~ <script src="https://apis.google.com/js/platform.js"></script>

<div class="g-ytsubscribe" data-channelid="UCHUvCZK9fpYctDE73hbrahw" data-layout="full" data-count="hidden"></div> ~~~

* [Linked In Profile](https://in.linkedin.com/in/kazi-abu-rousan-819848198)
<!-- ```python
using PyPlot
figure(figsize=(8,6))
plot(rand(5), rand(5))
savefig(joinpath(@OUTPUT, "ex_outpath_1.svg"))
```
$\tau$ 
This section is meant as a refresher if you're new to Franklin.
Have a look at both how the website renders and the corresponding markdown (`index.md`).
Modify at will to get a feeling for how things work!

Ps: if you want to modify the header or footer or the general look of the website, adjust the files inSSSS
* `src/_css/` and
* `src/_html_parts/`.

## The base with Markdown

The [standard markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) can be used such as titles using `#`, lists:
S
* element with **bold**
* element with _emph_

or code-blocks `inline` or with highlighting (note the `@def hascode = true` in the source to allow [highlight.js](https://highlightjs.org/) to do its job):

```julia
abstract type Point end
struct PointR2{T<:Real} <: Point
    x::T
    y::T
end
struct PointR3{T<:Real} <: Point
    x::T
    y::T
    z::T
end
function len(p::T) where T<:Point
  sqrt(sum(getfield(p, η)^2 for η ∈ fieldnames(T)))
end
```

You can also quote stuff

> You must have chaos within you to ...

or have tables:

| English         | Mandarin   |
| --------------- | ---------- |
| winnie the pooh | 维尼熊      |

Note that you may have to do a bit of CSS-styling to get these elements to look the way you want them (the same holds for the whole page in fact).

### Symbols and html entities

If you want a dollar sign you have to escape it like so: \$, you can also use html entities like so: &rarr; or &pi; or, if you're using Juno for instance, you can use `\pi[TAB]` to insert the symbol as is: π (it will be converted to a html entity).[^1]

If you want to show a backslash, just use it like so: \ ; if you want to force a line break, use a ` \\ ` like \\ so (this is on a new line).[^blah]

If you want to show a backtick, escape it like so: \` and if you want to show a tick in inline code use double backticks like ``so ` ...``.

Footnotes are nice too:

[^1]: this is the text for the first footnote, you can style all this looking at `.fndef` elements; note that the whole footnote definition is _expected to be on the same line_.
[^blah]: and this is a longer footnote with some blah from veggie ipsum: turnip greens yarrow ricebean rutabaga endive cauliflower sea lettuce kohlrabi amaranth water spinach avocado daikon napa cabbage asparagus winter purslane kale. Celery potato scallion desert raisin horseradish spinach carrot soko.

## Basic Franklin extensions

### Divs

It is sometimes useful to have a short way to make a part of the page belong to a div so that it can be styled separately.
You can do this easily with Franklin by using `@@divname ... @@`.
For instance, you could want a blue background behind some text.

@@colbox-blue
Here we go! (this is styled in the css sheet with name "colbox-blue").
@@

Since it's just a `<div>` block, you can put this construction wherever you like and locally style your text.

### LaTeX and Maths

Essentially three things are imitated from LaTeX

1. you can introduce definitions using `\newcommand`
1. you can use hyper-references with `\eqref`, `\cite`, ...
1. you can show nice maths (via KaTeX)

The definitions can be introduced in the page or in the `config.md` (in which case they're available everywhere as opposed to just in that page).
For instance, the commands `\scal` and `\R` are defined in the config file (see `src/config.md`) and can directly be used whereas the command `\E` is defined below (and therefore only available on this page):

\newcommand{\E}[1]{\mathbb E\left[#1\right]}

Now we can write something like

$$  \varphi(\E{X}) \le \E{\varphi(X)}. \label{equation blah} $$

since we've given it the label `\label{equation blah}`, we can refer it like so: \eqref{equation blah} which can be convenient for pages that are math-heavy.

In a similar vein you can cite references that would be at the bottom of the page: \citep{noether15, bezanson17}.

**Note**: the LaTeX commands you define can also incorporate standard markdown (though not in a math environment) so for instance let's define a silly `\bolditalic` command.

\newcommand{\bolditalic}[1]{_**!#1**_} <!--_ ignore this comment, it helps atom to not get confused by the trailing underscore when highlighting the code but is not necessary.-->

<!-- and use it \bolditalic{here for example}.

Here's another quick one, a command to change the color:

\newcommand{\col}[2]{~~~<span style="color:~~~#1~~~">~~~!#2~~~</span>~~~}

This is \col{blue}{in blue} or \col{#bf37bc}{in #bf37bc}.

### A quick note on whitespaces

For most commands you will use `#k` to refer to the $k$-th argument as in LaTeX.
In order to reduce headaches, this forcibly introduces a whitespace on the left of whatever is inserted which, usually, changes nothing visible (e.g. in a math settings).
However there _may be_ situations where you do not want this to happen and you know that the insertion will not clash with anything else.
In that case, you should simply use `!#k` which will not introduce that whitespace.
It's probably easier to see this in action:

\newcommand{\pathwith}[1]{`/usr/local/bin/#1`}
\newcommand{\pathwithout}[1]{`/usr/local/bin/!#1`}

* with: \pathwith{script.jl}, there's a whitespace you don't want 🚫
* without: \pathwithout{script.jl} here there isn't ✅

### Raw HTML

You can include raw HTML by just surrounding a block with `~~~`.
Not much more to add.
This may be useful for local custom layouts like having a photo next to a text in a specific way.

~~~
<div class="row">
  <div class="container">
    <img class="left" src="/assets/rndimg.jpg">
    <p>
    Marine iguanas are truly splendid creatures. They're found on the Gálapagos islands, have skin that basically acts as a solar panel, can swim and may have the ability to adapt their body size depending on whether there's food or not.
    </p>
    <p>
    Evolution is cool.
    </p>
    <div style="clear: both"></div>      
  </div>
</div>
~~~

**Note 1**: again, entire such blocks can be made into latex-like commands via `\newcommand{\mynewblock}[1]{...}`.

**Note 2**: whatever is in a raw HTML block is *not* further processed (so you can't have LaTeX in there for instance). A partial way around this is to use `@@...` blocks which *will* be recursively parsed. The following code gives the same result as above with the small difference that there is LaTeX being processed in the inner div.

@@row
@@container
@@left ![](/assets/rndimg.jpg) @@
@@
Marine iguanas are **truly splendid** creatures. They're not found in equations like $\exp(-i\pi)+1$. But they're still quite cool.
~~~
<div style="clear: both"></div>
~~~
@@

## Pages and structure

Here are a few empty pages connecting to the menu links to show where files can go and the resulting paths. (It's probably best if you look at the source folder for this).

* [menu 1](/menu1/)
* [menu 2](/menu2/)
* [menu 3](/menu3/)

## References (not really)

* \biblabel{noether15}{Noether (1915)} **Noether**,  Körper und Systeme rationaler Funktionen, 1915.
* \biblabel{bezanson17}{Bezanson et al. (2017)} **Bezanson**, **Edelman**, **Karpinski** and **Shah**, [Julia: a fresh approach to numerical computing](https://julialang.org/research/julia-fresh-approach-BEKS.pdf), SIAM review 2017.

## Header and Footer

As you can see here at the bottom of the page, there is a footer which you may want on all pages but for instance you may want the date of last modification to be displayed.
In a fashion heavily inspired by [Hugo](https://gohugo.io), you can write things like

```html
Last modified: {{ fill fd_mtime }}.
```

(cf. `src/_html_parts/page_foot.html`) which will then replace these braces with the content of a dictionary of variables at the key `fd_mtime`.
This dictionary of variables is accessed locally by pages through `@def varname = value` and globally through the `config.md` page via the same syntax.

There's a few other such functions of the form `{{fname p₁ p₂}}` as well as support for conditional blocks. If you wander through the `src/_html_parts/` folder and its content, you should be able to see those in action. --> 
