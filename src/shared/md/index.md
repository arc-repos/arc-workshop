# Master Amazon Web Services with [JSF Architect](https://arc.codes) 🎉

> Provision and deploy cloud infrastructure with a simple plaintext manifest 

<div class=hero>
  <section>
    <h2>🏋️‍♀️ Exercises</h2>
    <ul>
      <li>✅ Stateful website on a with user auth on a custom domain
      <li>✅ Function that executes on an interval 
      <li>✅ A basic JSON API for doing typical database CRUD
      <li>✅ Slack app that replies to slash commands and mentions
    </ul>
  </section>
  <section>
    <h2>💡 Superpowers Unlocked</h2>
    <ul>
    <li>📈 Scale without clusters, load balancing or provisioning
    <li>🔬 Isolated logic with side effects constrained
    <li>💰 Only pay for the compute you use (100% utilization)
    <li>🚀 Deploy instantly with zero downtime
    </ul>
  </section>
  <section>
    <h2>🎓 Prerequisites</h2>
    <ul>
    <li>⭐️ Comfortable with JavaScript and the NodeJS runtime
    <li>⭐️ Node `8.9.1` and npm `5.5.1` (NOTE: Lambda currently runs Node `6.10.x`)
    <li>⭐️ Amazon Web Services account with  `~/.aws/credentials` setup
    <li>⭐️ Willingness to buy a domain on Route53
    </ul>
  </section>
</div>

## Schedule

| Start | End   | Slides                                                                    | Notes                                                                 |
| ----- | ----- | --------------------------------------------------------------------------| --------------------------------------------------------------------- |
|  8:30 |  9:00 | 🎺  [A Brief Introduction to Amazon Web Services](/00-intro-to-aws)        | Understand the cloud vendor ecosystem and landscape                   |
|  9:00 |  9:30 | 🎺  [Introduction to JSF Architect](/01-intro-to-arc)                      | Learn how _architecture as text_ trancends _infrastructure as code_   |
|  9:30 | 10:30 | 🌟  [Intro Web Dev: HTML with API Gateway](/02-intro-to-web)               | `GET` hello worlds; `req._url`; shared layouts and nodemon            |
| 10:30 | 11:00 | _Coffee Break_                                                            | &nbsp;                                                                |
| 11:00 | 11:30 | 🌟  [Test Driven Intro to DynamoDB: Setup and DB Design](/03-intro-to-ddb) | keys, one-to-many, many-to-many, reate tables, sandbox; list tables   | 
| 11:30 | 12:00 | 🌟  [Test Driven Intro to DynamoDB: Reads](/03-intro-to-ddb)               | indexes, query, scan, get, batchRead                                  |
| 12:00 | 12:30 | 🌟  [Test Driven Intro to DynamoDB: Writes](/03-intro-to-ddb)              | put, update, delete, backWrite                                        |
| 12:30 |  1:30 | _Lunch_                                                                   | &nbsp;                                                                |
|  1:30 |  2:00 | 🌟  [Scheduled Functions](/04-replace-cron)                                | ping your domain every five mins and save to dynamo                   | 
|  2:00 |  2:30 | 🌟  [Build and deploy a JSON API](/04-json-api)                            | impl local restish crud actions                                       |
|  2:30 |  3:00 | _Coffee Break_                                                            | &nbsp;                                                                | 
|  3:00 |  3:30 | 🌟  [Build a Slackbot: Setup and Slack API Primer](/05-slackbot-api)       | creds; signin vs addtoslack; actions, options, events and slash urls  |
|  3:30 |  4:00 | 🌟  [Build a Slackbot: Slash and Mentions](/05-slackbot-api)               | &nbsp;                                                                |
|  4:00 |  4:30 | 🌟  [Build a Slackbot; Buttons and Menus](/05-slackbot-api)                | &nbsp;                                                                |
|  4:30 |  5:00 | 🌟  [Closing Thoughts and Next Steps](/06-fin)                             | &nbsp;                                                                |

- 🎺  Presentation
- 🌟  Presentation &amp; Class Exercise

#### Author Bio

In 2007ish Brian created [wtfjs.com](https://wtfjs.com) and later in 2009 at the first JSConf introduced PhoneGap. In 2012 he stewarded the creation of [Cordova](https://cordova.apache.org) at the Apache Software Foundation as Principle Scientist at Adobe Systems. Currently he is the CTO and cofounder of [begin.com](https://begin.com) from which [arc.codes](https://arc.codes) was extracted and donated to the [JS Foundation](https://js.foundation) in July 2017.

