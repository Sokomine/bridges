Mod for Minetest that adds bridges (only one node wide!), slim handrails and a self-building-one-node-wide bridge.

Crafting recipes:
<br> S stands for stick
<br> W stands for wooden slab
<br> V stands for either vines or leaves (both can be used)
<br> G stands for groundplate of bridge
<br> H stands for handrail
<br> - stands for "leave empty"

Groundplate: yields 2 "G" parts which are the basis for further bridges:
<br> V V V
<br> V W V
<br> V V V

Handrail: yields 4 "H" parts which are needed in further receipes:
<br> - - -
<br> - G -
<br> - - -

small bridge:
<br> S - S
<br> H G H
<br> S - S

middle part (fits between small bridges):
<br> - - -
<br> H G H
<br> - - -

corner of a bridge:
<br> S H S
<br> - G H
<br> S - S

T junction of a bridge:
<br> S H S
<br> - G -
<br> S - S

end of a bridge.
<br> S H S
<br> H G H
<br> S - S

handrail, one side closed:
<br> - - -
<br> - - -
<br> S H S

handrail, two sides closed:
<br> S - -
<br> H - -
<br> S H S

handrail, three sides closed (if you want to walk around it):
<br> S H S
<br> H - -
<br> S H S

a large, 3 nodes long bridge:
<br> - small_bridge -
<br> - middle_part_of_bridge -
<br> - small_bridge -


the self-building automatic bridge:
<br> large_bridge large_bridge large_bridge
<br> large_bridge large_bridge large_bridge
<br> large_bridge large_bridge large_bridge

