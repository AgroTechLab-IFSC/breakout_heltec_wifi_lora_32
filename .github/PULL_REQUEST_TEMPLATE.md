---
name: PCB Design Update
about: Submit changes to the schematic or board layout.
title: "[PCB] <A clear and concise title>"
labels: pcb, design
assignees: ''

---

### Description
Please provide a detailed description of the changes made in this pull request. What is the purpose of these changes?

* **What problem does this PR solve?**
* **What new functionality or improvement does it introduce?**

### Design Checklist
This checklist helps ensure all necessary steps for a PCB design change have been completed.

- [ ] **Schematic Changes:**
    - [ ] ERC (Electrical Rules Check) was run and passed.
    - [ ] All new components have a symbol and footprint, and are linked.
    - [ ] Component values, part numbers, and manufacturer data are correct.
    - [ ] The netlist was updated and committed.
- [ ] **Board Layout Changes:**
    - [ ] DRC (Design Rules Check) was run and passed with no errors.
    - [ ] All new components are placed and routed correctly.
    - [ ] All tracks, vias, and polygons are correctly updated.
    - [ ] Copper pour and ground planes were re-poured.
    - [ ] All silkscreen layers are readable and correctly oriented.
- [ ] **BOM (Bill of Materials) & Documentation:**
    - [ ] The BOM was regenerated and updated (if components were added/removed/changed).
    - [ ] The schematics were exported to PDF and committed.
    - [ ] The board layout was exported to PDF and committed.

### How to Review
Please provide clear instructions for the reviewer on how to check and verify the changes.

### Related Issues
Closes #[issue number]
---

### Screenshots/Visuals (Optional)
Add screenshots of the schematic or board layout here to help the reviewer visualize the changes.