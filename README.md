
[![Netlify Status](https://api.netlify.com/api/v1/badges/e060364c-6d9c-4c76-beba-b7d6c91f8fb7/deploy-status)](https://app.netlify.com/sites/point-zero/deploys)

# Point Zero

Point Zero is a truly minimal micro-blog theme for Jekyll.



## Point Zero eschews many of the typical blogger "must-haves" in pursuit of an uncluttered and esoteric reading experience.

This means:

- no social sharing or following options
- no logo
- no footer
- no sitewide navigation
- no link to homepage
- no sidebars
- no comments


## So, what _does_ it have?

- Point Zero will display your latest post on the homepage. The only navigation element from there, and throughout the site, is a single arrow icon that will randomly advance you to another post.
- Clicking the site title will not bring you back to the home page, but will display your `About` information.
- The layout is clean, simple, and responsive.


# Using the theme:

This repository is a template.

1. While logged into your GitHub account simply click the green button "Use this template"

2. Give your repository a name and an optional description. (It's not necessary to include all branches.)

3. In your newly created repository, open the `_config.yml` file

4. Edit the file to fill out the following fields:

```
- title:
(The site title. This will display in the header and title meta tags)

- email:
(Your email address, or address to the admin of the site)

- description:
(A description of the site. [Use best paractices](https://moz.com/learn/seo/meta-description))

-  baseurl:
(this is often left blank unless you are using a subdirectory of another site for the installation)

- url:
(the base hostname & protocol for - your site, e.g. http://example.com)

- author:
(the site author name. this can be you or the name of the site)
```


5. From here you'll want to [follow these instructions](https://www.netlify.com/blog/2020/04/02/a-step-by-step-guide-jekyll-4.0-on-netlify/#connecting-to-netlify) to launch the site on Netlify's free-tier:

# Netlify CMS

## [Netlify CMS](https://www.netlifycms.org) is built-in with the following configuration fields:


- layout: (hidden field, autofilled with the `post` layout type)

- title: sets the title of the post

- permalink: sets the permalink (slug) for the post

- date: this is auto filled with the post creation date, but can be updated in the CMS

- featured media (optional): the CMS is set to include multiple media types. Right now the options are image and YouTube Embed. This has nested items for image path and caption/alt text

- post content (optional): A simple pagebuilder tool adds WYSIWYG, Image, or YouTube embed content to the post. You can have multiples of each content type, and you can re-order the content at will.

## Authenticate on Netlify

With the configuration already set-up, you'll just need to [follow these steps to enable authentication on Netlify](https://www.netlifycms.org/docs/add-to-your-site/#authentication).


Once the CMS is set up, you can access it via  {yoursite.com}/admin

You can add content to the `about` modal via the Site Settings -> Site Info field.

You can create new posts or edit existing posts via the `Post` post type.



Although the purpose of this theme is somewhat esoteric in its exclusion of blogger "must-haves", you _can_ work around the limitations by leveraging the WYSIWYG editor in the `Post` post type if you desire.


## Plugins

### [Jekyll SEO Tag](https://github.com/discoform/shapes-for-jekyll-and-snipcart/projects/1)

A Jekyll plugin to add metadata tags for search engines and social networks to better index and display your site's content.


### [Jekyll Sitemap](https://github.com/jekyll/jekyll-sitemap)
Jekyll plugin to silently generate a sitemaps.org compliant sitemap for your Jekyll site.


### [Jekyll Autoprefixer](https://github.com/vwochnik/jekyll-autoprefixer)
This plugin provides simple autoprefixer support for Jekyll. To ensure compatibility with the latest version of JekyllI've clamped the `execjs` gem to version 2.7.0, [per this issue](https://github.com/ai/autoprefixer-rails/issues/160)

### [Jekyll Picture Tag](https://github.com/rbuchberger/jekyll_picture_tag)

The current configuration automatically builds resized images for most of your image library. I have not enabled `.webp` generation because the degradation in image sharpness is a little gross to look at. The settings can be found in `_data/picture.yml` if you're feeling adventurous.