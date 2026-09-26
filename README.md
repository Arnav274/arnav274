# Arnav Pawar

What I actually like is being in the middle of a problem: sitting with someone who has a vague idea, turning it into something buildable, then making sure it gets built. At Reg-X Innovations that meant writing the requirements and architecture spec for a fintech client's AI ticketing platform, then staying on to help build it. Outside of that: an EV charging app that ranks stations using real scheduling algorithms, an object detector that runs entirely in the browser, a hazard-reporting map for a township that didn't have one.

BSc Computer Science (1st), University of East Anglia.

<br/>

## Stack

<img src="https://skillicons.dev/icons?i=py,fastapi,ts,react,nextjs,postgres,docker,tailwind&theme=dark" />

<br/>
<br/>

## Projects

### [ev-charger-scheduling](https://github.com/Arnav274/ev-charger-scheduling)
`FastAPI` `PostgreSQL` `OSRM` `React` `Leaflet`

Ranks London's EV chargers the way a driver actually decides, not just by distance: wait time, price, and remaining range factored in too. Benchmarked six scheduling approaches against each other, including Dijkstra's algorithm and an Erlang-C queueing model, to see which produced recommendations that actually held up rather than the one with the fanciest name. The interesting result was that Dijkstra came last, because better routing sends everyone to the same chargers and they queue. Live station data from OpenChargeMap, containerised across four services, tested with pytest.

### [ticket-triage-widget](https://github.com/Arnav274/ticket-triage-widget)
`TypeScript` `Express` `PostgreSQL` `React`

An embeddable widget that asks an LLM to suggest a ticket's severity, then stores that suggestion separately from whatever the user actually picked, so the override rate stays measurable instead of disappearing. Degrades to a plain dropdown when the provider is slow or fails. Comes with a written security review covering what it does and does not do, including the gaps.

### [webai-smart-retail](https://github.com/Arnav274/webai-smart-retail) · [live demo](https://smartretailwebai.netlify.app/)
`TensorFlow.js` `COCO-SSD`

Real-time object detection that runs entirely client-side, nothing sent to a server. Point a webcam at a shelf, or drop in a photo or video, and it tags what it sees in the browser. Went in-browser specifically to avoid the latency and privacy cost of streaming video to a backend for something that doesn't need one.

### [job-application-tracker](https://github.com/Arnav274/job-application-tracker)
`Next.js` `PostgreSQL` `TypeScript`

Built after tracking my own job search in a spreadsheet for a few months and getting sick of it. Tracks every application's actual status instead of a half-remembered mental model of who I followed up with.

### [safevalley-map](https://github.com/Arnav274/safevalley-map)
`React` `Leaflet` `Firebase`

A hazard-reporting map for Johannesburg's Makers Valley, built for the Engineers Without Borders Digital Design Challenge. The brief was a community with no formal way to flag problems to the local council. This gave them one, on a map, usable without training.

<br/>

## Right now

Led UEA's ML Society and organised hackathons through uni; did canoeing and mountaineering with the societies there too. Also led a 4-person team to 4th out of 20+ at UEA Climate Hack, three hours ahead of the deadline. Now freelancing dev work for small businesses alongside the Reg-X internship.

I'm currently training MMA, I'm also learning guitar (currently stuck on Enter Sandman), and I'm hardstuck Immortal 3 in Valorant.

<table>
<tr>
<td align="center" width="50%">
<img src="https://is1-ssl.mzstatic.com/image/thumb/Music211/v4/86/a2/de/86a2dee2-78ee-071a-069a-4889a85ab450/075679566751.jpg/300x300bb.jpg" height="120" /><br/>
<sub>on repeat: <b>Tokyo</b> by Niko Rubio</sub>
</td>
<td align="center" width="50%">
<img src="https://covers.openlibrary.org/b/id/12735651-M.jpg" height="120" /><br/>
<sub>reading: <b>Bad Blood</b> by John Carreyrou</sub>
</td>
</tr>
</table>

<br/>

## Contact

<a href="mailto:arnavpawar.tech@gmail.com">
  <img src="https://img.shields.io/badge/Email-arnavpawar.tech%40gmail.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://linkedin.com/in/arnavspawar">
  <img src="https://img.shields.io/badge/LinkedIn-arnavspawar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
