![bootstrap-jekyll logo](/img/global/logo.png)

# bootstrap-jekyll

A boilerplate for making static websites built with jekyll, bootstrap 4, animate on scroll, lunr, and feather.

If you know a resource which is not listed here, make a pull request or open an issue. Please report broken links, outdated assets and spelling mistakes.

## Getting Started

Download this repository, install that latest version of [Jekyll](https://jekyllrb.com/), run `bundle exec jekyll serve` in the appropriate directory, and type `localhost:4000` in your favorite browser's address bar to get everything up and running locally.

## Asset List

- [Jekyll](https://jekyllrb.com/)
- [Bootstrap 4](https://getbootstrap.com/)
- [Animate on scroll](https://michalsnik.github.io/aos/)
- [Lunr](https://lunrjs.com/)
- [Feather](https://feathericons.com/)
- [Sticky-footer](https://getbootstrap.com/docs/4.1/examples/sticky-footer/)

## Roadmap

### To Do
Version 1.0

- Update front matter on index, post, and config to ensure the [SEO plugin](https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md) is being used to its full potential
- Make the URLs for Post SEO friendly by updating the config file
- Create more page layouts based on [Bootstrap 4 examples](https://getbootstrap.com/docs/4.1/examples/)
- Review [GitHub help](https://help.github.com/categories/customizing-github-pages/) for more ideas
- Consider adding multi-language support using this [plugin](https://github.com/vwochnik/jekyll-language-plugin)
- Review [Jekyll plugins](https://jekyllrb.com/docs/plugins/) for more ideas
- Incorporate form system using something free (preferably something that also lets marketers send out emails)
- Have a Back-End developer help with implementing the AWS environment on the free tier
- Back-End task: Incorporate the ability to schedule post using git [comment systems](https://serverless.com/blog/static-site-post-scheduler/)
- Update this documentation
- Create youtube tutorial series
- Create themes

### To Do
Version 2.0

- Create John Doe's Bio Page and link that to post

### To Maybe

- add lazy load
- incorporate firebase for login features such as commenting, chat, and dashboards


### To Done

- Setup a baseline for the Jekyll file directory
- Incorporate animate on scroll
- Incorporate Bootstrap 4 using Jekyll's sass compiler
- Incorporate lunr Search
- Incorporate feather icons
- Add CSS for sticky footers
- Update lunr search to search pages and posts
- Update Navbar to include active class dependent on page
- (Resolved) Nav menu burger is not working for smaller devices
- (Temp solution - turn off AOS) Bootstrap dropdown menu layering issues with animate on scroll (see nav)
- Add on hover dropdown menu
- Fix body padding issue (footer)
- Update liquid on blog.html to show all post
- Update Blog post style (figured out how and chose not to until a later date)
- Create html elements page

### Issue listed
- Update liquid on blog.html to limits the number of post showing
- Update liquid on blog.html to incorporate pagination
