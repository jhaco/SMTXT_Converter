# SMTXT_Converter
#### Stepmania TXT Converter and SM Generator for the [Stepmania Note Generator](https://github.com/cpuguy96/stepmania-note-generator) by cpuguy96 for [Stepmania](https://github.com/stepmania/stepmania/wiki/sm) by VR0. Used in conjunction with the [Stepmania File Parser](https://github.com/jhaco/SMFile_Parser) by me

Batch processes all .txt file generated by either [Stepmania File Parser](https://github.com/jhaco/SMFile_Parser) or [Stepmania Note Generator](https://github.com/cpuguy96/stepmania-note-generator) in the current directory of notegen_to_sm.py into .sm files usable by Stepmania

---

#### changelog (top-new):
- fixed a bug where notes that intersect multiple measures appeared in both measures, resulting in extra notes

#### issues:
- timing offset causes inaccuracies, will need a way to include that in all generated .txt files
