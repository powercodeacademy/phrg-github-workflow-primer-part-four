# Pairing Project No. 4

## The Plan

In the middle of this lesson's tasks, your responsibilities will pivot. Whomever starts as the driver will switch and become the navigator where the lesson specifies. And vice versa.

Before you start, acquire your designated project repo from the course instructor.

# HTML review, Markdown, and transition to Ruby

## Objectives

* HTML review
* Practice `git`
* Learn more about `Markdown` and upticks
* Explain Ruby methods

## 'Git' your updated version

Utilizing instructions from the previous pairing labs, update your local version of the specified repo with the most recent changes.

## Upticks

We learned in the first lab that `Markdown` is a *markup* language. One cool character in `Markdown` is the uptick:

```
`
```

Upticks are compiled down into HTML `<code>` elements. The use of single upticks looks like `this`. They create an *inline* code snippet. However, if you use 3 consecutive upticks to start and close your code, the snippet gets its own lines. Like so:

```ruby
puts "Hello upticks!"
```

## Instructions

1. Create a new git branch for your work
1. On the `index.html`, below student divs, create an ordered list of your's and your partner's 3 favorite foods
1. Pick your absolute favorite food and add a picture of it to the bottom of the page
1. Wrap the img in a link to a website devoted to your food
1. Format and style this list, img, and link so it appears tidy
1. Add, commit, and push your work
1. Open a PR with a screenshot of your new food section

Here's an example:

![Favorite Foods Example](https://raw.githubusercontent.com/powerhome/phrg-github-workflow-primer-part-four/master/favorite-foods-example.png?raw=true "Favorite Foods Example Section")

## Switch drivers

Time to write some Markdown. Do not write any HTML for the instructions below; instead, only use [Markdown](https://dillinger.io/)

1. Create a new git branch for your work
1. Delete the contents of the README.md and give it a new H1 of "My 4 Favorite Ruby methods" Remember, files that end in the `.md` extension are Markdown files. So an "H1" is really just a "#" followed by a space. [This is a great interactive site to practice Markdown](https://dillinger.io/).
1. Each of these 4 methods should be from different Ruby Classes. Leverage [Ruby documentation](https://ruby-doc.org/) for some ideas.
1. Give each Ruby method an H3 (in Markdown, that is "### ") with the method's name, surrounding it in single upticks to show that you are referring to code.
1. Below each method, define the method in your own words
1. Below each definition, use 3 upticks to show an example of the methods use. Feel free to use Ruby comments in your code snippet to make its application very clear - `# this is a comment example in Ruby`. Also, some flavors of `Markdown` allow you to provide language hints to direct the language color-coding like [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code).
1. Add, commit, and push your work
1. Open a PR with a screenshot of your 4 favorite Ruby methods

Here's an example:

![Markdown Ruiby Snippets](https://raw.githubusercontent.com/powerhome/phrg-github-workflow-primer-part-four/master/markdown-example.png?raw=true "Examples of adding Ruby Snippets in Markdown")
