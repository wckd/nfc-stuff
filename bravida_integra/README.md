## Research on Bravida Integra access system
* Added generated dictionary with possible KeyA's on their Mifare 1k 4b cards.
* Added Integra_accecss_v5.pdf and Integra_accecss_v6.pdf with technical info.

## Some notes:
* You need a clean reading of sector 0 and sector 3 with one of the key's in the dictionary (based on my initial research).
  * This may differ between setups/installs.
* Most sectors use the key FFFFFFFFFFFF for read and write, only the important data is programmed with another KeyA and KeyB.
  * You do not need KeyB on sector 3 to emulate, this is only used for initial read and programming at the guard station in my experience.
