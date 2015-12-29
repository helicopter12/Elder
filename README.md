# Elder
An autonomous Elder tree chopping and banking system.

Requirements:

    A Hatchet
    Unlock Lodestones for the following locations:
        Draynor
        Varrock
        Eagle's Peak
        Seer's Village
        Edgeville
        Catheberry
    Level 90+ Woodcutting (99 Recommended)

Script Features:

    Randomized locations and ordering - Picks 4 random locations in a random order to chop and then periodically switches locations in/out of the list (anti-pattern)
        Further Explanation: Say you start with the following locations: "Varrock" and "Draynor 1", after leaving either of those locations there is a ~10% chance that another location out of the six supported locations could be switched in. So now your elder tree list could be "E-Peak" and "Draynor 1", or it could remain unchanged. This anti-pattern helps to eliminate repeated steps and procedures.
    Smart Chopping System
        Eliminates spam clicking
        Features camera, and examination anti-ban
        Decides whether or not to bank before continuing to the next location
    Dead Tree Timer - Keeps a visible countdown timer of when a location's Elder will re-spawn.
    Teleportation via Lodestones - Saves time over running and cuts down on teleportation costs.
    Simple paint that displays the timers, script state/status, and profit.
    Fully autonomous - No settings to play with just start with the required materials where ever you are.


Recommended Settings:

    Computer dependent - but if you experience lagg then set your video settings to "Minimum"


Planned Future Features:

    Summoning capabilities? (Beaver +2 WC level -  Not sure if this would hurt or help profit)
    A more intelligent anti-ban system and upgraded anti-pattern
    Optimized handling for better speed and stability
