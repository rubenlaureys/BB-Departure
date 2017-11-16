# BB-Departure

The Departure module is one of the default modules of the MagicMirror. It is a simple way to display a static text on the mirror.

Using the module

To use this module, add it to the modules array in the config/config.js file:

modules: [
	{
		module: "Departure",
		
		position: "bottom_bar",	// This can be any of the regions.
		
		config: {
		
		// See 'Configuration options' for more information.
		
		text: "Hello world!"
		
		}
	}
]
