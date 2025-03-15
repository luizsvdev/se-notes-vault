## 1. Basic Concepts and Computer Systems History

### Main Computer Functions
- Data processing - performing mathematical operations
- Data movement - defining the destination of results
- Data storage - ensuring persistence
- Data control - managing and manipulating data

---

## 2. Bus, Memory, IO and OS Support

### CPU Architecture with Two Caches  

#### Diagram:
```mermaid
graph LR;
    CPU["CPU Reg"]
    L1["L1 Cache"]
    L2["L2 Cache"]
    RAM["Mem RAM"]

    CPU <-->|5ns| L1 <-->|15ns| L2 <-->|100ns| RAM
```

#### Definitions:  
- **HA (Hit Rate)** – The percentage of accesses that hit in a cache level  
- **MR (Miss Rate)** – The percentage of accesses that miss in a cache level  
- **AT (Access Time)** – The time required to access a memory level

$AT​=AT×(100AR​)×(1+FR)$