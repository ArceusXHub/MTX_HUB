local WarpNero = Instance.new("ScreenGui")
local MODILEGUISOMEXHUB = Instance.new("TextButton")
local MODILEGUISOMEXHUBHUI = Instance.new("UICorner")
local MODILEMAGE = Instance.new("ImageLabel")
MODILEGUISOMEXHUBHUI.Name = "MODILEGUISOMEXHUBHUI"
MODILEGUISOMEXHUBHUI.Parent = MODILEGUISOMEXHUB
MODILEMAGE.Name = "MODILEMAGE"
MODILEMAGE.Parent = MODILEGUISOMEXHUB
MODILEMAGE.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MODILEMAGE.BackgroundTransparency = 1.000
MODILEMAGE.BorderSizePixel = 0
MODILEMAGE.Position = UDim2.new(0.234619886, 0, 0.239034846, 0)
MODILEMAGE.Size = UDim2.new(0, 30, 0, 30)
MODILEMAGE.Image = "rbxassetid://7743870134"
WarpNero.Name = "WarpNero"
WarpNero.Parent = game.CoreGui
WarpNero.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
MODILEGUISOMEXHUB.Name = "MODILEGUISOMEXHUB"
MODILEGUISOMEXHUB.Parent = WarpNero
MODILEGUISOMEXHUB.BackgroundColor3 = Color3.fromRGB(30,20,20)
MODILEGUISOMEXHUB.BackgroundTransparency = 0.1
MODILEGUISOMEXHUB.BorderSizePixel = 0
MODILEGUISOMEXHUB.Position = UDim2.new(0.120833337, 0, 0.0952890813, 0)
MODILEGUISOMEXHUB.Size = UDim2.new(0, 55, 0, 55)
MODILEGUISOMEXHUB.Font = Enum.Font.SourceSans
MODILEGUISOMEXHUB.Text = "MTX"
MODILEGUISOMEXHUB.TextColor3 = Color3.fromRGB(153, 51, 255)
MODILEGUISOMEXHUB.TextSize = 20.000
MODILEGUISOMEXHUB.Draggable = true
MODILEGUISOMEXHUB.MouseButton1Click:Connect(function()
Fluent.Window:Minimize()
end)
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()
loadstring(game:HttpGet("https://pastebin.com/raw/Ht5HtN4Z"))()
local notif = loadstring(game:HttpGet("https://raw.githubusercontent.com/C7Metatron/MetatronX-Project/main/NotificationUI"))()
function notify(MetatronX,title,description,icon,color)
  notif:message {
      Title = MetatronX.."<font color='rgb(".. color ..")'>"..title.."</font>",
      Description = description,
      Icon = icon
  }
end
notify("MTX Hub  ","  Initiating","Loading MTX Hub!",7743870134,"99, 0, 255")
local Window = Fluent:CreateWindow({
  Title = "🥋 MTX HUB | Blox Fruit V2 👑 ",
  SubTitle = "By> Metatron | Mark: MARK 🐻#8145",
  TabWidth = 160,
  Size = UDim2.fromOffset(500, 320),
  Acrylic = false, -- The blur may be detectable, setting this to false disables blur entirely
  Theme = "Darker",
  MinimizeKey = Enum.KeyCode.K -- Used when theres no MinimizeKeybind
})
local Tabs = {
  Farm = Window:AddTab({ Title = "Farm", Icon = "rbxassetid://10734975486" }),
  Items = Window:AddTab({ Title = "Item Quest", Icon = "rbxassetid://10723396107" }),
  SFarm = Window:AddTab({ Title = "Settings Farm", Icon = "rbxassetid://7743870134" }),
  Stats = Window:AddTab({ Title = "Stats", Icon = "rbxassetid://10734951847" }),
  RaceV4 = Window:AddTab({ Title = "RaceV4", Icon = "rbxassetid://10734897102" }),
  Raid = Window:AddTab({ Title = "Raid", Icon = "rbxassetid://10723345749" }),
  Shop = Window:AddTab({ Title = "Shop", Icon = "rbxassetid://10734952273" }),
  Warp = Window:AddTab({ Title = "Warp", Icon = "rbxassetid://10734886202" }),
  Misc = Window:AddTab({ Title = "Misc", Icon = "rbxassetid://10723376114" }),
  Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
--// FINAL
local Options = Fluent.Options

InterfaceManager:SetLibrary(Fluent)

SaveManager:SetIgnoreIndexes({})

InterfaceManager:SetFolder("FluentScriptHub")
SaveManager:SetFolder("MTX Hub")

InterfaceManager:BuildInterfaceSection(Tabs.Settings)

Window:SelectTab(1)
------// BLOX FRUIT
--// Sea world
World1 = false
World2 = false
World3 = false
local placeId = game.PlaceId
if placeId == 2753915549 then
World1 = true
elseif placeId == 4442272183 then
World2 = true
elseif placeId == 7449423635 then
World3 = true
end
--// Select Area
if World1 then
    AreaList = {
    'Jungle', 'Buggy', 'Desert', 'Snow', 'Marine', 'Sky', 'Prison', 'Colosseum', 'Magma', 'Fishman', 'Sky Island', 'Fountain'
    } elseif World2 then
    AreaList = {
    'Area 1', 'Area 2', 'Zombie', 'Marine', 'Snow Mountain', 'Ice fire', 'Ship', 'Frost', 'Forgotten'
    } elseif World3 then
    AreaList = {
    'Pirate Port', 'Amazon', 'Marine Tree', 'Deep Forest', 'Haunted Castle', 'Nut Island', 'Ice Cream Island', 'Cake Island', 'Choco Island', 'Candy Island'
    }
    end

-----//// Script
loadstring(game:HttpGet("https://raw.githubusercontent.com/C7Metatron/MetatronX-Project/main/Quests%20MTXHub"))()

Tabs.Farm:AddParagraph({
    Title = "Farm Options",
    Content = ""
})

local Dropdown = Tabs.Farm:AddDropdown("Select Weapon", {
    Title = "Select Weapon",
    Values = {"Melee", "Sword",},
    Multi = false,
    Default = 1,
})

Dropdown:SetValue("Melee")

Dropdown:OnChanged(function(value)
    _G.SelectWeapon = value
end)
task.spawn(function()
	while wait() do
		pcall(function()
			if _G.SelectWeapon == "Melee" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Melee" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							_G.SelectWeapon = v.Name
						end
					end
				end
			elseif _G.SelectWeapon == "Sword" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Sword" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							_G.SelectWeapon = v.Name
						end
					end
				end
			elseif _G.SelectWeapon == "Gun" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Gun" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							_G.SelectWeapon = v.Name
						end
					end
				end
			elseif _G.SelectWeapon == "Fruit" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Blox Fruit" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							_G.SelectWeapon = v.Name
						end
					end
				end
			end
		end)
	end
    end)

local Dropdown = Tabs.Farm:AddDropdown("Farm Mode", {
    Title = "Farm Mode",
    Values = {"Auto Farm Level", "No Quest", "Near Farm", "Fast Farm Lv.1-300"},
    Multi = false,
    Default = 1,
})

Dropdown:SetValue("Normal")

Dropdown:OnChanged(function(value)
    _G.FarmMode = value
    FarmMode = value
end)
spawn(function()
    while wait() do
        if FarmMode == "Auto Farm Level" and _G.AutoFarm then
            pcall(function()
                local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
                if not string.find(QuestTitle, NameMon) then
                    StartMagnet = false
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
                if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                    StartMagnet = false
                    CheckQuest()
                    if BypassTP then
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude > 1500 then
                    BTP(CFrameQuest)
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude < 1500 then
                    TP1(CFrameQuest)
                    end
                else
                    TP1(CFrameQuest)
                end
                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude <= 5 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LevelQuest)
                    end
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                    CheckQuest()
                    if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                                if v.Name == Mon then
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        repeat task.wait()
                                            EquipWeapon(_G.SelectWeapon)
                                            AutoHaki()                                            
                                            PosMon = v.HumanoidRootPart.CFrame
                                            TP1(v.HumanoidRootPart.CFrame * Pos)
                                            v.HumanoidRootPart.CanCollide = false
                                            v.Humanoid.WalkSpeed = 0
                                            v.Head.CanCollide = false
                                            v.HumanoidRootPart.Size = Vector3.new(70,70,70)
                                            StartMagnet = true
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        until not _G.AutoFarm or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                    else
                                        StartMagnet = false
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                    end
                                end
                            end
                        end
                    else
                        TP1(CFrameMon)
                        UnEquipWeapon(_G.SelectWeapon)
                        StartMagnet = false
                        if game:GetService("ReplicatedStorage"):FindFirstChild(Mon) then
                         TP1(game:GetService("ReplicatedStorage"):FindFirstChild(Mon).HumanoidRootPart.CFrame * CFrame.new(15,10,2))
                        end
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while wait() do
        if FarmMode == "No Quest" and _G.AutoFarm then
            pcall(function()
                local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
                if not string.find(QuestTitle, NameMon) then
                    StartMagnet = false
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
                if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                    StartMagnet = false
                    CheckQuest()
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LevelQuest)
                    if BypassTP then
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameMon.Position).Magnitude > 1500 then
                    BTP(CFrameMon)
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameMon.Position).Magnitude < 1500 then
                    TP1(CFrameMon)
                    end
                else
                    TP1(CFrameMon)
                end
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                    CheckQuest()
                    if game:GetService("Workspace").Enemies:FindFirstChild(Mon) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                                if v.Name == Mon then
                                    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                        repeat task.wait()
                                            EquipWeapon(_G.SelectWeapon)
                                            AutoHaki()                                            
                                            PosMon = v.HumanoidRootPart.CFrame
                                            TP1(v.HumanoidRootPart.CFrame * Pos)
                                            v.HumanoidRootPart.CanCollide = false
                                            v.Humanoid.WalkSpeed = 0
                                            v.Head.CanCollide = false
                                            v.HumanoidRootPart.Size = Vector3.new(70,70,70)
                                            StartMagnet = true
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        until not _G.AutoFarm or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                    else
                                        StartMagnet = false
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                    end
                                end
                            end
                        end
                    else
                        TP1(CFrameMon)
                        UnEquipWeapon(_G.SelectWeapon)
                        StartMagnet = false
                        if game:GetService("ReplicatedStorage"):FindFirstChild(Mon) then
                         TP1(game:GetService("ReplicatedStorage"):FindFirstChild(Mon).HumanoidRootPart.CFrame * CFrame.new(15,10,2))
                        end
                    end
                end
            end)
        end
    end
end)

spawn(function()
	while wait() do
		if FarmMode == "Near Farm" and _G.AutoFarm then
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name and v:FindFirstChild("Humanoid") then
			        if v.Humanoid.Health > 0 then
			            repeat wait()
			              EquipWeapon(_G.SelectWeapon)
			                if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
			                	local args = {
				                	[1] = "Buso"
			                	}
			                	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			               	end
			                topos(v.HumanoidRootPart.CFrame * Pos)
			                v.HumanoidRootPart.CanCollide = false
			                Fastattack = true
			                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
						    game:GetService("VirtualUser"):CaptureController()
				       	    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 672), game.Workspace.CurrentCamera.CFrame)
				       	    AutoFarmNearestMagnet = true
				       	    PosMon = v.HumanoidRootPart.CFrame
			            until not _G.AutoFarmNearest or not v.Parent or v.Humanoid.Health <= 0 
			            AutoFarmNearestMagnet = false
			            Fastattack = false
			        end
			    end
			end
		end
	end
    end)
    spawn(function()
        while wait() do
            if FarmMode == "Fast Farm Lv.1-300" and _G.AutoFarm then
                pcall(function()
                if game.Players.LocalPlayer.Data.Level.Value >= 10 then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Shanda" then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        AutoHaki()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.HumanoidRootPart.CanCollide = false
                                        v.Humanoid.WalkSpeed = 0
                                        StardMag = true
                                        FastMon = v.HumanoidRootPart.CFrame
                                        v.HumanoidRootPart.Size = Vector3.new(80,80,80)                             
                                        TP1(v.HumanoidRootPart.CFrame * Pos)
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                    until not _G.Farmfast or not v.Parent or v.Humanoid.Health <= 0
                                    StardMag = false
                                    TP1(CFrame.new(-7678.48974609375, 5566.40380859375, -497.2156066894531))
                                    UnEquipWeapon(_G.SelectWeapon)
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Shanda") then
                            TP1(game:GetService("ReplicatedStorage"):FindFirstChild("Shanda").HumanoidRootPart.CFrame * CFrame.new(5,10,2))
                        end
                    end
                end)
            end
        end
    end)
local Toggle = Tabs.Farm:AddToggle("Auto Farm Selected", {Title = "Auto Farm Selected", Default = false })

Toggle:OnChanged(function(value)
    _G.AutoFarm = value
    _G.RemoveHit = value
    StopTween(_G.AutoFarm)
end)
spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        if _G.RemoveHit == true then
            game:GetService("ReplicatedStorage").Effect.Container.LevelUp:Destroy()
            game:GetService("ReplicatedStorage").Util.Sound:Destroy()
            game:GetService("ReplicatedStorage").Util.Sound.Storage.Other:FindFirstChild("LevelUp_Proxy"):Destroy()
            game:GetService("ReplicatedStorage").Util.Sound.Storage.Other:FindFirstChild("LevelUp"):Destroy()
            game:GetService("ReplicatedStorage").Effect.Container.Respawn:Destroy()        
        end
    end)
end)

Tabs.Items:AddParagraph({
    Title = "Items Options",
    Content = ""
})
if World1 then
local Toggle = Tabs.Items:AddToggle("AutoSecondWorld", {Title = "Auto Second World", Default = false })

Toggle:OnChanged(function(scfunc)
    AutoSecondSea = scfunc
    CancelTween(AutoSecondSea)
    if game:GetService("Players").LocalPlayer.Data.Level.Value <= 700 then
        Notification( 'Your Level not required for unlock second world.')
    end
end)
spawn(function()
    while task.wait() do
        if AutoSecondSea then
            pcall(function()
                if game.Players.LocalPlayer.Data.Level.Value >= 700 then
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress").UsedKey == false then
                        if not game.Players.LocalPlayer.Backpack:FindFirstChild("Key") or game.Players.LocalPlayer.Character:FindFirstChild("Key") then
                            game:GetService("
