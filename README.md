# ChironWire
![Image](https://user-images.githubusercontent.com/24895840/268515604-d84c6d8d-688e-4d3c-95ff-ff9d43035b9f.png)

The basics for this printer modification can be found at the [Voron Switchwireand](https://vorondesign.com/voron_switchwire) and [Voron Documentation](https://docs.vorondesign.com/).

My personal recommendation is to embark first on a Voron or CoreXY build. I built a Voron 2.4 and gained tons of satisfying experience and as a bonus I was left with some extra parts ;-). 

A Voron 0 will be more than enough to get the right experience and give you the possibility to print the necessary components in ABS. 

All the parts of my mod are printed in eSun ABS+ with my Voron 2.4.

I am not planning to print any ABS on this ChironWire printer!

From the Voron Switchwire you have to print the complete Gantry/XZ_Axis parts, taking care of substituting the modified files I included here. The main reason of the modification is because the Switchwire uses 30xx profiles while the Chiron has 20xx aluminum extruded profiles, so I just added 5mm to each component. Other parts are specific, depending on the electronics you will use.

In my case I used the following electronics:

[Bigtreetech Octopus Pro ](https://biqu.equipment/collections/control-board/products/bigtreetech-octopus-pro-v1-0-chip-f446?variant=39482166804578)with TMC2209 (you just need to control 3 steppers + extruder* so you can use a smaller MCU probably the best is the  [Manta M4P](https://biqu.equipment/collections/control-board/products/manta-m4p-m8p?variant=39847241154658) as it doesn't need the [U2C](https://biqu.equipment/products/bigtreetech-ebb-sb2209-can-v1-0?variant=40214284468322) and has the CP1 = no need of a Raspberry Pi)
U2C
[EBB SB2209 CAN ](https://biqu.equipment/collections/expansion-board/products/bigtreetech-ebb-sb2209-can-v1-0) (*the stepper for the extruder is included here)
[MINI12864 V2.0 LCD Screen](https://biqu.equipment/collections/lcd/products/bigtreetech-mini12864-v2-0-lcd-screen-rgb-backlight-mini-display-supports-marlin-diy-for-skr-3d-printer-part-1) 
Linear RAILS

Qty 5 - 12mm Linear Guide [MGN12H ](https://www.aliexpress.com/item/32829826159.html?spm=a2g0o.order_list.order_list_main.46.63281802o1rgNP)500mm 
Qty 2 - MGN12H Blocks (used for the Y to have double support) 
 

My sourcing reference (I am based in Sweden so the Amazon links):

Qty 2 - [10 pieces F629-2RS](https://www.amazon.se/dp/B0BZ55CZR6?ref=ppx_yo2ov_dt_b_product_details&th=1) (alternative [Aliexpress](https://www.aliexpress.com/item/1005003640031891.html?spm=a2g0o.order_list.order_list_main.35.77ff18020Tax80))
[Creality CR Touch](https://www.amazon.se/-/en/dp/B08RJ1RB13?psc=1&ref=ppx_yo2ov_dt_b_product_details) There is mod to sit the CR touch inside the Stealthburner but with the Voron Revo it seats at the same level as the nozzle so i moved it to the side. Less elegant but at least is the offset will not interfere with the printed part. Initially I thought to use TAP but realized the bed might not be strong enough for 800gr force. I am happy with the CR Touch so far given the bed is quite thin.
[NEMA14 36mm Stepper motor ](https://www.amazon.se/dp/B0BVRDGDN1?psc=1&ref=ppx_yo2ov_dt_b_product_details)for the CW2 extruder (alt [Aliexpress](https://www.aliexpress.com/item/1005005621777079.html?spm=a2g0o.order_list.order_list_main.41.63281802o1rgNP)) You can source a Stealthburner kit on Aliexpress (here just an [example](https://www.aliexpress.com/item/1005004568836712.html?spm=a2g0o.productlist.main.3.6547423fHaFYDB&algo_pvid=ab3b22f3-a241-4172-82ea-1691aeb40686&algo_exp_id=ab3b22f3-a241-4172-82ea-1691aeb40686-1&pdp_npi=4%40dis%21SEK%21253.91%21175.17%21%21%2122.12%21%21%40211b600e16947990326157317e7706%2112000029658406371%21sea%21SE%21940964974%21S&curPageLogUid=u82hELPaOFSB))
[KEY-REAR S48K Keychain, 48"](https://www.amazon.se/dp/B002SQ9P5K?psc=1&ref=ppx_yo2ov_dt_b_product_details)
[100 Pack 2020 2040 2060 Roll in Spring Loaded T Nut m3](https://www.amazon.se/dp/B08YNFGYNH?ref=ppx_yo2ov_dt_b_product_details&th=1)
Qty 2 - [M3 * 8mm](https://www.amazon.se/dp/B08K8FQWCZ?ref=ppx_yo2ov_dt_b_product_details&th=1) socket screws 50pcs/package
[M3 Black Allen Screws](https://www.amazon.se/dp/B0BK22PWQH?ref=ppx_yo2ov_dt_b_product_details&th=1) (various lengths)
[2GT 20 Teeth 5mm Bore Timing Pulley](https://www.amazon.se/dp/B07C9X59GD?psc=1&ref=ppx_yo2ov_dt_b_product_details)
[Bipolar Stepper Motor Cables ](https://www.amazon.se/dp/B08CY46X4R?psc=1&ref=ppx_yo2ov_dt_b_product_details)1M Step XH2.54 Terminal
[E3D RapidChange Revo](https://www.amazon.se/dp/B09YQ4NWB6?ref=ppx_yo2ov_dt_b_product_details&th=1)™ Voron - 1.75mm, 24V
[Cooling Fan DC 24V 50x50x15mm ](https://www.amazon.se/dp/B07NSVP7YG?psc=1&ref=ppx_yo2ov_dt_b_product_details)5015
[GT2 timing belt 6mm x 5m ](https://www.amazon.se/-/en/non-slip-upgrade-suitable-printers-belt-drive/dp/B09XJW2ZRC/ref=d_pd_sbs_sccl_3_2/258-5748106-4835941?pd_rd_w=7Ex7U&content-id=amzn1.sym.7ee47ebe-809d-45d7-81f5-e4eb265b3f72&pf_rd_p=7ee47ebe-809d-45d7-81f5-e4eb265b3f72&pf_rd_r=GP60EHYE90Y9S07XV0M6&pd_rd_wg=Cu7ax&pd_rd_r=9b408f04-15d8-415c-b0e3-f2560d14d414&pd_rd_i=B09XJW1XKJ&th=1)(I had a Ruthex already but cant find where I bought it)

**Disassembly and assembly steps**

1. remove all existing electronics 
2. remove the bed 

![Image](https://user-images.githubusercontent.com/24895840/268516586-ee7303f9-f4d0-4dfa-8ef0-a63744716e30.png)

3. if you want to achieve the full 400mm Y travel with the Stealthburner head you can move the Z columns 30mm backward drilling new holes to the frame (I haven't done it as atm I am OK having max Y travel 375mm)
4. invert the T-supports for the Z frame as they will interfere with the new motor supports XZ  
5. now it is a good time as any to install the X & Z stepper motors withe their motor_mount assembled (just snug the screws and lose the tensioner all the way)
6. install the upper idler assemblies
7. Y carriage modification
- don't forget to clean and lubricate the bearings of the rails (check YT tutorials)
- install the Y rails adding the 2nd rail block (be careful with derailing).
- connect the 3 pieces composing the Y carriage frame using the leftover 8mm spacers 
- sketch the hole pattern for the rails blocks (20x20mm) and space them 30mm
- punch for drilling 
- bolt together the trapezoidal parts and drill them at the same time (I used a 3.5-3,8mm drill to have some extra clearance). De-burr the holes
- bolt together the Y carriage frame and check that the heated bed fits. Mine was slightly off and just enlarged the 4 holes where the bed screws and springs sit.
- once you have installed the Y carriage frame check that the Y stop clicks. As mine was just on the edge I just added one of the original Z stop metal pieces while clamping the blocks connecting the Y belt.

![Image](https://user-images.githubusercontent.com/24895840/268516648-f3fbbabe-0560-459a-ab18-e3b1dca50837.png)

![Image](https://user-images.githubusercontent.com/24895840/268516666-fdbb0e47-b6f8-4b7d-839b-b833fb75a79a.png)

![Image](https://user-images.githubusercontent.com/24895840/268516720-4be53c2e-7412-4950-95f0-5e9549a6c73d.png)

8. install the Z rails all the way up against the upper z_carriage_stops (keep the plastic rails stoppers to avoid derailing) and the bottom z_carriage_stop + keyback assembly
9. **at this point there is no turning back to the old Chiron as we start Cutting**!!!
- Cut the X 2020 alu profile to 510mm 
- Cut the X rail to 467mm (I used a Dremel diamond disk)
10. install the XZ_blocks and make sure later that the belts are not touching the X alu profile

![Image](https://user-images.githubusercontent.com/24895840/268516840-a45de362-02b3-4e1b-8b6f-2b9aa8884b73.png)

![Image](https://user-images.githubusercontent.com/24895840/268516808-07819b85-8142-433f-87d3-cddb3d385074.png)

11. assemble the z_bearing_blocks (left and generic) to the X alu 2020 and bolt them to the Z carriage
12. install the Stealthburner head
13. cut the 5m GT2 belt in two. You need to shorten them few cm so you have around 5-6cm left each side for later be able to grab the pair and tension it. Do a test install and cut it (check YT tutorials, the 2 belts MUST be exactly the same length - teeth on teeth and slide them though your hands without skipping teeth, measure twice and get them right)
14. install the belts and tension them lightly (the extra length can be folded inside the X carriage). 
15. install the MCU, Raspberry Pi, U2C and the existing 800W(!) PU using the PU_support_1 and _2 and the existing metal bracket (edit 2023-09-24). I did not use the secondary 24V PU

![Image](https://user-images.githubusercontent.com/24895840/268517483-84397712-d028-4870-acfc-60659794f563.png)

16. install a fan 24V 60x60 using the printed support (one works fine with my setup) 
17. Now that the mechanical is done it is time to start wiring it all together (check [Github ](https://github.com/Jamiever6?tab=repositories)for most of the schematics of the electronics)
18. I attached as an example the printer.cfg file. I still have few things to sort out like the beeper and small issues but it is fully functional as soon as you have installed klipper, flashed the firmware, etc. etc. etc.
19. finish up with the spooler holder and if you want to have the tube like in mine, print the included bowden_retainer from the Voron 2.4
CREDITS: 

Voron awesome community, [github](https://github.com/VoronDesign)

[Revo nozzle holder ](https://www.printables.com/model/248325-revo-nozzle-holder)by Jan

[Angle bracket 90 ° ](https://www.thingiverse.com/thing:3409079)by Eternauta74

[2020 V-Slot Aluminium Extrusion Profile ](https://www.thingiverse.com/thing:5181722)by chris_kwng

[Raspberry Pi Camera Mount ](https://www.thingiverse.com/thing:4761307)by crsn00

USA chiron-voron-switchwire-parts-list by TheDarkSoul97
