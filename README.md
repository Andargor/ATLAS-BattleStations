# Battle Stations!

This mod automatically assigns crew to active, uncrewed weapons on a ship.

It's meant to allow you to move your crew to active weapon groups. E.g. you have crew on the right guns with no one on the left guns, deactivate the right group, activate the left group, and the crew changes sides to the left group.

When groups are activated from the steering wheel:

- Idle crew will mount uncrewed weapons in the active groups after a delay (currently a fixed value of 5s)
- Crew on weapons in inactive groups will also leave their station to man the weapons in the active groups
- If all active weapons are manned, they will dismount if their group is no longer active
- If no group is active, they will all dismount
- When activated, there is a target icon over the head of the crewmember when on ship. If it is yellow, there are no free weapons in active groups. If it is green, they are mounted on an active weapon
- There is an audible confirmation from each crewmember when they change state

To enable crewmembers to be activated in this fashion, there is an option under Behavior to "Activate Battle Stations" that must be selected on the radial menu for the crewmember. There is a visual indication on the crewmember that the logic is active.

You may not ask a crewmember to follow you or perform other actions if they are activated. To do so, you must select "Deactivate Battle Stations" under Behavior on the radial menu for the crewmember.

MOD ID: 1737646933