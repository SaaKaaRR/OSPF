# OSPF Multi-Area Lab

## Project Overview

This project demonstrates the design and implementation of a **Multi-Area OSPF (Open Shortest Path First)** network topology. The lab is designed to provide hands-on experience with OSPF hierarchical design principles, inter-area routing, and Area Border Router (ABR) functionality.

The topology consists of:

- **Area 0 (Backbone Area)**
- **Area 10**
- **Area 20**
- **Loopback network advertisement**
- **Inter-area route propagation**
- **Area Border Router (ABR) operations**

The primary objective of this lab is to understand how OSPF scales in larger environments by dividing the network into multiple areas and how routing information is exchanged between those areas through ABRs while maintaining a centralized backbone area.

---

## Lab Objectives

Upon completion of this lab, you will be able to:

### OSPF Fundamentals

- Understand the role and importance of OSPF as a link-state routing protocol.
- Understand the purpose of the Backbone Area (Area 0) in a multi-area OSPF design.
- Understand the concept of OSPF hierarchy and scalability.

### Configuration Tasks

- Configure OSPF in a multi-area environment.
- Assign interfaces to the appropriate OSPF areas.
- Configure and advertise loopback interfaces.
- Configure Area Border Routers (ABRs).
- Establish OSPF neighbor adjacencies between routers.

### Verification and Analysis

- Verify OSPF neighbor relationships.
- Verify OSPF Link-State Database (LSDB) synchronization.
- Analyze inter-area route propagation.
- Examine OSPF routing table entries.
- Identify Type 1, Type 2, and Type 3 LSAs within the topology.

### Troubleshooting

- Troubleshoot OSPF adjacency issues.
- Identify and resolve area mismatches.
- Verify OSPF route advertisements and route learning.
- Analyze common causes of routing and neighbor establishment failures.

---

## Expected Learning Outcomes

After successfully completing this lab, you should be able to:

1. Design a basic multi-area OSPF topology.
2. Implement OSPF routing across multiple areas.
3. Understand how ABRs facilitate communication between OSPF areas.
4. Verify proper route exchange between remote areas through Area 0.
5. Interpret OSPF operational outputs using verification commands.
6. Troubleshoot common OSPF deployment issues in enterprise networks.
