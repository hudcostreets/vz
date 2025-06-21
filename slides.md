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

# Toward Vision Zero in Hudson County

Hudson County Vision Zero Task Force meeting, 6/24/25

Ryan Williams

Hudson County Complete Streets


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
- JSQ

---
class: hccs
dragPos:
  tt: 41,347,371,180
  bus: 427,347,188,180
  njt: 627,347,188,180
  path: 427,133,265,_
  vz: 707,30,228,_
---

<style>
.slidev-layout.hccs {
  padding-top: 1.5rem;
  padding-left: 2.7rem;
  h1 { margin-bottom: 0 }
  p { margin: 0.4rem 0; }
  li { line-height: 2rem }
  blockquote { width: 75% }
  div.path { height: 36.5% }
  img {
    width: 100%;
    height: 100%;
    &[src*="path"] {
      object-fit: cover;
      object-position: top center;
    }
  }
}
/* TODO: theme var */
.dark .slidev-layout.hccs img { border: 1px solid white }
.light .slidev-layout.hccs img { border: 3px solid #00793f }
</style>


# Hudson County Complete Streets
> Our mission is to improve connectivity and transportation equity in Hudson County by advocating for safe streets, pedestrian and cycling infrastructure, and access to transit in each community.

Campaigns:
- [Improving PATH service][PATH]
- [Supporting congestion pricing][CP]
- [Opposing $11BN Turnpike-widening][TA]
- [Hudson County Vision Zero Action Plan][VZ]

👉 [hudcostreets.org]

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
[CP]: https://nyc.streetsblog.org/2025/03/21/advocates-demand-new-jersey-agencies-cough-up-congestion-pricing-data
[TA]: https://www.nj.com/traffic/2025/03/nj-turnpike-widening-opponents-demand-fresh-cost-and-traffic-numbers-for-107-b-project.html?gift=81525149-0b28-4c98-bd63-b6241996fd00
[VZ]: https://newsletter.hudcostreets.org/archive/january-2025-vision-zero-plan-launch-jan-11/

[hudcostreets.org]: https://hudcostreets.org/
[tt]: https://turnpiketrap.org/
[bus]: https://newsletter.hudcostreets.org/archive/save-our-hudson-county-buses-deadline-august-16/
[njt]: https://newsletter.hudcostreets.org/archive/action-alert-tell-gov-murphy-142m-for-nj-transit/
[vzi]: https://newsletter.hudcostreets.org/archive/january-2025-vision-zero-plan-launch-jan-11/

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
# layout: two-cols
class: nymtc
dragPos:
  xbl: 40,138,515,_
  nymtc: 567,135,310,_
---

<style>
.slidev-layout.nymtc {
  display: grid;
  padding: 1.5rem 2.5rem 2rem 2.5rem;
  grid-template-columns: 57% 40%;
  gap: 1rem;
  font-size: 1rem;
  .col-right { padding-top: 1rem }
}
</style>

<div class="col-left">
  <h1>BRT / <a href="https://www.panynj.gov/bridges-tunnels/en/lincoln-tunnel/xbl.html" target="_blank">Lincoln Tunnel Bus Lane</a></h1>

  > … busiest and most productive highway lane in the nation, moving over 1,850 buses and 70,000 passengers each weekday morning &nbsp;[<mdi-link />][xbl faq]
</div>
<div class="col-right">
  <h4>
    <a href="https://www.nymtc.org/en-us/Data-and-Modeling/Transportation-Data-and-Statistics/Publications/Hub-Bound-Travel" target="_blank">
      NYMTC "Hub-Bound Travel" reports
    </a>
  </h4>
  <p>Annual study of modes / vehicles in/out of Manhattan CBD</p>
</div>

[xbl]: https://www.panynj.gov/bridges-tunnels/en/lincoln-tunnel/xbl.html
[xbl faq]: https://www.panynj.gov/port-authority/en/help-center/faq/bridges-and-tunnels-faq.html

<a href="https://github.com/hudcostreets/hudson-transit#peak" target="_blank"><img v-drag="'xbl'" src="/xbl.png"/></a>
<!--
<img v-drag="'xbl'" src="/xbl.png"/>
-->

<a href="https://www.nymtc.org/Portals/0/Pdf/Hub%20Bound/2023%20Hub%20Bound/2023%20Hub%20Bound%20Report-%203.18.25.pdf?ver=7S_sDok5O_aw9bEN3A-NjA%3d%3d" target="_blank"><img v-drag="'nymtc'" src="/nymtc-hbt.png"/></a>
<!--
<img v-drag="'nymtc'" src="/nymtc-hbt.png"/>
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
    /*height: 14.8rem;*/
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
url: https://crashes.hudcostreets.org#vs-homicides
scale: 0.8
class: crashes
---
<style>
.crashes + footer { width: 50%; right: auto; }
.slidev-layout.crashes {
  p { margin-bottom: 0.5rem }
  img {
    width: 30%;
    height: 49%;
    object-fit: cover;
    object-position: top left;
    position: absolute;
    bottom: 2.8%;
  }
}
</style>

# [crashes.hudcostreets.org]
NJ crash data
- Fatal crashes, updated daily ([NJSP])
- All crashes, 2-3yr lag ([NJDOT])
- <logos-bluesky/> &nbsp;[@crashes.hudcostreets.org]
- <logos-slack-icon/> &nbsp;#crash-bot


<img src="/crash-bot.png"/>

[NJSP]: https://www.nj.gov/njsp/info/fatalacc/index.shtml
[NJDOT]: https://www.nj.gov/transportation/refdata/accident/rawdata01-current.shtm
[crashes.hudcostreets.org]: https://crashes.hudcostreets.org
[@crashes.hudcostreets.org]: https://bsky.app/profile/crashes.hudcostreets.org

---
layout: iframe-right
url: 'https://path.hudcostreets.org#vs-2019'
scale: 0.6
class: path
---
<style>
.slidev-layout.path {
  & + footer { display: none }
  pre {
    background-color: #f8f8f8;
    font-size: 0.6rem;
  }
  .flex {
    display: flex;
    flex-direction: row;
    gap: 1rem;
    .col {
      img {
        width: 100%;
      }
    }
  }
  .right-overlay {
    border: 1rem solid #00793f;
  }
  .small { font-size: 0.8rem; }
}
</style>

# [path.hudcostreets.org]
PATH ridership data
- Weekend ridership exceeding pre-COVID levels (despite worse service)
- Weekdays ≈60-70% of pre-COVID levels
- [PANYNJ Traffic and Volume stats](https://www.panynj.gov/path/en/about/stats.html) (PDFs)
<v-click>

- [Tabula]: extract tables from PDFs (library+GUI)
  ```json
  [
      { "y1": 121.284, "x1": 70.016, "y2": 245.247, "x2": 568.926 },
      { "y1": 261.316, "x1": 71.546, "y2": 407.469, "x2": 569.691 },
      { "y1": 482.459, "x1": 70.781, "y2": 603.36, "x2": 568.161 },
      { "y1": 620.96, "x1": 70.781, "y2": 761.757, "x2": 569.691 }
  ]
  ```
  <span class="small">([PATH-Monthly-Ridership-Report.json])</span>
- Soon️(?): LLMs / ML tools for reading PDFs
</v-click>

[PATH-Monthly-Ridership-Report.json]: https://github.com/hudcostreets/path/blob/main/templates/PATH-Monthly-Ridership-Report.json

<v-click at="+0"><img class="right-overlay" src="/tabula1.png"/></v-click>

<img v-click class="right-overlay" src="/tabula2.png"/>

<!--
<div class="flex">
  <a target="_blank" href="https://hudcostreets.org/panynj"><div class="col">
    <p>Petition / Campaign</p>
    <img src="/path-qr.png"/>
  </div></a>
  <a target="_blank" href="https://hudcostreets.org/panynj/volunteer"><div class="col">
    <p>Canvassing</p>
    <img src="/path-vols.png"/>
  </div></a>
</div>
-->

[path.hudcostreets.org]: https://path.hudcostreets.org
[Tabula]: https://tabula.technology/

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
class: srcs
---
# Data sources

<div style="font-size:0.5em">&nbsp;</div>

| Agency      | Data                               | Frequency                   | Delay       | Mirror / Site                                                                                                                |
|-------------|------------------------------------|-----------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------|
| [NJSP]      | Crashes (fatal)                    | Daily                       | 1d – 3mos   | [<logos-github-icon/>][hudcostreets/nj-crashes] [<logos-aws-s3 />][`s3://nj-crashes/njsp`] &nbsp;[crashes.hudcostreets.org]  |
| [NJ DOT]    | Crashes (all)                      | Annually                    | 2-3yrs ('22) | [<logos-github-icon/>][hudcostreets/nj-crashes] [<logos-aws-s3 />][`s3://nj-crashes/njdot`] &nbsp;[crashes.hudcostreets.org] |
| [Lyft]      | Citi Bike ridership                | Monthly                     | ≈1wk        | [<logos-github-icon/>][hudcostreets/ctbk.dev] [<logos-aws-s3 />][`s3://ctbk`]                &nbsp;[ctbk.dev]                |
| [PANYNJ]    | PATH Ridership                     | Monthly                     | 1-2mos      | [<logos-github-icon/>][hudcostreets/path]                                                    &nbsp;[path.hudcostreets.org]   |
| [NYMTC]     | Hudson River crossings             | Annually                    | 1-2yrs ('23) | [<logos-github-icon/>][hudcostreets/hudson-transit] [<logos-google-drive />][HCCS NYMTC]                                     |
| NJ Transit  | Rides per station/line             | OPRA                        | -           | [<logos-google-drive />][HCCS NJT]                                                                                           |
| NJ Turnpike | Exits x Veh types                  | OPRA                        | -           | [<logos-google-drive />][HCCS NJTA]                                                                                          |
| [Lyft]      | [Citi Bike system status][cb gbfs] | Realtime ([GBFS]) | 1min | -                                                                                                                            |
| PANYNJ      | [PATH real-time status][path realtime] | Realtime ([GTFS]) | 1min | [<logos-github-icon/>][mrazza/path-data] &nbsp;[<logos-github-icon/>][jamespfennell/path-train-gtfs-realtime]                |

[ctbk.dev]: https://ctbk.dev
[crashes.hudcostreets.org]: https://crashes.hudcostreets.org
[path.hudcostreets.org]: https://path.hudcostreets.org
[hudcostreets/hudson-transit]: https://github.com/hudcostreets/hudson-transit

[NJSP]: https://www.nj.gov/njsp/info/fatalacc/index.shtml
[NJ DOT]: https://www.nj.gov/transportation/refdata/accident/rawdata01-current.shtm
[PANYNJ]: https://www.panynj.gov/path/en/about/stats.html
[NYMTC]: https://www.nymtc.org/en-us/Data-and-Modeling/Transportation-Data-and-Statistics/Publications/Hub-Bound-Travel
[Lyft]: https://citibikenyc.com/system-data

[`s3://nj-crashes/njsp`]: https://nj-crashes.s3.amazonaws.com/index.html#/njsp/data
[`s3://nj-crashes/njdot`]: https://nj-crashes.s3.amazonaws.com/index.html#/njdot/data
[hudcostreets/path]: https://github.com/hudcostreets/path
[hudcostreets/nj-crashes]: https://github.com/hudcostreets/nj-crashes
[hudcostreets/ctbk.dev]: https://github.com/hudcostreets/ctbk.dev
[HCCS NYMTC]: https://drive.google.com/drive/folders/1Dm-ZBYxWaOaGgm08XCGOZCuvU2IQaPLN
[HCCS NJTA]: https://drive.google.com/drive/folders/1Ff4TUP6MmuoGvE0qTE2cgBukoxstB-93
[HCCS NJT]: https://drive.google.com/drive/folders/1IkeX8EOavWC1uUa1eHIIbVmE8i5tDuwE
[`s3://ctbk`]: https://ctbk.s3.amazonaws.com/index.html

[GBFS]: https://github.com/MobilityData/gbfs
[cb gbfs]: https://gbfs.citibikenyc.com/gbfs/2.3/gbfs.json
[cb gbfs stations]: https://gbfs.lyft.com/gbfs/2.3/bkn/en/station_information.json
[cb gbfs status]: https://gbfs.lyft.com/gbfs/2.3/bkn/en/station_status.json
[GTFS]: https://gtfs.org/

[path grpc]: https://github.com/mrazza/path-data
[path grpc blog]: https://medium.com/@mrazza/programmatic-path-real-time-arrival-data-5d0884ae1ad6
[path gtfs]: https://github.com/jamespfennell/path-train-gtfs-realtime
[path realtime]: https://www.panynj.gov/path/en/index.html

[mrazza/path-data]: https://github.com/mrazza/path-data
[jamespfennell/path-train-gtfs-realtime]: https://github.com/jamespfennell/path-train-gtfs-realtime

---
layout: iframe-right
url: https://hudcostreets.org/careers
class: end
---
<style>
.end + footer { width: 50%; right: auto; }
</style>

# Thank you!

We're hiring: [hudcostreets.org/careers].

[hudcostreets.org/careers]: https://hudcostreets.org/careers
