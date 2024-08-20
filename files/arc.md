# Archive files

The Denpa Men archive files, are, as far as we've come to know them, a proprietary archival format used in the Genius Sonority engine.
They are used in conjunction with [ZIPs](https://en.wikipedia.org/wiki/ZIP_(file_format)) and [SARCs](https://fileinfo.com/extension/sarc)<sup>[note](#sarc-fork)</sup>.

They contain all kinds of assets in them.

## Versions

There exist multiple versions of this archival format, here we try to detail all currently known differences and quirks.

All versions of the format contain < placeholder >

### The Denpa Men 3

< hex/text graph should go here >

Version 7
### Denpa Men Free

Version 10
### New Denpa Men

Version 14 contains 3 unsigned integers previously unseen
### The New Denpa Men Free

Version 16 contains 3 more unsigned integers previously unseen

## Tools
There are multiple tools to interact with this file type.

- [tdmextractor](https://github.com/NerduMiner/tdmextractor) by [Nerdy](https://github.com/NerduMiner) (also on [the organization github](https://github.com/dpmintern/tdmextractor))

- [QuickBMS](https://aluigi.altervista.org/quickbms.htm) + [Denpamen3 script](https://aluigi.altervista.org/bms/denpamen3.bms) (script also present in the [code-dump](https://github.com/dpmintern/code-dump/blob/master/denpamen3.bms))

  This script is not actively maintained. In most cases, one should use tdmextractor.

- [The maintained QuickBMS script](https://github.com/dpmintern/code-dump/blob/master/dpm.bms)

  In most cases, one should use tdmextractor.


## Notes
1. <a name="sarc-fork">So far, no ordinary SARC extractor has managed to unpack all SARC files present in the DPMF romfs, GS might've made their own fork of the format, for whatever reason. [claim to be yet verified]
