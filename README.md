# ZDApp

a test app, following the tutorial at https://support.zendesk.com/hc/en-us/articles/221688387

---

## Contributing

Here is how to setup the dev environment on a new machine:

### 1. Installing the ZAT gem

```
gem install zendesk_apps_tools
```

### 2. Cloning this repo

```
git clone git@github.com:fczuardi/zdapp.git
cd zdapp
```

### 3. Create a Zendesk account

Signup for the service, there is a 30 day trial and after that the cheapest
plan is US$5/month.

At the end of this process you should have a username + URL like:

```
https://YOUR_USERNAME.zendesk.com
```

### 4. Running the test server on localhost

```
zat server
```

Then open a ticket url appending ```?zat=true``` to the url, like ```https://subdomain.zendesk.com/agent/tickets/123?zat=true```

In your browser's Address bar, click the shield icon on the left (Chrome) or lock icon on the right (Firefox) and agree to load an unsafe script (Chrome) or to disable protection (Firefox). If you don't do this, the browser will block your app.

![](https://zen-marketing-documentation.s3.amazonaws.com/docs/en/zat_chrome_script.png)
