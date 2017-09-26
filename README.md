build firmware
	mos build --platform esp32

falsh the device
	mos flash
	
wifi password
	mos wifi SSID PASSWD

certificates and region for mqtt /!\ Need to create a group with the corect policy and add the user coresponding to 'API KEY' to that group, needs iot:CreateCertificatKey
	mos aws-iot-setup --aws-region eu-west-1 --aws-iot-policy mos-default
