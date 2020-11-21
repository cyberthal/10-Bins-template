
# Table of Contents

1.  [10 Bins organizes your life](#org92c60c1)
    1.  [What is it?](#orgd57fa70)
    2.  [Reading order](#orgef44d3e)
    3.  [Cascade matching](#org00c4124)
    4.  [Descending priority-density and filing-friendliness](#orgf65fc9e)
        1.  [Idiosyncratic?](#org0daec3c)
        2.  [Design principles](#org9fff520)
        3.  [Priority density](#orgcbb9665)
        4.  [Filing friendliness](#org2a2f895)
        5.  [Priority density again](#org094f1de)
        6.  [Case study: US Civil War](#orgc76ef05)
    5.  [Skimming the cream](#org75d79c6)
    6.  [Links](#org6888e64)


<a id="org92c60c1"></a>

# 10 Bins organizes your life


<a id="orgd57fa70"></a>

## What is it?

[Treefactor](http://treefactor-docs.nfshost.com) is a software tool that allows rapidly filing objects in a directory tree.  

However, having a fast tool doesn't help much if you can't decide where things should go!

That sounds like a joke, but it's not.  Deciding where to file your personal information is surprisingly difficult.  Keeping it synced to reflect changes in the world and yourself is even harder.

10 Bins solves this problem, making filing easy, automatic and reliable.

10 Bins is a directory structure and set of filing rules.  It's called "10 Bins" because there are 10 standard directories, numbered 0 through 9 for quick access.

10 Bins is part of Cyborganize.  To learn more, visit <http://cyberthal-docs.nfshost.com>


<a id="orgef44d3e"></a>

## Reading order

Each directory of 10 Bins contains a Readme file explaining its purpose.  Multiple file formats are provided with identical content.  Otherwise, the documentation avoids repetition.

For example, "Persinter" is defined in `3-Persinter`.  This definition is not repeated in deeper instances of "Persinter" directories.

"Solid names" is a conceptual prerequisite for "Name" directories and any directories cascade downstream.  "Solid names" is defined at `7-Names/2-Flat/Readme.org`.


<a id="org00c4124"></a>

## Cascade matching

10 Bins uses cascade matching.  Here's what that means.

First, we assume the directory list is sorted in descending alphabetical order, because this is the cross-platform standard.

Therefore, lower-number matches outrank higher-number matches.

In other words, earlier matches beat later ones.

For example, "Germany" is both a location and a name.  `5-Location` is earlier than `7-Names`, so "Germany" belongs in the former.


<a id="orgf65fc9e"></a>

## Descending priority-density and filing-friendliness


<a id="org0daec3c"></a>

### Idiosyncratic?

Is it arrogant to assert that my idiosyncratic 10 Bins is an universally-correct template for personal info management?

No, because 10 Bins is supported by objective logic.  Here's why.


<a id="org9fff520"></a>

### Design principles

10 Bins follows three design rules:

1.  Make info easily retrievable **when needed**.  The next time you need the info, you will think of it in X way.  So file it at X location, to convenience **future** you.

2.  Rank info by value density.  Density is value divided by volume.  Note that if info is crucial, its value is infinity, and therefore its size doesn't matter.

3.  Rank info by filing friendliness.  Filing structural ambiguity reduces info profitability by increasing retrieval and maintenance cost.

These rules sound complicated in theory, but they're easy in practice:

1.  Useful stuff goes up.
2.  Useless stuff goes down.
3.  Put things where you'll find them.


<a id="orgcbb9665"></a>

### Priority density

Info varies by personal priority-density.  A single sentence critical to your survival has maximum priority density.  A thousand page book about an irrelevant subject has minimum priority density.

10 Bins pushes high priority-density info upwards, in both sort order and tree depth.  

`0-Inbox` is first because its existence is a red flag.  If it exists, then you should stop and refile it before anything else.  Otherwise, arbitrary headings can be lost indefinitely in bypassed inboxes buried in the tree!

`1-Outbox` is next because it is effectively the Inbox for another repo.  A similar danger applies, although at least you know the info doesn't belong in the current repo.

`2-Codex` is next.  Its content is terse and dense.  You don't want your code snippets buried in your prose.

`3-Persinter` welcomes everything you feel is important enough to highlight.  You shouldn't overcrowd it, though.

As you can see, these first four directories follow the rule of descending priority density.


<a id="org2a2f895"></a>

### Filing friendliness

Info also varies by retrievability.  The more costly the retrieval, the less profitable the info.  Maintenance cost also reduces info profitability.

Stable info has high retrievability and low maintenance cost.  The next four directories are ranked primarily by stability.

`4-Time` is first, since both money and time are precisely and objectively quantifiable.  Both are precious.

`5-Location` is next, because geography is quite stable and fundamental, as is architecture.  Both are a bit more ambiguous and dynamic than time and money, though.

`6-Object` is next, because objects are more ambiguous and ephemeral than locations.  Many locations could be considered huge objects.

`7-Name` is next.  Names are more ephemeral than objects.  Your personal nomenclature evolves gradually.


<a id="org094f1de"></a>

### Priority density again

The last two directories follow the priority-density rule again.

`8-Action` is next.  Plans are more ephemeral than names, but more important than background info.

`9-Background` is last.  It contains huge quantities of poorly-retrievable info, most of it easily replaceable.


<a id="orgc76ef05"></a>

### Case study: US Civil War

Imagine you're filing info on the US Civil War.  Most would go in `5-Location` under USA.  Global info about the 1860s goes in `4-Time`.  Sociopolitical theories of state stressors might go in `9-Background`, with deeper discussion of individual theories filed by author's `7-Name`.  Discussion of muskets vs rifles goes in `6-Object`.

Simple, right?


<a id="org75d79c6"></a>

## Skimming the cream

The info that reaches `9-Background` is like skim milk.  All the creamy info, full of high priority-density, retrievability and stability, has already been removed.  What's left is protein and water.

Since the cream always rises to the top, 10 Bins generates rich, delicious thoughts.

This improves iterational velocity, accuracy, creativity, and effective intelligence.


<a id="org6888e64"></a>

## Links

-   [Discord](https://discord.gg/QC8Jv6H)
-   [Email](mailto:texas.cyberthal@gmail.com)

-   [Main docs page](https://cyberthal-docs.nfshost.com)
-   [Treefactor](http://treefactor-docs.nfshost.com)

