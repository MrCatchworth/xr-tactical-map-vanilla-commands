== Tactical Map Vanilla Commands Readme ==
Author: MegaJohnny
Egosoft Forums Thread: https://forum.egosoft.com/viewtopic.php?t=396379

This is an addon for the tactical map, and has no function without it. The following commands are added.

Right-click commands:
- Fly to Position: Right-click a point in space in sector or zone mode to have a ship move to that position.
- Stop Task: Right-click on the command selection itself to have it stop any task it's currently set to do. Not available in multi-select.
- Attack Object: Right-click an enemy object to have a ship attack it. Note that it's possible to give attack commands to ships with no weaponry this way.
- Fly to Zone: Right-click a zone in sector mode to have a ship move to that zone.

Grid commands:
- Withdraw from Battle: Issued on button press.
- Hold Position: Issued on button press.
- Refuel: On button press, contacts the ship's captain and opens the menu to select how much fuel should be bought. Not available in multi-select.
- Patrol: Requires a zone as a target. The command selection will patrol the target zone indefinitely.
- Transfer Wares: Requires an applicable player-owned ship or station as a target. The ware exchange menu will open between the command selection and the target. Not available in multi-select.
- Attack Object: Requires a non-player-owned ship or station as a target. The command selection will attack the target. Unlike the right-click version, non-hostile targets can be attacked this way.


== Known Issues ==

Fly to Position sometimes causes the ship to come to a full stop until you try to issue it again or leave the zone. I've no idea why right now.


== Changes ==
2017-10-09: 1.2
    - All commands are valid in multi-select mode, with the following exceptions:
        - Stop Task: If you right-click one of the selected ships on itself, the other ships are still being clicked onto a different ship, so it doesn't really work.
        - Refuel: Opens a menu pertaining to one ship, so doesn't make sense for multi-select.
        - Transfer Wares: Ditto.

2017-09-28: 1.1
    - Added ware exchange grid command
    - Added "force attack" grid command
    - Now properly signals "stop order" followed by command-specific order, as in vanilla gameplay - this fixes a bug where sometimes commands needed to be issued twice

2017-09-16: Initial release