# TgBot-monitoring-the-status-of-sites
telegram-бот для мониторинга состояния сайтов на языке Go. Бот обходит список URL-ов, который указан в конфиге, и, если этот URL не открывается или отдает не HTTP/200, то пишет о падении в определенный чат.
команды для бота :
    /site_list - покажет список сайтов в мониторинге и их статусы (про статусы ниже)
	/site_add [url] - добавит url в список мониторинга
	/site_del [url] - удалит url из списка мониторинга
	/help - отобразить это сообщение
	
	