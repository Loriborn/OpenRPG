# OpenRPG

Developed with Unreal Engine 4.27

OpenRPG is a work-in-progress showcase for a networked first person roleplaying game framework. All assets included in the project were created by me or are public domain.

The framework was designed to blend the old-school Ultima Underworld cursor interaction system with Daggerfall and modern RPG direct interaction. Existing code handles networked health and limb damage, physics interactions, movement, and inventory management. More complex systems for quests are planned. A custom shader is implemented to simulate PSX-era graphics (vertex jitter has been disabled for clarity).

Controls:
W,A,S,D - directional movement
Space - Jump
Shift - Sprint
Tab (hold) - toggle mouse interaction mode
E - default interaction
Z - pickup physics object
Right Mouse (when in mouse interaction mode and hovered over object) - object interaction context menu
Left mouse - attack (with item equipped)

Items can be dragged between inventories using the mouse and right clicking on an object in the world will allow you to equip that item. Inventory UI for equipping items is not done at the moment.

Because there is no UI for connecting to sessions, the only way to test networking is to open the project and run a simulated network test using the UE4 editor.
