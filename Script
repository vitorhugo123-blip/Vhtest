
local Players = game:GetService("Players")
local player = Players.LocalPlayer

local gui = Instance.new("ScreenGui")
gui.Name = "DandysWorldMenu"
gui.ResetOnSpawn = false
gui.Parent = player:WaitForChild("PlayerGui")

local frame = Instance.new("Frame")
frame.Size = UDim2.new(0, 280, 0, 400)
frame.Position = UDim2.new(0.5, -140, 0.5, -200)
frame.BackgroundColor3 = Color3.fromRGB(40, 28, 55)
frame.Active = true
frame.Draggable = true
frame.Parent = gui

local corner = Instance.new("UICorner")
corner.CornerRadius = UDim.new(0, 12)
corner.Parent = frame

local title = Instance.new("TextLabel")
title.Size = UDim2.new(1, 0, 0, 45)
title.BackgroundColor3 = Color3.fromRGB(125, 70, 180)
title.Text = "DANDY'S WORLD"
title.TextColor3 = Color3.new(1, 1, 1)
title.TextSize = 18
title.Font = Enum.Font.GothamBold
title.Parent = frame

local layout = Instance.new("UIListLayout")
layout.Padding = UDim.new(0, 7)
layout.HorizontalAlignment = Enum.HorizontalAlignment.Center
layout.SortOrder = Enum.SortOrder.LayoutOrder

local container = Instance.new("Frame")
container.Position = UDim2.new(0, 5, 0, 55)
container.Size = UDim2.new(1, -10, 1, -60)
container.BackgroundTransparency = 1
container.Parent = frame
layout.Parent = container

local function addButton(name, message)
    local b = Instance.new("TextButton")
    b.Size = UDim2.new(1, -8, 0, 38)
    b.BackgroundColor3 = Color3.fromRGB(85, 60, 110)
    b.TextColor3 = Color3.new(1, 1, 1)
    b.TextSize = 14
    b.Font = Enum.Font.GothamBold
    b.Text = name
    b.Parent = container

    local c = Instance.new("UICorner")
    c.CornerRadius = UDim.new(0, 8)
    c.Parent = b

    b.Activated:Connect(function()
        title.Text = message
    end)
end

addButton("✈ Fly", "Fly - demonstração")
addButton("🪙 Doar Ichor", "Ichor - demonstração")
addButton("❤️ Vida infinita", "Vida - demonstração")
addButton("🎭 Todos os Toons", "Toons - demonstração")
addButton("🩹 Gerar kit médico", "Itens - demonstração")
addButton("⚡ Extração: 100000", "Extração - demonstração")
addButton("🏃 Movimento: 10", "Movimento - demonstração") 
