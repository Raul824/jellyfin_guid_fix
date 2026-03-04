# Jellyfin GUID Corruption Fix

## Overview
This shell script addresses the issues concerning the corruption of GUIDs (Globally Unique Identifiers) in Jellyfin database.

## Requirements.
1. Shell environment
2. sqlite installed.

## Usage
1. Just download the file "guidfix"   
2. Make a copy of jellyfin.db to recov.db
3. From the logs check the tablename which has error in backup.
4. run the script `bash guidfix <TableName>`
5. It will show the records which are not in correct GUID format and will ask for confirmation to delete.

