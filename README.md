# Project plan
- healthcheck.rs = Actix + Maud, Bulma CSS, React JS, d3.js
- engine = runs in background, pings sites
- db = postgres

healthcheck.rs offers
- healthcheck.rs/http/<YOURSITE>
- healthcheck.rs/https/<YOURSITE>
- healthcheck.rs/badge/{uptime,p99}/{http,https}/<YOURSITE>

Will show uptime, p99 latency (for now). Later, add different regions.

  
 # Pitch: healthcheck.rs easily and freely monitors your service's uptime from a reliable third-party server.
