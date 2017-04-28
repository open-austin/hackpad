# Slackin

Slackin is a way to let people join the Open Austin Slack channel without having to ask a human to send out an invite.

[](https://openaustin-slackin.herokuapp.com/)https://openaustin-slackin.herokuapp.com/  or  [](http://slack.open-austin.org)http://s[l](http://s)[a](http://sl)[c](http://sla)[k](http://slac)[.o](http://slack)[p](http://slack.o)[e](http://slack.op)[n](http://slack.ope)[-](http://slack.open)[a](http://slack.open-)[u](http://slack.open-a)[s](http://slack.open-au)[t](http://slack.open-aus)[i](http://slack.open-aust)[n](http://slack.open-austi)[.o](http://slack.open-austin)[r](http://slack.open-austin.o)[g](http://slack.open-austin.or)

We can also add a badge to the Open Austin site (or any web page) with this code:

*   <script async defer src="[](http://slack.open-austin.org/slackin.js)http://slack.open-austin.org/slackin.js"></script> 

Original issue on the project-ideas repo:  [open austin/project ideas#19](https://github.com/open-austin/project-ideas/issues/19)
<undefined><li>Deployment instructions</li></undefined>

1.  Create a new app on Heroku

        1.  Easy way: go to the Slackin project page: [](https://github.com/rauchg/slackin)[https://github.com/rauchg/slackin](https://github.com/rauchg/slackin) and click the "**Deploy to Heroku**" link
    2.  Other way: clone the repository locally, install the [Heroku toolbelt](https://toolbelt.heroku.com/), create a new app from your local checkout, push code to Heroku

2.  Set a domain for the app

        1.  We named the app "openaustin-slackin", so the default domain was openaustin-slackin.herokuapp.com
    2.  To add a custom domain, go to the app's [Settings page](https://dashboard.heroku.com/apps/openaustin-slackin/settings) , find the Domains section and hit "Add Domain" -- we added "slack.open-austin.org".  The other half of this is configuring the DNS to point that name at "openaustin-slackin.herokuapp.com" with a CNAME or ALIAS record.

3.  Get an API token for Slack

        1.  log into Open Austin's Slack with an account that has admin privileges
    2.  go to [](https://api.slack.com/web)https://api.slack.com/web
    3.  scroll down to the "**Authentication**" section at the bottom
    4.  grab the token (you may have to generate a new token if it's not shown there)

Originally created by Larry Archer github.com/larcher.

info@open-austin.org Heroku account.