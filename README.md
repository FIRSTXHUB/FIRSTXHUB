local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/NiceBBMBThai12/NBTScript/main/UI-Library-Robloxx"))()
local window = library:Win()
local tap1 = window:addtap("Tab1")
local tap2 = window:addtap("Tab2")
local page1 = tap1:addpage()
local page2 = tap1:addpage()
local page3 = tap1:addpage()
local page4 = tap1:addpage()
page1:Ti("Teleport X Die \nคำเตือนถ้ามีของสำคัญอย่าใช้\tเป็นการรีตัว!")

page1:Button("คาเฟ่", function(value)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-361.497009, 149.246094, 250.991974, 0.997700334, 0, 0.067779839, -0, 1.00000012, -0, -0.067779839, 0, 0.997700334)
	wait(1)
	local A_1 = "SetSpawnPoint"
	local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
	Event:InvokeServer(A_1)

end)

page1:Button("ป่าเขียว", function(value)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2219.93237, 72.344101, -2706.96094, 0.326738358, -4.67980499e-09, 0.945114851, 4.79308646e-08, 1, -1.16187433e-08, -0.945114851, 4.90964602e-08, 0.326738358)
	wait(1)
local A_1 = "SetSpawnPoint"
local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
Event:InvokeServer(A_1)

end)

page1:Button("พังค์ ฮาซาร์ด", function(value)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5528.87061, 73.9775925, -5234.93457, -0.426287115, -2.65395155e-08, 0.904587924, 5.45683996e-08, 1, 5.50541515e-08, -0.904587924, 7.28307938e-08, -0.426287115)
	wait(1)
local A_1 = "SetSpawnPoint"
local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
Event:InvokeServer(A_1)

end)

page1:Button("ดันลอว์", function(value)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5528.87061, 73.9775925, -5234.93457, -0.426287115, -2.65395155e-08, 0.904587924, 5.45683996e-08, 1, 5.50541515e-08, -0.904587924, 7.28307938e-08, -0.426287115)
	wait(1)
local A_1 = "SetSpawnPoint"
local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
Event:InvokeServer(A_1)
wait(4)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut,0,false,0),
{CFrame = CFrame.new(-5548.59619, 329.066284, -5924.06738, 0.0117531903, -6.99113256e-09, -0.999930918, 1.18904273e-08, 1, -6.85185553e-09, 0.999930918, -1.18090746e-08, 0.0117531903)}):Play()

end)

page1:Button("ดันทำผลตื่น", function(value)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5528.87061, 73.9775925, -5234.93457, -0.426287115, -2.65395155e-08, 0.904587924, 5.45683996e-08, 1, 5.50541515e-08, -0.904587924, 7.28307938e-08, -0.426287115)
	wait(1)
local A_1 = "SetSpawnPoint"
local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
Event:InvokeServer(A_1)
wait(4)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut,0,false,0),
{CFrame = CFrame.new(-6446.69775, 249.557114, -4503.72119, -0.535159349, -7.4700985e-08, 0.84475112, 7.29553218e-09, 1, 9.30513835e-08, -0.84475112, 5.59602249e-08, -0.535159349)}):Play()

end)


local getdrop = page1:DropDown("Name DropDown","Name",{"a","b","c"}, function(value)
    print(value)
end)

local getlable = page1:Label("Text Label")

local getslider = page1:Slder("Slider",1,100,8, function(value)
    print(value)
end)

page4:Ti("Title")

page4:Toggle("Toggle1",nil, function(value)
    print(value)
end)

page4:Button("Button1", function(value)
    print(value)
end)

page4:Button1("Button2", function(value)
    print(value)
end)

local getdrop = page4:DropDown("Name DropDown","Name",{"a","b","c"}, function(value)
    print(value)
end)

local getlable = page4:Label("Text Label")

local getslider = page4:Slder("Slider",1,100,8, function(value)
    print(value)
end)
