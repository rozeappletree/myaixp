# `myaixp.com`


### Linking domain to gh pages

Add `A record` with `@` host in DNS records. And `CNAME record` with `www` host with 60mins.

```
A  @  185.199.108.153  AUTO TTL
A  @  185.199.109.153  AUTO TTL
A  @  185.199.110.153  AUTO TTL
A  @  185.199.111.153  AUTO TTL
CNAME Record  www  rozeappletree.github.io  60mins TTL
```

source: 

- [x] https://www.youtube.com/watch?v=2K7asqt8wMw
- [x] https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain
- [ ] https://thomasgauvin.com/writing/setting-up-a-subdomain-github-pages-namecheap/
- [ ] https://www.namecheap.com/support/knowledgebase/article.aspx/9678/2237/how-to-redirect-subdomain-to-a-certain-ip-address-along-with-a-port/
---

heavily inspired by dongyado's blog: http://dongyadoit.com
