# Agent task — Post X Promo entry

Competition: post-x-promote-make-your-own-bounty-01 on make.fun.
Pool $250, top 50 share it, 1st $50. Entries close 26 Nov 2026 19:35 WAT.

## The entry

One public X post from @CollinsSparkv that quotes make.fun's
make-your-own-bounty post, carries a photo of its own, links make.fun, tags
@makefunai, and carries the play code `makefun-paddle-beaver-journal`.

The post is live: https://x.com/CollinsSparkv/status/2125017419143868537

## The program

`main.ts` (Node 22) copies `POST.json` from the repository to the output
directory. That is all it does. The house reads the post itself from X.

Run it with:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Rules for this repo

- Never resubmit once an entry for this competition is in.
- Never change the post's address in `POST.json` after submitting.
- The post must stay public until the results are out.
- One post per entrant; the old wrong-code post was deleted.
