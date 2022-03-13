---
title: "Hacking with Swift - Day 2"
date: 2022-03-12T14:46:46-05:00
# weight: 1
# aliases: ["/first"]
tags: ["apple", "iOS", "swift"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Desc Text."
# canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
# cover:
#     image: "<image path/url>" # image path/url
#     alt: "<alt text>" # alt text
#     caption: "<text>" # display caption under cover
#     relative: false # when using page bundles set this to true
#     hidden: true # only hide on current single page
# editPost:
#     URL: "https://github.com/<path_to_repo>/content"
#     Text: "Suggest Changes" # edit text
#     appendFilePath: true # to append file path to Edit link
---

Paul covers `String`s and `String` interpolation.

The first checkpoint, a simple playground:

```Swift
let temperatureInCelsius = 21.4
let temperatureInFahrenheit = ((temperatureInCelsius * 9) / 5) + 32

print("The temperature is \(temperatureInCelsius) ℃ or \(temperatureInFahrenheit) ℉.")
```
