source: https://bbs.nextthing.co/t/basic-guide-to-turning-chip-into-a-bluetooth-audio-receiver-audio-sink/2187?u=fordsfords

	Disable=Socket Enable=Media,Source,Sink,Gateway


where you should see items “AudioSink” and “AudioSource” in the UUID array:


Make the bluetooth module powered and discoverable with some eponymous commands:

	

	

	
	