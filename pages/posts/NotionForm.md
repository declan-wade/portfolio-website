---
title: Notion Form
date: 2021/3/19
description: A simple demo to connect a form to Notion
tag: notion, react, web development 
author: You
type: post
---

# Overview:


**Final Product:** https://notion-form-sigma.vercel.app/

**Role:** Personal project

**Technology:** Next.js, React, Material UI, TypeScript, Vercel, Notion 

**Source code:** https://github.com/declan-wade/notion-form/tree/main

# Rationale:

* Web forms, especially forms for businesses are expensive, especially if you file uploads are required. I was not satisfied with the options on the market, thus I developed a flexible framework that can be deployed using a custom domain and custom blob storage solution with Notion.
* Notion is a popular task management, wiki, collaboration SaaS solution that offers a generous free tier and optional paid tier for teams. 
* Using the Notion API, this solution provides a completely free and flexible way to manage form submissions. 
* As Notion currently does not support file uploads via their API, I used Vercel Blob storage with an object URL to handle optional file submissions. 