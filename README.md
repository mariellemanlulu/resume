# Learn the Principles of Technical Documentation as You Build Your Own Static Resume Website

This document discusses about the principles of technical communication and demonstrate tools that are used for modern technical writing. Majority of the information references Andrew Etter's book, [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). Here you can find a tutorial on how to host a static website resume that showcases the principles and tools of technical documentation. Follow along to see it in action!

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

This is for students interested in learning and applying the principles of modern technical writing mentioned in [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by building a simple static resume website. No experience in Markdown or Github is assumed.

# Build Your Own Static Resume Website

[Add a GIF]

Start by going through the [instructions](#instructions). Then, find out more about the [principles]() applied throughout. By the end, you should have a working online resume and acquire knowlegde about modern technical documentation key principles and tools.

## Prerequisites

- **Resume formatted in Markdown** - Here is a [tutorial](https://www.markdowntutorial.com/) to learn Markdown within minutes. [Dillinger](https://dillinger.io/) is a great online markdown editor.
- **Git Version Control** - [Install Git.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) OSX and Linux system typically have this installed by default.
- **Jekyll** - [Install Jekyll](https://jekyllrb.com/docs/installation/), a static website generator that works with Github.
- **Github account** - A free account is acceptable. If you wish to make your website repository private, Github Pro is necessary. If you are a student, visit [GitHub Student Developer Pack](https://education.github.com/pack) to get one for free.

## Instructions

> Note: This set of steps forks a theme and lets you view and modify your site locally. Follow this [guide](https://guides.github.com/features/pages/) if you wish to make your site entirely remote.

1. Choose a Jekyll theme.
   - Visit this [gallery](https://github.com/topics/jekyll-theme) for a list of Jekyll themes.
   - For this project, I used [minimal](https://github.com/pages-themes/minimal).
   - Note: [mention plugins]
2. Fork the repository:
   - [add gif]

> Now that you have a separate copy of the repository, we can now modify it to make it your own.

3. Rename the repository.

   - `Settings > Repository Name`

4. Add a new branch

   - Go to `Settings > Branches` to make the new branch the default branch

5. Host your new site with Github Pages
   - Go to `Settings > Github Pages`.
   - Choose the new branch as the source and save.

> Your static site is now hosted on `[your-user-name].github.io/[repository-name]/`. It's now time to modify the site locally.

![sfsdf](./assets/img/clone-link.gif)

6. View site locally.

   - With the command line, go to the directory where you want the repository to reside.
     - `cd /home/user/my_project`
   - Clone the repository with the URL.
     - `git clone https://github.com/<username>/<repository-name>.git`
   - Go to the repository
     - `cd <repository-name>`
   - Switch to the new branch
     - `git checkout <new-branch-name>`
   - Run the local server
     - `bundle exec jekyll serve`
   - Visit local server address
     - `http://127.0.0.1:4000` _Note: it maybe different from you_

7. Modify site locally.

   - Open the project with your IDE
   - Replace `index.md` contents with your markdown-formatted resume contents.
   - Once save, refresh local page to see changes.
   - **Tips:**
     - You can change the formatting and styles with `HTML` and `CSS` in `_layouts/` and `_sass/`, respectively.
     - You can set global properties, e.g. title, in `_config.yml`.
       - _More about Jekyll configuration [here](https://jekyllrb.com/docs/configuration/)._
     - See [More Resources](#more-resources) for tutorials.

8. Update site remotely.
   - Stages files the were modified
     - `git add <file1> <file2>`
   - Commit your changes.
     - `git commit -m "<your commit message>"`
   - Push your changes:
     - `git push`
   - _More information about git commands [here](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)._

## Principles of Technical Writing

#### Why static webpages?

Documentation are simple. They don't need a ton of dependencies. They should be fast, portable and accessible to anyone. Static sites are exactly that. That is why they are great for documentation. They can be hosted almost anywhere. No extensive installation, databases nor large-scale software needed to make one.

#### Why did we use the tools that we used?

##### Lightweight Markup Language

- Using a lightweight markup language is highly recommended for technical documentation. They are designed to make the transition from content to a desired markup language, like HTML, seamless. Because the content is separated from everything else, it makes the editing process much more efficient. Unlike HTML or XML, the syntax is straightforward, clean and human readable.

- `Markdown` is the most popular lightweight markup language, hence, it is future proof. You can learn it in minutes! However, it provides limited features. Therefore, different Markdown "flavours" exists to make up for the lack of features. [Github Flavoured Markdown (GFM)](gfm) is used to write this `README.md`

##### Distributed Version Control

- Distributed Version Control provides many benefits when creating a documentation. It keeps track of the development history. It allows others to contribute to the same file concurrently. It provides the ability to work offline.

- `Git` is the version control being used for this repository and `GitHub` is the service that we use to manage our repositories. One advantage of this is that the documentation (this `README.md`) is stored alongside with the content. Doing so encourages the documentation to stay up to date and developers are more likely to contribute.

##### Static Website Generator

- Static website generator is what makes the job easy. Provide it with content (lightweight markup file) and a theme (HTML & CSS), and _viola_ it formats into a working website. Maintaining your site becomes effortless making your document in sync with the world in no time.

- `Jekyll` is the generator that Github Pages provides to process static websites. There are 3 ways you can work with Jekyll: [by modifiying settings](), [forking a theme](), or [starting from scratch](). Forking a theme was done for this project.

##### Hosting the site

- After developing your site, it's now time to make it alive. Having your website hosted on the internet where anyone with a link can visit avoids duplication. Etter defines this as [_single sourcing_](https://en.wikipedia.org/wiki/Single-source_publishing). Having only one copy of the documentation ensures accuracy, because you are maintaining from a "single source". Moreover, you will need a web hosting provider and, generally, it is not free.

- `Github Pages`, however, is free for hosting a static site with Jekyll!

### Key Points

- Avoid duplication, use **single-source publishing**.
- Keep **documentation with source code**.
- **Encourage contribution** by using accesible tools and version control.
- **Separate content and formatting** for easy maintenance.

## More Resources (draft)

- [Modern Technical Writing: An Introduction to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) (must have)
- [Markdown Tutorial](https://www.markdowntutorial.com/) (no need to explain markdown) (must have)
- [Flavoured Markdown Cheatsheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
- [Jekyll](https://jekyllrb.com/)
- [Markdown Cheatsheet]().
- [Editors best picks for markdown]

## Authors and Acknowledgments

- **Author:** Marielle Manlulu (@mariellemanlulu)
- **Group members for peer editing:**
  - Chris Ciceron (@chrisciceron)
  - Prakhar Sharma (@neil3108)
- **Minimal Theme Author:** Ben Balter (@benbalter)

## FAQs (draft)

##### 1. Why is Markdown better than word processor?

> Answer here

##### 2. Why is my resume not showing up?

> Answer here
