Hide In Trunk for FiveM (ox_inventory & ox_lib)

Hide In Trunk is a lightweight FiveM script that allows players to hide inside the trunk of a vehicle. Fully integrated with ox_inventory and ox_lib, this script supports NUI prompts and interactive targeting using ox_target.

Features

Hide in vehicle trunks: Players can enter and exit vehicle trunks.

Interactive prompts: Shows [E] prompt when hiding or exiting the trunk.

ox_target integration: Adds interaction target on the trunk for nearby players.

ox_lib notifications: Informative notifications for errors and actions.

Configurable language: All displayed texts are configurable in config.lua.

Animations: Play animations while hiding in the trunk.

Installation

Place the mytrunk folder into your resources folder.

Add ensure mytrunk to your server.cfg.

Make sure your server has ox_inventory and ox_lib installed.

Usage

Open trunk UI: Stand near a vehicle and press the trunk interaction key ([E]) via ox_target.

Exit trunk: Press [E] again to exit.

Optional command: /vleztdokufru – enter/exit trunk manually.

Configuration

Edit config.lua to change language texts:

Config.Language = {
    enter_trunk      = "Press [E] to exit trunk",
    trunk_busy       = "Someone is already in the trunk!",
    vehicle_locked   = "Vehicle is locked!",
    no_vehicle_near  = "No vehicle nearby!",
    me_enter_trunk   = "enters the trunk",
    me_exit_trunk    = "exits the trunk"
}

Dependencies

ox_inventory

ox_lib

ox_target

License

MIT License – free to use and modify for your server.
