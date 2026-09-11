# nms8280_4mb_mapper

![4MB mapper PCB](./KICAD/4mbmapper.png)

Project to document and create a 4MB module for a Philips NMS8280 MSX.

> **WARNING:** Do not use or build this board until the correct measurements
> have been completed on the prototype. This design has not yet been verified
> for production use.

The KiCad project, custom symbols, footprints, and board image are in
[KICAD](./KICAD). Project documents and datasheets are kept in [DOC](./DOC).

## Bill of Materials

<a href="./bom/ibom.html" target="_blank" rel="noopener noreferrer">Open the interactive BOM</a>

## Datasheets

- [4MB mapper documentation](./DOC/4mbnms8280.pdf)
- [HY5117404B](./DOC/HY5117404B.pdf)
- [SN74LS00](./DOC/SN74LS00.pdf)
- [SN74LS08](./DOC/SN74LS08.pdf)
- [SN74LS125](./DOC/SN74LS125.pdf)
- [SN74LS157](./DOC/SN74LS157.pdf)
- [SN74LS670](./DOC/SN74LS670.pdf)

The RAM used by this design is HY5117404B, represented by the custom
`HYB5117400BJ` symbol in the schematic. The `1464` custom symbol has no
manufacturer part number in the schematic, so no unambiguous datasheet can be
assigned to it.