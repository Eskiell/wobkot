# wobkot

Updated userland to use newer JSC bugs.

# How to use

- PS5: `src/ps5/kexp.bin` and `src/ps5/elfldr.elf` are included.
- PS4: place a compatible `payload.bin` in `src/ps4/`.
- `py host.py`
- open browser and type `https://{ip}`

# Bundled PS5 payloads

The following files are unmodified copies from [Eskiell/Relapse-Exploit at `ccbf049`](https://github.com/Eskiell/Relapse-Exploit/tree/ccbf0492ff255f5c7a53b037f46fbe868dbc614b/payloads):

| Bundled path | Source filename | Size |
| --- | --- | --- |
| `src/ps5/kexp.bin` | `kexp_2026_05_25.bin` | 18,912 bytes |
| `src/ps5/elfldr.elf` | `elfldr-ps5-1360.elf` | 397,024 bytes |

PS5 compatibility with Wobkot has not been validated. Relapse patches the imported `kexp` in memory before execution; Wobkot currently executes it without that patching step.

# References

- [CSSFontFace-Exploit](https://github.com/ntfargo/CSSFontFace-Exploit)
- [PS5-Webkit-Execution](https://github.com/ChendoChap/PS5-Webkit-Execution)
- [psfree-lapse](https://github.com/Al-Azif/psfree-lapse)
- [vue-after-free](https://github.com/Vuemony/vue-after-free)
- [PS4-webkit-exploit-6.XX](https://github.com/synacktiv/PS4-webkit-exploit-6.XX)
- [slopkit](https://github.com/jordyidk/slopkit)
- [Relapse-Exploit](https://github.com/ntfargo/Relapse-Exploit)

# Credits

Special thanks to:

- Nathan Fargo [writeup](https://linearfox.com/blog/cssfontface-uaf-playstation)
- nhk
- Dr.Yenyen
- AlAzif
- ArabPixel
- synacktiv [writeup](https://www.synacktiv.com/publications/this-is-for-the-pwners-exploiting-a-webkit-0-day-in-playstation-4) 
- cow
- idlesauce
- jordy
- ChendoChap
- sonic-iso
- SISTRo
