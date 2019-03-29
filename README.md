<p align="center">
<a href="https://pi-hole.net"><img src="https://pi-hole.github.io/graphics/Vortex/Vortex_with_text.png" width="150" height="255" alt="Pi-hole"></a><br/></br>
<b>Network-wide ad blocking via your own Linux hardware</b><br/>
</br>
<a href="https://pi-hole.net"><img src="https://pi-hole.github.io/graphics/Screenshots/pihole-dashboard.png" alt="Pi-hole Web interface"></a><br/>
</p>

<a href="https://biztactix.com.au">Biztactix</a> Fork from the original AdminLTE


Pi-hole[®](https://pi-hole.net/trademark-rules-and-brand-guidelines/)'s Web interface (based off of [AdminLTE](https://almsaeedstudio.com))  provides a central location to manage your Pi-hole and review the statistics generated by FTLDNS[™](https://pi-hole.net/trademark-rules-and-brand-guidelines/).

- **Easy-to-interpret**: simple graphs and beautiful colors make Pi-hole's stats easy to understand
- **Responsive**: looks great on desktop, tablets, and mobile devices
- **Useful**: control and configure your Pi-hole with our settings
- **Insightful**: use the query log, audit log, or long-term stats to gain insight into your networks activity

---
<a class="badge-align" href="https://www.codacy.com/app/Pi-hole/AdminLTE?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pi-hole/AdminLTE&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/10540ea45a3b4d5f992c05a2c9714609"/></a>
<img src="https://pi-hole.github.io/graphics/Badges/browserstack-badge.png" height="80"><br>

# Installation

The Web interface is enabled by default when you install Pi-hole.

## Post-installation: access the Web interface and gain insight into your network's activity
There are several ways to [access the dashboard](https://discourse.pi-hole.net/t/how-do-i-access-pi-holes-dashboard-admin-interface/3168):

1. `http://<IP_ADDPRESS_OF_YOUR_PI_HOLE>/admin/`
2. `http:/pi.hole/admin/` (when using Pi-hole as your DNS server)
3. `http://pi.hole/` (when using Pi-hole as your DNS server)

Once logged in (forgot your password?), you can view your network stats to see things like:

- the domains being queried on your network
- the time the queries were initiated
- the amount of domains that were blocked
- the upstream server queries were sent to
- the type of queries (`A`, `AAAA`, `CNAME`, `SRV`, `TXT`, etc.)
---

## Pi-hole is free, but powered by your support
There are many reoccurring costs involved with maintaining free, open source, and privacy respecting software; expenses which [our volunteer developers](https://github.com/orgs/pi-hole/people) pitch in to cover out-of-pocket. This is just one example of how strongly we feel about our software, as well as the importance of keeping it maintained.

Make no mistake: **your support is absolutely vital to help keep us innovating!**

### Donations
Sending a donation using our links below is **extremely helpful** in offsetting a portion of our monthly expenses:

- <img src="https://pi-hole.github.io/graphics/Badges/paypal-badge-black.svg" width="24" height="24" alt="PP"/> <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3J2L3Z4DHW9UY">Donate via PayPal</a><br/>
- <img src="https://pi-hole.github.io/graphics/Badges/bitcoin-badge-black.svg" width="24" height="24" alt="BTC"/> [Bitcoin](https://commerce.coinbase.com/checkout/fb7facaf-bebd-46be-bb77-b358f4546763): <code>1GKnevUnVaQM2pQieMyeHkpr8DXfkpfAtL</code></br>
- <img src="https://pi-hole.github.io/graphics/Badges/bitcoin-badge-black.svg" width="24" height="24" alt="BTC"/> [Bitcoin Cash](https://commerce.coinbase.com/checkout/fb7facaf-bebd-46be-bb77-b358f4546763): <code>qqh25hlmqaj99xraw00e47xmf8sysnyxhyww2d7dnh</code></br>
- <img src="https://pi-hole.github.io/graphics/Badges/ethereum-badge-black.svg" width="24" height="24" alt="BTC"/> [Ethereum](https://commerce.coinbase.com/checkout/fb7facaf-bebd-46be-bb77-b358f4546763): <code>0xF00aF43d2431BAD585056492b310e48eC40D87e8</code>

### Alternative support
If you'd rather not [donate](https://pi-hole.net/donate/) (_which is okay!_), there are other ways you can help support us:

- [Patreon](https://patreon.com/pihole) _Become a patron for rewards_
- [Digital Ocean](http://www.digitalocean.com/?refcode=344d234950e1) _affiliate link_
- [Stickermule](https://www.stickermule.com/unlock?ref_id=6055890701&utm_medium=link&utm_source=invite) _earn a $10 credit after your first purchase_
- [Pi-hole Swag Store](https://pi-hole.net/shop/) _affiliate link_
- [Amazon](http://www.amazon.com/exec/obidos/redirect-home/pihole09-20) _affiliate link_
- [DNS Made Easy](https://cp.dnsmadeeasy.com/u/133706) _affiliate link_
- [Vultr](http://www.vultr.com/?ref=7190426) _affiliate link_
- Spreading the word about our software, and how you have benefited from it

### Contributing via GitHub
We welcome _everyone_ to contribute to issue reports, suggest new features, and create pull requests.

If you have something to add - anything from a typo through to a whole new feature, we're happy to check it out! Just make sure to fill out our template when submitting your request; the questions that it asks will help the volunteers quickly understand what you're aiming to achieve.

### Presentations about Pi-hole
Word-of-mouth continues to help our project grow immensely, and so we are helping make this easier for people.

If you are going to be presenting Pi-hole at a conference, meetup or even a school project, [get in touch with us](https://pi-hole.net/2017/05/17/giving-a-presentation-on-pi-hole-contact-us-first-for-some-goodies-and-support/) so we can hook you up with free swag to hand out to your audience!

-----

## Getting in touch with us
While we are primarily reachable on our <a href="https://discourse.pi-hole.net/">Discourse User Forum</a>, we can also be found on a variety of social media outlets. **Please be sure to check the FAQ's** before starting a new discussion, as we do not have the spare time to reply to every request for assistance.

<ul>
  <li><b><a href="https://discourse.pi-hole.net/c/faqs">Frequently Asked Questions</a></b></li>
  <li><b><a href="https://github.com/pi-hole/pi-hole/wiki">Pi-hole Wiki</a></b></li>
  <li><b><a href="https://discourse.pi-hole.net/c/feature-requests?order=votes">Feature Requests</a></b></li>
  <li><a href="https://discourse.pi-hole.net/">Discourse User Forum</a></li>
  <li><a href="https://www.reddit.com/r/pihole/">Reddit</a></li>
  <li><a href="https://twitter.com/The_Pi_Hole">Twitter</a></li>
  <li><a href="https://www.facebook.com/ThePiHole/">Facebook</a></li>
  <li><a href="https://gitter.im/pi-hole/pi-hole">Gitter</a> (Real-time chat)</li>
  <li><a href="https://www.youtube.com/channel/UCT5kq9w0wSjogzJb81C9U0w">YouTube</a></li>
</ul>

# Features

## Mobile friendly interface
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/mobile-friendly.png" height="300" alt="Mobile friendly"></a>
</p>

## Password protection
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/password-protection.png" height="400" alt="Password protection"></a>
</p>

## Detailed graphs and doughnut charts
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/piecharts.png" alt="Pie charts"></a>
</p>

## Top lists of domains and clients
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/topdomains-clients.png" alt="Top domains/top clients"></a>
</p>

## A filterable and sortable query log
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/query-log-sorted.png" alt="Query log"></a>
</p>

## An audit log
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/audit-log.png" alt="Pi-hole Web interface"></a>
</p>

## Long Term Statistics to view data over user defined time ranges
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/long-term-stats.png" alt="Long-term stats"></a>
</p>

## A built-in debugger
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/debug.png" alt="Debugger"></a>
</p>

## Black and white lists
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/blacklist.png" alt="Blacklist"></a>
</br></br>
<img src="https://pi-hole.github.io/graphics/Screenshots/whitelist.png" alt="Whitelist"></a>
</p>

## The ability to easily manage and configure Pi-hole features
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/dashboard-settings.gif" alt="Settings"></a>
</p>

## ... and all the main features of the Command Line Interface!
<p align="center">
<img src="https://pi-hole.github.io/graphics/Screenshots/pihole-t.png" alt="Tail the log"></a>
</br></br>
<img src="https://pi-hole.github.io/graphics/Screenshots/pihole-q.png" alt="Query ad lists"></a>
</p>

## API
Full usage available [here](https://discourse.pi-hole.net/t/pi-hole-api/1863).  can be accessed at `/admin/api.php`. With either no parameters or `/admin/api.php?summary` it returns the following JSON:
```JSON
{  
   "domains_being_blocked":243038,
   "dns_queries_today":2385,
   "ads_blocked_today":414,
   "ads_percentage_today":17.35849,
   "unique_domains":429,
   "queries_forwarded":1537,
   "queries_cached":434,
   "clients_ever_seen":5,
   "unique_clients":5,
   "status":"enabled"
}
```

[There are many more parameters](https://discourse.pi-hole.net/t/pi-hole-api/1863), such as:

- `type & version`
- `summaryRaw`
- `summary`
- `overTimeData10mins`
- `topItems`
- `getQuerySources`
- `getForwardDestinations`
- `getQueryTypes`
- `getAllQueries`
- `enable`
- `disable`
- `recentBlocked`

Together with a token it is also possible to [enable and disable (also with a set timeout) blocking via the API](https://discourse.pi-hole.net/t/is-there-an-api-command-to-disable-ad-blocking/7693).

The API returns more information (in a slightly different format if `FTL` is running) - it supports a fall-back to the "old" PHP API if `FTL` is not running. Test the type and/or version of the API by using the parameter `type` and `version`.
