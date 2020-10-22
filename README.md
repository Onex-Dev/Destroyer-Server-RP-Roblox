
local SCRIPTRPROBLOX = Instance.new("ScreenGui")
local OpenFrame = Instance.new("Frame")
local Open = Instance.new("TextButton")
local Main = Instance.new("Frame")
local beautyA = Instance.new("Frame")
local Name = Instance.new("TextLabel")
local beautyB = Instance.new("Frame")
local Credit = Instance.new("TextLabel")
local AstonRP = Instance.new("TextButton")
local None = Instance.new("TextButton")
local None_2 = Instance.new("TextButton")
local LouquieRP = Instance.new("TextButton")
local Close = Instance.new("TextButton")

--Properties:

SCRIPTRPROBLOX.Name = "SCRIPT RP ROBLOX"
SCRIPTRPROBLOX.Parent = game.CoreGui
SCRIPTRPROBLOX.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

OpenFrame.Name = "OpenFrame"
OpenFrame.Parent = SCRIPTRPROBLOX
OpenFrame.Active = true
OpenFrame.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
OpenFrame.BorderSizePixel = 0
OpenFrame.Position = UDim2.new(0, 0, 0.444576919, 0)
OpenFrame.Size = UDim2.new(0, 102, 0, 34)

Open.Name = "Open"
Open.Parent = OpenFrame
Open.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.107843138, 0, 0.0916353092, 0)
Open.Size = UDim2.new(0, 80, 0, 26)
Open.Font = Enum.Font.Cartoon
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(255, 255, 255)
Open.TextSize = 30.000
Open.MouseButton1Down:connect(function()
	Main.Visible = true
	OpenFrame.Visible = false
end)

Main.Name = "Main"
Main.Parent = SCRIPTRPROBLOX
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.304243356, 0, 0.299165666, 0)
Main.Size = UDim2.new(0, 444, 0, 307)
Main.Visible = false
Main.Draggable = true 

beautyA.Name = "beautyA"
beautyA.Parent = Main
beautyA.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
beautyA.Size = UDim2.new(0, 444, 0, 36)

Name.Name = "Name"
Name.Parent = beautyA
Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name.BackgroundTransparency = 1.000
Name.BorderSizePixel = 0
Name.Position = UDim2.new(0.27477476, 0, 0, 0)
Name.Size = UDim2.new(0, 200, 0, 36)
Name.Font = Enum.Font.Cartoon
Name.Text = "Destroyer RP ROBLOX"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextSize = 20.000

beautyB.Name = "beautyB"
beautyB.Parent = Main
beautyB.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
beautyB.BorderColor3 = Color3.fromRGB(16, 16, 16)
beautyB.BorderSizePixel = 0
beautyB.Position = UDim2.new(0, 0, 0.876221478, 0)
beautyB.Size = UDim2.new(0, 444, 0, 38)

Credit.Name = "Credit"
Credit.Parent = beautyB
Credit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credit.BackgroundTransparency = 1.000
Credit.BorderSizePixel = 0
Credit.Position = UDim2.new(0.27477476, 0, 0, 0)
Credit.Size = UDim2.new(0, 200, 0, 36)
Credit.Font = Enum.Font.Cartoon
Credit.Text = "GUI Made By Onex#5860"
Credit.TextColor3 = Color3.fromRGB(255, 255, 255)
Credit.TextSize = 20.000

AstonRP.Name = "Aston RP"
AstonRP.Parent = Main
AstonRP.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
AstonRP.BorderSizePixel = 0
AstonRP.Position = UDim2.new(0.118900523, 0, 0.233316362, 0)
AstonRP.Size = UDim2.new(0, 119, 0, 50)
AstonRP.Font = Enum.Font.Cartoon
AstonRP.Text = "Aston RP"
AstonRP.TextColor3 = Color3.fromRGB(255, 255, 255)
AstonRP.TextSize = 25.000
AstonRP.MouseButton1Down:connect(function()
end)

None.Name = "None"
None.Parent = Main
None.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
None.BorderSizePixel = 0
None.Position = UDim2.new(0.598294854, 0, 0.568999827, 0)
None.Size = UDim2.new(0, 119, 0, 50)
None.Font = Enum.Font.Cartoon
None.Text = "None"
None.TextColor3 = Color3.fromRGB(255, 255, 255)
None.TextSize = 25.000

None_2.Name = "None"
None_2.Parent = Main
None_2.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
None_2.BorderSizePixel = 0
None_2.Position = UDim2.new(0.118900523, 0, 0.568999827, 0)
None_2.Size = UDim2.new(0, 119, 0, 50)
None_2.Font = Enum.Font.Cartoon
None_2.Text = "None"
None_2.TextColor3 = Color3.fromRGB(255, 255, 255)
None_2.TextSize = 25.000

LouquieRP.Name = "Louquie RP"
LouquieRP.Parent = Main
LouquieRP.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
LouquieRP.BorderSizePixel = 0
LouquieRP.Position = UDim2.new(0.598294854, 0, 0.233316362, 0)
LouquieRP.Size = UDim2.new(0, 119, 0, 50)
LouquieRP.Font = Enum.Font.Cartoon
LouquieRP.Text = "Louquie RP"
LouquieRP.TextColor3 = Color3.fromRGB(255, 255, 255)
LouquieRP.TextSize = 25.000
LouquieRP.MouseButton1Down:connect(function()
for i,v in pairs(game:GetDescendants()) do
if v:IsA("HooperBin") or v:IsA("Tool") then

v.Parent = game.Players.LocalPlayer.Backpack
end
end
end)

Close.Name = "Close"
Close.Parent = Main
Close.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.91228658, 0, -0.000508606434, 0)
Close.Size = UDim2.new(0, 38, 0, 36)
Close.Font = Enum.Font.Cartoon
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 20.000
Close.MouseButton1Down:connect(function()
	OpenFrame.Visible = true
	Main.Visible = false
end)
