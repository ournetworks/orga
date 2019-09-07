# Our Networks Orga[nizing]

This repository contains general, as opposed to year-specific, organizing and coordinating materials for the Our Networks team.

## Infrastructures

### Website

The Our Networks [website](https://ournetworks.ca) code is on [GitHub](https://github.com/ournetworks/ournetworks.ca), which auto-deploys to a [Digital Ocean](https://digitalocean.com) Droplet using [Travis CI](https://travis-ci.org).

Our DNS registrar is [Namecheap](https://namecheap.com) with name server pointed to Digital Ocean, which allows us to use its APIs to update DNS records with our CI process as needed. For example, our website is published to [Dat](https://dat.foundation) and [IPFS](https://ipfs.io), and our CI publishes the latest IPFS content hash of our website as a TXT record on `ipfs-website.ournetworks.ca`.

### Email

Our Networks is a member of [May First](https://mayfirst.coop), which we rely on for email forwarding and our low-traffic [mailing list](https://lists.mayfirst.org/mailman/listinfo/ournetworks) services, among other infrastrusture things. 

Our email addresses are as follow.

| Email address | Purpose                                                                                                          |
|:--------------|:-----------------------------------------------------------------------------------------------------------------|
| billets@      | Coordinate community billets                                                                                     |
| coc@          | Code of Conduct reporting monitored by organizer on CoC duty                                                     |
| orga@         | Main address used for general communications and account registrations that has a forward list to all organizers |

### Financial accounts

Our Networks uses [Alterna](https://www.alterna.ca) as the main provider for financial services. Sending transactions from this account require two signatures from organizers who are registered with the financial institution.

We use [Brown Paper Tickets](https://www.brownpapertickets.com) for ticket sales of our conferences and PayPal for small international transactions such as paying honoraria.

### Videos

Conference videos are live streamed by volunteers from [Toronto Mesh](https://tomesh.net) using [IPFS Live Streaming](https://github.com/tomeshnet/ipfs-live-streaming). Post-processed video recordings are published to:

| Host                                                                | Description                                                      |
|:--------------------------------------------------------------------|:-----------------------------------------------------------------|
| [Alexandria](https://alexandria.tomesh.net)                         | Media host by Toronto Mesh that is accessible over mesh networks |
| [Internet Archive](https://archive.org/details/@our_networks)       | Hosted on Internet Archive and with torrent available            |
| IPFS on [Infura](https://infura.io)                                 | Pinned on infrastructure provided by Infura                      |
| [YouTube](https://www.youtube.com/channel/UCudGRFTjVGsrKF0h27GER2g) | YouTube playlists                                                |

### Other accounts & tools

- [GitHub](https://github.com/ournetworks) for document and code repositories, and project planning with Issues and Projects
- [Google Drive](https://drive.google.com/drive/folders/1nZ7GtlC8cmSGPTq1yxj7guthSkyt4n20) for access-controlled documents and spreadsheets
- [Google Calendar](https://calendar.google.com/calendar/embed?src=aers7atolh0uurlfmkoki9kikg%40group.calendar.google.com&ctz=America%2FToronto) for shared calendar
- [HackMD](https://hackmd.io) for collaborative note-taking before moving to GitHub for archiving
- [Jitsi](https://meet.jit.si/ournetworks) for video meetings with [VOIP call-in](https://meet.jit.si/static/dialInInfo.html?room=ournetworks)
- [Meetup](https://www.meetup.com/p2p-and-dweb-toronto/) for Our Networks and Peer-to-peer and Decentralized Web Toronto events
- [Signal](https://signal.org) group for real-time communications among organizers
- [Twitter](https://twitter.com/_ournetworks) for propaganda to the public
- [Zoom](https://zoom.us) for live presentations
