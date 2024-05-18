---
title: Documentation
subtitle: Impact Theme Docs
description: Impact Theme Documentation
keywords: Impact Theme, Documentation
permalink: /docs
Lastmod: 2022-01-01T00:00:00.000Z
# lastModTitle: Documentation
image: /assets/images/undraw-docs.svg
imageWidth: 350px
---

### About

**A powerful theme for impactful websites** 

Beautiful and elegant company landing page theme this has a simple and minimalistic UI theme for [hugo](https://gohugo.io/) and is made with [bulma](https://bulma.io/) and is Licensed under the [MIT license](https://github.com/AcknologyHQ/impact-hugo/blob/main/LICENSE.txt)

[![license](https://img.shields.io/badge/license-MIT-blue.svg?logo=github)](https://github.com/AcknologyHQ/impact-hugo/blob/main/LICENSE.txt)

### Getting Started

Add the theme as git submodule to your hugo project.

```shell
$ cd /path/to/hugo/project

$ git submodule add https://github.com/AcknologyHQ/impact-hugo.git themes/impact
```

Configure your theme in your hugo project.

example config: `config.yaml`

```yaml
baseURL: "http://example.org"
languageCode: en-us
title: WEBSITE_TITLE

theme: impact

####
## Hugo Options
####

# Disable unwanted features
disableKinds:
    - RSS
    - taxonomy
    - term

disableHugoGeneratorInject: "true"

minify:
    minifyOutput: "true"
    tdewolff:
        html:
            keepComments: "true"
            keepQuotes: "true"

# Enable this to use html in markdown files
# markup:
#     goldmark:
#         renderer:
#             unsafe: "true"

####
## Theme Options
####

googleAnalytics: UA-XXXXX-X
enableRobotsTXT: "true"

params:
    icon: assets/icon.png

    # [Optional] Pages in the footer
    privacyPage: /privacy/
    termsPage: /terms/

    # [Optional] Custom last modified title
    lastModTitle: Last modified on

    # [Optional]
    footer:
        title: Impact Theme
        subtitle: A powerful theme for impactful websites

    # if you want to use custom copyright text
    # copyright:
    #     text: "YOUR_COMPANY_NAME"
    #     url: "COMPANY_URL"
    #     target: _blank
        
    social:
        - name: github
          icon: fa-github
          url: "GITHUB_URL"
        - name: twitter
          icon: fa-twitter
          url: "TWITTER_URL"
        - name: instagram
          icon: fa-instagram
          url: "INSTAGRAM_URL"
        - name: facebook
          icon: fa-facebook-square
          url: "FACEBOOK_URL"
        - name: linkedin
          icon: fa-linkedin
          url: "LINKKEDIN_URL"
        - name: youtube
          icon: fa-youtube
          url: "YOUTUBE_URL"

```

<br>
<br>


#### Other Options

**to hide**

powered by text: _`HidePoweredBy: "true"`_

made with text: _`HideMadeWith: "true"`_
