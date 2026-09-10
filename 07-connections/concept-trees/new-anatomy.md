---
id: CT-0003
type: connection-tree
name: The New Anatomy
status: developing
---

# The New Anatomy

## Scope

This connection tree tracks the movement from inherited medical authority toward anatomy, physiology, microscopy, and image-based life science.

## Nodes

- [Humoral medicine](../../03-discoveries-and-theories/humoral-medicine.md)
- [Anatomy](../../03-discoveries-and-theories/anatomy.md)
- [Andreas Vesalius](../../02-people/andreas-vesalius.md)
- [De humani corporis fabrica](../../09-research-and-sources/primary-sources/de-humani-corporis-fabrica.md)
- [Blood circulation](../../03-discoveries-and-theories/blood-circulation.md)
- [William Harvey](../../02-people/william-harvey.md)
- [De motu cordis](../../09-research-and-sources/primary-sources/de-motu-cordis.md)
- [Microscope](../../05-technologies/microscope.md)
- [Microscopy](../../03-discoveries-and-theories/microscopy.md)
- [Antonie van Leeuwenhoek](../../02-people/antonie-van-leeuwenhoek.md)
- [Robert Hooke](../../02-people/robert-hooke.md)
- [Micrographia](../../09-research-and-sources/primary-sources/micrographia.md)

## Relationships

```text
PER-0014 | published | SRC-0012 | Vesalius published De humani corporis fabrica in 1543. | Stanford Vesalius
SRC-0012 | challenged | CON-0018 | Vesalius corrected inherited Galenic anatomical claims. | Stanford Vesalius
CON-0019 | supported | CON-0017 | Direct dissection supported anatomical knowledge. | CC-HOS-15
TEC-0005 | technologically-enabled | CON-0026 | Printed anatomical images helped readers see bodies differently. | Stanford Vesalius
PER-0018 | developed | CON-0020 | Harvey argued for circulation through a closed system. | RCP Harvey
PER-0018 | published | SRC-0013 | De motu cordis presented Harvey's circulation theory. | RCP Harvey
CON-0021 | supported | CON-0020 | Harvey used living-animal observation in circulation research. | RCP Harvey
TEC-0004 | technologically-enabled | CON-0023 | Microscopes enabled observation below unaided sight. | CC-HOS-15
CON-0023 | led-to | CON-0024 | Microscope work opened a new microbial scale of life. | UCMP Leeuwenhoek
PER-0021 | published | SRC-0014 | Micrographia popularized microscope-enabled observation. | Royal Society
PER-0021 | introduced | CON-0025 | Hooke used the term cell for cork chambers. | Royal Society
```

## Open Questions

- Should anatomy and physiology be split into separate top-level categories later?
- How should we record ethically troubling practices such as vivisection and the sourcing of bodies for dissection?
- How should image credibility and instrument trust be modeled in connection trees?

## Sources

- Crash Course History of Science #15.
- Stanford History 13, "Andreas Vesalius." https://web.stanford.edu/class/history13/Readings/vesalius.htm
- Royal College of Physicians Museum, "Ceaseless motion: William Harvey's experimentations in circulation." https://history.rcp.ac.uk/exhibitions/past-exhibitions/ceaseless-motion-experimentations-circulation
- Royal Society, "Micrographia online." https://royalsociety.org/blog/2020/07/micrographia-online/
- University of California Museum of Paleontology, "Antonie van Leeuwenhoek." https://ucmp.berkeley.edu/history/leeuwenhoek.html
