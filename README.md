## Thanks

Thanks to [Karl Broman](https://kbroman.org/about.html) for his
[template](https://kbroman.org/simple_site/pages/independent_site) and guidelines to set up my personal page using github pages.


## Custom domain
The page [christianepeters.github.io](https://christianepeters.github.io/) points to my custom domain [cbcrypto.org](https://cbcrypto.org).

General info on how to configure:
* [Configuring a custom domain for your github pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
* Settings / Pages / Custom Domain: I set the custom domain to `www.cbcrypto.org`, so [cbcrypto.org](https://cbcrypto.org) will redirect to [www.cbcrypto.org](https://www.cbcrypto.org). I tried the other way round and ran into certificate issues. See [here](https://stackoverflow.com/questions/9082499/custom-domain-for-github-project-pages) for the general explanation.

## DNS config
* I bought my domain from [namecheap.com/](https://www.namecheap.com/) and configured
  * Domain / Nameservers: `Namecheap BasicDNS`
  * Advanced DNS:
    | Type 	       |Host | Value                       | TTL       |
    | -------------|-----|-----------------------------|-----------|
	  | A Record 	   | @   | 185.199.108.153             | Automatic |
	  | A Record 	   | @   | 185.199.109.153             | Automatic |
	  | A Record     | @   | 185.199.110.153             | Automatic |
	  | A Record     | @   | 185.199.111.153             | Automatic |
    | AAAA Record  | @   | 2606:50c0:8001::153         | Automatic |
    | AAAA Record  | @   | 2606:50c0:8002::153         | Automatic |
    | AAAA Record  | @   | 2606:50c0:8003::153         | Automatic |
    | AAAA Record  | @   | 2606:50c0:8000::153         | Automatic |
    | CNAME Record | www | christianepeters.github.io. | Automatic |


