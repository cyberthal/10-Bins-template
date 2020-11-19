
# Table of Contents

1.  [10 Bins organizes your life](#org8951f9f)
    1.  [What is it?](#org97b50a9)
    2.  [Reading order](#orgc76bba8)
    3.  [Cascade matching](#org6217aec)
    4.  [Descending priority-density and stability](#org37be5e3)
        1.  [Priority density](#org92fd0a2)
        2.  [Stability](#orgfa6d0e4)
        3.  [Priority density again](#org9b1624d)
    5.  [Skimming the cream](#org4efd41f)


<a id="org8951f9f"></a>

# 10 Bins organizes your life


<a id="org97b50a9"></a>

## What is it?

Treefactor is a software tool that allows rapidly filing objects in a directory tree.  

However, having a fast tool doesn't help much if you can't decide where things should go!

That sounds like a joke, but it's not.  Deciding where to file your personal information is surprisingly difficult.  Keeping it synced to reflect changes in the world and yourself is even harder.

10 Bins solves this problem, making filing easy, automatic and reliable.

10 Bins is a directory structure and set of filing rules.  It's called "10 Bins" because there are 10 standard directories, numbered 0 through 9 for quick access.


<a id="orgc76bba8"></a>

## Reading order

Each directory of 10 Bins contains a Readme file explaining its purpose.  Multiple file formats are provided with identical content.  Otherwise, the documentation avoids repetition.

For example, "Persinter" is defined in `3-Persinter`.  This definition is not repeated in deeper instances of "Persinter" directories.

"Solid names" is a conceptual prerequisite for "Name" directories and any directories cascade downstream.  "Solid names" is defined at `7-Names/2-Flat/Readme.org`.


<a id="org6217aec"></a>

## Cascade matching

Always sort the directory listing in descending alphabetical order.

Lower-number matches outrank higher-number matches.

In other words, earlier matches beat later ones.

For example, "Germany" is both a location and a name.  `5-Location` is earlier than `7-Names`, so "Germany" belongs in the former.


<a id="org37be5e3"></a>

## Descending priority-density and stability

Is it arrogant to assert that my idiosyncratic 10 Bins is an universally-correct template for personal info management?

No, because 10 Bins is supported by objective logic.  I'll explain.


<a id="org92fd0a2"></a>

### Priority density

10 Bins assumes descending alphabetical sort order, since that is the cross-platform default.

Info varies by personal priority-density.  A single sentence critical to your survival has maximum priority density.  A thousand page book about an irrelevant subject has minimum priority density.

10 Bins pushes high priority-density info upwards, in both sort order and tree depth.  

`0-Inbox` is first because its contents are of unknown importance until they're sorted.  Ignoring it might mean missing critical info.

`1-Outbox` is next because it is effectively the Inbox for another repo.  A similar danger applies, although at least you know the info doesn't belong in the current repo.

`2-Codex` has extremely high priority-density due the high info density and specificity of code-like info relative to prose.  Code snippets should be pulled out of bulk prose for easy retrieval.

`3-Persinter` welcomes everything else you feel is important enough to highlight.  You shouldn't overcrowd it, though.

As you can see, these first four directories follow the rule of descending priority density.


<a id="orgfa6d0e4"></a>

### Stability

Info also varies by retrievability.  The more costly the retrieval, the less profitable the info.  Maintenance cost also reduces info profitability.

Stable info has high retrievability and low maintenance cost.  The next four directories are ranked primarily by stability.

`4-Time` is first, since both money and time are precisely and objectively quantifiable.  The fact that time is precious doesn't hurt, either.

`5-Location` is next, because geography is quite stable, as is architecture.  Both are a bit more ambiguous and dynamic than time and money, though.

`6-Object` is next, because objects are clearly more ambiguous and dynamic than locations.  In fact, often locations could be considered very large objects.

`7-Names` is next, because names are more dynamic than the above.  Nomenclature gradually evolves, creating ambiguity and maintenance cost.


<a id="org9b1624d"></a>

### Priority density again

The last two directories follow the priority-density rule again.

`8-Action` contains much less info than `9-Background`.  Your plans are much more personally relevant than whatever background info helped you decide.


<a id="org4efd41f"></a>

## Skimming the cream

The info that reaches `9-Background` is like skim milk.  All the creamy info, full of high priority-density, retrievability and stability, has already been removed.  What's left is protein and water.

Since the cream always rises to the top, 10 Bins generates rich, delicious thoughts.

This improves iterational velocity, accuracy, creativity, and effective intelligence.

