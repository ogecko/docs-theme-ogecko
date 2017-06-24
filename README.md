# docs-theme-ogecko
A pure, simple and responsive Hexo theme for documenting technical information eg architecture, design, api, and process. Inspired by the [Meteor Guide](https://guide.meteor.com/) and [API Docs](http://docs.meteor.com/).

Includes support for the following features
* Navigation autogen sidebar and menu
* Code Signatures using JSdoc and apibox
* Google analytics and Segment Tracking
* Search and Indexing using Lunr and Algolia 
* Website Notification via Twitter using Nectar Ninja

## Adding this Theme to a Hexo site
1. Add this respository as a submodule to your site.

```
$ git submodule add  https://github.com/ogecko/docs-theme-ogecko/ yourproject/themes/ogecko
```

2. Edit the `_config.yml` file and change the following

```
theme: ogecko
api_box:
  data_file: 'data/data.js'
```


## Known **oGecko** repos that this theme is used by:
* https://github.com/ogecko/docs-api/
* https://github.com/ogecko/docs-kb/
* https://github.com/ogecko/docs-process/

If a change to this theme is made, those repos need their Git submodules updated.
