# Roadmap.DO - The Drivly Open Roadmap

## The Jeff Bezos API Mandate

Amazon started as an online bookstore, but it became what it is today through Jeff's Bezos 2002 memo mandating that everything being built at Amazon must have an API:

> 1. All teams will henceforth expose their data and functionality through service interfaces.
> 2. Teams must communicate with each other through these interfaces.
>    ...
> 5. All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.
> 6. Anyone who doesn’t do this will be fired.
> 7. Thank you; have a nice day!

## Communicate via APIs instead of Meetings

Brian Armstrong, Founder and CEO at Coinbase, in a letter to software engineers he demanded his team communicate via APIs instead of meetings. 

He directed his team to: 
> 1. “publish APIs so that other teams can benefit from what they’re building without ever needing to schedule a meeting.”
> 2. “productize their services and allow other teams to use them in a self-service way.”
> 
> If you want to know my honest opinion, frankly, I will do anything to avoid meetings. So I preach it.

## Do one thing, and do it well

Additionally, we want to embrace the Unix philosophy of:
- Do one thing, and do it well
- Expect the output of one program to be the input of a yet unknown other program
- Design and build software to be tried early
- Use tools instead of labor to automate tasks and solve problems

These are philosophies that we strongly believe at Drivly as well. 

## The Drivly Stack

Our core business consists of three layers:

```
Data -> Services -> Commerce
```

Data powers the services, and the data and services power the commerce.

But underneath the Data and Services layers, there are hundreds of lower-level abstractions.  Rather than allowing our higher-level code to bloat with lower-level concepts, we are going to be open-sourcing 100+ production-ready APIs that are valuable in and of themselves, but the greatest value is when they can be used as building blocks to rapidly assemble higher-order concepts and APIs.

## Primitives

- alarms.do
- alerts.do
- bindings.do - Service Binding Proxy Mesh
- [count.do](https://count.do) - Count Service
- [camel.case.do](https://camel.case.do) - Convert Text and JSON Object Keys to camelCase
- cname.do - Dynamic CNAME Proxy
- events.do -
- ddns.do - Dynamic DNS Service
- debug.do - 
- decode.do - 
- [decrypt.do](https://decrypt.do) - Decrypt Data
- [encrypt.do](https://encrypt.do) - Encrypt Data
- [fetch.do](https://fetch.do)
- [fetcher.do](https://fetcher.do)
- [flatten.do](https://flatten.do) - Flatten JSON Objects
- [hashes.do](https://hashes.do) - Generate and Validate Hashes
- hostname.do
- [kebab.case.do](https://kebab.case.do) - Convert Text and JSON Object Keys to kebab-case
- lists.do
- lodash.do
- modules.do
- obj.do
- [json.path.do](https://json.path.do) - JSON Path Transformer
- pkg.do 
- [pipe.do](https://pipe.do) - Unix Pipes in the Cloud
- [queue.do](https://queue.do) - FIFO (First-In First-Out) Queue
- [screaming.snake.case.do](https://screaming.snake.case.do) - Convert Text and JSON Object Keys to SCREAMING_SNAKE_CASE
- [snake.case.do](https://snake.case.do) - Convert Text and JSON Object Keys to snake_case
- [stacks.do](https://stacks.do) - LIFO (Last-In First-Out) Stack
- repo.do
- [req.do](https://req.do) - Capture Requests & Responses
- rewrites.do
- [title.case.do](https://title.case.do) - Convert Text and JSON Object Keys to Title Case
- schema.do
- [state.do](https://state.do) - Finite State Machine
- swr.do - Stale While Refresh Cached Proxy
- [un.flatten.do](https://un.flatten.do) - UnFlatten JSON Objects
- webhooks.do
- zones.do

## Utilities

- [api.qa](https://api.qa) - Hypermedia-driven Automated API Testing
- benchmark.do
- [colo.do](https://colo.do) 
- cors.do - CORS API Proxy
- logs.do

## API Foundations

- [triggers.do](https://triggers.do)
- [searches.do](https://searches.do)
- [actions.do](https://actions.do)

## API Utilities

- [apikeys.do](https://apikeys.do) - API Key Management & Analytics
- [crud.do](https://crud.do) - Dynamic Hypermedia-driven RESTful CRUD APIs
- rate.limit.do

## Security

- jwt.do
- keys.do
- [oauth.do](https://oauth.do)

## Database

- [graphdl.org](https://graphdl.org) - Graph Definition Language
- [graph.do](https://graph.do) - Managed Version of the GraphDL Reference Implementation
- database.do
- backups.do
- imports.do
- exports.do
- [bases.do](https://bases.do) - Airtable Base API Proxy to manage Airtable Rate Limits and prevent data loss
- sheet.do
- redis.do - Redis-compatible API on Durable Objects

## Data Transformation

- transform.do
- mashup.do
- scraper.do

## Communication

- emails.do
- texts.do
- discord.do
- slack.do
- drip.do

## Integration

- zaps.do - 

## Storage

- bucket.do

## Analytics

- analytics.do

## Workflows

- approvals.do
- flows.do
- workflows.do

## Product 

- features.do
- flags.do
- products.do

## Websites

- blogs.do
- content.do
- landing.do
- pages.do
- sites.do

## Marketing 

- hunts.do - Product Hunt Launch Automation
- flags.do
- waitlist.do

## Open Source

- sponsors.do - Drivly's GitHub Sponsor Application Form

## Startups

- startups.do
- drip.do - Automated Email Drip Campaigns
- interns.do
- careers.do
- monetize.do
- okr.do
- id8.do - Ideation tracking

## SaaS

- users.do

## Automotive Data

- dealers.do
- lenders.do
- listings.do
- makes.api.auto.dev - 
- vin.api.auto.dev - 
- listings.api.auto.dev - 


## Horizontal Services

- turk.do - Mechanical Turks API
- concierge.do - 
- checkout.do - Dynamic Checkout Redirection
- esignatures.do - Simple 
- notary.do - Remote Online Notary
- payments.do - Payment Facilitatation
- [income.do](https://income.do) - Income Verification
- poa.do - Power of Attorney

## Automotive Services

- inspection.api.driv.ly - Build a new vehicle
- transport.api.driv.ly - Transport a vehicle
- finance.api.driv.ly - Finance a vehicle
- insurance.api.driv.ly - Insure a vehicle

## Automotive Commerce

- build.api.driv.ly - Build a new vehicle
- buy.api.driv.ly - Buy a new or used vehicle
- sell.api.driv.ly - Sell a new or used vehicle


## [🚀 We're hiring!](https://careers.do/apply)
[Driv.ly](https://driv.ly) is simple APIs to buy & sell cars online, funded by some of the [biggest names](https://twitter.com/TurnerNovak) in [automotive](https://fontinalis.com/team/#bill-ford) and [finance & insurance](https://www.detroit.vc)

We're building our entire infrastructure on Cloudflare Workers, Durable Objects, KV, R2, and PubSub.  If you're as passionate about these transformational technologies as we are, we'd love for you to join our rapidly-growing team.
