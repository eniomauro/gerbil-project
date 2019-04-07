Super-project
--------------

Super-project, is an ultra-simple organization system (based on [Hamster-folder](https://github.com/archimodels/hamster-system#hamster-folder)) polished to meet the needs of architects.

*MANTRAS:*

- *progressive:* every project is different so folder's structure complexity will be adapted to each project.<sup>1</sup>
- *simple system with an easy learning curve for newbies:* a macro understanding of the project should be easy to grasp.

### So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [Subproject (phases)](#subproject-phases)
- [File naming](#file-naming)
- [Archiving](#archiving)
- [Layers](#layers)

---
#### Folders structure:

*@ project .subproject (phase) -specific folder*

- project: **@**

        Example: @house in lisbon

- subproject (phase): **.**

    	Inside projects you have project phases:
        Example: .permit

        To reduce the need of memorization, when naming the subproject folder
        add the project name:
        Example: @house in lisbon.permit

---
#### Subproject (phases):

- concept or CON - CON
- permit or PER - LIC
- tender or TEN - EXE
- building works or BLD - OBR
- (project) management or PMI

---
#### File naming:

*@ project . subproject (phase) - file + version*

- name your files using folders notation plus drawing/document name:

        Plans: PP1, P00, P01, P02, P03, ..
        Elevations: E01, E02, E03, E04, ..
        Sections: S01, S02, S03, ..
        
        Layout / presentation panel: L01, ..
        
        Visualizations: V01, V02, V03, ..
        Booklet: B01, B02, B03, ..
        
        Siteplan: G00
        Urban plan: U00
        
        Functional cores: N00, ..
        Detail: D01, D02, D03, ..
        
        Floor types plan: FP1, F00, F01, ..
        Ceiling types plan: CP1, C00, C01, ..
        Wall types plan: WP1, W00, W01, ..
        Openings (windows & doors): J00, ..
        Other equipment: Z00, ..

- hints on file naming:

        All sections: SSS
        All plans: PPP
        All elevations: EEE

<!-- ahinqtux -->
        
- avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

---
#### Archiving:

- archive files using BranchVer: **+ branch . progress**

        Use a letter as branch and 2 digits for work progress.
        Example: @house in lisbon.permit-plans+a82

        Use branch 'R' for releases of subprojects.
        Example: @house in lisbon.concept+R00

- keep updated *changelogs* in relevant folders.

---
#### Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

---
<sup>Notes:</sup><br>
<sup>1 - E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Gerbil-project</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.