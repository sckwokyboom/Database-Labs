# Database-Labs
 Completed assignments for the database course at NSU.

## Music Shop
Entities:
1. Table "Authors":
- Author ID (Primary Key)
- First Name
- Last Name
- Middle Name
- Alias

2. Table "Songs":
- Song ID (PK)
- Title

3. Table "Roles":
- Role ID (PK)
- Role Name (composer, lyricist, performer, etc.)

4. Table "Authors-Roles-Songs":
- Author ID (FK to Author ID in the "Authors" table)
- Song ID (FK to Song ID in the "Songs" table)
- Role ID (FK to Role ID in the "Roles" table)

5. Table "Disks":
- Disk ID (PK)
- Disk Title

6. Table "Disks-Songs":
- Disk ID (FK to Disk ID in the "Disks" table)
- Song ID (FK to Song ID in the "Songs" table)