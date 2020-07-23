# computersecuritytips_info
Blog about computer security tips for everyday folk. Hugo-based static blog.

## Building for local view

```
(cd themes/minimo && npm run build) && hugo server -D --disableFastRender
```

## Building for deployment

```
HUGO_ENV=production HUGO_BASEURL='https://computersecuritytips.info' hugo --buildDrafts --destination build
```