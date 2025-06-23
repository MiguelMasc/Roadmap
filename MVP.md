# MVP Core Features:


## Stage Management:

 - Create new stages (title, description)
 - Edit existing stages
 - Delete stages
 - Basic stage library/collection

## Canvas Basics:

 - Drag stages onto canvas
 - Move stages around canvas
 - Connect stages with arrows (drag from one stage to another)
 - Remove connections

## Simple Data Model:

   - Stage: id, title, description
   - Roadmap: id, name, list of stages and connections
   - Connection: from_stage_id, to_stage_id

## Minimal UI:

 - Stage palette - list of available stages to drag from
 - Canvas area - where roadmap gets built
 - Basic toolbar - save, clear, maybe zoom