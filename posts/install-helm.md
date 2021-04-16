---
title: Install Helm
published: false
description: Install helm with shell
tags: 'tutorial, linux'
cover_image: null
canonical_url: null
id: null
---


### Get the latest code

The following gets the latest installation script and saves it to 
`get_helm.sh` file.

```sh
curl https://raw.githubusercontent.com/kubernetes/helm/master/scripts/get > get_helm.sh
```

### Add `700` permissions

```sh
chmod 700 get_helm.sh
```

### Run the script

```sh
./get_helm.sh
```
