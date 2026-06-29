# Operations 101

> *Operations management is the administration of business practices to create the highest level of efficiency possible within an organization.*

---

## The Big Picture

Imagine you run a factory that makes bicycles:
- If your workers spend half their day waiting for parts to arrive, your operations are inefficient.
- If your assembly line is set up in a way that requires workers to walk back and forth across the warehouse to get tools, you are wasting time.
- If 5% of the bikes you build have defective brakes, you are wasting raw materials and risking lawsuits.

While strategy decides *what* the company should do, **operations** is the science of *how* to do it. Operations transforms raw inputs (labor, steel, rubber) into finished outputs (bicycles) as quickly, cheaply, and reliably as possible.

This article introduces process mapping, the concept of bottlenecks, and the famous operational frameworks of Lean and Six Sigma.

---

## Process Mapping and the Bottleneck

To optimize operations, managers map out every step of a process. This is called a **process map** or workflow.

Imagine a simple coffee shop process:

```
┌──────────────┐      ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
│  1. ORDER    │─────►│   2. BREW    │─────►│  3. PACKAGE  │─────►│  4. DELIVER  │
│  Takes order │      │  Makes drink │      │ Puts lid/bag │      │ Hands to cust│
│  (30 seconds)│      │  (120 seconds)      │  (15 seconds)│      │  (15 seconds)│
└──────────────┘      └──────────────┘      └──────────────┘      └──────────────┘
```

Each step takes a different amount of time. Step 2 (Brewing) takes the longest. 
- Even if the cashier takes orders faster (Step 1), or the packager places lids faster (Step 3), the shop cannot produce more than **one coffee every 120 seconds**.
- Step 2 is the **bottleneck**—the slowest part of the production process that limits the output of the entire system.

> **Rule of Operations:** To increase the capacity or speed of a business, you must focus *only* on improving the bottleneck. Speeding up non-bottleneck steps just creates piles of inventory or idle workers.

---

## Lean Operations: Eliminating Waste

Developed by Toyota in the mid-20th century, **Lean** is a methodology focused on maximizing customer value while minimizing **waste** (*muda*). Lean identifies seven primary wastes:

1. **Overproduction:** Producing goods before they are needed.
2. **Waiting:** Idle time between production steps.
3. **Transportation:** Unnecessary movement of raw materials or products.
4. **Processing:** Doing more work on a product than the customer values.
5. **Inventory:** Raw materials or finished goods sitting in warehouses. (This ties up capital and risks damage/obsolescence).
6. **Motion:** Unnecessary movement by workers during their tasks.
7. **Defects:** Mistakes that require scrap or rework.

By systematically mapping out work and removing these wastes, businesses can operate with fewer resources, smaller warehouses, and faster delivery times.

---

## Six Sigma: Minimizing Defects

While Lean focuses on speed and waste, **Six Sigma** focuses on quality and consistency. Developed by Motorola and popularized by General Electric, Six Sigma is a data-driven method designed to eliminate defects.

- **The Goal:** Reduce process variation so that **99.99966%** of all products are defect-free (no more than 3.4 defects per million opportunities).
- **The Method (DMAIC):**
  - **Define:** Identify the problem and goals.
  - **Measure:** Gather data on the current process.
  - **Analyze:** Find the root causes of defects.
  - **Improve:** Design and implement solutions.
  - **Control:** Monitor the process to maintain the improvements.

---

## Key Terms

- **Operations:** The day-to-day conversion of inputs into finished goods and services.
- **Process Map:** A visual representation of the steps in a workflow.
- **Bottleneck:** The constraint in a system that limits total output capacity.
- **Lean:** A methodology focused on eliminating waste and maximizing value.
- **Six Sigma:** A data-driven method for reducing defects and process variation.
- **Capacity:** The maximum output that a process can generate in a given time period.

---

## Further Reading

- [Strategy101](./Strategy101.md) — How operations execute a cost-leadership strategy
- [SupplyChain101](./SupplyChain101.md) — How operations coordinate with external suppliers and logistics
- [Productivity101](../Economics/Productivity101.md) — The economic metrics of operational efficiency
