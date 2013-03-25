# Responsive web design: the war has not yet been won

Responsive Web Design. All the cool kids are doing it. We extolled the virtues
of [Ethan’s holy trinity of fluid layouts, flexible images, and media queries](http://alistapart.com/article/responsive-web-design), and slowly but
surely everyone dropped fixed-width designs for websites that flex and bend to
every scenario, and adapt to every device.

Or did they?

Well, no. As widely adopted as the RWD process is, there are still numerous
designers, developers, freelancers, and agencies who continue to opt for the
safety of fixed widths, or adopt the process in a semi-complete sort of way —
like making several fixed designs that adapt to specific device sizes, or change
only when the screen is at a mobile-like resolution.

It’s easy to dismiss this crowd as old-school agencies, or print-focused
creatives who don’t ‘get’ the web, and they certainly do account for a large
amount of this RWD-wary crowd. But I’ve noticed a whole bunch of very web-savvy
people (whose work I respect, and many of whom I call friends) who seem not only
adverse to the idea of adopting the RWD process, but actually quite vocal in
their opposition.

So today I’d like to address these arguments and — hopefully — dispel some of
the myths that are preventing a huge number of talented people from embracing
the inherently fluid nature of the web.

## RWD is not mobile design

With no disrespect intended to the talented folks behind GoCardless, my heart
sank a little when I read [their blog post about why they’ve decided to ditch
responsive web design](https://gocardless.com/blog/unresponsive-design/). Their
argument hangs on the premise that only 2% of their audience were visiting the
site on a mobile device, and thus it wasn’t worth the extra time and effort to
make the site responsive (more on that in a second). Although the article is
well-written and eloquently substantiates their rationale, I can’t help but feel
that they’ve misinterpreted the meaning of RWD: namely, that it is not simply
mobile design. Nor is it tablet design, nor game console browser design, nor
screen-on-your-futuristic-fridge design. RWD, in my opinion, should be device
agnostic.

Allow me to elaborate. From [the very first responsive site I
created](http://2011.ampersandconf.com/), I made the decision to introduce media
queries only when it felt natural to re-adjust the content, rather than when the
screen width reached a device-specific dimensions, like ‘iPhone landscape’ or
‘iPad portrait’. I’ve always encouraged others to follow the same process, if
for no other reason than it stops us thinking about specific devices, and in
turn makes our sites more future-proof. A hardware manufacturer might introduce
a brand new product tomorrow that changes the world and uses completely
different dimensions. If you adjust your design __when it looks right__, you
won’t have to worry about retro-fitting your media queries for new devices.

## RWD does not have to take more time, or cost more money

Perhaps the biggest obstacle preventing people from getting behind the concept
of RWD is that it takes more time to build responsive sites, and more time
equals more money. Well, I won’t lie to you: it does.

To begin with, anyway.

Once you overcome that initial struggle of adapting to a new process, designing
and building responsive sites needn’t take any longer, or cost any more money.
The real obstacle is designers and developers being set in their ways. I know
this because I was one of those people, and to those of you who’ve now fully
embraced RWD, you may well be nodding in agreement: we all struggled with it to
begin with, just like we did when we moved from table-based layout to CSS.

For those of you who are unconvinced, I imagine you’re keen to point out that
different views mean different designs, and that will always mean longer design
periods and higher costs, right? And what about complex sites? It’s all very
well when you’re designing simple one-page blogs, I hear you cry.

Well, again I think it’s all about changing the way you work. Changing the way
you think about web design, really. For a start, get out of Photoshop. Don’t
design a ‘desktop’ view as a flat file and a ‘mobile’ view as a flat file, or
something between, or anything for that matter. Now has never been a better time
to embrace designing-in-the-browser. Sure, that’s a challenge, and if you’re not
particularly code-savvy, there’s certainly an overhead there while you acquire
those extra skills. But [if you’re a web designer, you should be able to write
code](http://elliotjaystocks.com/blog/web-designers-who-cant-code/).

I say this not to create some sort of elite, or to chastise those who don’t yet
have that knowledge, but because knowing your way around markup and CSS — and
therefore being able to quickly try out what works and what doesn’t work in the
browser — is the biggest step you could ever take in making RWD part of your
process instead of an add-on.

Add-ons take extra time and cost your clients more money. Integrated processes
don’t.

(As an aside, if you’re like me and like to keep things simple, you might find
[my 1000px responsive
grid](http://elliotjaystocks.com/blog/a-better-photoshop-grid-for-responsive-web-design/)
helps avoid some of the tough maths often associated with RWD.)

## RWD is worth it

If you’ve read everything I’ve written so far, I’ve hopefully got across two key
points:

* RWD is about making your site adaptable to any scenario, without worrying
about specific devices and their proprietary dimensions.

* RWD doesn’t need to take more time and therefore doesn’t need to cost your
clients more money. At least not after you’ve rethought your approach to web
design, anyway.

However, there may still be some of you out there who are still asking the
simple question, ‘__but is it worth it?__’ And it’s actually a very valid
question, especially in those circumstances — such as when you or your company
are adapting to a RWD workflow — when it can equate to more time and greater
costs.

The answer, as always, is: ‘__it depends__.’

Some desktop-optimised designs work fine just as they are on tablets, which was
one of GoCardless’ main points, and probably the main reason they saw RWD as
simply designing for mobile. But aside from just telling you that responsive
sites are far more likely to be future-proof as the plethora of computing
devices grows, it’s worth looking at some actual statistics.

Electric Pulp recently [evaluated the affect that responsive-ising a client’s
e-commerce site had on conversions, transactions, and
revenue](http://electricpulp.com/notes/you-like-apples/). The results were
overwhelmingly positive, even when taking in the overall (desktop) growth of the
product, as [detailed in a follow-up
post](http://electricpulp.com/notes/more-on-apples-mobile-optimization-in-ecommerce/).

At the end of last year, [Time magazine](http://time.com/time/) found that
moving to a responsive design worked wonders for them. Craig Ettinger, general
manager for Time.com, has detailed the positive increases in interviews for
[magazine.org](http://magazine.org/timecom-gm-craig-ettinger-bringing-responsive-web-design-iconic-brand)
and
[adweek.com](http://adweek.com/news/technology/time-moves-responsive-design-144666).

## In conclusion

I could go on about why I think Responsive Web Design is a great idea for your
websites, clients, colleagues, and of course users, but the thought I’ll leave
you with is this:

Create a new HTML document, add some content, don’t add any CSS, and view that
document in a browser. What do you see?

[The web has always been
fluid](http://adactio.com/journal/search/?query=liquid); we’ve just wasted a
good number of years forcing fixed pixels onto an inherently responsive
framework. The time to stop is now.