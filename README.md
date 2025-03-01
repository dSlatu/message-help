# message-help
display a help message


 es_extended\client\functions.lua 

ESX.ShowHelpNotification = function(msg)
    exports.kosmos_interact:ShowHelpNotification({
		message = msg,
	})
end
