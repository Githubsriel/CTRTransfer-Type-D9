## CTRTransfer (Type D9)
GodMode9 script that does Decrypt9 method of CTRNAND image transfer with added improvements.

### Recent Changes:
- Updated the script to support **32-byte SHA files** used in **11.15 firmware CTRNAND images**.
- The script now detects both **32-byte and 33-byte SHA files** and determines the region accordingly.
- If a **33-byte SHA file** is used, the last byte is still used for region detection.
- If a **32-byte SHA file** is used, the region is now extracted directly from the CTRNAND.

For more information about this script, please check this GBAtemp forum post:

[https://gbatemp.net/threads/release-godmode9-scripts-megathread.482150/page-9#post-8550543](https://gbatemp.net/threads/release-godmode9-scripts-megathread.482150/page-9#post-8550543)
