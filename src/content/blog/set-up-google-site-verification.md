---
title: Setting up Google Site Verification # CHANGE
author: Sound of Dialup
pubDatetime: 2023-08-12T17:10:34.188Z # CHANGE THE TIME
postSlug: set-up-google-site-verification # CHANGE
featured: false
draft: false
tags:
  - webdev # CHANGE
  - google
  - SEO
description: How to set up Google Site Verification. # CHANGE
---

Today I had to figure out how to set up Google Site Verification. According to ChatGPT (... heh), one of the benefits of GSV is receiving alerts if there are crawl errors, mobile usability problems, or security issues. I also wouldn't be surprised if it upped your ranking in Google searches, too, so figured it's worth knowing.

## Table of Contents

## Instructions

1. Head on over to [Google Search Console](https://search.google.com/search-console/ownership)
2. Add search property
3. Enter domain
4. Copy the provided string (for TXT record)
5. Go to your DNS provider (e.g. Namecheap)
6. Add new TXT record for `@` and paste the string from _Step 3_ as the Value.

![Screenshot of Namecheap's DNS settings, showing: Type = TXT Record, Host = @, Value = google-site-verification=(rest of string here), TTL = Automatic](/assets/google-site-verification-namecheap-txt-record.jpg "Namecheap DNS record")

Example Namecheap DNS record.

## What's all this then?

**[Google Site Verification](https://support.google.com/webmasters/answer/9008080?hl=en)** is a process that confirms website ownership and grants access to tools like Google Search Console, offering insights and control over a site's search performance, indexing, and security.

"**[Google Search Console](https://support.google.com/webmasters/answer/9128668?hl=en&ref_topic=9128571&sjid=12160696478003209607-AP)** is a free service offered by Google that helps you monitor, maintain, and troubleshoot your site's presence in Google Search results. You don't have to sign up for Search Console to be included in Google Search results, but Search Console helps you understand and improve how Google sees your site." (_Google_, 2023)
