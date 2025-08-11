-- Configurações
local basePosition = Vector3.new(0, 10, 0) -- Coordenadas da base
local superJumpPower = 150 -- Pulo padrão é ~50
local superSpeed = 50 -- Velocidade padrão é 16
local invencivel = true

-- Objetos importantes
local player = game.Players.LocalPlayer
local char = player.Character or player.CharacterAdded:Wait()
local humanoid = char:WaitForChild("Humanoid")

-- Função: Teleporte para a base
local function teleporteBase()
	char:MoveTo(basePosition)
end

-- Função: Ativar super pulo e super velocidade
local function
