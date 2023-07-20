# Academic Portfolio

A Github Pages template for academic portfolio websites.

## Instructions

1. Register a [Github](https://github.com/) account and verify your email address. (If you don't have any)
2. Fork [this repository](https://github.com/academicportfolio/academicportfolio.github.io) by clicking the **Fork** button in top-right.
3. From repository settings, change the name of your forked repository to `your-github-username.github.io`.
4. Modify site-wide configurations to match your requirements from `_config.yml`.
5. Upload any files (e.g pdf, zip etc.) to **files/** directory. These files will appear at https://[your-github-username].github.io/files/example.pdf.
6. To change the site avatar/logo, add your avatar in **assets/images** directory. Modify `_config.yml` to reflect your avatar's filename in `avatar-filename` variable.
```
avatar-filename: <yourFileName.jpg>
```
7. Replace **assets/favicon.png** with your own favicon.
8. To change site contents, add/modify files in different collection's directories.
  - Experience: Add/modify the contents from **_experiences** directory.
  - Education: Add/modify the contents from **_education** directory.
  - Skills: Add/modify the contents from **_skills** directory.
  - Projects: Add/modify the contents from **_projects** directory.
  - Publications: Add/modify the contents from **_publications** directory.
  - Certifications: Add/modify the contents from **_certifications** directory.
  - Achievements: Add/modify the contents from **_achievements** directory.
9. To add/modify blog posts, modify the contents in **_posts** directory. Follow the given filename structure for blog post e.g. `YYYY-MM-DD-my-post-title.md`.
10. After github pages deployment, your site will be available at `your-github-username.github.io`

## Enable Disqus Comments on Posts

- Sign up at [Disqus](disqus.com)
- Register your github site with disqus.
- Get Disqus shortname in admin>settings>general
- Edit your `_config.yml` of github, make sure it contains following content:
```
disqus:
    shortname: <your disqus short name>
```

## Enable Contact Form
- Sign up at [Formspree](https://formspree.io/)
- Create a new form and get the form's endpoint.
- Edit your `_config.yml` of github, make sure it contains following content:
```
formspree:
  endpoint: <form's endpoint> # e.g https://formspree.io/f/xxxxxxx
```

## Adding Google Analytics Tracking
- Login to [Google Analytics](https://analytics.google.com/) and create a new property to receive a Tracking ID for your website.
- Edit your `_config.yml` of github, make sure it contains following content:
```
google_analytics: UA—XXXXXXXX-X
```

## Bug Report/Feature Request
- To report bugs or to request new features, please create a new [issue](https://github.com/academicportfolio/academicportfolio.github.io/issues) and use appropriate label with the issue.