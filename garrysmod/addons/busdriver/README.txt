Example of bus driver job:

TEAM_BUS = DarkRP.createJob("Bus Driver", {
	color = Color(80, 45, 0, 255),
	model = "models/player/hostage/hostage_04.mdl",
	description = [[It's your duty to transport citizens around the city]],
	weapons = {},
	command = "busdriver",
	max = 2,
	salary = 60,
	admin = 0,
	vote = false,
	hasLicense = false,
})

Example of bus driver vehicle:

DarkRP.createVehicle({
	
	name = "sw_bus",
	
	model = "models/sligwolf/bus/bus.mdl",
	
	price = 1000,

	allowed = {TEAM_BUS},

	label = "Single Bus",

})

If you want to change any config settings then edit:
lua/entities/ticket_machine/shared.lua



https://github.com/Adzter/BusDriver
