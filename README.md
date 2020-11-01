# Learn the Principles of Technical Documentation as You Build Your Own Static Resume Website

This document is written to discuss about the principles of technical communication and demonstrate tools that are used for modern technical writing. Majority of the information references Andrew Etter's book, [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). Here you can find a tutorial on how to host a static website resume in which showcases the principles and tools that were mentioned. Follow along to see it in action!

## Table of Contents

- [Audience](#audience)
- [Build Your Online Resume](#instructions)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
  - [Principles of Technical Writing]()
    - [Lightweight Markup Language]()
    - [Version Control]()
    - [Static Website Generator]()
    - [Hosting Your Website]()
    - [Additional Notes]()
- [More Resources](#more-resources)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [FAQs](#faqs)

## Audience

This document is for students interested in learning and applying the principles of modern technical writing mentioned in [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by building a simple static resume website.

# Build Your Own Static Resume Website

[Explain what we are doing and how the README is formatted]

[Add a GIF]

## Prerequisites

- **Markdown** - Learn Markdown in minutes with this [tutorial](https://www.markdowntutorial.com/).
- **Markdown Editor** - [Dillinger](https://dillinger.io/) is a great online markdown editor.
- **Git Version Control** - [Install Git.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) OSX and Linux system typically have this installed by default.
- **Jekyll** - [Install Jekyll.](https://jekyllrb.com/docs/installation/)
- **GitHub account** - A free account is acceptable. If you wish to make your website repository private, you will need a Github Pro account. If you are a student, visit [GitHub Student Developer Pack](https://education.github.com/pack) to get one for free.

## Instructions

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

Documentation are simple. They don't need a ton of dependencies. They should be fast, portable and accessible to anyone. Static sites are exactly that. They can be hosted almost anywhere. No extensive installation, databases nor large-scale software needed to make one. As witnessed from the requirements and instructions above, very little is needed to create a static website. [Connect Documentation and Static sites].

#### Why did we use the tools that we used?

- `Markdown`, `GitHub Pages`, `Jekyll`, `Git` are few of the many useful technical documentation tools. They are accessible to anyone and are very easy to learn.

##### Lightweight Markup Language

- Using a lightweight markup language is highly recommended for technical documentation. They are designed to make the transition from content to a desired markup language, like HTML, seamless. Because the content is separated from everything else, it makes the editing process much more efficient. Unlike HTML or XML, the syntax is straightforward, clean and human readable.

- `Markdown` is the most popular lightweight markup language, hence, it is future proof. You can learn it in minutes! However, it provides limited features. Therefore, different Markdown "flavours" exists to make up for the lack of features. [Github Flavoured Markdown (GFM)](gfm) is used to write this `README.md`

##### Distributed Version Control

- Distributed Version Control provides many benefits when creating a documentation. It keeps track of the development history. It allows others to contribute to the same file concurrently. It provides the ability to work offline.

- `Git` is the version control being used for this repository and `GitHub` is the service that we use to manage our repositories. One advantage of this is that the documentation (this `README.md`) is stored alongside with the content. Doing so encourages the documentation to stay up to date and developers are more likely to contribute.

##### Static Website Generator

- Static website generator is what makes the job easy. Provide it with content (lightweight markup file) and a theme (HTML & CSS), and _viola_ the generator will turn it into a working website. Maintaining your site becomes effortless making your document in sync with the world in no time.

- `Jekyll` is the generator that Github Pages provides to process static websites. There are 3 ways you can work with Jekyll: [by modifiying settings](),[forking a theme](), or [starting from scratch](). Forking a theme was done for this project.

##### Hosting the site

- After developing your site, it's now time to make it alive. Having your website hosted on the internet where anyone with a link can visit avoids duplication. Etter defines this as _single sourcing_. Having only one copy of the documentation ensures accuracy, because you are maintaining from a "single source". Moreover, you will need a web hosting provider and, generally, it is not free.

- `Github Pages`, however, is free for hosting a static site with Jekyll!

##### Final Notes

- Single Sourcing
- Keep Documentation w/ source code
- Stay in sync
- Contribution
- Separate Content

## More Resources

- [Modern Technical Writing: An Introduction to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown Tutorial](https://www.markdowntutorial.com/) (no need to explain markdown)
- [Markdown Editor that I used](https://jbt.github.io/markdown-editor/)
- [Flavoured Markdown Cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
- [Jekyll](https://jekyllrb.com/)
- [Markdown Cheatsheet]().

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
