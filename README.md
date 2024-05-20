-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.251592368, 0, 0.334022045, 0)
Frame.Size = UDim2.new(0, 462, 0, 322)
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(18, 18, 18)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0, 0, -0.0186335407, 0)
TextLabel.Size = UDim2.new(0, 462, 0, 56)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "EXM2CHIN6 GUI"
TextLabel.TextColor3 = Color3.fromRGB(90, 0, 0)
TextLabel.TextSize = 57.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(18, 18, 18)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.826086938, 0)
TextLabel_2.Size = UDim2.new(0, 462, 0, 56)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Made By EXM2CHIN6"
TextLabel_2.TextColor3 = Color3.fromRGB(90, 0, 0)
TextLabel_2.TextSize = 37.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.019480519, 0, 0.189440995, 0)
TextButton.Size = UDim2.new(0, 167, 0, 41)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Inf Yield"
TextButton.TextColor3 = Color3.fromRGB(111, 0, 0)
TextButton.TextSize = 35.000
--PASTE THE SCRIPT BELOW UNDER THE BUTTON.


TextButton.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

