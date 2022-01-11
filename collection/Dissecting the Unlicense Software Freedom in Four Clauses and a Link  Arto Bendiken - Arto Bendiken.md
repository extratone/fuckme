# "Dissecting the Unlicense: Software Freedom in Four Clauses and a Link | Arto Bendiken"

*10-01-2022 17:57* 

> I've previously written on the motivation that led us to formulate the Unlicense, a template for dedicating your software to the public domain. Today, I will elucidate the rationale for and the provenance of each of the four brief paragraphs (plus footer) that constitute the Unlicense.
I've [previously written](https://ar.to/2010/01/set-your-code-free) on the motivation that led [us](https://groups.google.com/group/unlicense) to formulate the [Unlicense](https://unlicense.org/), a template for dedicating your software to the [public domain](https://me.stpeter.im/essays/publicdomain.html). Today, I will elucidate the rationale for and the provenance of each of the four brief paragraphs (plus footer) that constitute the Unlicense.

The Unlicense combines a public domain dedication and copyright waiver patterned after those of the well-known public domain [SQLite](https://www.sqlite.org/) project with the no-warranty statement from the widely-used [MIT/X11 license](https://en.wikipedia.org/wiki/MIT_License). We also provide a [well-defined process](https://unlicense.org/#unlicensing-contributions) instructing [Unlicense adopters](https://unlicense.org/#unlicensed-free-software) on how they can ensure that any third-party contributions remain likewise unencumbered by copyright.

The entire effort and [nascent movement](https://ostatic.com/blog/the-unlicense-a-license-for-no-license) could not have come about without the inspiration and example of the SQLite project, which [by any measure](https://www.sqlite.org/mostdeployed.html) is surely to be counted among the most successful public domain software projects of all time. SQLite has combined [technical excellence](https://aleccolocco.blogspot.com/2009/08/sqlite-lesson-in-low-defect-software.html) with a unique take on [liberal licensing](https://www.sqlite.org/different.html#license):

> The source code for SQLite is in the public domain. No claim of copyright is made on any part of the core source code. \[...\] This means that anybody is able to legally do anything they want with the SQLite source code.
> 
> There are other SQL database engines with liberal licenses that allow the code to be broadly and freely used. But those other engines are still governed by copyright law. SQLite is different in that copyright law simply does not apply.
> 
> The source code files for other SQL database engines typically begin with a comment describing your license rights to view and copy that file. The SQLite source code contains no license since it is not governed by copyright. Instead of a license, the SQLite source code offers a blessing:
> 
> > May you do good and not evil
> > 
> > May you find forgiveness for yourself and forgive others
> > 
> > May you share freely, never taking more than you give.

Over the years the SQLite project has needed to develop much of the [legal infrastructure and process](https://www.sqlite.org/copyright.html) necessary for any large public domain project. This includes e.g. collecting copyright waivers from contributors and issuing [special one-off licenses](https://www.hwaci.com/cgi-bin/license-step1) to megacorporations with legal departments unable to grok the concept of the public domain. Many a conversation on the project's [mailing lists](https://www.sqlite.org/support.html) illuminate the legal hurdles they have overcome and provide hoards of valuable information to anyone considering unlicensing their code into the public domain.

[We](https://groups.google.com/group/unlicense) launched the Unlicense initiative so that any software developer can now draw on this time-tested knowledge base, infrastructure and process to do what SQLite's authors have done: [set their code entirely free](https://ar.to/2010/01/set-your-code-free).

Now, it is certainly the case that you can perfectly well dedicate your code to the public domain without using the Unlicense, but information on how to do that can be hard to find and apply. Until now everyone who has released their software into the public domain has done so with differing wording, subject to differing legal interpretation in differing jurisdictions.

Contrasting this situation with the familiarity of simply copying a license file into your source code repository, it is perhaps no great surprise that many who would otherwise have been inclined to release their code into the public domain have instead opted for some very permissive license, avoiding the perceived legal morass of the public domain. This has constituted a barrier to both the production and adoption of public domain software.

We hope that the Unlicense can help change this for the better. Think of the Unlicense as a gateway to resurrecting the public domain in software.

## §1 The Executive Summary

The first paragraph of the Unlicense reads:

> This is free and unencumbered software released into the public domain.

In principle, wording such as this is in and of itself sufficient to dedicate a work to the public domain. In practice, given the litigious age we live in and the variations on how the public domain as a concept may be codified and interpreted in different jurisdictions, most authors will want to be somewhat more explicit. Hence the rest of the Unlicense.

This first paragraph is, hopefully, self-evident in its simplicity; but let us nonetheless briefly examine its constituents:

"Free" here means most of the definitions of the word in any English dictionary. It means "for free" as in "gratis" and "given or available without cost, payment or charge". It means "freedom" as in "not under the control or in the power of another", implying among other things "not subject to despotic government". It means "free to" as in "free to make use of". And, of course, it means "free from" as in "free from copyright" and "free of" as in "not subject to copyright".

"Unencumbered" qualifies and helps establish the aforementioned meanings by stating that your use of the software isn't burdened or weighed down by any restraints or obligations whatsoever; more on this in the next section. Some more loaded alternatives to "unencumbered" would be "unlicensed" or "uncontaminated", which also convey the notion that the software has no strings attached to it; but for the Unlicense text itself we felt it best to stick with the more neutral term.

Lastly, "the public domain" means those materials, in this case those pieces of software, that nobody claims as an [intellectual monopoly](https://levine.sscnet.ucla.edu/general/intellectual/againstfinal.htm) and hence are not subject to copyright. These works are available for anyone to use freely for any purpose.

## §2 The Freedoms

The second paragraph of the Unlicense reads:

> Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

This paragraph originates from [SQLite's](https://www.sqlite.org/) [public domain dedication](https://www.sqlite.org/copyright.html), with only "the original SQLite code" changed to "this software".

This is simply a listing of some of the specific things you can do with any entirely free public domain software. It is not intended to be exhaustive, merely illustrative. You have *complete* freedom to do *anything* ("for any purpose") you want with the software. When someone dedicates their work to the public domain, they are making a public guarantee that they will not send any copyright cops after you even if they personally dislike the uses you've put their software to.

You may notice the similarity to the [old saying](https://en.wikipedia.org/wiki/Evelyn_Beatrice_Hall) of "I disapprove of what you say, but I will defend to the death your right to say it."

So, yes, you are perfectly welcome to incorporate the code into proprietary software. Yes, you can relicense the code under any license you please. No, you don't need to include any original copyright statements (there are none) or a copy of the Unlicense. No, you don't *need* to give attribution to the original authors -- though as a matter of common courtesy you probably *should* be doing so!

The legal significance of this Unlicense clause is that even if it so happened that in some backward jurisdiction there were any questions about the interpretation of a public domain dedication like the Unlicense, the authors have here very explicitly granted permission to do just about anything with the software. So, while the Unlicense is not *intended* to be, legally speaking, an actual copyright license, but rather merely an explicit form of public domain dedication, the fallback strategy for any public domain-unfriendly jurisdictions is to in fact treat it as if it were an extremely permissive license.

We would like to eventually improve this paragraph somewhat, to make it read a bit better and to explicitly mention a few more of the things you are allowed to do. Ultimately, it ought to also be somewhat more, well, poetic.

## §3 The Legalese

The third paragraph of the Unlicense reads:

> In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

This legally significant paragraph is a statement of intent that has its origins in [SQLite's](https://www.sqlite.org/) [public domain dedication](https://www.sqlite.org/copyright.html), which in turn is based on the Creative Commons [public domain certification](https://creativecommons.org/licenses/publicdomain/) with the wording changed (improved, I should say) from the third person to the first person.

This paragraph is important because it establishes *intent*. Regardless of how the public domain as a concept is codified in the laws of a particular country, this paragraph makes it very clear that the authors have explicitly disavowed any and all monopoly privileges granted them by copyright law -- in the full knowledge that this could, in theory, be financially detrimental to them.

Since the fitness of this paragraph has been established in the SQLite project, we incorporated it as-is but for two trivial changes:

We changed "this code" to "this software" to ensure we're covering not just the code per se but everything that constitutes the software, typically the entirety of the source and binary distributions. There is better room for appropriate interpretation in "this software" than in "this code".

We also very purposefully added the introductory "in jurisdictions that recognize copyright laws" text. Beyond the immediate practical goal of helping you unlicense your software into the public domain, a secondary goal of the Unlicense is to help disseminate the idea that we perhaps really shouldn't be taking for granted the existence of copyright licensing and copyright laws in the first place.

If you actually take some time to read about the [history of copyright](https://questioncopyright.org/promise), you will discover that most everything you thought you knew about copyright is mistaken. Despite popular myth, copyright did *not*, in fact, come about as some noble effort to protect the rights of authors, but rather has its ignoble origin in the privatization of censorship in 16th century England. Its further developments have been by and for the distributors, as is evident even today with the major media companies seeking, and obtaining, what amount to perpetual extensions to their copyright terms.

All this notwithstanding, however, everyone twentysomething and younger knows that we are already well on our way to a [post-copyright world](https://levine.sscnet.ucla.edu/general/intellectual/againstfinal.htm). Since we wanted the Unlicense's wording to stand the test of time, we did not bake in the current implicit assumption that copyright is "just the way things are". Rather, we baked in the hope for a future where increasingly fewer jurisdictions cling to their obsolete copyright laws at a clear disadvantage to those freer corners of the world that have already let go of the concept.

## §4 The Don't-Sue-Me

The fourth paragraph of the Unlicense reads:

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

This no-warranty clause comes almost verbatim from the [MIT/X11 license](https://en.wikipedia.org/wiki/MIT_License), with the "the authors or copyright holders" changed to read merely "the authors". After all, the whole point of the Unlicense is that there no longer are any copyright holders for the software, only authors.

Now, it must surely be evident to every reasonable human being that this no-warranty paragraph is, inherently, a redundantly idiotic bunch of all-caps legalese in defense of the perfectly obvious point that "yeah, dumbass, I'll pay you the $0 in damages that the software cost you."

An alternative wording I'm fond of is "assume nothing works, and you may be pleasantly surprised; and when it breaks, you get to keep both pieces."

Redundant and idiotic as it may be, we knew we had to include a no-warranty clause of some kind. An often cited, though unwarranted, concern about releasing your software into the public domain is that this could leave you open to damage claims from litigious imbeciles who somehow managed to microwave their cat and burn down the house with the help of your code, whereas using a permissive license with lots of capital letters would magically prevent this.

So, whether to alleviate a perceived problem or a real one, we felt we did need to very explicitly disclaim any implied warranties as part of the Unlicense public domain dedication. We evaluated the all-caps clauses in various permissive licenses, including the [BSD](https://en.wikipedia.org/wiki/BSD_licenses) and [ISC](https://en.wikipedia.org/wiki/ISC_license) licenses. They all read somewhat differently but hit the same points. In the end we preferred the MIT/X11 license's wording as well as its (relative) brevity, so that's what we incorporated.

We have preserved the all-caps nature of the paragraph only for the sake of your reading pleasure, namely so that your eyes can gently and quickly glaze over it and continue on their way.

## §5 The Link

The footer of the Unlicense reads:

> For more information, please refer to [https://unlicense.org/](https://unlicense.org/)

This final line of the Unlicense simply contains an optional link to the [Unlicense.org](https://unlicense.org/) website. This is the only "viral" part of the Unlicense, and, naturally, you're perfectly welcome to leave it out from your copy of the Unlicense if you should so choose.

We expect that most adopters of the Unlicense will want to retain the link, however. If you care enough to swim against the mainstream in choosing to unlicense your code into the public domain, you will likely care enough to consider the Unlicense an idea worth spreading. But the choice is up to you.

This concludes my overview of the ingredients that went into the initial version of the Unlicense. If you believe you can improve on any of this, please join the [Unlicense mailing list](https://groups.google.com/group/unlicense) and let us know how.

*Kudos to [Ben Lavender](https://bhuga.net/) and [Mike Gogulski](https://www.nostate.com/) for their valuable input on this article.*
***

==**14062**== Words

- **[Dissecting the Unlicense: Software Freedom in Four Clauses and a Link | Arto Bendiken](https://ar.to/2010/01/dissecting-the-unlicense)**