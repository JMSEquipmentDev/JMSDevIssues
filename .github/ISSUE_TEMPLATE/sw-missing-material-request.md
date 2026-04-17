---
name: SW Missing Material Request
about: A request for when the SolidWorks CADLinkMacro is unable to find a known material
title: "[Missing Material]"
labels: Material's Issue
assignees: evanrisk
type: Missing Material

---

## 🧱 SW Missing Material Request

> Use this form when a SolidWorks material does not correctly map to an Epicor material  
> and results in **"(Unknown)" material** in the CADLinkMacro.

---

### 📌 Project
- [ ] CADLinkMacro  
- [ ] Other: ___________

---

### 🧪 Material Name (SolidWorks)
(Exact material name from SolidWorks)

---

### 🔍 Material Type
- [ ] Plate / Sheet 
- [ ] Weldment Profile  
- [ ] Plastic (UHMW, etc.)  
- [ ] Rubber (Neoprene, etc.)  
- [ ] Other: ___________

---

### 📏 Key Properties

**Thickness:**
(e.g. 0.125, 10GA, etc.)

**Width (if applicable):**
  
**Length (if applicable):**

**Profile Description (for weldments):**
(e.g. L2x2x1/4, C3x5, etc.)

---

### 🧠 Expected Behavior
What should the material resolve to in Epicor?

- Expected Material Type:
- Expected Part Number (if known):

---

### ❌ Current Behavior
What is happening now?

- [ ] "(Unknown)" appears in BOM Description  
- [ ] MaterialPartNumber is blank  
- [ ] Incorrect material assigned  
- [ ] Other: ___________

---

### 🔎 Search / Lookup Info (if known)
(Any known search string, descriptor, or XML mismatch details)

---

### 📎 Example Part
- Part Number:
- File Type: (SLDPRT / SLDASM)

---

### 📸 Attachments
(Screenshots of material, cut list, BOM, etc.)

---

### 📝 Additional Notes
(Anything else that might help identify the correct Epicor mapping)

---

## 🔄 Internal Use (Engineering / Data Team)

- [ ] Added to XML material list  
- [ ] Verified in SolidWorks  
- [ ] Verified in CADLinkMacro output  
- [ ] Synced with Epicor  

**Resolution Notes:**
