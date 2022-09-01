# Roadmap.DO - The Drivly Open Roadmap

## [Drivly](https://driv.ly)

[Drivly](https://driv.ly) is simple APIs to buy & sell cars online, funded by some of the [biggest names](https://twitter.com/TurnerNovak) in [automotive](https://fontinalis.com/team/#bill-ford) and [finance & insurance](https://www.detroit.vc)

We're building our entire infrastructure on Durable Objects and the Cloudflare Workers ecosystem as composable, open-source microservices.  

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

- alarms.do - Time-based Triggers
- alerts.do - Generate Alerts when State Changes or Conditions are Met
- bindings.do - Dymamic Service Binding Proxy Mesh
- [count.do](https://count.do) - Count Service
- [camel.case.do](https://camel.case.do) - Convert Text and JSON Object Keys to camelCase
- cname.do - Dynamic CNAME Proxy
- events.do - 
- ddns.do - Dynamic DNS Service
- debug.do - Debug HTTP Requests & APIs
- decode.do - Decode Data
- [decrypt.do](https://decrypt.do) - Decrypt Data
- [encrypt.do](https://encrypt.do) - Encrypt Data
- [fetch.do](https://fetch.do) - Fetch API
- [fetcher.do](https://fetcher.do) - Iterative & Recursive Fetcher
- [flatten.do](https://flatten.do) - Flatten JSON Objects
- [hashes.do](https://hashes.do) - Generate and Validate Hashes
- hostname.do - Dynamically Generate Domain Names
- [kebab.case.do](https://kebab.case.do) - Convert Text and JSON Object Keys to kebab-case
- lists.do 
- [lodash.do](https://lodash.do) - Lodash as REST API
- modules.do
- obj.do
- [json.path.do](https://json.path.do) - JSON Path Transformer
- pkg.do - Dynamic Package Management
- [pipe.do](https://pipe.do) - Unix Pipes in the Cloud
- [queue.do](https://queue.do) - FIFO (First-In First-Out) Queue
- [screaming.snake.case.do](https://screaming.snake.case.do) - Convert Text and JSON Object Keys to SCREAMING_SNAKE_CASE
- [snake.case.do](https://snake.case.do) - Convert Text and JSON Object Keys to snake_case
- [stacks.do](https://stacks.do) - LIFO (Last-In First-Out) Stack
- repo.do
- [req.do](https://req.do) - Capture Requests & Responses
- rewrites.do
- [title.case.do](https://title.case.do) - Convert Text and JSON Object Keys to Title Case
- [schema.do](https://schema.do) - Dynamic Schema Inference and Generation
- [state.do](https://state.do) - Finite State Machine
- swr.do - Stale While Refresh Cached Proxy
- [un.flatten.do](https://un.flatten.do) - UnFlatten JSON Objects
- webhooks.do - Webhook Managment API
- zones.do - Cloudflare Zone Management

## Utilities

- [api.qa](https://api.qa) - Hypermedia-driven Automated API Testing
- [benchmark.do](https://benchmark.do) - Benchmark Performance over Time
- [colo.do](https://colo.do) 
- cors.do - CORS API Proxy
- [perf.do](https://perf.do) - Measure HTTP Request Performance & Latency
- [colo.do](https://colo.do) - Cloudflare Durable Object Proxy for specific Colo Locations
- [logging.do](https://logging.do) - Logging-as-a-Service API

## API Foundations

- [triggers.do](https://triggers.do) - API Triggers
- [searches.do](https://searches.do) - API Searches
- [actions.do](https://actions.do) - API Actions

## API Utilities

- [apikeys.do](https://apikeys.do) - API Key Management & Analytics
- [crud.do](https://crud.do) - Dynamic Hypermedia-driven RESTful CRUD APIs
- rate.limit.do - API Rate Limiting Service
- compose.do - Dynamically Compose & Chain APIs

## Security

- jwt.do
- keys.do
- [oauth.do](https://oauth.do) - OAuth2 Service

## Database

- [graphdl.org](https://graphdl.org) - Graph Definition Language
- [graph.do](https://graph.do) - Managed Version of the GraphDL Reference Implementation
- [database.do](https://database.do) - Durable Object-based Database
- backups.do - Backup Durable Objects
- imports.do - Import Data into Durable Objects
- exports.do - Export Data into Durable Objects
- [bases.do](https://bases.do) - Airtable Base API Proxy
- sheet.do - Google Sheets API Proxy
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

- analytics.do - Analytics with Durable Objects and Workers Analytics Engine

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

- crms.do - Customer Relationship Management System (CRM) Durable Object
- users.do - User Management

## Automotive Data

- dealers.do
- lenders.do
- listings.do
- makes.api.auto.dev - 
- vin.api.auto.dev - 
- listings.api.auto.dev - 


## Finance

- ach.do - ACH Transfers

## Horizontal Services

- bos.do - Bill of Sale API
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
If you're as passionate about these transformational technologies as we are, we'd love for you to join our rapidly-growing team.
