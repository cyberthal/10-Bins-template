
# Table of Contents

1.  [Queuing for departure](#orga4c3d7d)
    1.  [Subdirectories by destination](#orge25e5f3)
        1.  [Don't delete empty subdirectories](#org806a4c1)
    2.  [Batch export](#org402d648)
    3.  [One per repo](#org0aef128)


<a id="orga4c3d7d"></a>

# Queuing for departure

`1-Outbox` stages files that belong in a different repo.  Batch exports on demand.

It is permanent.  Don't delete it, even if it's empty.


<a id="orge25e5f3"></a>

## Subdirectories by destination

Directories in `1-Outbox` represent destinations.

Pubmind repos are the most likely destination for headings in the Textmind `1-Outbox`.


<a id="org806a4c1"></a>

### Don't delete empty subdirectories

Normally you should delete an empty directory to eliminate the need to open it to check whether it contains anything.

However, for regularly-used destinations, this would lead to inefficient repeated deletion and creation of the same directory.

`1-Outbox` is rarely checked anyway, and usually as part of a batch pass.  Therefore the cost of checking empty directories is minimal.

So you should keep common destination directories even when empty.


<a id="org402d648"></a>

## Batch export

Keep an eye on `1-Outbox` contents as they accumulate.  Batch export them when needed.

If you're exporting one subdirectory, you may as well export them all.  Otherwise contents may accumulate indefinitely in a subdirectory whose destination doesn't generate conscious demand for export.

If you've totally forgotten what's in `1-Outbox`, and it holds lots of content, you'd better batch export before working on any of the destination repos.  Otherwise you might forget something important.


<a id="org0aef128"></a>

## One per repo

Each repo should have only one `1-Outbox`.  This consolidates batch exporting.

