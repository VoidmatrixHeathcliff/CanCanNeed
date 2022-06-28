# CanCanNeed

**CanCanNeed Macro**

To replace the double conditional `if` statement with `CanCanNeed`.

## Example

Before:

```c
if (A && B) C++;

// or

if (A)
    if (B)
        C++;
```

After:

```c
#include "CCN.h"

CanCanNeed(A, B, C++)
```