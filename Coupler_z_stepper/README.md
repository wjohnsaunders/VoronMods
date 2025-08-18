# Coupler Z Stepper

The Voron Trident is speced to use steppers with integrated leadscrews for the Z axis.
I had several normal steppers, couplers and leadscrews on hand, and I didn't want to
purchase additional parts.

The problem with using the stock Z stepper mounts is that the coupler restricts how
low the bed can travel, and you lose at least 50mm of Z travel. The solution is to
lower the steppers so that the top of the couplers are flush with the top of the
mount. No Z height is lost with this approach.

This design uses the Creality rigid couplers as used on the Ender 3 and CR10. If you
don't have any spare, they are a few dollars each on AliExpress.

The screw holes have been recessed so they the standard length screws can be used.
During my build I have found that any mod needing different length screws can stall
the project for weeks, if you need to order them from AliExpress. So I learnt the
hard way to retain support for the original length bolts where possible.

Note: For my 300x300x300 Trident a 350mm leadscrews is ample to get full travel and not
hit the toolhead. For a Trident with 250mm Z travel you will want 300mm ones instead.

## Printing

These should be printed as they appear in the STL file, top surface down. The strange
shape of the cutouts on the side is to allow printing without bridging. They provide
access to the grub screw on the coupler, save a ton of plastic, and shorten the print
time as well. There are probably a lot more savings to be made here with more time
spent tinkering in the CAD, the cutouts were done very quickly.
