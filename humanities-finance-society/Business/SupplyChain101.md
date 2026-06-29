# Supply Chain 101

> *A supply chain is the network of all the individuals, organizations, resources, activities, and technology involved in the creation and sale of a product, from the delivery of source materials to the destination customer.*

---

## The Big Picture

When you buy a smartphone:
- The cobalt in its battery was mined in the Democratic Republic of Congo.
- The microchips were designed in the US and manufactured in Taiwan.
- The screen was produced in South Korea.
- The phone was assembled in China.
- The finished product was flown across the ocean, stored in a local warehouse, and delivered to your doorstep.

How did all these independent global activities coordinate perfectly to deliver a working phone to you? 

They did it through a **supply chain**. Supply chain management is the art of coordinating suppliers, factories, shipping ports, warehouse inventories, and delivery trucks to ensure products are delivered on time without wasting capital.

This article introduces the stages of a supply chain, the Just-in-Time inventory model, the dangerous "bullwhip effect," and the importance of resilience.

---

## The Stages of a Supply Chain

A typical supply chain moves in a linear flow, with materials moving "downstream" and cash moving "upstream":

```
┌──────────────┐      ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
│ 1. SUPPLIER  │─────►│ 2. FACTORY   │─────►│3. DISTRIBUTOR│─────►│ 4. RETAILER  │
│ Raw materials│      │ Manufactures │      │ Stores in    │      │ Sells to     │
│ (e.g., steel)│      │ parts/goods  │      │ warehouses   │      │ end consumer │
└──────────────┘      └──────────────┘      └──────────────┘      └──────────────┘
```

- **Procurement:** Buying raw materials or parts from suppliers.
- **Logistics:** The physical movement and storage of goods (via ships, trains, trucks, and warehouses).
- **Distribution:** Managing inventory and delivering products to retail stores or directly to customer homes.

---

## Inventory Management: Just-in-Time (JIT)

One of the biggest costs in a supply chain is **inventory**—goods sitting in warehouses. Storing inventory is expensive (paying for space, security, insurance) and risky (goods can spoil, break, or become obsolete).

To solve this, many companies use the **Just-in-Time (JIT)** model:
- Instead of keeping months of parts in a warehouse, parts are scheduled to arrive at the factory floor exactly when they are needed for assembly (literally "just in time").
- **Example:** Toyota's suppliers deliver parts to the assembly line multiple times a day.
- **The Benefit:** Saves millions in storage costs and keeps the business lean.
- **The Risk:** Zero buffer. If a supplier has a strike, or a storm delays a shipping container by one day, the entire factory must shut down immediately.

---

## The Bullwhip Effect: Communication Breakdown

A major challenge in supply chains is the **bullwhip effect**—the phenomenon where small fluctuations in retail sales cause massive, wild swings in factory orders upstream.

Imagine a sudden 10% increase in customer purchases of a specific toy:
1. **The Retailer** notices the bump and panics that they will run out of stock. They order **20% more** toys from the distributor to be safe.
2. **The Distributor** sees the 20% order jump, adds their own buffer, and orders **50% more** toys from the manufacturer.
3. **The Manufacturer** sees the 50% order jump, orders **100% more** raw materials from the supplier, and runs their factory night and day.
4. **The Result:** When customer demand returns to normal, the supply chain is flooded with massive amounts of unwanted inventory.

The bullwhip effect is caused by a lack of shared information and delayed communication across the chain.

---

## Resilience: Building Buffers

Modern supply chain management focuses on **resilience**—the ability to withstand unexpected shocks (like pandemics, geopolitical conflicts, or canal blockages):

- **Nearshoring/Reshoring:** Moving factories closer to the home country to reduce shipping times and borders (rather than outsourcing to the cheapest country across the globe).
- **Dual Sourcing:** Buying key parts from two different suppliers in different regions, ensuring a backup is always available.
- **Safety Stock:** Keeping a small buffer of vital parts to survive minor delivery delays.

---

## Key Terms

- **Supply Chain:** The network of processes and organizations that deliver a product from raw materials to customer.
- **Logistics:** The physical transportation and storage of goods.
- **Just-in-Time (JIT):** An inventory strategy where materials are delivered immediately before they are needed, minimizing storage costs.
- **Bullwhip Effect:** The amplification of demand fluctuations as orders move upstream in a supply chain.
- **Resilience:** The capacity of a supply chain to recover quickly from disruptions.
- **Procurement:** The process of sourcing and purchasing goods and services.

---

## Further Reading

- [Operations101](./Operations101.md) — How internal factory processes coordinate with supply chains
- [Trade101](../Economics/Trade101.md) — The economic principles of global trade networks
- [CorporateFinance101](./CorporateFinance101.md) — How inventory levels affect working capital
