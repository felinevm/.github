# The Feline Project (work in progress)

Feline is another coding website that is simultaneously *great for young or beginner programmers*, and yet *extremely powerful for talented programmers*.

## The Manifesto
### Why?

Feline is inspired by Scratch. Scratch is extremely great for young programmers, or other people who want to get the base fundamentals. However, after fundamentals, there isn't anywhere
to go that isn't *pushing the limits of Scratch* (looking at you, Griffpatch).

Code.org is comparitively way better. The blocks aren't as elegant (not a grid layout, and instead localized), but you also have the option to write in JavaScript for specific modes. However,
the JavaScript you can use is outdated (no lambda functions?) 

Other than greivances with the tools above, those tools only teach the fundamentals. What if you could teach *more*? What if you could teach how CPUs work internally, with assembly instructions?
What if you could teach *real application development*? What if you could teach the basics of Linux? What if you could teach people what a REST API is, what a database is, how to do security, 
and more? Those tools can't really do that. I want a tool *to do that*. We need to be helping the next generation of programmers.

### How?

Most programming sites have a programming language, and an interpreter, and that's it. Instead, what we do, is we implement the RISC-V specification, and emulate whatever we want. This means that
you could teach more real-world programming languages, like Go, which is what we would use.

Using this, we could make a basic Scratch clone, sure. We could also allow tinkerers to modify part of Feline's own code (the Go drivers, libraries, etc) to see what would happen. However, using this,
we could boot fully competent systems, such as Linux. Using this *opens the floodgates on what we could do*. 

## The Stage

This is merely an idea, but I **will** implement this (at least the VM, Buildroot images, basic runtime, etc)
