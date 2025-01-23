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

***Tags*** might seem like part of a cure. Perhaps you're thinking
of a vast, flat (i.e. unhierarchical) pool of content, with faceted
tags for narrowing searches down. But that doesn't really work either.
Not well, anyways.

Furthermore, to be useful, tags themselves should be hierarchical,
so that's a complicating factor.	

And when you're talking content reuse (for example), it's not
just munltiple child nodes that are important, it's multiple
parent nodes too. From the viewpoint of a node, one speaks of
***Contents*** but also of ***Contexts***.

So, any particular content node can have
- multiple children
- multiple parents
- multiple incoming facet links
- and let's not forget
  - arbitrarily large amounts of metadata
  - multiple versions
  - multiple formats of (re)presentation
  - concurrent modification 

This makes it all much more interesting than a simple top-down tree.

# Foods for Thought

- [RelFS summary at GH](https://github.com/nayuki/Relational-File-System)
- [RelFS rationale](https://www.nayuki.io/page/designing-better-file-organization-around-tags-not-hierarchies)
- [RelFS commentary](https://karl-voit.at/2020/05/19/RelFS/)
- [File Systems: The Original Hypermedia](https://jon.work/og/#1) 
- [Multitrees: Enriching and Reusing Hierarchical Structure](https://adrenaline.ucsd.edu/kirsh/Articles/In_Process/MultiTrees.pdf) 
- _(local copies are in subdirectory `local/`)_

# UI

"Normal" trees can be shown easily, like so:
```
~/trellous >> tree
.
├── local
│   ├── Designing better file orgzn around tags not hierarchies.xhtml
│   ├── File Systems The Original Hypermedia.html
│   ├── MultiTrees.pdf
│   └── RelFS A Hypothetical Tag-Based File System.html
├── menifasto.md
```

If tags are done right, then foldirectory structure
becomes just a default mode for navigation, and a
substructure for the rest of the system to build on. 

When contexts are wanted in addition to contents,
and when tags are wanted, a 2-by-2 grid might work,
whetehr the item is a foldirectory or a document:

```
tags     contexts
     item
multi    contents
```

Multi could be a previoew, or metadata, or a review
panel, or whatever, changing dynamically. 
