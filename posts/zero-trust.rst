.. title: Zero Trust
.. slug: zero-trust
.. date: 2020-03-12 20:10:07 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
.. has_math: true

.. include:: common.rst

"Zero Trust. Security the Google way."

Where do |I| even start? At a link about "zero trust" and internet security.
Seems like something relevant to the themes covered in these posts. Certainly it
is quite a band wagon rolling through today's IT scene. So |I| clicked and
started reading.

My jaw has fallen so hard to the floor that |I| am having trouble organizing my
thoughts sufficiently to explain.

.. TEASER_END

A Man's Home Is His Castle
==========================

Let me try an analogy. |I| want a bit of security at home, reasonably enough. So
what do |I| do? |I| buy a lock and install it on my front door. Do |I| want a
*lot* of security? |I| buy a big lock. Maybe even two. |I| may even install
locks on the windows.

Now this is not a perfect solution; there are many problems. |I| have to keep
the keys safe, of course. And what happens if a burglar breaks in through a
window? The miscreant has full access to everything in the house. It is pretty
much game over. How would |I| even know which rooms he went through?

Trade offs need to be considered. |I| could install a safe behind the proverbial
picture on the wall in the study. A safe provides a higher degree of security to
an admittedly limited subspace of my domicile, but it can still be cracked and
it takes longer to access whatever is inside, inconveniencing me.

This, |I| have learned from the good people at `Beyond Corp`_ is much too old
fashioned. They term it "castle and moat" approach. Are we in the `dark ages`_
still? Wouldn't |I| rather do trust the Google way? A lock on the front door?
Pish! That is mere "perimeter control." So old fashioned. Let my family walk
freely between rooms? Heaven forbid! That is too much trust. **Zero trust** is
the aim, remember?

.. _`Beyond Corp` : https://beyondcorp.com/
.. _`dark ages` : https://www.youtube.com/watch?v=grbSQ6O6kbs

A New Approach to Enterprise Security
=====================================

So what is the new "zero trust" approach? How has Google "reimagined what a
security framework should look like to be truly effective in today's world"?

Instead of locking the front door, locks are put on every single door inside my
house. And -- and this is a big and -- every family member is given a
radio-tracked ankle bracelet to identify them. When they come to a door and ask
for it to be opened -- oh, did |I| forget to mention that |I| don't have the
keys for any of these locks? -- when they come to a door and ask for it to be
opened their identity and access rights can be confirmed before the door is
opened.

And recorded. That action -- opening the bathroom door for my child -- is
logged and analyzed and remembered. Why? To detect aberrant behavior. Someone
going rogue could compromise my security. The house will be secure, but |I| may
be cleaning puddles off the floor in front of the bathroom door late at night if
my child happens to drink a big glass of water before going to bed.

Finally, |I| pay for all this! For the locks, their installation, the ankle
bracelets, the on-going monitoring, the unlocking |...|

What could possibly go wrong?

OK. |I| have to drop the sarcasm; it is only raising my blood pressure.

----

The Players
===========

Zero Trust grew out of a series of white papers that Google published starting
in 2014 describing what they called `BeyondCorp \: A New Approach to enterprise Security`_ .
BeyondCorp now, however, appears to be owned by the Okta_ corporation, who
describe their business as identity management. They help enterprises with
Customer Identity and Workforce Identity.

.. _`BeyondCorp \: A New Approach to enterprise Security` : https://research.google/pubs/pub43231/
.. _Okta : https://www.okta.com/

Now what does it take to establish identity? Does establishing Customer Identity
constitute tracking? If an ambitious company decided to turn these same
techniques to Workforce Identity would that constitute invasive data harvesting?
Or does that just mean Human Resource?

Did |i| mention that Okta owns Workday_ , the out-sourced human resources
company. They do HR for myriad enterprises. They know everything about the
employees of their clients: names, ages, addresses, bank accounts, salaries,
health care, special needs, daily work records, |...| Everything.

.. _Workday : https://www.workday.com/

What could possibly go wrong?

It might be unfairly cynical of me to point out what |I| find a curious feature
of their software. When logging in to their web site one enters a name and
password. Nothing too unusual there. Then one has to press a button -- again not
an unusual user experience. What is unusual, perhaps revealing, is the label of
the button ones presses. It is not "login" or "sign in" or "connect".

**Submit** The button is labeled "Submit."

A simple glance at the Boards of Directors show these guys are going to be around
a while, too. Okta has venture backing from Andressen Horowitz and Sequoia
Capital although they have never turned a profit. Nor do they expect to in the
foreseeable future according to their 10-K_ filings. The obvious cynical question
arises: if you are not making a profit and don't expect to then why are you at
it? What are you up to?

.. _10-K : https://investor.okta.com/static-files/72d24232-5650-40aa-9b36-b6276173b827


Ulterior Motives?
=================
Imagine your are a company that wants to index the world's knowledge. Public
data is easy, but what about all that grey literature existing behind corporate
firewalls? It is beyond robot web crawlers. If those pesky firewalls weren't
there it would be easy to see everything. Zero trust obviates the need for
firewalls.

Zuboff has shown the value to be had from our personal data. |I| have already
expressed my own shock upon realizing the ability of cloud vendors to extract
similar meta data on the corporate level. Zero trust makes this data fine grained.
Every access by every employee to every internal application, web end-point,
and API tracked in real time.

Think about that seriously for a moment. We aren't talking about high school
students liking their friends' latest fashion. Look at the list of Okta's
clients_. Did you find the US Department of Justice or was that buried too deep
amongst the thousands of others?

.. _clients : https://www.okta.com/customers/

Downside
========
What could possibly go wrong? Do |I| need to mention `single point of failure`_ ?

.. _`single point of failure` : https://en.wikipedia.org/wiki/Single_point_of_failure

More disturbingly, consider the weapons potential of this sort of technology.
Think about what could be done. How it could go undetected. A subtle delay here.
An individual blocked access there. Go ahead, take a moment. |I|'ll wait |...|

Don't forget there are people whose job it is to think these things through.
Now imagine *paying* a company to install it across all your IT infrastructure
and run it for you all the while maintaining identifying information on your
entire workforce with an application siting on all their mobile phones.

Imagine a world in which the Scientologists developed Stuxnet_.

.. _Stuxnet : https://www.quora.com/What-is-the-most-sophisticated-piece-of-software-ever-written-1/answer/John-Byrd-2

----

|I| have to stop. This is too creepy. Where is Bruce Schneier when we need him?

