# Do it again

This looks more like a journal than a blog right now, but that's because most of my ~ struggles ~ at this point are personal instead of professional. Once I start explaining why I'm great at working instead of great at being a human being, that's when it turns into a blog instead of me

## I learned a lot today

But I just wanna type and write stuff. Willie Lieberman is cool. I read about IRC and NMAP and watched the first two episodes of Breaking Bad. I've come to the conclusion that Nmap just has a bad user experience. It does something complicated, but the interface being limited to a command line just really doesn't help explain it. First you see if there're hosts with a host scan, then you scan the host's ports with a port scan. When you kick off an Nmap scan you give a range of IPs (hosts) and ports/services, as well as describe various pieces of metadata (round trip time timeout, hosts to scan in parallel, specifics about flags or data in the probes, etc.)

After writing the 120% of a blog post (I'm 20% through the second post, so I've written 120% of a post? I guess?) I see that prior vision will be crucial to writing a coherent post. My mind is in a few places right now, I've been dabbling in what I'm learning about today, and that really doesn't make it easier for me or someone else to understand what I'm trying to say.

## Specific - netlify

Netlify is awesome. They make something hard easy, and they do it very well. I love that they've built the beautifuyl abstraction of "just develop and deploy", but I guess I fear for the same reasons that I hate how complicated operating systems are now. Back in the ~olden days~ it was nice and simple, you could grok a whole system. But that's not the direction webdev is going in, which is fine. The basics are simple, but the frameworks and the hackyness and everything else that lets development speeds get wicked fast get prety complicated - there's no incentive to distill. Well, Netlify distills. AND they increase capabilities at the same time!? That's crazy. But of course, the cost of doing so is that they're abstracting a lotta stuff. It's approaching the class of tool where knowing how to use it does NOT equate to knowing how to build it.

## Tools

Maybe a post about classifications of tools (users vs. builders, pro vs. amateur) is warranted? I wanted to use C and vim and git as a *builder*, not just as a user. That's a big force that drives me. I see how it's impractical sometimes, but other times I just derive a lotta enjoyment outta something like knowing how to extend syntax highlighting in vim. Or grokking the branching model of git. Both are simple! But I didn't need to really learn them when I learned them. The syntax highlighting tidbit will most likely never be useful, but the git branching model has already been invaluable.

## Fauna db

I learned about fauna db, which seems pretty cool. It's just a cloud-based database, but it seems really easy to use, which I like. I've never understood databases, even though they're really simple. I learned what an 'index' is toady. I imagined it as a pointer you stick into a piece of data, analagous to an index tab. But it's more like an addendum at the back of a book, telling you things (or where to find things) (like a real book's index... duh. Ahahahaha)

## IRC

I've wanted to learn how to use IRC for a while now, I've just never gotten around to it.

## Digital trail - pocket

When I look something up, it sometimes takes a few links before I find a good learning resource on it. I try to always save the best ones in pocket or something in order to have a digital trail, I want to do my part in distilling the knowledge on the internet. If everyone could recognize bad info vs. good info and throw out the bad, then the critical path for learning something would be drastically improved. The only issue is... it's tough to know when information is good or bad. The unknown unknowns get you.

After reading the first 7 chapters of the Nmap book throroughly, I feel like I have a STRONG understanding of what Nmap is, and what/how it does. That let me realize that the book just explained things in an overly-thorough way - in the eyes of a beginner. For a professional, or for someone wanting a resource to look up that option they forgot, it's fantastic. If I find a 5 minute webpage that describes Nmap in a way that I feel woulda given me an equatable amount of understanding to the 7 chapters, then that's a perfect candidate for the resource collection. The digital trail, that I want all those who wish to follow in my footsteps to read. It hopefully won't take ANYONE 21 years to learn as much as I did in 21 years in the future, thanks to the distillation of cruft outta the information sphere they're a part of. That being said, Knowing how to recognize cruft from gold is a good skill, and one that I'm trying to develop. And only giving someone gold will probably have some negative side-effects.

Learning is facilitated by 1) understandable systems 2) understandable information and 3) intelligence. Intelligence can be changed, but it's slow. Systems are complicated only by necessity. If a tool is displayed as overly complicated for no reason (@ people who write stuff in C pretty much lol), then that's just how it is. I kinda view it as horizontal. You want a pyramid, with a tiny understandable tidbit at the top that, when inspected, leads to a more in-depth and technical explanation. Which, when inspected, leads to another layer. Ideally there's not too many layers, or else it gets impossible to hold the whole thing in your head. But it's find if there're many layers, because you can just have users master one layer before moving to the next one. (Simple git/vim operations, then stuff like push -f and macros using registers, then all the lit stuff like the branching model and vimscript.) Nmap is like only 2 or 3 layers of complexity, there aren't really many abstracitons. The tidbit is "Scan machines". The next layer is "Scan IPs to see if there're hosts, then scan the ports to see if there're programs". Prerequisite knowledge is that the OS catches all packets being sent to a machine, and based on the "tag" or "port number" on the packet, it'll determine which process to send the packet to. Then a program will read the packet payload as input and proceed with execution. As for number 2, "understandable information", I guess that one's self-explanatory. You can write something simple in a complicated fashion and have it look like gobbeldygook. Obfuscating true meaning with purple prose (or TLAs lmao), OR wrong assumptions about what your audience knows are both highly detrimental to transmitting information. And maybe the blog-post format is just bad in the first place.

I think that I should link more external readings into my posts. I can already envision an easy-to-write vim mapping that'll help me do that. It'll be executed from visual mode. It'll wrap the highlighted text in brackets, then pull the link from the system clipboard and put that into parenthesis. Or maybe I should use some sorta better text editor.

Well, I've rambled enough. It feels nice to put my thoughts into writing, I feel like I don't have to keep them in my head for as long. I guess that means that I can forget them and be chill with it ! [Closure](https://youtu.be/E-F1U4bV2m8).
