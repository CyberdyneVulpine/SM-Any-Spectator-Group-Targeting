# [Any] Spectator Group Targeting
**Version 1.0.1**
## Description:

Allows admins to target spectators, unassigned players, or both using 3 new group targets.  


## Target Specifiers:

-   **@spec**
    -   All players who have joined the spectator team.
-   **@unassigned**
    -   Players who have not joined any team (may include connecting players).
-   **@notonteams**
    -   All the above.

## Cvars:

-   **sm_spec_target_version**
    -   Plugin Version


## Install Instructions:

1.  Place  **SpectatorTarget.smx**  into your addons/sourcemod/plugins/ folder.

  
## Usage:

In any command where you can use group targeting (eg, @all), you will be able to use @spec, etc.  
> Example: '_sm_kick @spec'_  would kick all players in spectate.   

## Version History:  
-   **V1.0.0**
       -   Initial Release
-   **V1.0.1**
    -   Now ignores SourceTV/Replay bots.