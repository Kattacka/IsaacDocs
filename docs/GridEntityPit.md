---
tags:
  - Class
---
# Class "GridEntityPit"

???+ info
    You can get this class by using the following function:

    * [GridEntity.ToPit()](GridEntity.md#topit)

    ???+ example "Example Code"
        `Game():GetRoom():GetGridEntity(25):ToPit()`

## Class Diagram
--8<-- "docs/snippets/GridEntityClassDiagram.md"
## Functions
### Make·Bridge () {: aria-label='Functions' }
[ ](#){: .reporplus .tooltip .badge }
#### void MakeBridge ( [GridEntity](GridEntity.md) parentEntity) {: .copyable aria-label='Functions' }
parentEntity can be `nil` to use the default texture as the bridge
???- warning "Warning"
    An additional unknown argument after parentEntity was added in Repentance+ that must be set or else the function will error. Setting it to 0 appears to restore functionality.
___
### Set·Ladder () {: aria-label='Functions' }
[ ](#){: .alldlc .tooltip .badge }
#### void SetLadder ( boolean Value ) {: .copyable aria-label='Functions' }

___
### Update·Collision () {: aria-label='Functions' }
[ ](#){: .alldlc .tooltip .badge }
#### void UpdateCollision ( ) {: .copyable aria-label='Functions' }

___
## Variables
### Has·Ladder {: aria-label='Variables' }
[ ](#){: .alldlc .tooltip .badge }
#### boolean HasLadder  {: .copyable aria-label='Variables' }

___
