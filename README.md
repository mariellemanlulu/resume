# How to Host a Static Website : Principles of Modern Technical Communication

This document is written to discuss about the principles of technical communication and demonstrate tools that can be used for modern technical writing. Majority of the information references Andrew Etter's book, Modern Technical Writing: An Introduction to Software Documentation. Here you can find a tutorial on how to host a static website resume to showcase the principles and tools that were mentioned. Follow along to see it in action!

## Table of Contents

- [Audience](#audience)
- [Prerequisites](#prerequisites)
- [Hosting a Static Website](#instructions)
  - Step by step instruction
  - Tools and principles used
    - Version control using Git
    - Static Website for hosting using GitHub Pages
    - Static Website Generator using Jekyll
    - Lightweight Markup Language using Markdown
- [More Resources](#more-resources)
  - (Include at least other resources)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [FAQs](#faqs)

## Audience

This document is for computer science student who are interested in learning the principles of modern technical writing and learning how to create a static resume website. By the end, student should acquire knowledge about the tools that they can use to make a static website and be knowledgeable about the principles of technical writing.

## Instructions

[Explain what we are doing]

#### Prerequisites

- Markdown
- Git Version Control
- Jekyll
- GitHub account, free for students

1. Find a Jekyll theme [Provide a link]()
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
12. Publish from local to remote with `git push --setupstream origin <new-branch-name>`
13. Set up GitHub Pages environment
    - Settings > GitHub Pages > Select your new branch > Click Save.
14. Visit `<username>.github.io/<repository-name>` to new your new static website
15. Add a README.md

16. Create a repo

Static Website Resume Demo:
![Provide a GIF](gif.png)

### Principles of Technical Writing

#### Why static webpages?

Documentation do not need a ton of dependencies. They should be simple, fast, portable and accessible. Static webpages are exactly that. They can be hosted almost anywhere. No extensive installation, databases and large-scale software needed to make one. As witnessed from the requirements and instructions above, very little is needed to create static website.

#### Why did we use the tools that we used?

- Encourage contribution
- Distribution

##### Lightweight Markup Language

- Using a lightweight markup language is highly recommended for technical documentation. They are designed to make the transition from content to the desired markup language like HTML seamless. Because the content is separated from everything else, it makes the editing process much more efficient. Unlike HTML or XML, the syntax is straightforward, clean and human readable. It is very easy to learn.

- `Markdown` is the most popular lightweight markup language, hence, it is future proof. However, it provides limited features. Therefore, different Markdown "flavours" exists to make up for the lack of features.

##### Distributed Version Control

- Distributed Version Control provides many benefits when creating a documentation. It keeps track of the development history. It allows others to contribute to the same file concurrently. It provides the ability to work offline.

- `Git` is the version control being used and `GitHub` is the service that we use to manage our repositories. One advantage of this is that the documentation, which is this `README.md` is stored alongside with the content. Doing so encourage the documentation to stay up to date and developers are more likely to contribute.

##### Static Website Generator

##### Github Pages for hosting

##### Additional Notes

## More Resources

- [Modern Technical Writing: An Introduction to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown Tutorial](https://www.markdowntutorial.com/) (no need to explain markdown)
- [Markdown Editor that I used](https://jbt.github.io/markdown-editor/)
- [Flavoured Markdown Cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
- [Jekyll](https://jekyllrb.com/)

## Authors and Acknowledgments

- **Author:** Marielle Manlulu (@mariellemanlulu)
- **Group members for peer editing:**
  - Chris Ciceron (@chrisciceron)
  - Prakhar Sharma (@neil3108)
- **Minimal Theme Author:** Ben Balter (@benbalter)

## FAQs

##### 1. Why is Markdown better than word processor?

> Answer here

##### 2. Why is my resume not showing up?

> Answer here
