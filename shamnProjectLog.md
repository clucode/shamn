Smart Home AdHoc Mobile Network
SHAMN 

the plan
	central home assistant server (hosted on ras pi or pinephone?)
	distributed control nodes to run a variety of tasks (esp32 and rp2040 based in all likelyhood)
	hopefully field programmable?


concerns
	battery life for both nodes and server needs to be 8+ hrs before needing a swap
	components need to be designed for durability (think full contact larp)


server
	probably either a pi or the pinephone if i can get that working 



nodes
	each node should have battery and display for power and signal diagnostics
	check pinout for battery modboard, neopixel modboard, and investigate adding led display for battery and other status messages


node type ideas

 	NeoPixel controller
		this node should be small enough to fit in something like a set of wristbands or ankle braces (perhaps vambraces and shin guards to hide the battery and controller, 
		[MAKE SURE TO REINFORCE BATTERY CAGE]
		Parts Needed:
			esp32 - ordered
			battery contoller - ordered
			neopixel controller - ordered
			led display - in stock

	Biomonitor
		node should provide heart rate and blood pressure if possible (maybe integrate a pulse Oximeter?)
		eeg(brainwave scanner) - needs more research 
		sweat sensor?

		Parts needed:
			esp32
			battery controller
			led display

	
	Body Cam
		node should allow for video recording and clipping with a button press


	vr Trackers



	Servo control


