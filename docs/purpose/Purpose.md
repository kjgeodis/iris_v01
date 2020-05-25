---
tags: [Purpose]
---

# Purpose

The main purpose for MILESTONE REQUEST operation is for GEODIS agents to update milestones on shipments via the IRIS
API instead of doing this manually via Milestone Entry in IRIS. When a milestone is added via this script,
the milestone is added on the shipment in NextGen.

**Please note:**
1. Only one milestone event is allowed in each request (see addmilestoneext.xsd for reference).
2. Use the Estimated segment, to indicate this is an estimate date, otherwise its assumed Actual.