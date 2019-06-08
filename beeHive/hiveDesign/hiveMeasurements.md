# BeeHive Measurements
<!-- Eric Sandbling, https://github.com/ericsandbling/openApiary -->

This document sets out to establish a baseline for the important and global measurement parameters of the _openApiary_ - _**beeHive**_ in line with national standards.

## Introduction

<!-- SBR Standard - Mått för yngelrum och skattlådor med tillbehör, 4th revision, SBR 2005, read (2019-05-25): http://www.olandsbiodlarforening.se/files/SBR_Standard_Mtt_p_Yngelrum_ramar.pdf -->

Using standard measurements and definitions in the hive design ensures both compatibility with _Original Parts Manufacturer (OEM)_ parts as well as utilizes when appropriate the accumulated empirical expertise inherent in the standard.

Standard measurements and norms for tolerances in the materials used for bee cultivation is necessary. Most especially for the apiary is the [_Bee Space_][bee-space], where a too small space will encourage the bees to fill and seal, and a too large space will allow the uncontrolled development of combs.

## National Standards

Different countries and regions have developed different standards with regard to hive measurements and tooling. This is something to consider for different markets. E.g. in Sweden the bee space is located above the [_honey frames_][honey-frame], compared to the US where the bee space is located below the frames.

This document will _(for now)_ focus on the standards developed in Sweden, as the deployment of the designs developed here will initially be targeted for Sweden.

The Swedish standards for beehive measurements are published by [Sveriges Biodlares Riksförbund (SBR)][sbr].

## Parts of the Beehive

### Bee Frame

The _outer_ measurements of the bee frames are given in _mm_ for each fram type according to the table below.

_Abbreviations:_
 * **TB:** Top bar lath
 * **L:** Length
 * **H:** Height
 * **W:** Width (of each lath)
 * **Tt:** Thickness of the top bar lath
 * **Tb:** Thickness of the bottom lath
 * **Ts:** Thickness of the side lath

| Frame Type            | TB  | L   | H	  | W  | Tt	| Tb | Ts	|
| ---                   | --- | --- | --- | -- | -- | -- | -- |
| Svea      	          | 330	| 300	| 300	| 25 | 10	| 10 | 10	|
| 1/2 Svea 	            | 330	| 300	| 146	| 25 | 10 | 10 | 10	|
| Norsk	                | 398	| 365	| 260	| 25 | 10 | 10 | 10	|
| 1/2 Norsk       	    | 398	| 365	| 160	| 25 | 10 | 10 | 10	|
| Wieslander	          | 396	| 366	| 278	| 25 | 10 | 10 | 10	|
| Lågnormal             | 396	| 366	| 222	| 25 | 10 | 10 | 10	|
| LS<sup>(1)</sup>      | 396	| 366	| 300	| 25 | 10 | 10 | 10	|
| 1/2 LS                | 396	| 366	| 146	| 25 | 10 | 10 | 10	|
| Langstroth	          | 480	| 448	| 232	| 25 | 10 | 10 | 10	|
| Farrar<sup>(2)</sup>  | 480	| 448	| 159	| 25 | 13 | 10 | 10	|
| Shallow<sup>(3)</sup> | 480	| 448	| 137	| 25 | 13 | 10 | 10	|
| Dadant      	        | 480	| 448	| 286	| 25 | 15 | 15 | 10	|
| Tolerances            | +.5 | +.5 | +1  |    | +0 |    |    |
|                       | -.5 | -1  | -1  |    | -1 |    |    | |

_**Notes:**_:

 1. **LS:** Lågnormal Svea
 2. **Farrar:** 3/4 Langstroth
 3. **Shallow:** Låglangstroth

Tolerances for the height measurements are calculated from the outer lower edge of the frame to the inner top bar lath edge.

#### Wiring

All frames except for Langstroth, Farrar and Dadant are wired vertically. These frames are wired horizontally. Wire hole diameter is _2-3 mm_.

**Wire thickness** according to:

 * Tinned iron wire: _0.4 mm_
 * Stainless steel: _0.3 - 0.4 mm_

**Number of wires** according to:

 * Svea: 4
 * Langstroth: 5
 * Farrar: 3
 * Shallow: 3
 * Dadant: 6
 * All others: 5

The first and last wire shall be placed 15 mm from the inner edge. The distance between the wires (4-5 wires) are calculated according to:

$$\frac{Length - 2 * 15}{N_{wires}-1}$$

For top bars with a thickness greater than _10 mm_ to over hang, beyond the length of the frame shall be reduced to exactly _10 mm_ to ensure the correct [_bee space_][bee-space].

#### Distance Pins

**Side Glides** are used to maintain the correct bee space between the frames and the wall of the box. The side glide shall measure _6 mm_ in height.

One side glide shall be placed _20 mm_ from the bottom edge of the frame on each side.

Frames with a height exceeding _230 mm_ shall have an additional pin on each side _70 mm_ from the top most edge of the frame.

**Frame Spacers** are used to maintain the correct bee space between the individual frames. The frame spacers shall measure _10 mm_ in height.

Two frame spacers shall be placed on the left side lath of each side of the frame. One in the center of the intersection between the top bar and side lath and on _35 mm_ from the bottom edge of the frame.

#### Bee Space

The bee space above the frames shall, with the measurements given above, measure _8 mm_. On the side of the frames the bee space measures _8 mm_, with an exception for _Norsk_ where the bee space measures _7.5 mm_.

The bee space bellow all frames in the beehive shall not measure below _15 mm_.

### Brood and Honey Boxes

Internal measurements for the brood and honey boxes are given in _mm_ per frame type according to table below.

_Abbreviations:_
 * **N:** Number of frames
 * **W:** Width
 * **L:** Length
 * **H:** Height

<<<<<<< HEAD
| Frame Type            | N  | W   | L	 | H   | Note   |
| ---                   | -- | --- | --- | --- | ------ |
| Svea      	          | 5	 | 316 | 189 | 308 |        |
| -                     | 8  | 316 | 316 | 308 | Square |
| -                     | 10 | 316 | 382 | 308 |        |
| -                     | 18 | 316 | 720 | 308 |        |
| 1/2 Svea 	            | 8	 | 316 | 316 | 154 | Square |
| -                     | 10 | 316 | 382 | 154 |        |
| Norsk	                | 10 | 380 | 380 | 268 | Square |
| 1/2 Norsk       	    | 10 | 380 | 380 | 168 | Square |
| Wieslander	          | 10 | 382 | 382 | 286 | Square |
| Lågnormal             | 5  | 382 | 189 | 230 |        |
| -                     | 8  | 382 | 316 | 230 |        |
| -                     | 10 | 382 | 382 | 230 | Square |
| -                     | 18 | 382 | 720 | 230 |        |
| LS<sup>(1)</sup>      | 13 | 382 | 487 | 308 |        |
| 1/2 LS                | 13 | 382 | 487 | 154 |        |
| Langstroth	          | 10 | 464 | 370 | 240 |        |
| Farrar<sup>(2)</sup>  | 10 | 464 | 370 | 167 |        |
=======
| Frame Type            | N  | W   | L	 | H   | Note |
| ---                   | -- | --- | --- | --- |
| Svea      	          | 5	 | 316 | 189 | 308 |
| -                     | 8  | 316 | 316 | 308 | Square |
| -                     | 10 | 316 | 382 | 308 |
| -                     | 18 | 316 | 720 | 308 |
| 1/2 Svea 	            | 8	 | 316 | 316 | 154 | Square |
| -                     | 10 | 316 | 382 | 154 |
| Norsk	                | 10 | 380 | 380 | 268 | Square |
| 1/2 Norsk       	    | 10 | 380 | 380 | 168 | Square |
| Wieslander	          | 10 | 382 | 382 | 286 | Square |
| Lågnormal             | 5  | 382 | 189 | 230 |
| -                     | 8  | 382 | 316 | 230 |
| -                     | 10 | 382 | 382 | 230 | Square |
| -                     | 18 | 382 | 720 | 230 |
| LS<sup>(1)</sup>      | 13 | 382 | 487 | 308 |
| 1/2 LS                | 13 | 382 | 487 | 154 |
| Langstroth	          | 10 | 464 | 370 | 240 |
| Farrar<sup>(2)</sup>  | 10 | 464 | 370 | 167 |
>>>>>>> f8845d5919c9ecb59a658cd16976d930662b0bdb
| Shallow<sup>(3)</sup> | 12 | 464 | 464 | 145 | Square |
| Dadant      	        | 12 | 464 | 464 | 294 | Square |

_**Notes:**_:

 1. **LS:** Lågnormal Svea
 2. **Farrar:** 3/4 Langstroth
 3. **Shallow:** Låglangstroth

Wall thickness shall measure _22 mm_, with the exception of 5-frame boxes where the wall thickness in parallel to the frames shall measure _12 mm_.

Isolated boxes will have increased wall thickness.

#### Handles

Handles shall be placed in the middle of the side face 2/3 up from the bottom edge.

Brood and honey boxes made out of **wood** shall include a handle carved into the side face of the box. _15 mm_ deep, _30 mm_ wide and _100 mm_ long. Alternatives is however allowed with protruding handles.

**Isolated** brood and honey boxes may include foldable handles.

**Foam** brood and honey boxes shall have the handle integrated in the structure of the box.

#### Frame Grove and Ledge

The [frame grove][frame-grove] shall be _13 mm_ wide allow the top bar of the frames to sink down _18 mm_ from the top edge of the box.

The frame grove may include an optional frame ledge _8 mm_ high made of metall. If a frame ledge is included the:

 * fasteners shall be counter sunk
 * the ledge shall be flush with the inner wall of the box
 * the frame groove depend enough to accept the height and thickness of the ledge and still allow the frames to sink down the specified amount.

The frame ledge shall be _20 mm_ shorter than the length of the frame grove and centered.

#### Cover Boards

The [cover boards][cover-boards] can be made out of multiple boards of wood, sheets of glass, plastic or hemp fibers.

The length of the cover board shall exceed the inner length of the box with _44 mm_. The thickness of the boards shall measure for:

 * **Wood:** _10 mm_
 * **Glass:** _6 mm_
 * **Plastic:** _>4 mm_

The width shall measure for:

 * _Lågnormal_, _Svea_ and _Norsk_:
  - Wood: _70 mm_
  - Plastic and glass: _70 mm_ alt. _140 mm_

* _Langstroth_, _Farrar_ and _Dadant_:
  - Wood: _72 mm_
  - Plastic and glass: _72 mm_ alt. _127 mm_

<!-- References -->
[bee-space]: ./../../dkr/definitions.md#bee-space
[cover-boards]: ./../../dkr/definitions.md#cover-boards
[frame-grove]: ./../../dkr/definitions.md#frame-grove
[honey-frame]: ./../../dkr/definitions.md#honey-frame
[sbr]: www.biodlarna.se
