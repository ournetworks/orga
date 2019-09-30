# Our Networks: Website

The Our Networks [website](https://ournetworks.ca) code is on [GitHub](https://github.com/ournetworks/ournetworks.ca), which auto-deploys to a [Digital Ocean](https://digitalocean.com) Droplet using [Travis CI](https://travis-ci.org).

Our DNS registrar is [Namecheap](https://namecheap.com) with name server pointed to Digital Ocean, which allows us to use its APIs to update DNS records with our CI process as needed. For example, our website is published to [Dat](https://dat.foundation) and [IPFS](https://ipfs.io), and our CI publishes the latest IPFS content hash of our website as a TXT record on `ipfs-website.ournetworks.ca`.
