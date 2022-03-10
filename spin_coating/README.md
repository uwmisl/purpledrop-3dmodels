Spin Coater Chuck
=================

Building surfaces for the PurpleDrop requires spin-coating a hydrophobic
coating. Many spin-coaters come with a vacuum chuck for holding the substrate,
and this works well for glass plates. However, it does
not work so well for the dielectric film, as it is not as rigid. Additionally,
commercial spin coaters are expensive and may not be available, but it
it possible to [build one](https://github.com/mcbridejc/spincoater) cheaply
from hobby motors.

This chuck system allows for quick release of 100x74mm dielectric frame (the
standard size used by all MISL electrode boards), 50x50mm glass plates, and
50x75mm glass plates. It is designed to be attached to 
[this servo city motor hub](https://www.servocity.com/0-125-0-770-set-screw-hub/)
but an adapter is also available to use this fixture on a standard vacuum chuck
spin coater.

## The Main Chuck

To build the chuck, you will need to print these components, and you will
need M2 threaded heat inserts (like [these](https://www.mcmaster.com/94459A110/))
plus M2x5mm screws (like [these](https://www.mcmaster.com/92000A012/)) to
attach the locking arms.

The part can be printed on an FDM 3D printer with PLA filament. The heat inserts
are then melted into the holes in the part -- special "heat-set insert tips" for 
soldering irons exist for this, although it is possible to insert them using a
standard conical soldering iron tip. If you've never used heat inserts, consider
printing a small test part with some 3.2mm diameter holes and practicing on that
first.

![Spincoater Chuck](images/chuck.jpg?raw=true "Spincoater Chuck")

[spincoater_100x74_chuck.stl](spincoater_100x74_chuck.stl) - The main part

[spincoater_chuck_lock_lever.stl](spincoater_chuck_lock_lever.stl) - Two of these attach to secure the part in place

## Glass adapters

For coating glass top plates, there are two adapters (one for 50x50mm, and one
for 50x75mm glass) which can be quickly attached to the main chuck. Flexure in
the arms is used to secure the glass plate.

Both adapters use a common base. To build the adapter the base and glass chuck
should be printed, and they can then be glued together with CA glue.

![Glass Adapter](images/glass_adapter.jpg?raw=true "Glass Adapter")

[spincoater_chuck_adapter_base.stl](spincoater_chuck_adapter_base.stl)

[spincoater_glass_chuck_50x75.stl](spincoater_glass_chuck_50x75.stl)

[spincoater_glass_chuck_50x50.stl](spincoater_glass_chuck_50x50.stl)

## Vacuum Chuck Adapter

The vacuum adapter is two parts, which glue together (CA glue recommended)
and then glue onto the main chuck component.
It is intended to fit on a 40mm diameter vacuum chuck.
Make sure that you get a good seal -- i.e. you can pull a strong vacuum -- 
with the face. I have found it to work, but this may depend on the 
surface quality of your 3D printed part, as well as the stiffness of the seal
on the chuck. If you find it leaks, you may be able to glue on a small laser
cut piece of acrylic or other plastic to provide a smooth surface to seal.

[spincoater_chuck_vacuum_adapter_A.stl](spincoater_chuck_vacuum_adapter_A.stl)
[spincoater_chuck_vacuum_adapter_B.stl](spincoater_chuck_vacuum_adapter_B.stl)
