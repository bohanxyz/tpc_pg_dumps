# TPC Database Backup Files

## File List
- `tpch_1g_dump.sql.gz` - Complete PostgreSQL database backup for `TPC-H 1GB` (compressed)

## Quick Start - Restore from Backup

```bash
# Restore from backup
gunzip -c tpch_1g_dump.sql.gz | psql tpch
```
