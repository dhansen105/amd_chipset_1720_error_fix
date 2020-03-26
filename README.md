# dhansen105-gmail.com
AMD Chipset Driver 1720 Error Fix

To fix this error run the "amd_1720_error_fix.reg" file within this repository.

Took me awhile to find this digging in the event viewer and looking through registry but I think I found the root cause.

Looks like AMD didn't expect users to skip driver updates because one of their previous updates created this String value in registry while prior ones didn't and the new installs are expecting this to be in registry and not accounting for it if missing.

Thanks and hope this helps,

Daniel
