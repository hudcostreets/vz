---
theme: ./theme
title: Toward Vision Zero in Hudson County
info: Hudson County Vision Zero Task Force presentation by Hudson County Complete Streets
selectable: true
class: text-center  # apply unocss classes to the current slide
colorSchema: dark
drawings:  # https://sli.dev/features/drawing
  persist: false
mdc: true
layout: section
---

# Toward Vision Zero<br>in Hudson County

Hudson County Vision Zero Task Force meeting, 6/24/25

Ryan Williams

Hudson County Complete Streets

<!--
[hudcostreets.org](https://hudcostreets.org)

Slides: [vz.hccs.dev](https://vz.hccs.dev)
-->

---
class: quiz
dragPos:
  jfk: 535,0,445,_
---

<style>
.quiz {
  &+footer { display: none; }
  .body {
    width: 55%;
  }
  img { z-index: 1 !important; }
  .credit {
    position: absolute;
    bottom: 1rem;
    right: 1rem;
    z-index: 2;
    font-size: 0.9rem;
    background-color: rgba(0, 0, 0, 0.7);
    padding: 0.2rem 0.4rem;
  }
}
</style>

# Pop Quiz 💡

<div class="body">

### **Q:** What's the busiest hour of the year on:
- JFK Boulevard
- Rt 139

<br/>

# 🤔

<div v-click>Answer in a few slides…</div>
</div>

<img v-drag="'jfk'" src="/jp-jfk.jpg" />
<div class="credit">
Credit: @jerseyphotographer
</div>

---
class: hccs
dragPos:
  tt: 41,347,371,180
  bus: 427,347,188,180
  njt: 627,347,188,180
  path: 427,133,265,_
  vz: 707,31,228,_
---

<style>
.slidev-layout.hccs {
  padding-top: 1.5rem;
  padding-left: 2.7rem;
  h1 { margin-bottom: 0 }
  p { margin: 0.4rem 0; }
  li { line-height: 2rem }
  blockquote { width: 70% !important; }
  div.path { height: 36.5% }
  img {
    width: 100%;
    height: 100%;
    &[src*="path"] {
      object-fit: cover;
      object-position: top center;
    }
  }
  .body {
    /*font-size: 1rem;*/
    p:first-child { margin-top: 0; }
    li {
      line-height: 1.8rem !important;
    }
  }
}
/* TODO: theme var */
.dark .slidev-layout.hccs img { border: 1px solid white }
.light .slidev-layout.hccs img { border: 3px solid #00793f }
</style>


# Hudson County Complete Streets
> Our mission is to improve mobility in Hudson County by advocating for<br/>**safe streets**, pedestrian and cycling **infrastructure**, and **access to transit.**

<div class="body">

Campaigns:
- [Improve PATH service][PATH]
- [Bus rapid transit on JFK][JFK]
- Bike/Ped infrastructure ([Viaduct], [JFK Blvd E])
- [Oppose $11BN Turnpike-widening][TA]
- [Hudson County Vision Zero Action Plan][VZ]

👉 [hudcostreets.org]
</div>

<div v-drag="'tt'"><a target="_blank" href="https://turnpiketrap.org/"><img src="/tt.png"/></a></div>
<div v-drag="'bus'"><a target="_blank" href="https://newsletter.hudcostreets.org/archive/save-our-hudson-county-buses-deadline-august-16/"><img src="/bus.jpeg"/></a></div>
<div v-drag="'njt'"><a target="_blank" href="https://newsletter.hudcostreets.org/archive/action-alert-tell-gov-murphy-142m-for-nj-transit/"><img src="/njt.jpeg"/></a></div>
<div v-drag="'path'" class="path"><a target="_blank" href="https://hudcostreets.org/panynj"><img src="/path.jpg"/></a></div>
<div v-drag="'vz'"><a target="_blank" href="https://newsletter.hudcostreets.org/archive/january-2025-vision-zero-plan-launch-jan-11/"><img src="/vz.png"/></a></div>
<!--
<img v-drag="'tt'" src="/tt.png"/>
<img v-drag="'bus'" src="/bus.jpeg"/>
<img v-drag="'njt'" src="/njt.jpeg"/>
<img v-drag="'path'" src="/path.jpg"/>
<img v-drag="'vz'" src="/vz.png"/>
-->

[PATH]: https://hudcostreets.org/panynj
[JFK]: https://hudcostreets.org/fix-jfk-blvd
[Viaduct]: https://hudcostreets.org/viaduct
[JFK Blvd E]: https://hudcostreets.org/jfkblvdeastredesign
[CP]: https://nyc.streetsblog.org/2025/03/21/advocates-demand-new-jersey-agencies-cough-up-congestion-pricing-data
[TA]: https://www.nj.com/traffic/2025/03/nj-turnpike-widening-opponents-demand-fresh-cost-and-traffic-numbers-for-107-b-project.html?gift=81525149-0b28-4c98-bd63-b6241996fd00
[VZ]: https://newsletter.hudcostreets.org/archive/january-2025-vision-zero-plan-launch-jan-11/

[hudcostreets.org]: https://hudcostreets.org/
[tt]: https://turnpiketrap.org/
[bus]: https://newsletter.hudcostreets.org/archive/save-our-hudson-county-buses-deadline-august-16/
[njt]: https://newsletter.hudcostreets.org/archive/action-alert-tell-gov-murphy-142m-for-nj-transit/
[vzi]: https://newsletter.hudcostreets.org/archive/january-2025-vision-zero-plan-launch-jan-11/

---
class: plots
dragPos:
  hom: 16,75,215,148
  sp: 16,234,215,148
  path: 16,393,215,147
  jc: 241,73,185,242
  hc: 241,325,185,216
  xbl: 436,21,331,267
  cb-m: 436,298,331,242
  cb: 777,20,192,124
  cb-r: 777,154,192,120
  cb-g: 777,286,192,120
  cb-u: 777,418,192,120
---

<style>
.slidev-layout.plots {
  & + footer { display: none }
  padding-top: 1.6rem;
  img {
    width: 100%;
    height: 100%;
  }
}
</style>

<!--
<div v-drag="'hom'"><img src="/hom.png"/></div>
<div v-drag="'sp'"><img src="/njsp.png"/></div>
<div v-drag="'path'"><img src="/path-vs19.png"/></div>
<div v-drag="'jc'"><img src="/jc.gif" /></div>
<div v-drag="'hc'"><img src="/hc-map.png"/></div>
<div v-drag="'xbl'"><img src="/xbl.png"/></div>
<div v-drag="'cb-m'"><img src="/g2410.png"/></div>
<div v-drag="'cb'"><img src="/cb.png"/></div>
<div v-drag="'cb-r'"><img src="/cb-r.png"/></div>
<div v-drag="'cb-g'"><img src="/cb-g.png"/></div>
<div v-drag="'cb-u'"><img src="/cb-u.png"/></div>
-->

<div v-drag="'hom'" ><a target="_blank" href="https://crashes.hudcostreets.org/#vs-homicides"><img src="/hom.png"/></a></div>
<div v-drag="'sp'"  ><a target="_blank" href="https://crashes.hudcostreets.org/#per-year"><img src="/njsp.png"/></a></div>
<div v-drag="'path'"><a target="_blank" href="https://path.hudcostreets.org/#vs-2019"><img src="/path-vs19.png"/></a></div>
<div v-drag="'jc'"  ><a target="_blank" href="https://map.bikejc.org/?ll=40.720_-74.068&z=14"><img src="/jc.gif" /></a></div>
<div v-drag="'hc'"  ><a target="_blank" href="https://crashes.hudcostreets.org/map/hudson"><img src="/hc-map.png"/></a></div>
<div v-drag="'xbl'" ><a target="_blank" href="https://github.com/hudcostreets/hudson-transit"><img src="/xbl.png"/></a></div>
<div v-drag="'cb-m'"><a target="_blank" href="https://ctbk.dev/stations?ll=40.717-74.045&z=15&ss=JC115&ym=2410"><img src="/g2410.png"/></a></div>
<div v-drag="'cb'"  ><a target="_blank" href="https://ctbk.dev/"><img src="/cb.png"/></a></div>
<div v-drag="'cb-r'"><a target="_blank" href="https://ctbk.dev/?s=b&pct&rt=ce&d=2002-"><img src="/cb-r.png"/></a></div>
<div v-drag="'cb-g'"><a target="_blank" href="https://ctbk.dev/?y=m&s=g&pct&g=mf&d=1406-2102"><img src="/cb-g.png"/></a></div>
<div v-drag="'cb-u'"><a target="_blank" href="https://ctbk.dev/?s=u&pct"><img src="/cb-u.png"/></a></div>

# Proving it, locally

[hom-cmp]: https://crashes.hudcostreets.org/#vs-homicides
[xbl]: https://github.com/hudcostreets/hudson-transit
[grove-2410]: https://ctbk.dev/stations?ll=40.717-74.045&z=15&ss=JC115&ym=2410
[path]: https://path.hudcostreets.org/#vs-2019


---
layout: section
---
# Status Quo

---
class: deaths
dragPos:
  plot: 20,218,370,_
  stats: 397,217,224,_
  homs: 55,127,689,_
  map: 629,92,342,_
---

<style>

.deaths {
  &+footer { display: none; }
  .slidev-vclick-hidden { display: none; }
  h1 {
    position: relative;
    z-index: 10
  }
  img {
    z-index: 1 !important;
  }
  .link {
    position: absolute;
    right: 1rem;
    bottom: 0;
    font-size: 0.9rem;
    z-index: 2;
  }
}
</style>

<div v-click="[0,1]">

# Hudson County – Deaths, Injuries, Property Damage

Car crashes kill more people **than murders**

<img v-drag="'homs'" src="/hc-vs-homs.png" />
</div>
<div v-click>

# Hudson County – Deaths, Injuries, Property Damage

- 50 crashes per day (reported to police).
- Per year:
  - 23 deaths (9 pedestrians, 10 drivers, 2 passengers, 1-2 cyclists)
  - 150 serious injuries, 1,000-4,000 other injuries

<img v-drag="'plot'" src="/hc-traffic-deaths.png" />
<img v-drag="'stats'" src="/hc-crash-stats.png" />
<img v-drag="'map'" src="/hc-crash-map.png" />

</div>

<div class="link">

[crashes.hudcostreets.org](https://crashes.hudcostreets.org)
</div>

---
class: cars
dragPos:
  cars: 415,88,555,_
---

<style>
.cars {
  &+footer { display: none; }
  .slidev-vclick-hidden { display: none; }
  padding-left: 2rem;
  .left {
    width: 42%;
  }
}
</style>

# Cost of car-dependence
277k cars in Hudson County:
<div class="left">

- **≈$3BN / year** buying, insuring, maintaining
- **≈$2BN auto debt** ($1TN nation-wide)
- **10% increase** since COVID ‼️

<br/>
<div v-click>
Traffic and parking will only get worse, if the number of cars keeps rising.
</div>
<br/>
<div v-click>
People need (and want) transportation alternatives…
</div>
</div>
<div v-click>
<br/>

["D" air quality grade…][ALA]
</div>

<img v-drag="'cars'" src="/hc_vehs_title.png" />

[ALA]: https://www.lung.org/research/sota/city-rankings/states/new-jersey/hudson

---
class: quiz-a
dragPos:
  wt: 366,211,297,_
---

<style>
.quiz-a {
  &+footer { display: none; }
  .body {
    width: 75%;
    margin-bottom: .5rem;
  }
  & > div:nth-child(2) {
    margin-top: 0;
  }
  video.wt {
    border: 1rem solid #00793f;
    border-left: none;
    position: absolute;
    right: 0;
    bottom: 0;
    height: 100%;
  }
  .left {
    width: 36%;
    &.inner > ul > li { list-style: none; }
  }
}
</style>
# Pop Quiz (cont.)

<div class="body">

### **Q:** What's the busiest hour of the year on:
- JFK Boulevard
- Rt 139

</div>
<div v-click="1">

### **A:** Jersey City Ward Tour
<div class="left">

- 2,000 cyclists
  - Rolling closures: **5-30 minutes**
  - JFK: 25,000 vehicles per day, ≤2,000 per hour
</div>

<video class="wt" src="/wt.mp4" onclick="this.ended ? (this.currentTime = 0, this.play()) : this.paused ? this.play() : this.pause()" />
</div>
<div v-click="2">

- 16 miles, 6 wards

<img v-drag="'wt'" src="/wt.png" />
</div>
<div v-click="3" class="left">

- Children can bike from downtown, to Greenville, to West Side, to Heights, and back.
</div>
<div v-click="4" class="left inner">
<ul><li><ul><li>When we make it safe (no cars)</li></ul></li></ul>
</div>

---
layout: section
class: opps-section
---

<style>
.opps-section {
  &+footer { display: none; }
  img {
    display: inline;
    width: 70%;
  }
}
</style>
# Opportunities

<img src="/mode-capacities.png" />

---
class: nymtc
dragPos:
  xbl: 300,20,665,_
  nymtc: 40,135,310,_
---

<style>
.nymtc {
  &+footer { display: none; }
  .col-left { width: 25%; }
}
</style>
<div class="col-left">

## [Lincoln Tunnel Bus Lane](https://www.panynj.gov/bridges-tunnels/en/lincoln-tunnel/xbl.html)

<br/>

> … busiest and most productive highway lane in the nation, moving over 1,850 buses and 70,000 passengers each weekday morning &nbsp;[<mdi-link />][xbl faq]

1 bus lane moves **5x** as many people per hour…

as 5 car lanes (Lincoln+Holland) _combined_ 🤯.

95% of Holland Tunnel vehicles are cars

80% have 1 person
</div>

[xbl]: https://www.panynj.gov/bridges-tunnels/en/lincoln-tunnel/xbl.html
[xbl faq]: https://www.panynj.gov/port-authority/en/help-center/faq/bridges-and-tunnels-faq.html

<a href="https://github.com/hudcostreets/hudson-transit#peak" target="_blank"><img v-drag="'xbl'" src="/xbl.png"/></a>

<!--
<img v-drag="'xbl'" src="/xbl.png"/>
-->

---
class: opps
dragPos:
  cars: 405,38,565,_
  mode: 54,173,889,_
  intra: 52,281,629,_
---
<style>
.opps {
  &+footer { display: none; }
  .slidev-vclick-hidden { display: none; }
  padding-left: 2rem;
  .left {
    width: 42%;
  }
}
</style>

# Opportunities
- 30% of cars are households' 2nd (or more)
  - Car-sharing
  - Replacing with (e)bikes, scooters
<div v-click="[0,1]">
<img v-drag="'cars'" src="/hc_vehs_title.png" />
</div>
<div v-click="[1,2]">
<img v-drag="'cars'" src="/hc_vehs_years_title.png" />
</div>
<div v-click="1">

- 33% of households already car-free
</div>
<div v-click="[2,3]">
<img v-drag="'mode'" src="/njtpa-hc-modes.png" />
</div>
<div v-click="2">

- < 50% of trips by car
</div>
<div v-click="3">

- 68% of trips are within Hudson County
</div>
<div v-click="3">
<img v-drag="'intra'" src="/njtpa-intra-hc-crop.png" />
</div>

<!--
<iframe width="560" height="315" src="https://www.youtube.com/embed/IFg5PRpeLzs?t=18" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
-->

---
layout: iframe-right
url: https://ctbk.dev
scale: 0.8
class: ctbk
---
<style>
.ctbk + footer { display: none; }
.slidev-layout.ctbk {
  padding: 2rem 1rem 0 2rem;
  p { margin-bottom: 0.5rem }
  li { line-height: 1.75rem }
  img:not(.right-overlay) {
    height: 14.8rem;
    position: absolute;
    padding-left: 1rem;
    bottom: 1rem;
    z-index: 1;
  }
  .right-overlay {
    border: 1rem solid #00793f;
    border-left: none;
  }
}
</style>

# Hudson County – <br>Bike Share Opportunity
- **10,000 trips per day** achievable in **5 years**
  - Largely replacing car trips
  - Cheaper, cleaner, quieter, safer mobility
- Grove St (≈5 car-parking spots): **300 rides per day**
- JC+HOB: [63%][ebikes] ebike share, [78%][subs] annual members

[![](/g2505.png)][2505]

<img v-click="[0,1]" class="right-overlay" src="/cb-opp2.png" />

<!--
Show JC+HOB plateau, ebike share over time, Grove St 80/day in Feb '25
Show station map by add date
-->

[ctbk.dev]: https://ctbk.dev
[`s3://ctbk`]: https://ctbk.s3.amazonaws.com/index.html
[`s3://tripdata`]: https://tripdata.s3.amazonaws.com/index.html
[cb data]: https://www.citibikenyc.com/system-data
[ctbk gh]: https://github.com/hudcostreets/ctbk.dev
[2505]: https://ctbk.dev/stations?ll=40.717-74.045&z=15&ss=JC115&ym=2505
[ebikes]: https://ctbk.dev/?s=b&pct&rt=ce&d=2002-&r=jh
[subs]: https://ctbk.dev/?s=u&pct&r=jh

---
layout: iframe-right
url: https://map.bikejc.org/?l=wbr
class: jc
---
<style>
/*.jc + footer { width: 50%; right: auto; }*/
.jc + footer { display: none }
</style>

# [map.bikejc.org]
- Wraps/Joins [JC ArcGIS layers][jc gis]
- ≈2,000 lane-miles for cars, ≈20 miles of protected bike lanes

See also:
- [JC Bike Master Plan][bmp] / [bikejc.github.io/bike-master-plan] / [PDF]
- [NJGIN index] of agency ArcGIS servers:
  [![](/njgin.png)][NJGIN index]

[map.bikejc.org]: https://map.bikejc.org
[bmp]: https://street-plans.com/lets-ride-jc-bicycle-master-plan-jersey-city-nj/
[bikejc.github.io/bike-master-plan]: https://bikejc.github.io/bike-master-plan/
[PDF]: https://cdn5-hosted.civiclive.com/UserFiles/Servers/Server_6189660/File/Community/Transportation/LetsRideJCMasterPlan-FinalDraft%206.16.19_09_30.pdf
[jc gis]: https://jerseycity.maps.arcgis.com/apps/mapviewer/index.html?webmap=c8b0f0723aad4c68ab68861ee071f218
[NJGIN index]: https://njogis-newjersey.opendata.arcgis.com/

---
layout: iframe-right
url: /bh24.pdf
class: hob
---
<style>
.hob + footer { display: none; }
.dark .slidev-layout.hob {
  background: #6436a9 url('/bh-white.png') no-repeat right bottom;
  --slidev-code-background: #6436a9;
  --slidev-code-radius: 0;
  background-size: 6rem;
}
.light .slidev-layout.hob {
  /*color: #6436a9;*/
  color: black;
  background: white url('/bh.png') no-repeat right bottom;
  background-size: 6rem;
}
.slidev-layout.hob {
  h1 {
    line-height: 3.3rem;
  }
}
</style>

# [2024 Bike Hoboken Traffic Injury Report][bh24]
- [Bike Hoboken] OPRA'd all 2024 crash records
- Data entry from PDFs (many volunteer-hours)
- [NJTR-1] forms (crashes involving autos) and "incident reports" (ped and/or bike only)

**0 pedestrian injuries involving bicycles or e-bikes on a sidewalk** (despite [brouhaha], "test+vest" [ordinance][ord])

[bh24]: https://www.bikehoboken.org/articles/2024-bike-hoboken-traffic-injury-report
[Bike Hoboken]: https://www.bikehoboken.org/
[NJTR-1]: https://www.nj.gov/transportation/refdata/accident/pdf/NJTR-1CrashReportManual2023.pdf
[brouhaha]: https://www.nj.com/hudson/2024/03/tests-and-vests-for-hoboken-ebike-workers-is-now-law-despite-pushback-from-police-chief.html?gift=03ec6bf2-a21c-4217-beb2-00b526b0d92a
[ord]:https://www.hobokennj.gov/resources/commercial-e-delivery-operators

---
layout: section
class: end
---

# Thank you!


---
class: us
---
<style>
.slidev-layout.us {
  padding-right: 5rem;
  h2 {
    margin-top: 1.7rem;
    margin-bottom: 0.5rem;
  }
  .right-overlay {
    padding: 2rem;
  }
}</style>

# Big picture – US transportation sector is broken
≈100% car-dependence:

- [\$TNs][IMF] of subsidies, [\$TNs][debt] of auto debt, [\$TNs][insurance] of auto insurance (other people's crashes)
- [MMs][deaths] of violent deaths, [10MMs][injuries] of injuries, [10MMs][disease] of respiratory diseases / cognitive impairments
- [MMmts][CO2] of CO₂; pollution / particulates / noise
- [Worse mobility][cn hsr], no childhood autonomy, hollowed-out cities, less community

[IMF]: https://www.imf.org/en/Topics/climate-change/energy-subsidies
[debt]: https://www.lendingtree.com/auto/debt-statistics/
[insurance]: https://www.statista.com/outlook/fmo/insurances/non-life-insurances/motor-vehicle-insurance/united-states
[deaths]: https://en.wikipedia.org/wiki/Motor_vehicle_fatality_rate_in_U.S._by_year#By_year
[injuries]: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813560#:~:text=In%202022%20an%20estimated%202.38,injured%20from%202020%20to%202021.
[disease]: https://www.who.int/data/gho/data/themes/topics/indicator-groups/indicator-group-details/GHO/ambient-air-pollution
[CO2]: https://www.eia.gov/tools/faqs/faq.php?id=307&t=10

[shinkansen]: https://en.wikipedia.org/wiki/Shinkansen#Safety_record
[cn hsr]: https://www.threads.net/@thetransitguy/post/DGY0GP6B3hD/video-this-is-the-beijing-shanghai-corridor-which-takes-4-hours-and-18-minutes-to-cove
[world transit]: https://www.thetransportpolitic.com/2023/06/07/once-a-leader-in-urban-rail-investment-the-united-states-now-trails/
[road deaths per capita]: https://www.nytimes.com/2022/11/27/upshot/road-deaths-pedestrians-cyclists.html

**Unprecedented, civilization-scale disaster**, entirely a policy choice. We have the technology to do better.

## Theory of change
- **Internet / Social Media**: shows people what's possible, enables organizing
- **Data for decision-making**: proliferation of sensors/data and tools for analyzing/responding
- **New technology**: ebikes/micromobility, faster/quieter transit, app-cars / AVs can reduce car dependence

<a target="_blank" href="https://www.thetransportpolitic.com/2023/06/07/once-a-leader-in-urban-rail-investment-the-united-states-now-trails/"><img v-click class="right-overlay" src="/subway-countries.jpeg"/></a>

<a target="_blank" href="https://www.nytimes.com/2022/11/27/upshot/road-deaths-pedestrians-cyclists.html"><img v-click class="right-overlay" src="/deaths-per-capita.png"/></a>

---
---

TODO:
- Fix JFK; bus lane
- Hudson County Bike Share Opportunity (300,000 rides/month)
- Ward Tour
- Ebikes
- Viaduct
- Ward Tour, capacity
- Eli Bender
- TurnpikeTrap
- JSQ

- glowy crash map 2022 update
- Specify HC in homs plot
  - Add statewide click
- Link "deaths" plots
- WT kids
