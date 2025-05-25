# RLS_advanced
Users
  ↓
UserGroup (many-to-many)
  ↓
AccessGroup
  ↓
GroupPermissions (Region + Department)
  ↓              ↓
DimRegion      DimDepartment
     ↓              ↓
            FactSales

