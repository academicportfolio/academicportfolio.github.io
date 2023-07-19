# Academic Portfolio

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