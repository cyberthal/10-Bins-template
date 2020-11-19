
# Table of Contents

1.  [Queuing for departure](#org55f827c)
    1.  [Subdirectories by destination](#org36afcc5)
        1.  [Don't delete empty subdirectories](#org2333a3e)
    2.  [Batch export](#orge93e047)
    3.  [One per repo](#org505c96f)


<a id="org55f827c"></a>

# Queuing for departure

`1-Outbox` is a directory for content that does not belong in this repo.

It is permanent.  Don't delete it, even if it's empty.


<a id="org36afcc5"></a>

## Subdirectories by destination

Directories in `1-Outbox` represent destinations.

Pubmind repos are the most likely destination for headings in the Textmind `1-Outbox`.


<a id="org2333a3e"></a>

### Don't delete empty subdirectories

Normally you should delete an empty directory to eliminate the need to open it to check whether it contains anything.

However, for regularly-used destinations, this would lead to inefficient repeated deletion and creation of the same directory.

`1-Outbox` is rarely checked anyway, and usually as part of a batch pass.  Therefore the cost of checking empty directories is minimal.

So you should keep common destination directories even when empty.


<a id="orge93e047"></a>

## Batch export

Keep an eye on `1-Outbox` contents as they accumulate.  Batch export them when needed.

If you're exporting one subdirectory, you may as well export them all.  Otherwise contents may accumulate indefinitely in a subdirectory whose destination doesn't generate conscious demand for export.

If you've totally forgotten what's in `1-Outbox`, and it holds lots of content, you'd better batch export before working on any of the destination repos.  Otherwise you might forget something important.


<a id="org505c96f"></a>

## One per repo

Each repo should have only one `1-Outbox`.  This consolidates batch exporting.

