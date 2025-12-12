First, check if the user has already provided instructions about which slice(s)
to implement.

**If the user HAS provided instructions:** Proceed to PHASE 2 to implement those
specified slice(s).

**If the user has NOT provided instructions:**

Read `agent-os/specs/[this-spec]/tasks.md` to review the available slices, then
output the following message to the user and WAIT for their response:

```
Should we proceed with implementation of all slices in tasks.md?

If not, then please specify which slice(s) to implement.
```
