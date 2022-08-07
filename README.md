# Roadmap.DO - The Drivly Open Roadmap

## The Jeff Bezos API Mandate

Amazon started as an online bookstore, but it became what it is today through Jeff's Bezos 2002 memo mandating that everything being built at Amazon must have an API:

> 1. All teams will henceforth expose their data and functionality through service interfaces.
> 2. Teams must communicate with each other through these interfaces.
>    ...
> 5. All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.
> 6. Anyone who doesn’t do this will be fired.
> 7. Thank you; have a nice day!

Brian Armstrong, Founder and CEO at Coinbase, in a letter to software engineers he demanded his team communicate via APIs instead of meetings. 

He directed his team to: 
> 1. “publish APIs so that other teams can benefit from what they’re building without ever needing to schedule a meeting.”
> 2. “productize their services and allow other teams to use them in a self-service way.”
> 
> If you want to know my honest opinion, frankly, I will do anything to avoid meetings. So I preach it.

These are philosophies that we strongly believe at Drivly as well. 

Our core business consists of three layers:

```
Data -> Services -> Commerce
```

Data powers the services, and the data and services power the commerce.

But underneath the Data and Services layers, there are hundreds of lower-level abstractions.  Rather than allowing our higher-level code to bloat with lower-level concepts, we are going to be open-sourcing 100+ production-ready APIs that are valuable in and of themselves, but the greatest value is when they can be used as building blocks to rapidly assemble higher-order concepts and APIs.

### Primitives

- alarms.do
- alerts.do
- bindings.do - Service Binding Proxy Mesh
- count.do - Count Service
- cname.do - Dynamic CNAME Proxy
- events.do -
- ddns.do - Dynamic DNS Service
- debug.do - 
- decode.do - 
- fetch.do
- hostname.do
- lists.do
- lodash.do
- modules.do
- obj.do
- pkg.do 
- queue.do - FIFO implementation on Durable Objects
- stacks.do - LIFO implementation on Durable Objects
- repo.do
- rewrites.do
- schema.do
- swr.do - Stale While Refresh Cached Proxy
- webhooks.do
- zones.do

### Utilities

- api.qa - Hypermedia-driven Automated API Testing
- benchmark.do
- colo.do 
- cors.do - CORS API Proxy
- logs.do

### APIs

- apikeys.do
- crud.do - Dynamic Hypermedia-driven RESTful CRUD APIs
- rate.limit.do

### Security

- jwt.do
- keys.do
- oauth.do

### Database

- graphdl.org
- graph.do
- database.do
- backups.do
- imports.do
- exports.do
- bases.do - Airtable Base API Proxy to manage Airtable Rate Limits and prevent data loss
- sheet.do

### Data Transformation

- transform.do
- mashup.do
- scraper.do

### Communication

- emails.do
- texts.do
- discord.do
- slack.do
- drip.do

### Integration

- zaps.do - 

### Storage

- bucket.do

### Analytics

- analytics.do

### Workflows

- approvals.do
- flows.do
- workflows.do

### Product 

- features.do
- flags.do
- products.do

### Websites

- blogs.do
- content.do
- landing.do
- pages.do
- sites.do

### Marketing 

- hunts.do - Product Hunt Launch Automation
- flags.do
- waitlist.do

### Open Source

- sponsors.do - Drivly's GitHub Sponsor Application Form

### Startups

- startups.do
- drip.do - Automated Email Drip Campaigns
- interns.do
- careers.do
- monetize.do
- okr.do
- id8.do - Ideation tracking

### SaaS

- c

### Automotive Data

- dealers.do
- lenders.do
- listings.do
- makes.api.auto.dev - 
- vin.api.auto.dev - 
- listings.api.auto.dev - 


### Horizontal Services

- turk.do - Mechanical Turks API
- concierge.do - 
- checkout.do - Dynamic Checkout Redirection
- esignatures.do - Simple 
- notary.do - Remote Online Notary
- payments.do - Payment Facilitatation
- income.do - Income Verification
- poa.do - Power of Attorney

### Automotive Services

- inspection.api.driv.ly - Build a new vehicle
- transport.api.driv.ly - Transport a vehicle
- finance.api.driv.ly - Finance a vehicle
- insurance.api.driv.ly - Insure a vehicle

### Automotive Commerce

- build.api.driv.ly - Build a new vehicle
- buy.api.driv.ly - Buy a new or used vehicle
- sell.api.driv.ly - Sell a new or used vehicle
