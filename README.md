<div align="center">
  <img src="https://user-images.githubusercontent.com/5386772/137594938-e5bcaf58-79d7-4042-bfdf-1887d9b5e446.png" width="30%"/>
  <h1>Healthcheck.rs</h1>
 <em>
  Add uptime monitoring to your site with just one click.
 </em>
</div>
<br />

<div align="center" markdown="1">
<a href ="https://deps.rs/repo/github/hermodapp/api" target="_blank"><img src="https://deps.rs/repo/github/hermodapp/api/status.svg" /></a>
<a href ="https://github.com/hermodapp/api/actions/workflows/general.yml"  target="_blank"><img src="https://github.com/hermodapp/api/actions/workflows/general.yml/badge.svg" /></a>
<a href="https://docs.rs/hermod-api/*/hermod_api/"  target="_blank">
    <img src="https://img.shields.io/badge/docs-latest-blue.svg"
      alt="docs.rs docs" />
  </a>
    <img src="https://img.shields.io/website-up-down-green-red/https/api.hermodapp.com/health_check" />
</div>

<img width="1640" alt="banner" src="https://user-images.githubusercontent.com/5386772/137595091-a784c66e-e648-4ea2-9b9c-3b74689b9395.png">

# Project plan
- healthcheck.rs = Actix + Maud, Bulma CSS, React JS, d3.js
- engine = runs in background, pings sites
- db = postgres

healthcheck.rs offers
- healthcheck.rs/http/<YOURSITE>
- healthcheck.rs/https/<YOURSITE>
- healthcheck.rs/badge/{uptime,p99}/{http,https}/<YOURSITE>
  
Basically, deps.rs but for healthchecks. The essential/core features from pingdom for free.
  
## Alerts: 
healthcheck.rs/alert gives you a code. Put this in a static file or 200 route called /HEALTH_CHECK_RS to prove you're really you. Put your email in.
Now, healthcheck.rs will alert you if your site goes down for more than 30 seconds or p99 latency over the last 10 minutes is above 3 seconds (all are configurable).

Will show uptime, p99 latency (for now). Later, add different regions.

  
 ## Pitch: 
healthcheck.rs easily and freely monitors your service's uptime from a reliable third-party server.
