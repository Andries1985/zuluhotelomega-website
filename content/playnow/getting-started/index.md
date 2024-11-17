---
title: "Getting started on Zuluhotel Omega"
description: "How to start playing on Zuluhotel Omega. Step-by-step instructions. Please read carefully."
# linkTitle:
date: 2024-11-16T11:47:31+01:00
draft: false
noindex: false
featured: true
pinned: true
nav_weight: 1
nav_icon:
  vendor: bootstrap
  name: play
  color: green
categories:
  - Guide
tags:
  - Installation
images:
  - /images/installation.jpeg
# menu:
#   main:
#     weight: 100
#     params:
#       icon:
#         vendor: bs
#         name: book
#         color: '#e24d0e'
---

Below are the instructions on how to get started. Please read carefully. If you have any issues contact us on Discord.

{{< bs/alert danger >}}
{{< markdownify >}}
Please download and install [Ultima Online 9th Anniversary](https://mega.nz/file/w4EyGK5Q#Kbr5zlKhffrdtsBxLy3M4huotLMl6vKiLtO-LcRWFTQ) first. Make sure NOT to update it.
{{< /markdownify >}}
{{< /bs/alert >}}

## Requirements

- A fresh installed Ultima Online 9th anniversary edition that hasn't been updated.

## Step 1: Download the Zuluhotel Omega shard files

Download our [shard files]().

## Copy the Example Site

```sh
cp -r theme-cards/exampleSite mysite
```

## Change Working Directory

```sh
cd mysite
```

## Tweak `go.mod`

{{< bs/alert >}}
{{< markdownify >}}
This guide uses `sed` command to edit the file, please feel free to open and edit the `go.mod` with your favorite editor.
{{< /markdownify >}}
{{< /bs/alert >}}

### Replace Module Path

The module path is the identifier of your site, which typically is your repo URL, take `github.com/user/repo` as an example, you'll need to replace the `module github.com/hbstack/theme-cards/exampleSite` with `module github.com/user/repo`.

```sh
sed -i '1s/.*/module github.com\/user\/repo/' go.mod
```

### Delete the `replace` Directive

To build the site successfully, you'll need to delete the internal used `replace` directive: `replace github.com/hbstack/theme-cards => ../`.

```sh
sed -i '/^replace/d' go.mod
```

## Install Dependencies

```sh
npm ci
```

## Hugo Module Proxy (Optional)

A [Hugo module proxy](https://hugomods.com/blog/2023/04/go-and-hugo-proxy-servers/) is required when the default proxy isn't accessible from your location, i.e. China.

## Preview Locally

```sh
npm run dev
```

## What's Next?

1. Tweak Configurations, such as `baseURL`, `giscus.*` and so on.
2. Remove testing content.
3. Read the [documentation](https://hbstack.dev/).
4. Find more [modules](https://hbstack.dev/modules/).
