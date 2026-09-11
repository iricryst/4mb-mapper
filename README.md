# nms8280_4mb_mapper

![4MB mapper PCB](./kicad/4mbmapper.png)

Project to document and create a 4MB module for a Philips NMS8280 MSX.

> **WARNING:** Do not use or build this board until the correct measurements
> have been completed on the prototype. This design has not yet been verified
> for production use.

The KiCad project, custom symbols, footprints, and board image are in
[kicad](./kicad). Datasheets are kept in [kicad/datasheets](./kicad/datasheets).

<a href="./bom/ibom.html" target="_blank" rel="noopener noreferrer">BOM</a>

## Datasheets

- [SN74LS00](./kicad/datasheets/SN74LS00.pdf)
- [SN74LS08](./kicad/datasheets/SN74LS08.pdf)
- [SN74LS125](./kicad/datasheets/SN74LS125.pdf)
- [SN74LS157](./kicad/datasheets/SN74LS157.pdf)
- [SN74LS670](./kicad/datasheets/SN74LS670.pdf)

The RAM used by this design is HY5117404B, represented by the custom
`HYB5117400BJ` symbol in the schematic. Its archive entry is available at
[Datasheet Archive](https://www.datasheetarchive.com/HY5117404B-datasheet.html),
but the site currently exposes the document through a dynamic viewer rather than
a directly downloadable PDF. The `1464` custom symbol has no manufacturer part
number in the schematic, so no unambiguous datasheet can be assigned to it.
