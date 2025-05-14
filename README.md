# Macintosh SE Type PSU Model 4XDC

- [Purchase link](https://www.tindie.com/products/ttdesign/4xdc-apple-macintosh-se30-se-power-supply-psu/)

The 4XDC Special Edition is our flagship AC-DC power supply designed for the Apple Macintosh SE/30 and SE, built using all-new, modern components. It features quad DC power outputs with separate power modules for each of the machine's voltage rails, providing ample power to exceed the original specifications. It is an evolution of previous designs where the two +12 VDC rails are powered by their own power converter to minimize crosstalk between the sweep and disk rails. Some machine configurations may be more sensitive to this phenomenon, such as having a Micron Xceed internal grayscale video board installed.

The 4XDC has an optional "AUX" 5 VDC connector intended to bypass the power distribution through the analog board to the logic board. This is recommended for highly upgraded machine build configurations. The components for the optional cable are in the project list below. You can also find the extraction tool in the list at other stores.

- [Digikey AUX Cable Parts List](https://www.digikey.com/en/mylists/list/I7A1GWLQ9M)

Note: I believe 450 mm wires are long enough, so check to see if that seems reasonable. In order to make the bypass, you will need to extract/pull out the 5 V orange wires from the original 14-pin logic board cable assembly and connect the AUX wires up directly to the logic board connector. Ground wires are included as well just in case, but that may not be necessary. If you do include ground wires, you may want to make two twisted pairs to help suppress noise and you will need to pull two ground wires from the original logic board cable assembly.

Also make sure to prevent rubbing / direct contact of the wires on metal parts such as the enclosure for long term reliability and safety.

### AUX Bypass Performance Data:

**Macintosh SE/30 Configuration:**

- 2x 450 mm 16 AWG wires from PSU AUX direct to the logic board J12 connector (pins 12 & 13 per legend <- **verify!!**)
- Logic board with 128MB RAM
- Daystar Turbo 040 40 MHz
- Rasterops Colorboard
- Bolle Ethernet PDS combo riser
- Logic board current draw: ~5.5 A | voltage at test card interface J14 ~4.90 V

The above configuration is the highest draw config I have found so far in limited testing. At a lighter load (board + Bolle riser), ~ 2.5A it was at ~4.96V.
