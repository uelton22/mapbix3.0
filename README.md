# mapbix3.0
Sistema de monitoramento de backbone fibra ótica ou wireless


Notas da nova versão Mapbix 3.0

Backend
	Nodejs
	Zabbix-Promise
	Socket.io
	Express
	Cors
	dotenv
	bcrypt
	jsonwebtoken
	mongoose
	lodash
Frontend
	Reactjs
	leaflet
	react-leaflet
	socket.io-client
	axios
	Material UI
	highcharts

Funcionalidades

	Pop
		Adicionar
		Editar
		Excluir
		Pesquisar
		Adicionar obsevação na rota ex: custo, portas desligadas
		Ao adicionar observação adicionado circulo ao redor do pop

	Rota
		Adicionar
		Editar
		Excluir
		Pesquisar
		Monitoramento ICMP Ping, Status Interfaces, Consumo das interfaces download e upload e speed das portas.
		Visualizar Consumo de downlaod e upload no grafico
		Rota altera a cor para status de DOWN, UP E ALTO CONSUMO
		Alarme sonoro nas alteração dos status
		Mensagem de alerta com informações da rota

	Usuário
		Adicionar
		Editar
		Excluir
		Restrição de usuário sem privilegios de administrador
