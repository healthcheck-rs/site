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
