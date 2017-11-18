= Welcome to FnCorp! =

Welcome to FnCorp, new hire!

We do things differently here at FnCorp and this document will serve as your
orientation. Everything we do is built on an approach called Live Specification
or live-spec for short. We'll talk about live-spec below but first we need to
talk about dead specification.

= Dead Specification =

If you're coming from some other company like BigCorp, you've likely interacted
with something we here call dead-spec. At other companies, before you start a
project, you open your word processor and create a specification document. Or
several specification documents.

Of course you don't finish the specification in one sitting, that would be
amazing but impossible. It's impossible because you don't know all the
requirements and constraints when you start a project. You forge ahead anyways
because the project needs to get done.

After weeks or months of meetings and specification revisions, you have enough
to get started! The project is approved and everyone starts building their
pieces.

There's one problem... the spec isn't really done. Some parts of the system
seemed to small or simple to specify. Other parts, were left incompletely
specified because you were waiting for details from other teams or other
companies.

For a while, if your company is very, very dilligent, you and some other
coworkers will update the specification when you notice a detail is missing or
incorrect. Eventually, however, this task is overwhelmed by several factors.

The first is that you're very busy. There's a lot of work to do (more than you
wrote in your spec) and making progress on the project is really important.
It's easy to not notice when you're making an implementation choice that isn't
captured in the spec and, even if you do notice, it's easier just to move on to
the next task.

Another factor is that there's a lot of details for this project and it's hard
to keep track if which ones are out of date or incorrect. Sure, testing will
eventually catch parts of the system that diverge but people will fix one
system or the other with a local fix and move on.

Also, changes to the spec seem very official. You had a lot of fairly painful
meetings to hash out the details in the spec. It's far easier to just make a
decision and implement it rather than risking more protracted meetings to hash
out the right answer that you're sure you just put into the implementation
anyways. Why update the spec -- it will only cause trouble!

And so, the spec, that was never really complete or accurate in the first case,
is left behind to rot as the implementation moves fowards. Sure, deviations and
undesigned parts of the implementation will cause last minute panics as final
testing shines the harsh light of reality on the project but that's just how
things go, right? Can we do any better?

= Live Specidfication =

Of course we can do better!

The idea of live-spec is quite simple but also very abstract. The idea is this:

  live-spec is the practice of extracting implementation details directly from
  the specification to use in the implementation.

That's it! It doesn't seem like much but it changes *everything*. We'll get
into the details of how we go about this later. For now let's think about the
ways that this can impact a project.

