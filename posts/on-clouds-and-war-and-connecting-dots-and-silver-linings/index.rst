.. title: On Clouds and War and Connecting Dots and Silver Linings
.. slug: on-clouds-and-war-and-connecting-dots-and-silver-linings
.. date: 2019-04-30 00:54:05 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
.. has_math: true

.. include:: common.rst


|I| am beginning to *get* cloud computing. While |I| come from the "dev" side of
DevOps |I| am starting to understand the operational advantages of a cloud
architecture. After all, it is hard to ignore the deluge of articles and
evangelism presenting the myriad benefits of cloud. But |I| don't want to speak
of any of that. Instead |I| want to tell a story about war and technology and
smart people putting 2 and 2 together.


Connecting Dots...
--------------------------------------------------------------------------------
In the 1990s |I| met and worked with many programmers from the Geographic
Information Systems (GIS) arena. From them |I| learned the basics of how the
Global Positioning System (GPS) developed and run by the United States military
works. This was before the days of Wikipedia_ where you can learn much more
today, but back then |I| was fascinated by one story in particular.

.. _Wikipedia: https://en.wikipedia.org/wiki/Global_Positioning_System

GPS signals have been available for civilian use since the 1980s. The signal is
purposely degraded by an introduced error to prevent the system being used for
purposes unapproved by its owners, the United States government. This introduced
error can be switched on and off, and the entire signal can be denied to civilian
devices altogther when the error is removed.

The man |I| met spoke of a GIS conference that took place when the United States
was on the verge of military action. |I| do not remeber the particular event he
was describing, but, as you will shortly see, that is not relevant to this story.
Contemplated military action is news worthy and there was much in the media.
Would the US act? Wouldn't it? Should it? Shouldn't it? Then as now, the news
was full of many views and opinions. The timing of any action, however, was not
revealed before hand.

And so we come to a table of GIS practioners, sharing lunch during a conference,
many of them with GPS devices. Today such things are common place in our smart
phones but in those days it was only at such a gathering that many would be
seen together. During lunch, this man's GPS device suddenly lost signal. So, too,
did his neighbor's. And across the table. Everyone's device suddenly lost signal.

A silence fell, he recalled, as they realized the cause. Civilian GPS access had
been switched off. Why? They knew if the error was switched off, public access
would also be stopped. Why would the error be switched off? |I| was still in the
dark until he explained that at the moment of invasion, the error is removed to
enable the invading Marines to set up local base stations with full accuracy.
Within minutes the error can be reintroduced; the invading forces can
account for it using their accurate local base stations.

The civilian signal was only off for the span of a few minutes, but that group
not only noticed, they knew what it meant. Half way around the planet, they knew
before any news report confirmed it: the Marines had gone in.


... and More Dots
--------------------------------------------------------------------------------

So what does this have to do with cloud computing architectures?

|I| am still reading Shoshana Zuboff's excellent and disturbing, **The Age of
Surveillance Capitalism**. Within it, she defines and recounts the genesis,
methodologies, and ongoing aims of this new form capitalism. Through a series of
innovations and accidents of history, its originators discovered the predictive
value of what she terms "behavioral surplus." In information technology we know
this as "metadata."

Those GIS professionals were the first civilians in the Western world to know
the very moment, to the minute, when a military invasion began a half a world
away. Such is the power of metadata analysis. Eight people, sitting around a
lunch table... and they knew!

Today's surveillance capitalists have created and continue to grow empires from
the behavioral surplus |--| the metadata |--| of our lives. Every search and
click and "like." Zuboff's anlaysis is thorough and chilling. |I| am eager to
see if she tells of what |I| report here. If she does |I| will know that |I|
understand her; if she doesn't then this may be my first contribution to the
cause.

Consider: We know from her of the rapacious and insatiable appetite of
surveillance capitalist for ever increasing sources of behavioral surplus. We
know, too, of the astronomical profits they reap from the predicative and
frightenlingly manipulative value they derive from their appropriation of such
metadata.

And know they invite us to run all of our software on their hardware, in their
data centers. Why? Is it simply to ease our operational problems? To make our
lives easier? It may do that, but there will be two costs we pay. First and
publically for the service. As each instance spins up and spins down. But we
will pay again through the metadata they claim as their own.

Imagine you are running an application that deals with shares: tracking,
trading, anything; many shares, across many markets. To load balance you divide
the work based on ticker symbol. Your cloud instances will spin up and down
based on load: A-B, C-D, E-F, G-H, and so on. Suddenly your application spins
up 100 more instances. Maybe this is done by someone at your company, maybe it
happens automatically because you wrote a smart application that monitors its
internal latencies and throughputs.

Would it be fair to conclude that 100 new instances spinning up imply an
increased load or the anticipation of such? So, this load... is it for tickers
that start with A-B or G-H or M-N? What could you conclude from knowing that?
Could a guess be made as to whose shares are going to see action? The data
within the application remains private, but the metadata of instances starting
and stopping yields volumes of information itself.

While easy to explain, such a scenario is unlikely to happen to any large
investment bank. Such canny customers have long known the importance of even
the smallest scraps of information. Perhaps this explains the "hybrid solutions"
cloud vendors are starting to offer: their cloud infrastructure, hosted on
premise in private data centers. Will the investment banks trust them?

Block chain technology is often presented as a privacy panacea these days. The
number of band wagons |I| have seen roll by in my career engenders a certain
scepticiism in me as new ones appear, but block chain may yet have its uses.
|I| do not know enough to embrace or dismiss it entirely. Let's put down a
few dots we all know and see what connections we make.

Proof of work in block chain implementations takes a lot of compute power.
Cloud vendors, eager for this business,  are offering nodes and instances primed
for such compute intensive jobs. We also read that cloud technology has advanced
to the point where instances can be migrated between servers on the fly.

So imagine a rack of servers in a cloud that suddenly starts running hot. Power
consumption soars. A smart cloud will move jobs as necessary to even the load.
In distributing such loads, the cloud vendor will know whose jobs are running
hottest. They will know who is doing a lot of proof of work. They may not know
why, but they will know when. When the load grows, when it drops, when it stops.
Does that sound like something block chain evangelist will approve? Block chains
may keep their ledgers anonymous and secure, but they leak metadata like
everything else.

Lots of isolated data points, meaningless dots... But what can you conclude
from connecting those dot to millions of others? Dots from apps that track
shares, that allocate rides, that order pizza, that control power stations, that
monitor crops, that sense frosts in orchards...

Surveillance capitalist have appropriated behavioral surplus from everything we
do and use it to infer more about us than we know of ourselves. With their
cloud architectures they are now aiming to do the very same thing to the
corporations for which we work, to every application we write, from IoT to
enterprise to government to public service. Everything that runs "in the cloud,"
grist to their mills

Clouds and Linings
--------------------------------------------------------------------------------
The saying is that all clouds have a silver lining. Not these new clouds.

These are lined with gold.

|I| said |I| am beginning to get cloud architecture. |I| certainly
understand now why the vendors present it as "the new *golden* age of cloud."


