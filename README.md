# Tunneling DP through USB4

Two 4K60 monitors on one Thunderbolt dock, each trained at HBR3 ×4: 64.8 Gbps over a 40 Gbps USB4 link, yet both light up. A DP main link never idles, and stuffing fills whatever the pixels don't use, so reserving by link rate books the stuffing too. This lightning talk shows how Bandwidth Allocation mode lets i915/xe reserve only what the mode needs from the USB4 Connection Manager, and how the DP IN and DP OUT adapters strip and rebuild the stuffing so only real data crosses the link.

![overview](https://kunaljoshi95.github.io/xdc-presentation/abstract.svg)
