repita task.wait() até game:IsLoaded()
Mesa local = {7449423635,2753915549,4442272183}
jogo:GetService("StarterGui"):SetCore("EnviarNotificação",{
	Título = "Ler", -- Obrigatório
	Texto = "Vai ser fode seu filha da puta~", -- Obrigatório
	Ícone = "rbxassetid://9709149431", -- Opcional
	Duração = 1000
})
se table.find(TablePlace,game.PlaceId) então
    getgenv().Jogo = "BF"
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/BF-New.lua"))()
outro
    game.Players.LocalPlayer:Kick("não suportado")
fim
