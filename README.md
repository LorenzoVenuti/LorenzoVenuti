# Lorenzo Venuti

I like problems where the answer has to be both correct and on time — vision pipelines that
have to spot a defect, and schedulers that are not allowed to miss a deadline.

Most of what I build starts the same way: something is slower, noisier or more manual than it
needs to be, and I want to see whether it can be made to behave. Sometimes that turns into a
serious piece of engineering, sometimes into a thing that plays a song when I clap. Both are
here.

## What you'll find

**Personal experiments** — ideas I wanted to try, usually small, and usually because the setup
annoyed me first.

**University projects** — computer vision, real-time systems, embedded and IoT. These are the
ones with measurements attached: I care more about being able to *defend* how a system behaves
than about it merely working.

**Automation** — things built for work or for my own workflow, published in a simplified form
when the underlying idea is mine to share.

## Currently in the open

**[realtime-traffic-controller](https://github.com/LorenzoVenuti/realtime-traffic-controller)**
— a hard real-time traffic light controller in C11, driving a SUMO simulation over TraCI: four
`SCHED_FIFO` tasks, a gateway that owns the socket so the blocking term can actually be
computed, and an emergency vehicle that gets a green light before it arrives. The measurement
data is published whole, including the result that does not flatter it — measured against the
real cost of a simulator roundtrip, the system is not formally schedulable, while staying
functionally correct and safe. Being able to say that precisely is the point of the project.

**[ironman-powerup](https://github.com/LorenzoVenuti/ironman-powerup)** — clap twice and your
Mac plays a song, greets you and opens your editor; clap three times and it stops. A microphone
listener, a background LaunchAgent, and a few macOS quirks documented on the way out.

## Team projects

**[library-booking-system](https://github.com/PinelliLuca/library-booking-system)** — IoT
platform that helps students find a free seat in the university library, through a web app and
sensors. Contributor.

---

📫 [LinkedIn](https://www.linkedin.com/in/lorenzovenuti)

⭐ Stars are always welcome — the current count leaves generous room for growth.
