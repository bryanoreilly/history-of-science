---
id: CT-0001
type: connection-tree
name: The New Astronomy
status: developing
---

# The New Astronomy

## Scope

This connection tree tracks the Episode 13 chain from Copernicus through Tycho, Kepler, and Galileo.

## Nodes

- [Geocentrism / Ptolemaic system](../../03-discoveries-and-theories/geocentrism.md)
- [Heliocentrism / Copernican system](../../03-discoveries-and-theories/heliocentrism.md)
- [Tychonic system](../../03-discoveries-and-theories/tychonic-system.md)
- [Tycho Brahe](../../02-people/tycho-brahe.md)
- [Johannes Kepler](../../02-people/johannes-kepler.md)
- [Kepler's laws of planetary motion](../../03-discoveries-and-theories/keplers-laws-of-planetary-motion.md)
- [Galileo Galilei](../../02-people/galileo-galilei.md)
- [Telescope](../../05-technologies/telescope.md)
- [Telescopic astronomy](../../03-discoveries-and-theories/telescopic-astronomy.md)

## Relationships

```text
CON-0002 | challenged-by | CON-0001 | Copernican astronomy displaced Earth from the central explanatory position. | SRC-0002
PER-0002 | developed | CON-0003 | Tycho proposed a geo-heliocentric compromise system. | CC-HOS-13
PER-0002 | observed | EXP-0001 | Tycho's 1572 new-star observation challenged immutable heavens. | SRC-0003
PER-0002 | influenced | PER-0004 | Kepler used Tycho's observational data. | Galileo Project Kepler
PER-0004 | published | SRC-0004 | Astronomia nova contains Kepler's first two planetary laws. | SRC-0004
CON-0004 | challenged | CON-0006 | Ellipses and variable speeds replaced perfect circular uniformity. | BAdW Kepler Edition
TEC-0001 | technologically-enabled | CON-0008 | Telescopes made new astronomical observations possible. | PBS NOVA
PER-0005 | observed | CON-0009 | Galileo observed Jupiter's satellites. | SRC-0006
CON-0009 | challenged | CON-0002 | Jupiter's satellites showed more than one center of motion. | Galileo Project Jupiter Satellites
```

## Open Questions

- How should we represent the shift from mathematical astronomy to physical astronomy?
- How much nuance should the Tychonic system receive before Episodes 1-12 are backfilled?
- Should "new star" observations become a separate event/observation category later?

## Sources

- Crash Course History of Science #13.
- Stanford Encyclopedia of Philosophy, "Johannes Kepler." https://plato.stanford.edu/entries/kepler/
- The Galileo Project, "Tycho Brahe." https://galileo.library.rice.edu/sci/brahe.html
- The Galileo Project, "Johannes Kepler." https://galileo.library.rice.edu/sci/kepler.html
- The Galileo Project, "Satellites of Jupiter." https://galileo.library.rice.edu/sci/observations/jupiter_satellites.html
- BAdW Kepler Edition, "The Planetary Laws." https://kepler.badw.de/en/on-johannes-kepler/the-planetary-laws.html
