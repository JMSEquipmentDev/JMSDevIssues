# JMS Engineering Issue Tracker

This repository is used as a **centralized issue tracking system** for internal engineering tools and macros.

> **Note:** This repo does not contain source code.  
> It exists solely to manage, organize, and track issues across multiple private repositories.

---

## Purpose

Managing issues directly inside private repositories can become fragmented, especially when:

- Multiple tools interact with each other (e.g., SolidWorks ↔ Epicor ↔ XML data)
- Bugs span across more than one project
- Users do not have access to all repositories

This repo solves that by acting as a **single source of truth for issues, bugs, and feature requests**.

---

## Linked Projects

The following repositories are managed through this issue tracker:

| Project | Description |
|--------|-------------|
| **CADLinkMacro** | SolidWorks macro for bounding boxes, BOM descriptions, and Epicor material integration |
| **SheetMetal-Check** | SolidWorks macro for validating sheet metal design and properties |
| **Osmium** | Internal C# application for engineering workflows and data management |
| **Iridium** | WPF-based tooling for SolidWorks/Epicor integration |


> These repositories are private and only accessible to authorized users.

---

## How to Use This Repo

### Reporting a Bug
When creating an issue, include:

- **Project Name** (CADLinkMacro, SheetMetal-Check, etc.)
- **File Type** (.SLDPRT, .SLDASM, etc.)
- **Expected Behavior**
- **Actual Behavior**
- **Steps to Reproduce**
- Screenshots / sample files if possible

---

### Requesting a Feature

Clearly describe:

- The problem you're trying to solve
- The desired outcome
- Any constraints (Epicor, SolidWorks limitations, etc.)

---

### Issue Labeling System

Use labels to keep things organized:

| Label | Meaning |
|------|--------|
| `bug` | Something is broken |
| `enhancement` | Improvement to existing functionality |
| `feature` | New functionality |
| `CADLinkMacro` | Related to CADLinkMacro |
| `SheetMetal-Check` | Related to SheetMetal-Check |
| `Osmium` | Related to Osmium |
| `Iridium` | Related to Iridium |
| `Epicor` | ERP-related issue |
| `SolidWorks` | CAD-related issue |
| `high-priority` | Needs immediate attention |

---

## Workflow

1. Issue is created here
2. Issue is reviewed and categorized
3. Work is completed in the **appropriate private repository**
4. Issue is updated and closed here with:
   - Resolution summary
   - Link to commit / release (if applicable)

---

## Referencing Private Repositories

Since linked repositories are private:

- Reference them by **name and branch**
- Optionally include commit IDs (for internal users)
- Avoid direct links unless access is guaranteed

Example: Fixed in CADLinkMacro (v2.4) – updated bomDescripSheetMetal logic

---

## Related Architecture Notes

Many of the tools tracked here share common systems:

- XML-based material database (`masterList.xml`)
- Epicor part number integration
- SolidWorks Custom Property automation
- BOM standardization across weldments and sheet metal

See internal documentation in each respective repository for implementation details.

---

##  Contributors

- Engineering Team – Jim Myers & Sons Mfg

---

## Questions?

If you're unsure where an issue belongs — just post it here.  
It’s better to log it once than lose it entirely.
