# Microsoft Fabric Learning Series — Day 2  
## OneLake Architecture: The Foundation of Fabric

### Overview  
OneLake is the unified, enterprise-wide storage layer for Microsoft Fabric.  
It acts as the “OneDrive for data,” providing a single, logical data lake for all analytics workloads — Lakehouse, Warehouse, Real-Time, Data Science, and Power BI.

### Key Concepts  

#### **1. One Logical Lake**
- All Fabric items store data in OneLake  
- No duplication across workspaces  
- Eliminates siloed storage

#### **2. Delta Tables Everywhere**
- Standardized storage format  
- ACID transactions  
- Optimized for analytics and ML

#### **3. Shortcuts**
- Virtual pointers to external data  
- No copying required  
- Connects ADLS, AWS S3, and other lakes

#### **4. Direct Lake Mode**
- Power BI reads Delta tables directly  
- No import or refresh  
- Massive performance boost

#### **5. Unified Security & Governance**
- Centralized access control  
- Lineage and catalog built-in  
- Consistent policies across workloads

### Why OneLake Matters  
OneLake simplifies:
- Storage management  
- Data sharing  
- Governance  
- Cross-team collaboration  
- Performance for BI and analytics

It is the backbone of the entire Fabric ecosystem.

### Visual (Optional)
If you have a OneLake diagram, upload it here:
`/images/day2_onelake_architecture.png`

