Script for FiveM: https://theadmiesters-fivem-resources.tebex.io/package/4799069

Video example: https://www.youtube.com/watch?v=9VX-R7xORow

Tutorial:

- Put the files , on Sounds folder inside of CarAudioExtensions folder Resourcer in your server

DsgFarts_Crackly.wav
DsgFarts_Snappy.wav 
DsgFarts_Snappy2.wav

- then edit the config.json file with the car that you want.

        },
	"golf7gti": {
		"shifterSounds": ["paddle1"],
		"shifterSoundVolume": 0.1,
		"shifterSoundsInteriorOnly": true,
		"upshiftSounds": ["DsgFarts_Snappy", "DsgFarts_Crackly", "DsgFarts_Snappy2"],
		"upshiftSoundInteriorVolume": 0.1,
		"upshiftSoundVolume": 0.4
	},