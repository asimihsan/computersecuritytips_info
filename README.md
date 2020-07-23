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

## DNS

### Old NS record

```
ns-1035.awsdns-01.org.
ns-468.awsdns-58.com.
ns-1917.awsdns-47.co.uk.
ns-967.awsdns-56.net.
```

### Old SOA record

```
ns-1035.awsdns-01.org. awsdns-hostmaster.amazon.com. 1 7200 900 1209600 86400
```