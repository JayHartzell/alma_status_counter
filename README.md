# alma_status_counter

## Overview
Generates some basic output about the number of physical items and their associated `base_status`. If an item has a `base_status` of `Not in Place`, the code then looks at the item's `process_type`. Output provides counts of items marked as `In Place`, as well as the associated process type of items `Not in Place`

### Requirements
- r bibs key
- `mms_id` of the bib record you want to change
- `holding_id` for each holding you want assessed
