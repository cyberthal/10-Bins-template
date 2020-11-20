
# Table of Contents

1.  [Queuing for departure](#org0c9ef44)
    1.  [Subdirectories by destination](#orgc16c79f)
        1.  [Don't delete empty subdirectories](#orgd7aefae)
    2.  [Batch export](#org38d9f70)
    3.  [One per repo](#org5c27503)


<a id="org0c9ef44"></a>

# Queuing for departure

`1-Outbox` stages files that belong in a different repo.  Batch exports on demand.

It is permanent.  Don't delete it, even if it's empty.


<a id="orgc16c79f"></a>

## Subdirectories by destination

Directories in `1-Outbox` represent destinations.

Pubmind repos are the most likely destination for headings in the Textmind `1-Outbox`.


<a id="orgd7aefae"></a>

### Don't delete empty subdirectories

Normally you should delete an empty directory to eliminate the need to open it to check whether it contains anything.

However, for regularly-used destinations, this would lead to inefficient repeated deletion and creation of the same directory.

`1-Outbox` is rarely checked anyway, and usually as part of a batch pass.  Therefore the cost of checking empty directories is minimal.

So you should keep common destination directories even when empty.


<a id="org38d9f70"></a>

## Batch export

Treemind has main and satellite repos.  Textmind and Binmind are main repos.  Textmini and Binmini are satellite repos.

For main repos, keep an eye on `1-Outbox` contents as they accumulate.  Batch export them when needed.

If you're exporting one subdirectory, you may as well export them all.  Otherwise contents may accumulate indefinitely in a subdirectory whose destination doesn't generate conscious demand for export.

If you've totally forgotten what's in `1-Outbox`, and it holds lots of content, you'd better batch export before working on any of the destination repos.  Otherwise you might forget something important.

For satellite repos, batch export at the end of each work session.  Who knows when you'll return to that repo.  Leaving info in the Outbox risks misplacing it indefinitely.

If the correct destination is uncertain, just return the object to the main repo.


<a id="org5c27503"></a>

## One per repo

Sometimes one repo has multiple 10 Bins instances.

However, each repo should have only one `1-Outbox`.  

This consolidates batch exporting, and prevents delays and misplacement.

