local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Soul Hub", "DarkTheme")
local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("Tween")
Section:NewButton("Start island", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(779.757812, 5.80257845, 1428.88416, 0.00445016194, 6.87092978e-08, -0.999990106, 5.70701921e-08, 1, 6.89639563e-08, 0.999990106, -5.73765284e-08, 0.00445016194)}):Play()
end)
Section:NewButton("Middle Town", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(-659.789978, 7.87804747, 1574.92932, 0.205921501, -1.74688584e-08, -0.978568494, 2.03769464e-08, 1, -1.35634917e-08, 0.978568494, -1.71472223e-08, 0.205921501)}):Play()
end)
Section:NewButton("Jungle", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-1407.05139, 22.8778763, 357.044128, 0.925870478, 8.67817818e-08, 0.377841026, -5.84823034e-08, 1, -8.63716281e-08, -0.377841026, 5.78719295e-08, 0.925870478)}):Play()
end)
Section:NewButton("Sky1", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-4849.29688, 717.722107, -2631.96558, -0.0842466578, 9.08218496e-08, 0.996444941, -3.58900536e-08, 1, -9.41802867e-08, -0.996444941, -4.36968364e-08, -0.0842466578)}):Play()
end)
Section:NewButton("Sky2", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(45, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-7878.96729, 5545.60742, -369.694153, 0.47236082, -1.69267689e-09, -0.881405294, 2.65808064e-09, 1, -4.95916863e-10, 0.881405294, -2.10859463e-09, 0.47236082)}):Play()
end)
Section:NewButton("Prison", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(4879.5957, 5.67797613, 735.525024, -0.071622923, -5.3517013e-08, -0.997431755, -9.45784251e-08, 1, -4.68633843e-08, 0.997431755, 9.09790359e-08, -0.071622923)}):Play()
end)
Section:NewButton("Pirates village", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(-1120.73779, 4.77785349, 3818.38574, -0.968537807, 3.37889855e-10, 0.248866558, 3.44554962e-09, 1, 1.20516601e-08, -0.248866558, 1.25299708e-08, -0.968537807)}):Play()
end)
Section:NewButton("Marine Base", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-2520.79346, 6.88147211, 2039.27588, 0.0922097862, -2.21243042e-08, -0.995739579, -7.54918759e-08, 1, -2.92098399e-08, 0.995739579, 7.78636888e-08, 0.0922097862)}):Play()
end)
Section:NewButton("MarineFord", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(-4816.25244, 20.6776543, 4362.61621, 0.9099406, 5.93734448e-08, -0.414738566, -5.52939525e-08, 1, 2.18432348e-08, 0.414738566, 3.0564884e-09, 0.9099406)}):Play()
end)
Section:NewButton("Magma island", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-5229.09229, 8.6161356, 8440.7041, 0.291255295, -1.01126588e-07, -0.95664537, -3.96240019e-08, 1, -1.17773304e-07, 0.95664537, 7.22082163e-08, 0.291255295)}):Play()
end)
Section:NewButton("Desert", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(890.93219, 3.42753291, 4102.61816, -0.852948904, 8.99797286e-08, -0.521994412, 1.06236641e-07, 1, -1.21591581e-09, 0.521994412, -5.64920484e-08, -0.852948904)}):Play()
end)
Section:NewButton("Fountain city", "ButtonInfo", function()
local TweenService = game:GetService("TweenService") 
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),  
{CFrame = CFrame.new(5043.5249, 1.52707756, 4050.91919, -0.59180218, -5.46830279e-08, -0.806083202, -6.47269403e-08, 1, -2.03173602e-08, 0.806083202, 4.01514413e-08, -0.59180218)}):Play()
end)
Section:NewButton("Snow village", "ButtonInfo", function()
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(30, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(1122.62158, 7.32920694, -1177.59998, -0.870202422, -5.59631346e-08, 0.492694378, -4.86958989e-08, 1, 2.75786505e-08, -0.492694378, 6.81332508e-12, -0.870202422)}):Play()
end)
