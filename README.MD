Published at https://matkoniecz.github.io/dead_links_testing_site/

To be used in testing of dead link detector script(s)

Recommended tool: [htmlproofer](https://github.com/gjtorikian/html-proofer)

```
git clone https://github.com/matkoniecz/dead_links_testing_site
cd dead_links_testing_site
htmlproofer . --assume-extension --check-html --check-favicon --log-level warn
```

See also [other tools I considered](https://github.com/matkoniecz/website-checklist/blob/master/validators.md#detecting-dead-links)
