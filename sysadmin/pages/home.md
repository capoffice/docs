---
title: Home
sort: 100
---

# MD-CMS

This is the default startpage for MD-CMS. 

## Testing MD-CMS

If you want to test `MD-CMS` you can grab `samplesite` from the repo and place the content in your website root. This page (`pages/home.md`) won't be replaced.

**Post listing tests** below contains various custom tags to display posts. There are no posts now, but if you download the `samplesite` it will fetch the posts in 

## Post listing tests

## Reverse chronological (newest first)

```mdcms
posts-date-reversechronological
limit: 3
paginate: no
```

## Chronological (oldest first)

```mdcms
posts-date-chronological
limit: all
paginate: none
```

## By year (date, reverse chrono)

```mdcms
posts-date-reversechronological-byyear
limit: all
defaultyear: current
selectyear: yes
paginate: none
```

## By year+month (datetime, chrono)

```mdcms
posts-datetime-chronological-byyearmonth
limit: all
defaultyear: 2024
selectyear: yes
```

## Last 30 days

```mdcms
posts-date-reversechronological-lastmonth
limit: all
paginate: none
```

## Paginated (2 per page)

```mdcms
posts-datetime-reversechronological
limit: 2
paginate: yes
```
