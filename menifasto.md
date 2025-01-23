# The Name

Trees are *everywhere* in I.T. and in Knowledge Representation.
There's no avoiding them. And when your main hammer is an RDMS,
trees are difficult to nail, and difficult to make more elaborate.

But there are some interesting ideas "out there". One is `RelFS`,
and its author has some interesting ideas. Another is `muiltitrees`,
to help organise complex trees. 

So let's say: `Tree + RelFS + Multitree ~= Trellis`

... _(and interestingly, a trellis is what a multitree can resemble)_

# IRL

Trees form the basis of filesystems, because nothing better
has gained world domination quite like simple trees have.
(Hard links and soft links are just window dressing.)

Top-down. Directed. Single-rooted. 

__**Tags**__ might seem like part of a cure. Perhaps you're thinking
of a vast flattened pool of content, with faceted tags for
narrowing searches down. But that doesn't really work either.
Not well, anyways.

Furthermore tags themselves need to be hierarchical, so that's
a complicating factor.							

And when you're talking content reuse (for example), it's not
just munltiple child nodes that are important, it's multiple
parent nodes too. There's **Contents** and but OTOH there's
**Contexts** too.

So, any particular content node can have
- multiple children
- multiple parents
- multiple incoming facet links
- and don't forget arbitrarily large amounts of metadata
- and multiple versions and multiple (re)presentation formats 

This makes it much more interesting than a simple top-down tree.

# Foods for Thought

- [RelFS summary at GH](https://github.com/nayuki/Relational-File-System)
- [RelFS rationale](https://www.nayuki.io/page/designing-better-file-organization-around-tags-not-hierarchies) [local]()
- [File Systems: The Original Hypermedia)(https://jon.work/og/#1) [local]()
- [Multitrees: Enriching and Reusing Hierarchical Structure](https://adrenaline.ucsd.edu/kirsh/Articles/In_Process/MultiTrees.pdf)

