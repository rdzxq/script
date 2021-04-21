-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local title = Instance.new("TextLabel")
local Unanchored = Instance.new("TextButton")
local Moveunanchored = Instance.new("TextButton")
local RagdollEngine = Instance.new("TextButton")
local Seeprivatechats = Instance.new("TextButton")
local Dexv4 = Instance.new("TextButton")
local DarkHub = Instance.new("TextButton")
local dickR6 = Instance.new("TextButton")
local infyield = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.BorderColor3 = Color3.fromRGB(255, 255, 255)
main.Position = UDim2.new(0.257467985, 0, 0.273178816, 0)
main.Size = UDim2.new(0, 259, 0, 161)
main.Active = true
main.Draggable = true

title.Name = "title"
title.Parent = main
title.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
title.BorderColor3 = Color3.fromRGB(255, 255, 255)
title.Size = UDim2.new(0, 259, 0, 21)
title.Font = Enum.Font.PermanentMarker
title.Text = "SHITTY GUI BY RDZ"
title.TextColor3 = Color3.fromRGB(47, 255, 95)
title.TextSize = 14.000

Unanchored.Name = "Unanchored"
Unanchored.Parent = main
Unanchored.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Unanchored.BorderColor3 = Color3.fromRGB(255, 255, 255)
Unanchored.Position = UDim2.new(0, 0, 0.130434781, 0)
Unanchored.Size = UDim2.new(0, 109, 0, 27)
Unanchored.Font = Enum.Font.DenkOne
Unanchored.Text = "Unachored"
Unanchored.TextColor3 = Color3.fromRGB(90, 255, 20)
Unanchored.TextSize = 14.000
Unanchored.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/WkZwcGjf", true))()
end)

Moveunanchored.Name = "Move unanchored"
Moveunanchored.Parent = main
Moveunanchored.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Moveunanchored.BorderColor3 = Color3.fromRGB(255, 255, 255)
Moveunanchored.Position = UDim2.new(0.579150558, 0, 0.130434781, 0)
Moveunanchored.Size = UDim2.new(0, 109, 0, 27)
Moveunanchored.Font = Enum.Font.DenkOne
Moveunanchored.Text = "move unanchored"
Moveunanchored.TextColor3 = Color3.fromRGB(90, 255, 20)
Moveunanchored.TextSize = 14.000
Moveunanchored.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/EmTvZeVr", true))()
end)

RagdollEngine.Name = "Ragdoll Engine"
RagdollEngine.Parent = main
RagdollEngine.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RagdollEngine.BorderColor3 = Color3.fromRGB(255, 255, 255)
RagdollEngine.Position = UDim2.new(0, 0, 0.347826093, 0)
RagdollEngine.Size = UDim2.new(0, 109, 0, 28)
RagdollEngine.Font = Enum.Font.DenkOne
RagdollEngine.Text = "Ragdoll engine"
RagdollEngine.TextColor3 = Color3.fromRGB(90, 255, 20)
RagdollEngine.TextSize = 14.000
RagdollEngine.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Scripts/master/Vynixius%20Ragdoll%20Engine"))()
end)

Seeprivatechats.Name = "See private chats"
Seeprivatechats.Parent = main
Seeprivatechats.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Seeprivatechats.BorderColor3 = Color3.fromRGB(255, 255, 255)
Seeprivatechats.Position = UDim2.new(0, 0, 0.788819849, 0)
Seeprivatechats.Size = UDim2.new(0, 109, 0, 23)
Seeprivatechats.Font = Enum.Font.DenkOne
Seeprivatechats.Text = "See private chats"
Seeprivatechats.TextColor3 = Color3.fromRGB(90, 255, 20)
Seeprivatechats.TextSize = 14.000
Seeprivatechats.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/iAU0w3NN", true))()
end)

Dexv4.Name = "Dex v4"
Dexv4.Parent = main
Dexv4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dexv4.BorderColor3 = Color3.fromRGB(255, 255, 255)
Dexv4.Position = UDim2.new(0, 0, 0.571428597, 0)
Dexv4.Size = UDim2.new(0, 109, 0, 24)
Dexv4.Font = Enum.Font.DenkOne
Dexv4.Text = "Dev v4"
Dexv4.TextColor3 = Color3.fromRGB(90, 255, 20)
Dexv4.TextSize = 14.000
Dexv4.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://418957341")[1].Source)()
end)

DarkHub.Name = "Dark Hub"
DarkHub.Parent = main
DarkHub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
DarkHub.BorderColor3 = Color3.fromRGB(255, 255, 255)
DarkHub.Position = UDim2.new(0.579150558, 0, 0.347826093, 0)
DarkHub.Size = UDim2.new(0, 109, 0, 28)
DarkHub.Font = Enum.Font.DenkOne
DarkHub.Text = "Dark hub"
DarkHub.TextColor3 = Color3.fromRGB(90, 255, 20)
DarkHub.TextSize = 14.000
DarkHub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://darkhub.xyz/remote-script.lua'), true))()
end)

dickR6.Name = "dick R6"
dickR6.Parent = main
dickR6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
dickR6.BorderColor3 = Color3.fromRGB(255, 255, 255)
dickR6.Position = UDim2.new(0.579150498, 0, 0.571428597, 0)
dickR6.Size = UDim2.new(0, 109, 0, 24)
dickR6.Font = Enum.Font.DenkOne
dickR6.Text = "FE dick (R6)"
dickR6.TextColor3 = Color3.fromRGB(90, 255, 20)
dickR6.TextSize = 14.000
dickR6.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/F4trNP96", true))()
end)

infyield.Name = "inf yield"
infyield.Parent = main
infyield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
infyield.BorderColor3 = Color3.fromRGB(255, 255, 255)
infyield.Position = UDim2.new(0.579150558, 0, 0.776397526, 0)
infyield.Size = UDim2.new(0, 109, 0, 25)
infyield.Font = Enum.Font.DenkOne
infyield.Text = "Inf yield"
infyield.TextColor3 = Color3.fromRGB(90, 255, 20)
infyield.TextSize = 14.000
infyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
