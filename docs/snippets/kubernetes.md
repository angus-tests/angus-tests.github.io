---
layout: default
title: Kubernetes
parent: Snippets
---


# Kubernetes snippets

This page contains the most commonly used Kubernetes commands for the command line, the command line tools are known as **kubectl** and the full list of commands can be found [Here](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

> **_NOTE:_**  All the snippets shown on this page will use "kc" this will only work if you have a bash alias configured, if you do not add the following to your bash profile
```bash
alias kc="kubectl"
```



## Get pods

```bash
kc get pods
```