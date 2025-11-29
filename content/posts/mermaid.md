---
title: Mermaid
subtitle:
date: 2025-11-29T07:07:43Z
slug: 5040c28
draft: false
author:
  name:
  link:
  email:
  avatar:
description:
keywords:
license:
comment: false
weight: 0
tags:
  - Tools
categories:
  - Tools
hiddenFromHomePage: false
hiddenFromSearch: false
hiddenFromRelated: false
hiddenFromFeed: false
summary:
resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: false
lightgallery: false
password:
message:
repost:
  enable: false
  url:

# See details front matter: https://fixit.lruihao.cn/documentation/content-management/introduction/#front-matter
---
# Diagramming Tool - Mermaid

Recently I came across one diagramming tool in mardown language and how easy it is to draw them like any other HTML script and its even simpler.

Refer [Link for syntax help](https://docs.mermaidchart.com/mermaid-oss/syntax/flowchart.html "Mermaid official")

# Mermaid ExamplesFlowcharts

```mermaid

graph TD
   	A-.->B(Process 1)
   	A-->C[[Process 2]]
   	B-==oD([Stop])
   	C-->D
```

## Class Diagrams

```mermaid
classDiagram
	class Person {
		Id: Guid
		Name: string
		LastName:string
	} 
```


```mermaid
classDiagram
	class Animal{
		+String name
		+int age
		+void makeSound()
	}
	class Dog{
		+String breed
		+void fetch()
	}
	Animal <|-- Dog
```

## Timeline Diagram

```mermaid

timeline
    title History of Social Media Platform
    2002 : LinkedIn
    2004 : Facebook
         : Google
    2005 : YouTube
    2006 : Twitter
```

## Pie chart 

```mermaid
pie title Pets adopted by volunteers
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 15
```
