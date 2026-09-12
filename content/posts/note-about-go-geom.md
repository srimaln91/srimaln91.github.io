---
title: "A note about go-geom"
date: 2026-09-09T00:00:00-04:00
description: "effort to bring some of the capabilities of established C/C++ geospatial libraries into the Go ecosystem"
summary: "An optional text snippet that overrides the automatic list page summary."
draft: false
tags: ["CGO", "GoLang", "GeoSpatial"]
categories: ["tech"]
author: "Srimal"

# PaperMod Specific Features
showToc: true
TocOpen: false
readingTime: true
replyByEmail: false
comments: true
canonicalURL: ""
disableHLJS: false
disableShare: false
hideSummary: true
searchHidden: false

# Cover Image Configuration
cover:
  image: "images/geom-cover.png" # path relative to your static/ folder or a full URL
  alt: "The cover image of the post"
  caption: ""
  relative: false # when true, path is relative to the post folder
  hidden: false # hide cover image from the post page itself, keep on list page
  hiddenInList: true
---

A project I worked on some time ago that I still look back on with a lot of interest is go-geom, a Go library for geospatial operations.

It was an effort to bring some of the capabilities of established C/C++ geospatial libraries such as GEOS, liblwgeom, and PROJ into the Go ecosystem through Go bindings. It supported operations such as geometry manipulation, coordinate transformations, buffering, GeoJSON/WKT handling, and other geospatial calculations.

What made the project interesting was working at the boundary between Go and native C/C++ code. It was a great learning experience in areas such as CGO, memory management, native library integration, and understanding how complex geospatial algorithms are implemented underneath higher-level APIs.

It was completed several years ago, but it remains one of the projects I really enjoyed working on. It just brings back some nostalgic memories. :)

[See the project on GitHub](https://github.com/srimaln91/go-geom)