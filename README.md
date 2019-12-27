# crkbd (Corne) sandwich/skeleton case
# BOM
- 2x top plate
- 2x bottom plate
- 14x 8mm standoff (at this height, the hotswap sockets have a ~1mm gap to the bottom plate, for a very low build)
- 14x M2x6 screw for top
- 14x M2x4 flathead screw for bottom (8mm standoff + 1.5mm top plate + 1.5mm bottom plate = 11mm, so top + bottom screw length cannot exceed 11mm, whatever you pick)
- *additional 10x M2x5 screw (optional)*
- *10x thin M2 nut (optional)*
- *10x nylon M2 washer (optional)*
# Part Sources
- Plates: while I'm very happy with the aluminum plates my friend Alan milled for me (see my [build log]([https://imgur.com/gallery/dX9OCEV](https://imgur.com/gallery/dX9OCEV)) for more info including his business card), if I had to do it over again, I would prefer the heft of stainless so I'd probably go through Laserboost. The other reasons are that my plates are technically 1/16", which is outside the 1.5±0.1mm Cherry spec, so we had to mill some Gon-style recesses on the underside to allow switch snap-in. We also had to use some goofy switch cutout corner geometry to achieve the minimum corner radius with the mill bit we had, whereas a laser cutter should be able to achieve a small radius corner pretty naturally.
- Standoffs: it's hard to find standoffs other than the ridged or hex brass ones everyone carries, but I've been very happy with these (again, 8mm is what I ended up using -- originally built with 10mm but I upgraded later): [https://www.aliexpress.com/item/32780971435.html](https://www.aliexpress.com/item/32780971435.html)
- Socket head screws for top: McMaster-Carr: [https://www.mcmaster.com/91292A831](https://www.mcmaster.com/91292A831) -- style is personal preference, but I like these socket head screws.
- Flathead screws for bottom
- Nuts, washers: I didn't end up using these, so I forget where I got them -- just generic thin M2 nuts and nylon washers
# Design Notes
Each side of the board has 7 mounting points connecting the top plate to the bottom plate, hence 14 standoffs and 28 screws. When I designed this case, I had never used hotswap before and I was worried the friction of the sockets would not be enough to suspend the PCBs under the top plates. So I also included 5 holes in the top plate (see the "internal mounting" version) that allow you to secure the PCBs to the top plates using thin nuts and nylon washers (acting as fender washers to give the nuts a footprint to rest on, since the PCB holes are pretty large). In practice, the hotswap sockets were definitely plenty to keep the PCBs in place, so I just populated those internal mounting holes with dummy screws so it didn't look weird: in my build, the PCBs are held in place only by their hotswap sockets and **I suggest you omit the internal mounting holes and associated 10x hardware** (see the non-internal mounting top plate files).
The bottom plate, the regular top plate (both milled and laser-cut), and the internal mounting top plate (both milled and laser-cut) are all offered in DXF and DWG (all scaled 1:1 in metric), and they are all designed straight off of foostan's official crkbd documentation ([https://github.com/foostan/crkbd/tree/master/case/acrylic_plate/cherry](https://github.com/foostan/crkbd/tree/master/case/acrylic_plate/cherry)) -- I even reached out to foostan directly to make sure I was interpreting the DXF correctly.

# Result
![nude shot](https://i.imgur.com/2aRXoYC.jpg)
![with caps](https://i.imgur.com/AsmHP4G.jpg)
