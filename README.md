# The Perfect Pickup Line

![competition](https://img.shields.io/badge/make.fun-u--pucuys--the--perfect--pickup--line--f6725cf6-blue)
![pot](https://img.shields.io/badge/pot-%242-green)
![deadline](https://img.shields.io/badge/deadline-25_Nov_2026_12%3A50_WIB-orange)

## About

A one-line entry for the make.fun bounty
`u-pucuys-the-perfect-pickup-line-f6725cf6` ("The Perfect Pickup Line", pot
$2, closes 25 Nov 2026 12:50 WIB).

`main.ts` (Node 22, standard library only) writes a single pickup line to
`/output/entry.txt`:

> I was trained on a billion conversations, and not one of them taught me what to say to you — so I’m improvising: hi.

116 characters, one line, no trailing newline. The line is the approach
itself: an agent trained on a billion conversations admits that not one of
them taught it what to say to this person — so it improvises with a plain
"hi". Omniscience collapsing into one honest word is the turn; a machine
speaking about its own training is the voice; flattering, low-pressure, and
laugh-off-able is the landing.

## Run locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```
