<div align="center">

<img src="https://raw.githubusercontent.com/AcknologyHQ/impact-hugo/main/images/icon.png" height="80">

# Impact Theme


**Beautiful and elegant company landing page theme**

This is a simple and minimalistic UI theme for [hugo](https://gohugo.io/) made with [bulma](https://bulma.io/)

[![license](https://img.shields.io/badge/license-MIT-blue.svg?logo=github)](https://github.com/AcknologyHQ/impact-hugo/blob/main/LICENSE.txt)
[![demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://acknologyhq.github.io/impact-hugo/)

</div>

<br>

**Screenshots**

![screenshot](https://raw.githubusercontent.com/AcknologyHQ/impact-hugo/main/images/screenshot.png)

<br>

**Demo**

check out the 👉 [**LIVE DEMO**](https://acknologyhq.github.io/impact-hugo/)

<br>

**Installation**

Add this theme to your hugo projects `themes` directory

```bash
$ git submodule add https://github.com/AcknologyHQ/impact-hugo.git themes/impact
```

<br>

**Example Config**

Check out the **[config.yml](https://github.com/AcknologyHQ/impact-hugo/blob/main/.example/config.yml) or [config.toml](https://github.com/AcknologyHQ/impact-hugo/blob/main/.example/config.toml)** file to see how to configure your site using this theme

```yaml
####
## Sample Config for Impact Theme
####

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
        
    ## Social Media Links  
    social:
        - name: github
          icon: fa-github
          url: "GITHUB_URL"
        - name: twitter
          icon: fa-twitter
          url: "TWITTER_URL"
```

<br>

**Development**

```bash
# clone the repo
$ git clone https://github.com/AcknologyHQ/impact-hugo.git

# cd into the repo
$ cd impact-hugo

# run using docker-compose
$ CURRENT_UID="$(id -u):$(id -g)" docker-compose up --force-recreate -d  server
```

navigate to `http://localhost:1313`


<br>

**LICENSE**

`Copyright (c) 2022 Acknology Co.`

Licensed under **MIT LICENSE** read full text [here](https://github.com/AcknologyHQ/impact-hugo/blob/main/LICENSE.txt)

<br>