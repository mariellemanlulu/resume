# How to Host a Static Website : Principles of Modern Technical Communication

This document is written to discuss about the principles of technical communication and demonstrate tools that can be used for modern technical writing. Majority of the information references Andrew Etter's book, Modern Technical Writing: An Introduction to Software Documentation. Here you can find a tutorial on how to host a static website resume to showcase the principles and tools that were mentioned. Follow along to see it in action!

## Table of Contents

- [How to Host a Static Website : Principles of Modern Technical Communication](#how-to-host-a-static-website--principles-of-modern-technical-communication)
  - [Table of Contents](#table-of-contents)
  - [Audience](#audience)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [Principles of Technical Writing](#principles-of-technical-writing)
      - [Why static webpages?](#why-static-webpages)
      - [Why did we use the tools that we used?](#why-did-we-use-the-tools-that-we-used)
          - [Lightweight Markup Language](#lightweight-markup-language)
          - [Version Control](#version-control)
          - [Static Website Generator](#static-website-generator)
          - [Github Pages for hosting](#github-pages-for-hosting)
          - [Additional Notes](#additional-notes)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgments](#authors-and-acknowledgments)
  - [FAQs](#faqs)
        - [1. Why is Markdown better than word processor?](#1-why-is-markdown-better-than-word-processor)
        - [2. Why is my resume not showing up?](#2-why-is-my-resume-not-showing-up)

## Audience

This document is for computer science student who are interested in learning the principles of modern technical writing and learning how to create a static resume website. By the end, student should acquire knowledge about the tools that they can use to make a static website and know the importance of hacing a static website.

## Prerequisites

- Markdown
- Git Version Control
- Jekyll
- GitHub account, free for students

## Instructions

1. Find a theme
2. Fork the theme's repository
3. Rename the repository
4. Clone the theme on your local
5. Create a new branch
6. Make the new branch as the main branch

   - Settings > branch > change the main branch

7. Replace content of index.md with the markdown formatted resume the you created
8. Run `bundle exec jekyll serve` and visit your local IP address (`http://127.0.0.1:4000/`) to view locally
9. Format as you like
10. Stage your changes with `git add <file>`
11. Commit your changes with `git commit -m "<commit message>"`
12. Publish from local to remote with `git push --setupstream origin <new-branch-name>
13. Set up GitHub Pages environment
    - Settings > GitHub Pages > Select your new branch > Click Save.
14. Visit `<username>.github.io/<repository-name>` to new your new static website
15. Add a README.md

### Principles of Technical Writing

#### Why static webpages?

#### Why did we use the tools that we used?

###### Lightweight Markup Language

###### Version Control

###### Static Website Generator

###### Github Pages for hosting

###### Additional Notes

## More Resources

- [Modern Technical Writing: An Introduction to to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown Tutorial](https://www.markdowntutorial.com/) (no need to explain markdown)
- [Markdown Editor that I used](https://jbt.github.io/markdown-editor/)
- [Flavoured Markdown Cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
- [Jekyll](https://jekyllrb.com/)

## Authors and Acknowledgments

- **Author:** Marielle Manlulu (@mariellemanlulu)
- **Group Members:**
  - Chris Ciceron (@chrisciceron)
  - Prakhar Sharma (@neil3108)
- **Minimal Theme Author:** Ben Balter (@benbalter)

## FAQs

##### 1. Why is Markdown better than word processor?

> Answer here

##### 2. Why is my resume not showing up?

> Answer here
