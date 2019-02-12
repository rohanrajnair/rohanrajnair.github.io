[![portfolYOU](./docs/header.png)](https://youssefraafatnasry.github.io/portfolYOU/)

<div align="center">
    <i>A beautiful portfolio Jekyll theme that works with GitHub Pages.</i><br><br>
</div>

[![screenshots](./docs/portfolYOU.gif)](https://youssefraafatnasry.github.io/portfolYOU/)

<div align="center">
    <sub><sup>© 2019 portfolYOU, licensed under the <a href="./LICENSE">MIT License</a>.</sup></sub>
</div>

## Download & Usage

1. Clone or [Download][download] this repo.
1. Delete unnecessary files and folders:
   - README.md
   - LICENSE
   - docs/
1. Change the configuration options in `_config.yml` depending on your needs.
1. Add `project-name.md` to `_projects` directory to add a new project.
1. Add `YYYY-MM-DD-article-name.md` to `_posts` directory to add a new article.
1. Modify `_data/` files to add new skills or items to the timeline.
1. Modify `pages/about.md` to write your own bio.
1. Set up portfolYOU [locally] or publish it to [GitHub Pages][gh-pages].

[download]: https://github.com/YoussefRaafatNasry/portfolYOU/archive/master.zip
[gh-pages]: https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/
[locally]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

## Sections

portfolYOU's sections are **independent**, you can remove any section upon your needs. Here's a list of the files and folders needed by each section:

| Projects                      | Articles               | About                             |
| :---------                    | :---------             | :---------                        |
| pages/projects.html           | pages/articles.html    | pages/about.md                    |
| _sass/projects.scss ¹         | _sass/_articles.scss ¹ | _sass/_skills.scss ¹              |
| assets/js/card_animation.js ² | _layouts/post.html     | _sass/_timeline.scss ¹            |
| _projects/ ³                  | _posts/ ⁴              | _layouts/about.html               |
|                               |                        | _includes/skills-others.html      |
|                               |                        | _includes/skills-programming.html |
|                               |                        | _includes/timeline.html           |
|                               |                        | _data/                            |

<small>
    <b>If you are deleting any section, please consider the following:</b><br>
    ¹ remove reference from <code> assets/css/custom.scss </code><br>
    ² remove reference from <code> _includes/scripts.html </code><br>
    ³ remove collections and defaults from <code> _config.yml </code><br>
    ⁴ remove permalink from <code> _config.yml </code>
</small>

## Dependencies

| Dependency                  | Version |
| :-------------------------- |:-------:|
| [Animate.css][animate]      | v3.7.0  |
| [Bootstrap][bootstrap]      | v4.2.1  |
| [FontAwesome][font-awesome] | v5.6.3  |
| [jQuery][jquery]            | v3.3.1  |
| [Popper.js][popper]         | v1.14.6 |
| [wow.js][wow]               | v1.1.2  |

[animate]: https://daneden.github.io/animate.css/
[bootstrap]: https://getbootstrap.com/
[font-awesome]: https://fontawesome.com/
[jquery]: https://jquery.com/
[popper]: https://popper.js.org/
[wow]: https://wowjs.uk/

## Credits & Inspiration

1. [CSS3 Animated Skill Progress bar][skills-progress-bar] _A pen by Shah Zobayer Ahmed._
1. [How to Create Bootstrap Card Hover Effect (jQuery)][cards-hover] _A video by Daily Tuition._
1. [Vertical Timeline (HTML-SCSS-CSS)][vertical-timeline] _A video by DevPen._

[skills-progress-bar]: https://codepen.io/speeedsam/pen/VeOGEq
[cards-hover]: https://www.youtube.com/watch?v=2qQxwT-Qm5E
[vertical-timeline]: https://www.youtube.com/watch?v=TP4THzsAa3M&t=2s