
### Sidenotes

1. How to "snapshot" generic/random operations? 
  - Bitcoin has always a value / transaction stable specification
  - R: ACL
2. Need of local storage?
3. Temporal access vs rule-override
4. Group and individual ACL (e.g. nurses vs doctor x)
  - Fine-Grained Access Control with Object-Sensitive Roles
5. Permissions: Read / Write / R&&W
6. Snapshots?
  - At every 10 iterations do a snapshot, adding metadata
    - {ops: [ -- ], meta: {timestamp, entityname, snapshot(T/F)} }
  - Two-level blockchain
    - snapshots + blocks

7. Sidechain for snapshots