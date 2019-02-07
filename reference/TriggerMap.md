GLOBAL
    StarCode
        Source
        READ ME
        <Starcode> Start Code
        <Starcode> Store Integer Value
        <Starcode> Set Code
        <Starcode> Set Encryption Alphabet
        <Starcode> Get Code
        <Starcode> Get Integer Value
        <Starcode> Encrypt String
        <Starcode> Compress String
        <Starcode> Hash String
        <Starcode> Remove Hash from String
        <Starcode> Validate String
        <Starcode> Decrypt String
        <Starcode> Decompress String
    ------- Base Records
    recAutoCamStyle
    recColorScheme
    recNamePanelImage
    recUnit
    recPlayerSelectMode
    recPet
    recUpgrade
    recHelpTopic
    recStoreAisle
    recStoreItem
    recLeague
    recOptionTab
    ------- Main Globals
    recGlobals
    recGameState
    recGlobals <(Unknown Record)>
    recGameState <(Unknown Record)>
    ------- Pranks
    recPrank
    recPranks <(Unknown Record)[50]>
    ------- Teams
    recTeam
    recTeamsSource <(Unknown Record)[100]>
    recTeams <(Unknown Record)[100]>
    ------- Players
    recCamEvent
    recFloatingIcon
    recPlayer
    recPlayers <(Unknown Record)[17]>
    recFloatingIcons <(Unknown Record)[2000]>
    ------- UI
    recNavButton
    recTeamButton
    recUI
    recUI <(Unknown Record)>
    ------- Chat
    recChatItem
    recChatList <(Unknown Record)[201]>
    ------- Match
    recMatch
    recMatchLog
    recMatches <(Unknown Record)[20]>
    recMatchLogs <(Unknown Record)[20][1000]>
    ------- Store
    recStoreItems <(Unknown Record)[200]>
    ------- Comment
    Initialize Globals
    Initialize Unit Data
    Initialize Map Units
    Initialize Help
    Initialize Pranks
    Initialize Name Panel Images
    Initialize Color Schemes
    Initialize Auto Cam Styles
    ------- Game Initialization
    Game Init Before Tutorial
    Game Init After Tutorial
    UI Initial Config for Player
    Maps
        Map Init
        1v1
            ------- No close-by-ground spawns
            Map: Star Station
            Map: Metropolis
            Map: Entombed Valley
            ------- Cross-map spawns
            Map: Antiga Shipyard
            ------- Random spawns (or only 2 spawn points)
            Map: Invader
            Map: Honorgrounds
            Map: Ulrena
            Map: Port Aleksander
            Map: Kings Cove
            Map: Cyber Forest
            Map: Lost and Found
            Map: Abyssal Reef
            Map: Proxima Station
            Map: Paladino Terminal
            Map: Overgrowth
            Map: New Gettysburg
            Map: Frozen Temple
            Map: Central Protocol
            Map: Lerilak Crest
            Map: Ruins of Seras
            Map: Dusk Towers
            Map: Orbital Shipyard
            Map: Prion Terraces
            Map: Frost
            Map: Daedalus Point
            Map: Habitation Station
            Map: Heavy Rain
            Map: Derelict Watcher
            Map: Polar Night
            Map: Whirlwind
            Map: Alterzim Stronghold
            Map: Yeonsu
            Map: Red City
            Map: Neo Planet S
            Map: Akalon Wastes
            Map: BelShir Vestige
            Map: Abyssal City
            Map: Cloud Kingdom
            Map: Daybreak
            Map: Dual Sight
            Map: Ohana
        2v2
            Map: Boneyard
            Map: Crooked Maw
            Map: Infestation
    Research
        recResearch
        recResearch <(Unknown Record)[4][7][11][5]>
        Initialize Research
        Initialize Terran Research
        Initialize Zerg Research
        Initialize Protoss Research
    Structures
        recStructures
        recStructures <(Unknown Record)[4][7][11]>
        Initialize Structures
        Initialize Terran Structures
        Initialize Zerg Structures
        Initialize Protoss Structures
    ------- Global Periodic Trigger
    Periodic: Every Game Second
    Periodic: Every Real Second
    ------- TESTER
    fixendgame
Bling
    Set Decal Texture
    Set Actor Tint for Player
    Turf Markers
        Create Turf Markers for Player
        Destroy Player Turf Markers
        Move Turf Markers
    Turf Symbols
        Create Turf Symbols for Player
        Destroy Player Turf Symbols
    Pets
        Initialize Pets
        Timer: Spawn Match Pets
        Timer: Spawn Faceoff Pets
        Clear Pet Utterances Player 1
        Clear Pet Utterances Player 2
        Clear Pet Utterances Player 3
        Clear Pet Utterances Player 4
        Clear Pet Utterances Player 5
        Clear Pet Utterances Player 6
        Clear Pet Utterances Player 7
        Clear Pet Utterances Player 8
        Clear Pet Utterances Player 9
        Clear Pet Utterances Player 10
        Clear Pet Utterances Player 11
        Clear Pet Utterances Player 12
        Clear Pet Utterances Player 13
        Clear Pet Utterances Player 14
        Make Pet Utter X for Player
        Make Pets Return Home for Player
        Create Match Pets for Player
        Create Faceoff Pets for Player
        Destroy Player Pets
        Rename Player Pet
        makePetNameText
Players
    Bank
        Load Bank for Player
        Save Bank for Player
        Save All Player Banks
        Load All Player Banks
    Callback for Player Leaving Game
    Handle Player Leaving Game
    Cleanup from Player Leaving Prematurely
    getTeamUnitOfPlayer
    getTeamNameOfPlayer
    getPlayerDisplayNameForPlayer
    makePlayerProfileText
    getPlayerWinPercentage
    getPlayerPeepRating
    pgObservers
    pgPlayers
    Initialize Players
    Make Dummy
    Set Player Colors to Color Scheme
    Kick Unregistered Players
    Set Player Assets Based on Color
Teams
    Calculate Team Info
    Refresh Team Selection List
    Calculate Team Selections
    matchConditionsMet
    Clear Out Match Selections
    Setup Match Team List
    ------- Comment
    Calculate Sonas Ratings
    ------- Comment
    makeTeamList
    getNumObservers
    Debug Teams
    Initialize Teams
    Initialize More Teams
    Add Player to Team
    Remove Player from Team
    Kick Player Off Team
    Refresh Player UI
UI
    Initialize UI
    Initialize General UI
    Avatars
        Newb Dialog
            Pulldown: League
            Pulldown: Race
            Refresh Blizzard UI Panel
            Periodic: Newb Team Cooldown
            Button: Newb Team Selection
            Button: Cancel Team
            Select Random Team for Player
            Create Newb Team Dialog
            ------- Comment
            Create Cancel Play Dialog
        Join Confirmation
            Button: Decline Join
            Button: Confirm Join
            Create Join Confirmation Dialog
        Periodic: Team Cooldown
        Timer: Team Cooldown End
        ------- Comment
        Buttons: Team Selection
        Button: X Avatars Dialog
        Create Avatars Dialog
        Try to Add Player to Team
        Initialize Avatar Buttons
        Refresh Avatar Buttons for Player
        ------- Comment
        Button: Avatars Next Page
        Button: Avatars Previous Page
        Refresh Avatar Dialog Page for Player
    Betting
        Periodic: Betting Countdowns
        Timer: Betting Interval
        Timer: Betting Period
        Timer: Betting Close
        Slider: Change Potential Bet
        Pulldown: Team to Win
        Button: X Betting Dialog
        Button: Place Bet
        Award Betters at End of Match
        Clear Out Betting
        Refresh Betting Payouts For Player
        New Betting Period for Player
        Refresh Pot Label
        Create Betting Dialog
        Initialize Betting for Match
        Enable Betting Controls
        Disable Betting Controls
    Bling 2
        Button: X Inventory Dialog
        Buttons: Inventory
        Buttons: Store
        Create Bling Dialog
        ------- Pets
        Pulldowns: Pet Type
        Pulldowns: Pet Spawn
        Refresh Pet UI for Player
        ------- Turf Markers
        Pulldowns: Turf Marker Type
        Pulldowns: Turf Marker Spawn
        Refresh Turf Marker UI for Player
        ------- Turf Symbols
        Pulldowns: Turf Symbol Type
        Pulldowns: Turf Symbol Spawn
        Refresh Turf Symbol UI for Player
        ------- Comment
        test: moving peepmode logo
    Blizzard Leader Panel
        Create Blizzard UI Dialog
        Move Blizzard UI to Cinematic for Player
        Move Blizzard UI to Normal for Player
        Move Blizzard UI to Fullscreen for Player
    Chat
        Periodic: Update Chat
        Chat: Any message
        replaceSpecialChars
        convertChatItemToText
        Create Chat Message
        Create Chat Dialogs
        Refresh Chat
        isChatIndexVisibleToPlayer
        Create Forced System Message
    Chat Log
        Chat Help
            Button: X Chat Help Dialog
            Create Chat Help Dialog
        Button: X Chat Log Dialog
        Button: Chat Refresh
        Button: Chat Help
        Checkbox: Chat Log Check All
        Create Chat Log Dialog
        Refresh Chat Log Player Listing
        Refresh Chat Log for Player
    Commentator Choice
        Buttons: Commentator Team Vote
        Button: Commentator Defer Vote
        Timer: Commentator Choice Ends
        Periodic: Commentator Choice Countdown
        Launch Commentator Choice
        Create Commentator Choice Dialog
        Refresh Commentator Choice Controls
    Dashboard
        Create Dashboard
        Refresh Dashboards for All Players
        Refresh Dashboard for Player
    Floating Icons
        TEST
        TEST 2
        TEST 3
        ------- Comment
        Floating Icons - Unit Production (Create)
        Floating Icons - Unit Production (Destroy)
        Floating Icons - Research (Create)
        Floating Icons - Research (Destroy)
        Create Floating Icon
        Destroy Floating Icon for All Players
        Destroy All Floating Icons
        Refresh Floating Icons for Player
        Refresh Floating Icon
        Set Floating Icon Offsets
        convertGameLinkToIconText
    Global UI Actions/Triggers
        Button: Show Fair Message Log
        convertSecondsToTime
        formatIntegerAsText
        Enter Cinematic Mode for Player
        Exit Cinematic Mode for Player
        Temp Exit Cinematic Mode for All Players
        Enter Movie Mode for Player
        Temp Enter Cinematic Mode for All Players
        Exit Movie Mode for Player
        Hide All Leftside Dialogs for Player
        Hide All Leftside Dialogs Except Blizz and Log
        Hide All Rightside Dialogs for Player
        Hide All Rightside Dialogs Except Resource Panels
        Hide All Center Dialogs for Player
        Enter Fullscreen Mode for Player
        Exit Fullscreen Mode for Player
        Toggle PeepMode UI for Player
        Show/Hide PeepMode UI for Player
        Actor - Show/Hide Actor For Player Group
        Show All Structure Actors from Player to Player
        Sync applyVision Structure Actors from Player to Player
    Help
        Pulldown: Section
        Slider: Help Scroll
        Button: X Help Dialog
        Create Help Dialog
    Init Screen
        Button: Skip Tutorial
        Skip Tutorial for Player
        Timer: End Tutorial
        Periodic: Tutorial Cooldown
        Start Init Screen
        Start Tutorial
        End Init Screen
    Keyboard Shortcuts
        ------- Name Panel
        Key: Alt-N (Name Panel)
        Key: Ctrl-Alt-N (Customize Name Panel)
        Key: Alt-Q (Quick Panel)
        ------- Quick Panels
        Key: Alt-Y (Structures Panel)
        Key: Alt-U (Research Panel)
        Key: Alt-I (Resources)
        Key: Alt-A (Supply)
        Key: Alt-R (Units Killed)
        Key: Alt-V (APM)
        ------- Observer Vision
        Key: Alt-0 (Observe Everyone)
        Key: Alt-1 (Observe Item 1)
        Key: Alt-2 (Observe Item 2)
        Key: Alt-3 (Observe Item 3)
        Key: Alt-4 (Observe Item 4)
        Key: Alt-5 (Observe Item 5)
        Key: Alt-6 (Observe Item 6)
        Key: Alt-7 (Observe Item 7)
        Key: Alt-8 (Observe Item 8)
        Key: Alt-9 (Observe Item 9)
        ------- Blizz UI Panels
        Open Blizz UI Panel for Player
        Key: Shift-Alt-R (Resources)
        Key: Shift-Alt-I (Income)
        Key: Shift-Alt-S (Spending)
        Key: Shift-Alt-U (Units)
        Key: Shift-Alt-T (Structures)
        Key: Shift-Alt-L (Units Lost)
        Key: Shift-Alt-D (Production)
        Key: Shift-Alt-G (Upgrades)
        Key: Shift-Alt-A (Active Forces)
        Key: Shift-Alt-M (APM)
        Key: Shift-Alt-E (EPM)
        Key: Shift-Alt-C (EPM as well)
        ------- Tools
        Key: Alt-W (Auto Cam)
        Key: Alt-C (Cinematic Mode)
        Key: Alt-H (Logs)
        Key: Alt-D (Blizzard UI)
        Key: Alt-B (Betting)
        Key: Alt-L (Leaderboard)
        Key: Alt-S (ResourcePanel)
        Key: Alt-M (Advanced Resource Panel)
        ------- Camera Controls
        Key: Alt-Z (Zoom Out)
        Key: Alt-X (Zoom In)
        Key: Ctrl-Shift-U (Zoom Out)
        Key: Ctrl-Shift-O (Zoom In)
        Key: Ctrl-Shift-J (Yaw Left)
        Key: Ctrl-Shift-L (Yaw Right)
        Key: Ctrl-Shift-I (Pitch Up)
        Key: Ctrl-Shift-K (Pitch Down)
        Key: Ctrl-Shift-Y (Default Angle)
        Key: Ctrl-Shift-H (Default View)
        Key: Ctrl-Shift-1 (Auto Cam Style 1)
        Key: Ctrl-Shift-2 (Auto Cam Style 2)
        Key: Ctrl-Shift-3 (Auto Cam Style 3)
        Key: Ctrl-Shift-4 (Auto Cam Style 4)
        Key: Ctrl-Shift-5 (Auto Cam Style 5)
        ------- Commentator Tools
        Key: Alt-J (Map Analysis)
        Key: Alt-K (Map Overlay)
        Key: Alt-P (Pen)
        Key: Alt-O (Erase Pen)
        ------- Fullscreen
        Key: Alt-E (Fullscreen Mode)
        ------- Remove PeepMode UI
        Key: Ctrl-Alt-E (Hide PeepMode UI)
        ------- Menus
        Key: F8
        Key: F9
        Key: Ctrl-F9
        Key: F11
        Key: F12
        ------- Debug Keystroke Sequence
        Debug Sequence: Step 1
        Debug Sequence: Step 2
        Debug Sequence: Step 3
        Debug Sequence: Step 4
        Timer: Debug Sequence Expires
        ------- Comment
        Key: Ctrl-K (Kick a Player)
    Leaderboard
        Button: X Leaderboard
        Buttons: Leaderboard Sort
        Create Leaderboard
        Refresh Leaderboard for All Players
        Refresh Leaderboard for Player
    Versus Screen
        Timer: Blinking Subtitle
        Create Loading Match Dialog
        Destroy Loading Match Dialog
    Match Log
        Match History
            Listbox: Match Selection
            Button: X Match History Dialog
            Button: Refresh History
            Checkbox: History Check All
            makeMatchDetailsText
            Create Match History Dialog
            Refresh Match History Listbox
        Button: Match History
        Checkboxes: Log Filters
        Handle Match Event (Log/Chat)
        AorAnPrefixForUnitType
        ------- Comment
        Create Match Log Dialog
        Refresh Match Log Dialog for Player
        Refresh Match Log Text for Player
        Disable Match Log Player Filters for Player
        Enable Match Log Player Filters for Player
    Minimap
        Button: X Minimap
        Setup Minimap UI
    Name Panel
        ------- Comment
        Button: Quick Panel
        Create Name Panel
        Add Name Panel Element to Global List
        ------- Comment
        Refresh Name Panel Main
        Refresh Name Panel Supply
        Refresh Name Panel Extras
        Clear Name Panel
        ------- Comment
        Refresh Name Panel Main for Player
        Refresh Name Panel Item Visibility for Player
        Refresh Name Panel Scores for Player
        Refresh Name Panel Polls for Player
        Refresh Name Panel Betting for Player
        Refresh Name Panel Message for Player
        Refresh Name Panel Position for Player
        Refresh Name Panel Style for Player
        Refresh Name Panel Main Graphic for Player
        ------- Comment
        Fade In Name Panel Graphic
        Fade Out Name Panel Graphic
    Nav Buttons
        Buttons: Nav
        Button: Teams
        Button: Options
        Button: Menu
        Button: Chat
        Button: Help
        ------- Comment
        Initialize Nav Buttons
        Create Nav Buttons
        ------- Comment
        Hide All Nav Buttons for All Players
        Show Nav Buttons for Player
        Hide Nav Buttons for Player
        Show Fair Message Log Button for Player
        Hide Fair Message Log Button for Player
    Observer Controls
        Pulldown: Observer Vision
        Checkbox: Auto Cam
        Button: Zoom In
        Button: Zoom Out
        Button: Cinematic Mode
        Button: Blizz UI
        Button: Logs
        Button: Stats
        Button: Betting
        Button: Leaderboard
        Apply Zoom to Player Cam
        Refresh Observer Pulldown
        Create Observer Dialog
        ------- Comment
        Camera Yaw Left for Player
        Camera Yaw Right for Player
        Camera Pitch Up for Player
        Camera Pitch Down for Player
        Reset Camera to Default Angle for Player
        Reset Camera to Default View for Player
        roundRealToNearestIncrement
    Options
        Customize Name Panel
            Change Player Values Dialog
                Create Change Player Names Dialog
                Button: X Change Player Names Dialog
                Textbox: Player Name
            Create Name Panel Options Dialog
            Apply Name Panel Settings for Player
            Sync Name Panel Settings from Player to Player
            ------- Comment
            Button: X Name Panel Options Dialog
            Button: Apply Name Panel Settings
            Button: Apply Name Panel Settings to All
            Button: Change Player Values
            ------- Comment
            Textbox: Custom Message
            Textbox: Custom Scores
            Textbox: Custom Polls
            Pulldown: Name Panel Position
            Pulldown: Name Panel Style
            Pulldown: Name Panel Message
            Checkbox: Show Supply
            Checkbox: Show Scores
            Checkbox: Show Polls
            Checkbox: Show Betting Amounts
            Checkbox: Show Tooltips
            Checkbox: Rotate Logos
        Kick Player
            Button: X Kick Player Dialog
            Button: Kick Player
            Pulldown: Kick Player
            Button: Confirm Kick Player
            Refresh Kick Player Dialog for Player
            Create Kick Player Dialog
        Button: X Options Dialog
        Button: X Personal Options Dialog
        Button: Personal Options
        Button: Votable Options
        Button: Customize Name Panel
        ------- Votable Options
        Pulldown: Match Mode
        Pulldown: Player Select
        Pulldown: Color Scheme
        Checkbox: Enforce Competitive Spawns
        Checkbox: Disable Bling
        Checkbox: Disable Zoom
        Checkbox: Allow Chat
        Checkbox: Allow Cooperative
        Checkbox: End Match
        ------- Personal Options
        Checkbox: Hide Name Panel
        Checkbox: Show Floating Icons
        Checkbox: Advanced Resource Panel
        Slider: Smart Cam idle time
        Pulldown: Auto Cam Style
        ------- Comment
        Buttons: Option Tabs
        ------- Comment
        Create Option Tabs Dialog
        Create Votable Options Dialog
        Create Personal Options Dialog
        ------- Comment
        Hide All Option Dialogs for Player
        getMajorityOfVoters
        getTwoThirdsMajorityOfVoters
        getMajorityOfObserverVoters
        Refresh All Voting
        Refresh Voting Match Mode
        Refresh Voting Player Select Mode
        Refresh Voting Color Scheme
        Refresh Voting Spawning
        Refresh Voting Cooperative Control
        Refresh Voting Bling
        Refresh Voting Zooming
        Refresh Voting Allow Chat
        Refresh Voting End Match
    Quick Panel
        Button: Structures
        Button: Research
        Button: Resources
        Button: Supplies
        Button: Killed
        Button: APM
        Create Quick Dialog
        Refresh All Quick Dialogs
        Refresh Quick Dialog for Player
        Update TOW Module
    Research Panel
        TEST: research
        TEST: research cancel
        Create Research Panels
        Destroy Research Panels
        Update Research Icon
        Refresh All Research Panels
        Reset Research Panels
        Show Research Dialogs for Player
        Hide Research Dialogs for Player
        makeResearchTooltip
        Handle Research Event
        Clear All Research Memory
    Resource Panels
        Periodic: Refresh Stats
        Button: Toggle Simple Stats
        Toggle Simple Stats for Player
        Reset Resource Panels for Faceoff
        Create Blizzard Resource Dialog
        Create Advanced Resource Dialog
        Refresh Resource Panels
    Resource Trading
        Timer Expire
        Button: X Resource Trading
        Button: Launch Resource Trading
        Button: Send Resources
        Button: More Minerals
        Button: Less Minerals
        Button: More Vespene
        Button: Less Vespene
        Refresh Resource Trading Dialog for Player
        Create Resource Trading Dialog
    Store
        Purchase Confirmation
            Button: Confirm Purchase
            Button: Decline Purchase
            Create Purchase Confirmation Dialog
        DEVETST: Morechips
        ------- Comment
        Pulldown: Aisle
        Button: X Store Dialog
        Button: Cash My Chips
        Button: Purchase Item
        Initialize Store
        Create Store Dialog
        Refresh Store Dialog for Player
        Purchase Item for Player
        Cash Chips for Player
    Team Restrictions
        Button: X Team Restriction Dialog
        Checkbox: Check All
        Checkboxes: Player Restrictions
        Create Team Restriction Dialog
    Sketch Pad
        Mouse Move: Pen
        Mouse Down: Engage Pen
        Mouse Up: Disengage Pen
        Use Pen
        ------- Comment
        Create Sketch Dialog
        Engage Sketchpad for Player
        Disengage Sketchpad for Player
        Erase Pen Trail for Player
        Refresh Sketchpad Townhall Icons
        Hide Townhall Icons for Player
    Structure Panel
        makeStructureTooltip
        TEST: structures
        Create Structure Panels
        Update Structure Icon
        Refresh All Structure Panels
        Reset Structure Panels
        Destroy Structure Panels
        Show Structure Dialogs for Player
        Hide Structure Dialogs for Player
        Refresh Structure Counts for Player Unit Type
        Clear All Structure Memory
    Surrender Dialog
        Button: Surrender Decline
        Button: Surrender Confirm
        Create Surrender Dialog
Auto Cam
    ------- Level 1: Scout
    Scouting
    ------- Level 2: Structures
    Builds Structure
    Enhances Structure
    Cancels Structure
    ------- Level 3: Army Unit Move/Attacks
    Unit Ordered to Move/Attack
    ------- Level 4: Any unit is attacked
    Unit is Attacked
    ------- Level 5: Building razed
    Building Razed
    ------- Player Following
    Player 1 Camera Moves
    Player 2 Camera Moves
    Player 3 Camera Moves
    Player 4 Camera Moves
    Player 5 Camera Moves
    Player 6 Camera Moves
    Player 7 Camera Moves
    Player 8 Camera Moves
    Player 9 Camera Moves
    Player 10 Camera Moves
    Player 11 Camera Moves
    Player 12 Camera Moves
    Player 13 Camera Moves
    Player 14 Camera Moves
    ------- Comment
    Periodic: Auto Cam Rotation
    Initialize Slow Rotation for Player
    ------- Comment
    Cycle Idle Cam
    Refresh Auto Cams
    Handle Cam Event
Faceoff
    Pranks
        Run Prank from Player
        Clear All Prank Entities
        ------- Comment
        Prank: All Work and No Play
        Prank: Swap Player's Faceoff Unit to Worker
        ------- Comment
        Prank: Zergling Party
        Timer: Zergling Cheer
        ------- Comment
        Prank: Confused SCVs
        ------- Comment
        Prank: Mothership Vortex
        ------- Comment
        Prank: Bow Before Mengsk
        ------- Comment
        Prank: Forest Clearing
        ------- Comment
        Prank: Run Zergling Run
        ------- Comment
        Prank: Drink Me
        Prank: Make Player's Faceoff Unit Little
        Prank: Make Player's Faceoff Unit Normal
        ------- Comment
        Prank: Funhouse
        Prank: Make Player's Faceoff Unit Stretch
        ------- Comment
        Prank: Zen Garden
        ------- Comment
        Prank: Game Show
        ------- Comment
        Prank: Crystal Altar
        ------- Comment
    Marine: Stimpack
    Thor: Strike Cannons
    Stalker: Blink
    Sentry: Guardian Shield / Hallucination
    Baneling: Annihilation
    Infestor: Infested Terran / Fungal / Neural Parasite
    Ghost: Cloak
    Medivac: Drop Marines
    Phoenix: Lift
    Oracle: Attack
    High Templar: Psionic Storm
    Probe: Warp In
    ------- Comment
    Periodic: Rotate Camera
    Periodic: Move Teams in Circle
    Periodic: Match Countdown
    Idle Units: Face Center of Faceoff
    Timer: Match Countdown
    Timer: Start Minibattle
    Faceoff Transition Start
    ------- Comment
    DEVTEST: Create dummy third player
    Create Faceoff
    Initialize Faceoff
    Create Dummy Players
    Calculate Faceoff Points
    Start Minibattle
    Initialize Weather
    Initialize Faceoff Camera
    Refresh Faceoff
    Create Faceoff Decals
    Move Faceoff Decals
    Destroy Faceoff Decals
    Show Loading Screen
Match
    Reveal Player Mechanic
        Create Reveal Countdown Dialog
        Refresh Reveal State for Player
        Periodic: Reveal Countdown
        Timer: Reveal Player
        countPlayerTownhalls
    Control Groups
        Control Group: Control-0
        Control Group: Shift-0
        Control Group: Alt-0
        Control Group: Control-1
        Control Group: Shift-1
        Control Group: Alt-1
        Control Group: Control-2
        Control Group: Shift-2
        Control Group: Alt-2
        Control Group: Control-3
        Control Group: Shift-3
        Control Group: Alt-3
        Control Group: Control-4
        Control Group: Shift-4
        Control Group: Alt-4
        Control Group: Control-5
        Control Group: Shift-5
        Control Group: Alt-5
        Control Group: Control-6
        Control Group: Shift-6
        Control Group: Alt-6
        Control Group: Control-7
        Control Group: Shift-7
        Control Group: Alt-7
        Control Group: Control-8
        Control Group: Shift-8
        Control Group: Alt-8
        Control Group: Control-9
        Control Group: Shift-9
        Control Group: Alt-9
        ------- Comment
        Observer Selects a Unit of Player He's Observing
        ------- Comment
        Sync Control Groups from Player to Player
        Clear Control Groups for Player
    Triggers
        Periodic: Refresh Game Clock(s)
        ------- Match Log Events
        Structure Started
        Structure Completed
        Structure Canceled
        Unit Creation
        ------- Comment
        StructEnhance: Orbital Command Start
        StructEnhance: Orbital Command Cancel
        StructEnhance: Orbital Command Complete
        ------- Comment
        StructEnhance: Planetary Fortoress Start
        StructEnhance: Planetary Fortress Cancel
        StructEnhance: Planetary Fortress Complete
        ------- Comment
        StructEnhance: Warp Gate Start
        StructEnhance: Warp Gate Cancel
        StructEnhance: Warp Gate Complete
        ------- Comment
        StructEnhance: Warp Gateway Start
        StructEnhance: Warp Gateway Cancel
        StructEnhance: Warp Gateway Complete
        ------- Comment
        StructEnhance: Lair Start
        StructEnhance: Lair Cancel
        StructEnhance: Lair Complete
        ------- Comment
        StructEnhance: Hive Start
        StructEnhance: Hive Cancel
        StructEnhance: Hive Complete
        ------- Comment
        StructEnhance: Greater Spire Start
        StructEnhance: Greater Spire Cancel
        StructEnhance: Greater Spire Complete
        ------- Comment
        Morph: Baneling
        Morph: Lurker
        Morph: Overseer
        Morph: Archon
        Morph: Brood Lord
        ------- Comment
        Research Upgrade Started
        Research Upgrade Completed
        Research Upgrade Cancelled
        ------- Comment
        Unit Death
        ------- Comment
        Check for Defeat
        ------- Comment
        Initialize Match
        ------- Comment
        Apply applyVision
    Initialize Match
    Clear All Units / Exploration
    Remove Player from Match
    Assign Start Positions
    Sort Teams by Start Position
    Initialize Map Objects/Resources
    Unshare Vision of Lowered Depots
    Initialize Match for Player
    Prepare Starting Units for All Players
    Create Starting Units for All Players
    Prepare Staring Units for Player
    Create Starting Units for Player
    Initialize Match for Observer
    DEVETST: Disable shared control
    Set Team Alliances / Vision
    ------- Commit players by saving banks as if losing
    Commit Match Players
    Save Player Banks As If Losing
Victory Screen
    Check for Match End / Assign Winners
    Run Victory Screen
    Stop Victory Sound
    Cleanup after Victory/Match
Main Initialization
