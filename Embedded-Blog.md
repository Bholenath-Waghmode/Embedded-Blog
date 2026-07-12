---
layout: default
title: Technical Vault
---

# 🐧 Embedded Engineering Q&A Vault

<!-- 
  ========================================================================
  🎯 GEEKSFORGEEKS INTERACTIVE TOP TOGGLE BLOCK
  This creates a clickable "View Question Menu" button bar that reveals
  or hides your question list smoothly on click.
  ========================================================================
-->
<details class="gfg-toggle-panel" style="margin-bottom: 30px;">
  <summary class="gfg-toggle-btn">🔍 View / Hide Question Menu Directory</summary>
  <div class="gfg-toggle-content" style="padding: 15px; background: #ffffff; border-radius: 6px; margin-top: 10px; border: 1px solid #e0e0e0; border-left: 4px solid #2f8d46;">

  * **Embedded C:**
    * Questions Answers:
      * [Q1. What's Volatile?](#q1-whats-volatile)
  * **Device Driver:**
    * Questions Answers:
      * [Q1. What's a Device Driver?](#q1-whats-a-device-driver)

  </div>
</details>

---

## 🛠️ Category: Embedded C

### Q1. What's Volatile?

* **Ans:** The `volatile` keyword tells the compiler optimizer that a variable's value can change at any moment outside the control of the running source code block.
* This explicitly forces the CPU architecture to re-fetch the variable contents directly from actual physical memory space arrays every single time it is accessed.

```c
volatile uint32_t *status_reg = (uint32_t *)0x40003000;
while (*status_reg == 0); 
```

> **Interview Tip:** Always apply `volatile` attributes when tracing memory-mapped input/output address bounds.

---

## ⚙️ Category: Device Driver

### Q1. What's a Device Driver?

* **Ans:** A device driver is a highly specialized kernel-space software framework module that operates as a direct translator between the core operating system kernel and specific hardware assets.

#### Driver-to-Hardware Architecture Diagram:
![Device Driver Architecture Flowchart](./images/driver_flow.png)
