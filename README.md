print(":)")
-- KzSystem(getgenv().PCMode)| คุณใช้ PC ใช้มั้ย ใช้เปลี่ยนเป็น true แต่ถ้าคุณใช้มือถือเปลี่ยนเป็น false
-- KzSystem(getgenv().UIHit)| ปิดการแสดงของ UI false ต้องการดูเปลี่ยนเป็น true
--getgenv().PCMode = false -- true / false 
--getgenv().UIHit = true -- true / false 

if _G.RunScriptRequest then
    game:GetService("Players").LocalPlayer:Kick("[ do not run repeatedly ]")
    wait(.5)
    game:GetService("Players").LocalPlayer:Kick("Code = 01/0100/1/0/00/1/2/00512")
else
    _G.RunScriptRequest = true
end

if getgenv().PCMode then

local function playtroll()
   local sound = Instance.new("Sound", game.workspace)
   sound.SoundId = "rbxassetid://626777433"
   sound.PlayOnRemove = true
   sound.Volume = 3
   sound:Destroy()
end

   local function gamekiller()
      while true do
          local fucku = 1
      end
   end
   
   game:GetService("RunService").RenderStepped:connect(function()
   for i,v in pairs(game.CoreGui:GetChildren()) do
      if v:FindFirstChild("PropertiesFrame") then
      if v:FindFirstChild("ExplorerPanel") then
      if v:FindFirstChild("SideMenu") then
          warn("DarkDex Detected") setclipboard("MrMaxNaJa#7138")
          Loop()
          playtroll()
          game.Players.LocalPlayer:kick("Anti Dark Dex")
          wait(.3)
          game:Shutdown()
           playtroll()
           wait(0.2)
          gamekiller()
      end
      end
      end
   end
   end)
   
game:GetService("RunService").RenderStepped:connect(function()
game:GetService("CoreGui").DevConsoleMaster.DevConsoleWindow:Destroy()
for i,v in pairs(game.CoreGui:GetChildren()) do
    if v:FindFirstChild("PropertiesFrame") then
        warn("DarkDex Detected") setclipboard("MrMaxNaJa#7138")
        Loop()
        game.Players.LocalPlayer:kick("Do not open DarkDex")
        wait(.3)
        game:Shutdown()
    end
 end
 end)
    spawn(function()
        game:GetService("RunService").RenderStepped:connect(function()
            game.CoreGui.ChildAdded:connect(function(p1)
                if p1:FindFirstChild("PropertiesFrame") or p1:FindFirstChild("ExplorerPanel") or p1:FindFirstChild("SaveInstance") then -- Dark Dex and
                    Loop()
                    playtroll()
                    print("?")
                    wait(.1)
                    while true do
                        setclipboard("MrMaxNaJa#7138")
                        wait(1)
                    end
                end
            end)
        end)
    end)

spawn(function()
    function Loop()
        pcall(function()
            game:GetService("RunService").RenderStepped:connect(function()
                killroblox = true
                print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")print("LoL")
            end)
        end)
    end
end)
spawn(function()
    if killroblox then
        pcall(function()
function SetupCharCollide(Char)
    CharParts = {}
    Char:WaitForChild("Head")
    for i, v in pairs(Char:GetChildren()) do
        if v:IsA("BasePart") then
            table.insert(CharParts, v)
        end
    end
end
if game.Players.LocalPlayer.Character then
    SetupCharCollide(game.Players.LocalPlayer.Character)
end
game.Players.LocalPlayer.CharacterAdded:connect(function(Ch)
    SetupCharCollide(Ch)
end)
end)
end
end)

end

if getgenv().UIHit == true then
    getgenv().UIMain = 500
elseif getgenv().UIHit == false then
    getgenv().UIMain = 380
else
    getgenv().UIMain = 500
end

getgenv().TextUI_I = "[+] Auto Farm Chest"
getgenv().TextUI_II = "[+] FastAttack [4]"
getgenv().TextUI_III = "Donate บาท 10 บาท ได้หมด"

    spawn(function()
        while task.wait() do
            pcall(function()
                getgenv().TextUI_IIII = "Wallet : 0990860437 | 18/5/2566" --28/4/2566
            end)
        end
    end)

local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/NaJaxHub/ser/main/UI-Kz"))()

loadstring(game:HttpGet("https://raw.githubusercontent.com/NaJaxHub/ser/main/Fastlol.lua"))()

--fast

print("UI Loading")
repeat wait()
until game:IsLoaded()
repeat wait()
until game:GetService("Players")
repeat wait()
until game:GetService("Players").LocalPlayer
repeat wait()
until game:GetService("Players").LocalPlayer.PlayerGui
repeat wait()
until game:GetService("ReplicatedStorage").Effect.Container

if not game:IsLoaded() then
	local IsLoaded = Instance.new("Message", workspace)
	IsLoaded.Text = "Wait Game Loading"
	game.Loaded:Wait()
	IsLoaded:Destroy()
	wait() --10
end
local Levelplayer = game.Players.LocalPlayer.Data.Level.Value
local UserPy = game.Players.LocalPlayer.Name
print("User " ..UserPy.."  ใช้งาน")
print(UserPy)

local url = "https://discord.com/api/webhooks/1097747887603069008/O0fx-kGw0Z_-u-XlHL2kxo6W8e_jbsoHlzjLFh5d9MLdNYfesHLIX27VMN3F93212BHt" -- ur webhook url
local data = {
	["username"] = 'NaJa Hub', -- Webhook name here
	["avatar_url"] = "https://cdn.discordapp.com/attachments/948603231192363058/1088077196997955704/Untitled-1_copy.png", -- ur discord logo url
	["embeds"] = {
		{
			["description"] = "เลเวล : " ..Levelplayer .."  User :" ..UserPy.. "   ใช้งานสคริป",
			["color"] = tonumber(0x0000ff), -- color id	
			--["timestamp"] = DateTime.now():ToIsoDate(),
		}
	},
}
local newdata = game:GetService("HttpService"):JSONEncode(data)
local headers = {["content-type"] = "application/json"}
request = http_request or request or HttpPost or syn.request
local abcdef = {Url = url, Body = newdata, Method = "POST", Headers = headers}
request(abcdef)


wait()
print("Settings Service")
_G.Settings = {
	Main = {
	    ["No Tween Quest"] = true,--
		["Auto Farm Level"] = false,--
		["Fast Auto Farm Level"] = false,--
		["Auto Observation"] = false,
        ["Auto Observation Hop"] = false,
        ["Auto Update Label Observation"] = true,
		--[Chest]
		["TweenChest[1]"] = false,
		["TweenChest[2]"] = false,
		["Auto Farm Chest [Main]"] = false,
		["TweenChest"] = false,
		--[Settings Chest]
		["Chest1"] = false,
		["Chest2"] = true,
		["Chest3"] = true,
		--[Mob Aura]
		["Distance Mob Aura"] = 1000, -- {Max : 5000} 
		["Mob Aura"] = false,
		--[World 1]
		["Auto New World"] = false,--
		["Auto Saber"] = false,--
		["Auto Pole"] = false,
		["Auto Pole Hop"] = false,
        ["AutoBuyLegendarySword"] = true,--
        ["AutoBuyEnchancementColour"] = true,--
		["Auto Buy Ablility"] = false,
		--[World 2]
		["Auto Third Sea"] = false,
		["Auto Factory"] = false,
		["Auto Farm law Sword"] = false,
		["Auto Factory Hop"] = false,
		["Auto Bartilo Quest"] = false,
		["Auto True Triple Katana"] = false,
		["Auto Rengoku"] = false,--
		["Auto Dark Coat"] = false,--
		["Auto Ectoplasm"] = false,--
		["Auto Swan Glasses"] = false,
		["Auto Buy Legendary Sword"] = false,
		["Auto Buy Enchanment Haki"] = false,
		--[World 3]
		["Auto Holy Torch"] = false,
		["Auto Farm Boss Hallow"] = false,--
		["Auto Buddy Swords"] = false,--
		["Auto Observation Haki v2"] = false,--
		["Auto Rainbow Haki"] = false,--
		["Auto Musketeer Hat"] = false,--
		["Auto Buddy Sword"] = false,--
		["Auto Farm Bone"] = false,--
		["Auto Cavander"] = false,
		["Auto Yama Sword"] = false,
		["Auto Tushita Sword"] = false,
		["Auto Serpent Bow"] = false,
		["Auto Dark Dagger"] = false,
		["Auto Cake Prince"] = false,
		["Auto Elite Hunter"] = false,
		["Auto Dough V2"] = false,
		["Auto Random Bone"] = false,
		--[For God Human]
		["Auto Fish Tail Sea 1"] = false,
		["Auto Fish Tail Sea 3"] = false,
		["Auto Magma Ore Sea 1"] = false,
		["Auto Magma Ore Sea 2"] = false,
		["Auto Mystic Droplet"] = false,
		["Auto Dragon Scales"] = false,
	},
	FightingStyle = {
		["Auto God Human"] = false,
		["Auto Superhuman"] = false,
		["Auto Electric Claw"] = false,
		["Auto Death Step"] = false,
		["Auto Fully Death Step"] = false,
		["Auto SharkMan Karate"] = false,
		["Auto Fully SharkMan Karate"] = false,
		["Auto Dragon Talon"] = false,
	},
	Boss = {
	    ["Select Boss"] = {},
	    ["Auto Boss Select"] = false,
	    ["Auto Farm All Boss"] = false,
	},
	Mastery = {
		["Select Multi Sword"] = {},
		["Farm Mastery SwordList"] = false,
		["Auto Farm Gun Mastery"] = false,
		["Auto Farm Fruit Mastery"] = false,
		--["Mob Health (%)"] = true,
		["Mob Health (%)"] = "15",
	},
	Configs = {
	    ["SelectTypeModeFarm"] = {"Mode : Rough"}, --,"Mode : Smooth"}, --"Mode : Rough,Smooth"
	    --["SelectTypeModeFarm"] = true
	    ["Fast Attack[1]"] = false,
	    ["Fast Attack[2]"] = true,
	    ["Fast Attack[3]"] = false,
	    ["Fast Attack[4]"] = false,
	    ["Fast Attack[5]"] = false,
	    ["Fast Attack[6]"] = false,
		["Double Quest"] = false,
		["Bring Monster"] = true,
		["Bypass TP"] = true,
		["Bypass"] = false,
		["Select Team"] = {
			"Pirate"
		}, --{Pirate,Marine}
		["Select Weapon"] = {},
		--[Misc Configs]
		["Auto Haki"] = true,
		["Distance Auto Farm"] = 20, --{Max : 50}
		["Camera Shaker"] = false,
		--[Skill Configs]
		["Skill Z"] = true,
		["Skill X"] = true,
		["Skill C"] = true,
		["Skill V"] = true,
		--[Mob Configs]
		["Show Hitbox"] = false,
		["Bring Mob"] = true,
		["Disabled Damage"] = false,
        ["Black|Screen"] = false,
        ["White|Screen"] = false,
	},
	Stat = {
		--[Auto Stats]
		["Enabled Auto Stats"] = false,
		["Auto Stats Kaitun"] = false,
		["MaxPoint Stats"] = true,
		["MaxPoint Stats Kaitun"] = true,
		["Select Stats"] = {"Melee"}, --{Max Stats,Melee,Defense,Sword,Devil Fruit,Gun}
		--["Point Select"] = 1, --{Recommended , Max : 9}
		--[Auto Redeem Code]
		["Enabled Auto Redeem Code"] = false,
		["Select Level Redeem Code"] = 1, --{Max : 2400}
	},
	Misc = {
		["No Soru Cooldown"] = false,
		["No Dash Cooldown"] = false,
		["Infinities Geppo"] = false,
		["Infinities Energy"] = false,
		["No Fog"] = false,
		["Wall-TP"] = false,
		["Fly"] = false,
		["Fly Speed"] = 1,
		--[Server]
		["Auto Rejoin"] = true,
	},
	Teleport = {
		["Teleport to Sea Beast"] = false,
	},
	Fruits = {
		["Auto Buy Random Fruits"] = false,
		["Auto Store Fruits"] = false,
		["Select Devil Fruits"] = {}, -- {"Bomb-Bomb","Spike-Spike","Chop-Chop","Spring-Spring","Kilo-Kilo","Spin-Spin","Kilo-Kilo","Spin-Spin","Bird: Falcon","Smoke-Smoke","Flame-Flame","Ice-Ice","Sand-Sand","Dark-Dark","Revive-Revive","Diamond-Diamond","Light-Light","Love-Love","Rubber-Rubber","Barrier-Barrier","Magma-Magma","Door-Door","Quake-Quake","Human-Human: Buddha","String-String","Bird-Bird: Phoenix","Rumble-Rumble","Paw-Paw","Gravity-Gravity","Dough-Dough","Shadow-Shadow","Venom-Venom","Control-Control","Soul-Soul","Dragon-Dragon"}
		["Auto Buy Devil Fruits Sniper"] = false,
	},
	Raids = {
		["Auto Raids"] = false,
		["Kill Aura"] = false,
		["Auto Awakened"] = false,
		["Auto Next Place"] = false,
		["Select Raids"] = {}, -- {"Flame","Ice","Quake","Light","Dark","String","Rumble","Magma","Human: Buddha","Sand","Bird: Phoenix","Dough"},
	},
	Combat = {
		["Fov Size"] = 200,
		["Show Fov"] = false,
		["Aimbot Skill"] = false,
	},
	HUD = {
		["FPS"] = 60,
		["LockFPS"] = false,
		["Boost FPS Windows"] = false,
		["White Screen"] = false,
	},
	ConfigsUI = {
		ColorUI = Color3.fromRGB(255, 0, 127), --{Color UI}
	}
}

_G.Kai = {
	["Check Swords"] = {
		["Enabled Check"] = true,
	},
	["Check Fighting Style"] = {
		["Enabled Check"] = true,
	},
	["Check Awakening Fruits"] = {
		["Enabled Check"] = true,
	},
	["Check Fruits"] = {
		["Enabled Check"] = true,
	},
}

function LoadSettings()
	if readfile and writefile and isfile and isfolder then
		if not isfolder("Kz Hub Free Scripts") then
			makefolder("Kz Hub Free Scripts")
		end
		if not isfolder("Kz Hub Free Scripts/Blox Fruits/") then
			makefolder("Kz Hub Free Scripts/Blox Fruits/")
		end
		if not isfile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json") then
			writefile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json", game:GetService("HttpService"):JSONEncode(_G.Settings))
		else
			local L_54_ = game:GetService("HttpService"):JSONDecode(readfile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json"))
			for L_55_forvar0, L_56_forvar1 in pairs(L_54_) do
				_G.Settings[L_55_forvar0] = L_56_forvar1
			end
		end
	else
		return warn("Status : Undetected Executor")
	end
end

function SaveSettings()
	if readfile and writefile and isfile and isfolder then
		if not isfile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json") then
			LoadSettings()
		else
			local L_57_ = game:GetService("HttpService"):JSONDecode(readfile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json"))
			local L_58_ = {}
			for L_59_forvar0, L_60_forvar1 in pairs(_G.Settings) do
				L_58_[L_59_forvar0] = L_60_forvar1
			end
			writefile("Kz Hub Free Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json", game:GetService("HttpService"):JSONEncode(L_58_))
		end
	else
		return warn("Status : Undetected Executor")
	end
end

LoadSettings()

print("Team..")
repeat
	wait()
	if game.Players.LocalPlayer.Team == nil and game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Visible == true then
		if _G.Settings.Configs["Select Team"] == "Pirate" then
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Position = UDim2.new(9999, 9999, 9999, 9999)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Size = UDim2.new(0, 10000, 0, 10000)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Position = UDim2.new(- 4, 0, - 5, 0)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			wait(.1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, true, game, 1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, false, game, 1)
		elseif _G.Settings.Configs["Select Team"] == "Marine" then
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Size = UDim2.new(0, 10000, 0, 10000)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Position = UDim2.new(9999, 9999, 9999, 9999)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Position = UDim2.new(- 4, 0, - 5, 0)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			wait(.1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, true, game, 1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, false, game, 1)
		else
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Position = UDim2.new(9999, 9999, 9999, 9999)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Size = UDim2.new(0, 10000, 0, 10000)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Position = UDim2.new(- 4, 0, - 5, 0)
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.BackgroundTransparency = 1
			wait(.1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, true, game, 1)
			game:service"VirtualInputManager":SendMouseButtonEvent(500, 500, 0, false, game, 1)
		end
	end
until game.Players.LocalPlayer.Team ~= nil and game:IsLoaded()

-- [Place Id Check]
local PlaceId = game.PlaceId
if PlaceId == 2753915549 then
	World1 = true;
elseif PlaceId == 4442272183 then
	World2 = true;
elseif PlaceId == 7449423635 then
	World3 = true;
else
    game:GetService("Players").LocalPlayer:Kick("รันได้แค่ BF")
    print("รันได้แค่ BF")
    wait(1)
    game.Players.LocalPlayer:kick("(/00/210/5815//151/5/151/51/15)")
    wait(1.5)
    game:Shutdown()
    kickcash("//a/a//a//a//a///a///s///s//s//d/a//jsdfjghlkfdhgjcxbzvn//0001/01")
end

-- [Functions Equip Weapon]
function EquipWeapon(L_62_arg0)
	pcall(function()
		if game.Players.LocalPlayer.Backpack:FindFirstChild(L_62_arg0) then 
			local L_63_ = game.Players.LocalPlayer.Backpack:FindFirstChild(L_62_arg0) 
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(L_63_) 
		end
	end)
end

-- [Body Gyro]

spawn(function()
	game:GetService("RunService").Stepped:Connect(function()
	    if _G.Settings.Main["Auto New World"] or _G.Settings.Main["TweenChest[1]"] or _G.Settings.Main["TweenChest[2]"] or _G.Settings.Main["Auto Farm Chest [Main]"] or _G.Settings.Main["TweenChest"] or _G.Settings.Main["Auto Saber"] or _G.Settings.Main["Auto Pople"] or getgenv().AutoObservation or
            --[World 2] 
            _G.AutoAllBoss or _G.Settings.Boss["Auto Farm All Boss"] or _G.Settings.Main["Auto Farm law Sword"] or
            _G.Settings.Main["Auto Third Sea"] or _G.Settings.Main["Auto Bartilo Quest"] or _G.Settings.Main["Auto Dark Coat"] or _G.Settings.Main["Auto Swan Glasses"] or _G.Settings.Main["Auto True Triple Katana"] or _G.Settings.Main["Auto Rengoku"] or _G.Settings.Main["Auto Ectoplasm"] or 
            _G.Settings.FightingStyle["Auto Fully Death Step"] or _G.Settings.FightingStyle["Auto Fully SharkMan Karate"] or
			 --[World 3]
            _G.Settings.Main["Auto Observation Haki v2"] or _G.Settings.Main["Auto Rainbow Haki"] or _G.Settings.Main["Auto Elite Hunter"] or _G.Settings.Main["Auto Musketeer Hat"] or _G.Settings.Main["Auto Buddy Sword"] or _G.Settings.Main["Auto Farm Bone"] or _G.Settings.Main["Auto Ken-Haki V2"] or _G.Settings.FightingStyle["Auto God Human"] or _G.Settings.Main["Auto Cavander"] or _G.Settings.Main["Auto Cursed Dual Katana"] or _G.Settings.Main["Auto Yama Sword"] or _G.Settings.Main["Auto Tushita Sword"] or _G.Settings.Main["Auto Serpent Bow"] or _G.Settings.Main["Auto Dark Dagger"] or _G.Settings.Main["Auto Cake Prince"] or _G.Settings.Main["Auto Dough V2"] or _G.Settings.Main["Auto Holy Torch"] or _G.Settings.Main["Auto Buddy Swords"] or _G.Settings.Main["Auto Farm Boss Hallow"] or _G.Settings.Main["Mob Aura"] or _G.Settings.Main["Auto Material Soul Guitar"] or _G.Settings.Main["Auto Quest Soul Guitar"] or YamaQuest2 or YamaQuest1 or Auto_Cursed_Dual_Katana or Tushita_Quest2 or Tushita_Quest1 or AutoFarmMaterial or teleporttop or AutoFarmChest or --[For God Human] 
			_G.Settings.Main["Auto Fish Tail Sea 1"] or _G.Settings.Main["Auto Fish Tail Sea 3"] or _G.Settings.Main["Auto Magma Ore Sea 2"] or 
			_G.Settings.Main["Auto Magma Ore Sea 1"] or _G.Settings.Main["Auto Mystic Droplet"] or _G.Settings.Main["Auto Dragon Scales"] or 
			--[Boss] 
			_G.Settings.Boss["Auto All Boss"] or _G.Settings.Boss["Auto Boss Select"] or 
			--[Mastery]
			_G.Settings.Mastery["Auto Farm Fruit Mastery"] or _G.Settings.Mastery["Auto Farm Gun Mastery"] or _G.Settings.Mastery["Farm Mastery SwordList"] or
			--[Teleport]
			_G.Settings.Teleport["Teleport to Sea Beast"] or
			--[Raids]
			_G.Settings.Raids["Auto Raids"] or _G.Settings.Raids["Auto Next Place"] or farm or AutoFarmBone or AutoFarmChest or FramBoss or KillAllBoss or _G.AutoNew or _G.AutoThird or _G.AutoSaber or _G.AutoPoleHOP or _G.AutoPole or _G.AutoRengoku or _G.AutoEvoRace2 or _G.AutoQuestBartilo or _G.AutoHakiRainbow or _G.AutoEliteHunter or _G.AutoYama or _G.HolyTorch then
			
			if not KRNL_LOADED and game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
				setfflag("HumanoidParallelRemoveNoPhysics", "False")
				setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			else
				if not game:GetService("Workspace"):FindFirstChild("Part") then
					local Part = Instance.new("Part")
					Part.Name = "Part"
					Part.Parent = game.Workspace
					Part.Anchored = true
					Part.Transparency = 1
					Part.Size = Vector3.new(50,0.5,50)
				elseif game:GetService("Workspace"):FindFirstChild("Part") then
					game.Workspace["Part"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.8,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)
				end
			end
			for _, v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if v:IsA("BasePart") then
					v.CanCollide = false
				end
			end
		end
	end)
end)

spawn(function()
	game:GetService("RunService").Stepped:Connect(function()
        if _G.Part or Auto_Farm_Level or _G.Settings.Main["Auto Farm Level"] then
            if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Death") then
                game:GetService("ReplicatedStorage").Effect.Container.Death:Destroy()
            end
            if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Respawn") then
                game:GetService("ReplicatedStorage").Effect.Container.Respawn:Destroy()
            end
            if not KRNL_LOADED and game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
				setfflag("HumanoidParallelRemoveNoPhysics", "False")
				setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			else
                if not game:GetService("Workspace"):FindFirstChild("Part") then
                    local Part = Instance.new("Part")
                    Part.Name = "Part"
                    Part.Parent = game.Workspace
                    Part.Anchored = true
                    if getgenv().FarmModeSmooth then
                        Part.Transparency = 0.9
                    elseif getgenv().FarmModeRough then
                        Part.Transparency = 1
                    end
                    Part.Size = Vector3.new(50,0.5,50)
                elseif game:GetService("Workspace"):FindFirstChild("Part") then
                    game.Workspace["Part"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.8,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)
                end
            end
            for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
                if v:IsA("BasePart") then
                    v.CanCollide = false
                end
            end
            --[[if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                local Noclip = Instance.new("BodyVelocity")
                Noclip.Name = "BodyClip"
                Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Noclip.MaxForce = Vector3.new(100000,100000,100000)
                Noclip.Velocity = Vector3.new(0,0,0)
            end]]
		end
	end)
end)

-- [Bring Mob]

spawn(function()
	while true do
		wait()
		if setscriptable then
			setscriptable(game.Players.LocalPlayer, "SimulationRadius", true)
		end
		if sethiddenproperty then
			sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
		end
	end
end)

task.spawn(function()
	while task.wait() do
		pcall(function()
			if StartMagnet then
				for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then --not string.find(v.Name,"Boss") and 
						if InMyNetWork(v.HumanoidRootPart) then
							v.HumanoidRootPart.CFrame = PosMon
							v.Humanoid.JumpPower = 0
							v.Humanoid.WalkSpeed = 0
							v.Humanoid.NameDisplayDistance = 0
							v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
							v.HumanoidRootPart.CanCollide = false
							v.Head.CanCollide = false
							if v.Humanoid:FindFirstChild("Animator") then
								v.Humanoid.Animator:Destroy()
							end
							sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius", math.huge)
							v.Humanoid:ChangeState(12) --12
							v.Humanoid:ChangeState(14) --12
						end
                    end
				end
			end
		end)
	end
end)

-- [No Stun]

spawn(function()
	if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
		game.Players.LocalPlayer.Character.Stun.Changed:connect(function()
			pcall(function()
				if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
					game.Players.LocalPlayer.Character.Stun.Value = 0
				end
			end)
		end)
	end
end)

-- [Isnetwork Owner]

function InMyNetWork(L_88_arg0)
	if isnetworkowner then
		return isnetworkowner(L_88_arg0)
	else
		if (L_88_arg0.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 363 then 
			return true
		end
		return false
	end
end

-- [Function (Abandoned Quest , Others)]

function Com(L_89_arg0, ...)
	local L_90_ = game:GetService("ReplicatedStorage").Remotes:FindFirstChild("Comm" .. L_89_arg0)
	if L_90_:IsA("RemoteEvent") then
		L_90_:FireServer(...)
	elseif L_90_:IsA("RemoteFunction") then
		L_90_:InvokeServer(...)
	end
end

-- [Tween Functions (toTarget)]
--[[if getgenv().FarmModeSmooth then
    local r = game:GetService("Players").LocalPlayer
    L_3_func = function(Pos)
        task.spawn(function()
            pcall(function()
                if r:DistanceFromCharacter(Pos.Position) <= 340 then 
                    r.Character.HumanoidRootPart.CFrame = Pos
                else if not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                    local K = Instance.new("Part",game.Players.LocalPlayer.Character)
                    K.Size = Vector3.new(1,0.5,1)
                    K.Name = "Root"
                    K.Anchored = true
                    K.Transparency = 0.75
                    K.CanCollide = false
                    K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,0) --(0,20,0)--
                end
                local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Pos.Position).Magnitude
                local z = game:service("TweenService")
                local B = TweenInfo.new((Pos.Position - game.Players.LocalPlayer.Character.Root.Position).Magnitude/ 340,Enum.EasingStyle.Linear) --300--
    local S,g = pcall(function()
                local q = z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame = Pos})
                    q:Play()
                end)
                if not S then return g end
                game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                if S and game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                    pcall(function()
                        if(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-Pos.Position).Magnitude >= 20 then 
                            spawn(function()
                                pcall(function()
                                    if(game.Players.LocalPlayer.Character.Root.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 100 then --150--
                                        game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                                    else
                                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.Root.CFrame
                                    end
                                end)
                            end)
                            elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Pos.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Pos.Position).Magnitude < 20 then 
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
                            elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Pos.Position).Magnitude < 10 then 
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
                            end
                        end)
                    end
                end
            end)
        end)
end
end]]
--[[function L_3_func(CFgo)
    local tweenfunc = {}
    if (game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude <= 20 then
        pcall(function()
            tween:Cancel()

            game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.CFrame = CFgo

            return
        end)
    end
    local tween_s = game:service"TweenService"
    local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - CFgo.Position).Magnitude/365, Enum.EasingStyle.Linear)
    local tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = CFgo})
    tween:Play()

    function tweenfunc:Stop()
        tween:Cancel()
    end 

    return tweenfunc
end]]

-- [Tween Functions]

local function topos(...)
	local L_91_ = {
		...
	}
	local L_92_ = L_91_[1]
	local L_93_
	if type(L_92_) == "vector" then
		L_93_ = L_92_
	elseif type(L_92_) == "userdata" then
		L_93_ = L_92_.Position
	elseif type(L_92_) == "number" then
		L_93_ = CFrame.new(unpack(L_91_))
		L_93_ = L_93_.p
	end

	local L_94_
	local L_95_ = math.huge;
	if game.Players.LocalPlayer.Team then
		for L_96_forvar0, L_97_forvar1 in pairs(game.Workspace._WorldOrigin.Playerspawns:FindFirstChild(tostring(game.Players.LocalPlayer.Team)):GetChildren()) do 
			local L_98_ = (L_93_ - L_97_forvar1:GetModelCFrame().p).Magnitude;
			if L_98_ < L_95_ then
				L_95_ = L_98_;
				L_94_ = L_97_forvar1.Name
			end
		end
		if L_94_ then
			return L_94_
		end 
	end
end

--BTP

function BTP(L_99_arg0)
	game.Players.LocalPlayer.Character.Head:Destroy()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_99_arg0
	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_99_arg0
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint")
end

function bypasspoint(Point)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Point
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Point
end

-- [Functions Click]

function Click()
	game:GetService("VirtualUser"):CaptureController()
	game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 672))
end

-- [loadstring Api]
--print("loadstring Api |FF...   Api")
--loadstring(game:HttpGet("https://pastebin.com/raw/3Ry5iz2M"))() --_G.VeryFast = a
--------------------------------------------------------------------------------------------------------------------------------------
local L_4_ = loadstring(game:HttpGet("https://pastebin.com/raw/EK13Njf3"))() --redeem Code
--print("loadstring Api |FF..1   Api")
-- [Get FightingStyle]

function GetFightingStyle(L_136_arg0)
	ReturnText = ""
	for L_137_forvar0 , L_138_forvar1 in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if L_138_forvar1:IsA("Tool") then
			if L_138_forvar1.ToolTip == L_136_arg0 then
				ReturnText = L_138_forvar1.Name
			end
		end
	end
	for L_139_forvar0 , L_140_forvar1 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
		if L_140_forvar1:IsA("Tool") then
			if L_140_forvar1.ToolTip == L_136_arg0 then
				ReturnText = L_140_forvar1.Name
			end
		end
	end
	if ReturnText ~= "" then
		return ReturnText
	else
		return "Not Have"
	end
end

-- [CheckMasteryWeapon]

function CheckMasteryWeapon(L_141_arg0, L_142_arg1)
	if game.Players.LocalPlayer.Backpack:FindFirstChild(L_141_arg0) then
		if tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(L_141_arg0).Level.Value) < tonumber(L_142_arg1) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(L_141_arg0).Level.Value) >= tonumber(L_142_arg1) then
			return "true UpTo"
		end
	end
	if game.Players.LocalPlayer.Character:FindFirstChild(L_141_arg0) then
		if tonumber(game.Players.LocalPlayer.Character:FindFirstChild(L_141_arg0).Level.Value) < tonumber(L_142_arg1) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Character:FindFirstChild(L_141_arg0).Level.Value) >= tonumber(L_142_arg1) then
			return "true UpTo"
		end
	end
	return "else"
end

--[GetWeaponInventory]

function GetWeaponInventory(L_143_arg0)
	for L_144_forvar0, L_145_forvar1 in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(L_145_forvar1) == "table" then
			if L_145_forvar1.Type == "Sword" then
				if L_145_forvar1.Name == L_143_arg0 then
					return true
				end
			end
		end
	end
	return false
end

-- [GetMaterial]

function GetMaterial(L_146_arg0)
	for L_147_forvar0, L_148_forvar1 in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(L_148_forvar1) == "table" then
			if L_148_forvar1.Type == "Material" then
				if L_148_forvar1.Name == L_146_arg0 then
					return L_148_forvar1.Count
				end
			end
		end
	end
	return 0
end

--[Create Variables]

local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local tween = game:GetService("TweenService")
local RunService = game:GetService("RunService")
local LocalPlayer = game:GetService("Players").LocalPlayer
local Mouse = LocalPlayer:GetMouse()
local plr = game.Players.LocalPlayer

--[Text Animation]
local function AnimateText(Text)
	for i = 1, #Text, 1 do
		game:GetService("Players").LocalPlayer.PlayerGui.Main.Version.Text = string.sub(Text, 1, i)
		wait(0.01)
	end
end

--[When Game Load]


print("Text Animation")
print("Kz Hub by -None") --naja

-- [CustomFindFirstChild]

local function L_7_func(L_149_arg0)
	for L_150_forvar0, L_151_forvar1 in pairs(L_149_arg0) do
		if game:GetService("Workspace").Enemies:FindFirstChild(L_151_forvar1) then
			return true
		end
	end
	return false
end

-- [CheckMaterial]

local function L_11_func(L_158_arg0)
	if World1 then 
		if (L_158_arg0 == "Magma Ore") then 
			MaterialMob = {
				"Military Soldier [Lv. 300]",
				"Military Spy [Lv. 325]"
			};
			CFrameMon = CFrame.new(- 5815, 84, 8820);
		elseif ((L_158_arg0 == "Leather") or (L_158_arg0 == "Scrap Metal")) then 
			MaterialMob = {
				"Brute [Lv. 45]"
			};
			CFrameMon = CFrame.new(- 1145, 15, 4350);
		elseif (L_158_arg0 == "Angel Wings") then 
			MaterialMob = {
				"God's Guard [Lv. 450]"
			};
			CFrameMon = CFrame.new(- 4698, 845, - 1912);
		elseif (L_158_arg0 == "Fish Tail") then 
			MaterialMob = {
				"Fishman Warrior [Lv. 375]",
				"Fishman Commando [Lv. 400]"
			};
			CFrameMon = CFrame.new(61123, 19, 1569);
		end 
	end 
	if World2 then 
		if (L_158_arg0 == "Magma Ore") then 
			MaterialMob = {
				"Magma Ninja [Lv. 1175]"
			};
			CFrameMon = CFrame.new(- 5428, 78, - 5959);
		elseif (L_158_arg0 == "Scrap Metal") then
			MaterialMob = {
				"Swan Pirate [Lv. 775]"
			};
			CFrameMon = CFrame.new(878, 122, 1235);
		elseif (L_158_arg0 == "Radioactive Material") then 
			MaterialMob = {
				"Factory Staff [Lv. 800]"
			};
			CFrameMon = CFrame.new(295, 73, - 56);
		elseif (L_158_arg0 == "Vampire Fang") then 
			MaterialMob = {
				"Vampire [Lv. 975]"
			};
			CFrameMon = CFrame.new(- 6033, 7, - 1317);
		elseif (L_158_arg0 == "Mystic Droplet") then 
			MaterialMob = {
				"Water Fighter [Lv. 1450]",
				"Sea Soldier [Lv. 1425]"
			};
			CFrameMon = CFrame.new(- 3385, 239, - 10542);
		end 
	end 
	if World3 then 
		if (L_158_arg0 == "Mini Tusk") then 
			MaterialMob = {
				"Mythological Pirate [Lv. 1850]"
			};
			CFrameMon = CFrame.new(- 13545, 470, - 6917);
		elseif (L_158_arg0 == "Fish Tail") then 
			MaterialMob = {
				"Fishman Raider [Lv. 1775]",
				"Fishman Captain [Lv. 1800]"
			};
			CFrameMon = CFrame.new(- 10993, 332, - 8940);
		elseif (L_158_arg0 == "Scrap Metal") then 
			MaterialMob = {
				"Jungle Pirate [Lv. 1900]"
			};
			CFrameMon = CFrame.new(- 12107, 332, - 10549);
		elseif (L_158_arg0 == "Dragon Scale") then 
			MaterialMob = {
				"Dragon Crew Archer [Lv. 1600]",
				"Dragon Crew Warrior [Lv. 1575]"
			};
			CFrameMon = CFrame.new(6594, 383, 139);
		elseif (L_158_arg0 == "Conjured Cocoa") then 
			MaterialMob = {
				"Cocoa Warrior [Lv. 2300]",
				"Chocolate Bar Battler [Lv. 2325]",
				"Sweet Thief [Lv. 2350]",
				"Candy Rebel [Lv. 2375]"
			};
			CFrameMon = CFrame.new(620.6344604492188, 78.93644714355469, - 12581.369140625);
		elseif (L_158_arg0 == "Demonic Wisp") then
			MaterialMob = {
				"Demonic Soul [Lv. 2025]"
			};
			CFrameMon = CFrame.new(- 9507, 172, 6158);
		elseif (L_158_arg0 == "Gunpowder") then
			MaterialMob = {
				"Pistol Billionaire [Lv. 1525]"
			};
			CFrameMon = CFrame.new(- 469, 74, 5904);
		elseif (L_158_arg0 == "Bone") then
			MaterialMob = {
				"Pistol Billionaire [Lv. 1525]"
			};
			CFrameMon = CFrame.new(- 469, 74, 5904);
		end 
	end 
end

-- [Check Quest]
function CheckQuest() 
    MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
    if World1 then
        if MyLevel == 1 or MyLevel <= 9 then
            Mon = "Bandit"
            LevelQuest = 1
            NameQuest = "BanditQuest1"
            NameMon = "Bandit"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MyLevel == 10 or MyLevel <= 14 then
            Mon = "Monkey"
            LevelQuest = 1
            NameQuest = "JungleQuest"
            NameMon = "Monkey"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
        elseif MyLevel == 15 or MyLevel <= 29 then
            Mon = "Gorilla"
            LevelQuest = 2
            NameQuest = "JungleQuest"
            NameMon = "Gorilla"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)
        elseif MyLevel == 30 or MyLevel <= 39 then
            Mon = "Pirate"
            LevelQuest = 1
            NameQuest = "BuggyQuest1"
            NameMon = "Pirate"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)
        elseif MyLevel == 40 or MyLevel <= 59 then
            Mon = "Brute"
            LevelQuest = 2
            NameQuest = "BuggyQuest1"
            NameMon = "Brute"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)
        elseif MyLevel == 60 or MyLevel <= 74 then
            Mon = "Desert Bandit"
            LevelQuest = 1
            NameQuest = "DesertQuest"
            NameMon = "Desert Bandit"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)
        elseif MyLevel == 75 or MyLevel <= 89 then
            Mon = "Desert Officer"
            LevelQuest = 2
            NameQuest = "DesertQuest"
            NameMon = "Desert Officer"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)
        elseif MyLevel == 90 or MyLevel <= 99 then
            Mon = "Snow Bandit"
            LevelQuest = 1
            NameQuest = "SnowQuest"
            NameMon = "Snow Bandit"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)
        elseif MyLevel == 100 or MyLevel <= 119 then
            Mon = "Snowman"
            LevelQuest = 2
            NameQuest = "SnowQuest"
            NameMon = "Snowman"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1201.6412353515625, 144.57958984375, -1550.0670166015625)
        elseif MyLevel == 120 or MyLevel <= 149 then
            Mon = "Chief Petty Officer"
            LevelQuest = 1
            NameQuest = "MarineQuest2"
            NameMon = "Chief Petty Officer"
            CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-4881.23095703125, 22.65204429626465, 4273.75244140625)
        elseif MyLevel == 150 or MyLevel <= 174 then
            Mon = "Sky Bandit"
            LevelQuest = 1
            NameQuest = "SkyQuest"
            NameMon = "Sky Bandit"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.new(-4953.20703125, 295.74420166015625, -2899.22900390625)
        elseif MyLevel == 175 or MyLevel <= 189 then
            Mon = "Dark Master"
            LevelQuest = 2
            NameQuest = "SkyQuest"
            NameMon = "Dark Master"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.new(-5259.8447265625, 391.3976745605469, -2229.035400390625)
        elseif MyLevel == 190 or MyLevel <= 209 then
            Mon = "Prisoner"
            LevelQuest = 1
            NameQuest = "PrisonerQuest"
            NameMon = "Prisoner"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5098.9736328125, -0.3204058110713959, 474.2373352050781)
        elseif MyLevel == 210 or MyLevel <= 249 then
            Mon = "Dangerous Prisoner"
            LevelQuest = 2
            NameQuest = "PrisonerQuest"
            NameMon = "Dangerous Prisoner"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5654.5634765625, 15.633401870727539, 866.2991943359375)
        elseif MyLevel == 250 or MyLevel <= 274 then
            Mon = "Toga Warrior"
            LevelQuest = 1
            NameQuest = "ColosseumQuest"
            NameMon = "Toga Warrior"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.new(-1820.21484375, 51.68385696411133, -2740.6650390625)
        elseif MyLevel == 275 or MyLevel <= 299 then
            Mon = "Gladiator"
            LevelQuest = 2
            NameQuest = "ColosseumQuest"
            NameMon = "Gladiator"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.new(-1292.838134765625, 56.380882263183594, -3339.031494140625)
        elseif MyLevel == 300 or MyLevel <= 324 then
            Mon = "Military Soldier"
            LevelQuest = 1
            NameQuest = "MagmaQuest"
            NameMon = "Military Soldier"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.new(-5411.16455078125, 11.081554412841797, 8454.29296875)
        elseif MyLevel == 325 or MyLevel <= 374 then
            Mon = "Military Spy"
            LevelQuest = 2
            NameQuest = "MagmaQuest"
            NameMon = "Military Spy"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.new(-5802.8681640625, 86.26241302490234, 8828.859375)
        elseif MyLevel == 375 or MyLevel <= 399 then
            Mon = "Fishman Warrior"
            LevelQuest = 1
            NameQuest = "FishmanQuest"
            NameMon = "Fishman Warrior"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(60878.30078125, 18.482830047607422, 1543.7574462890625)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            end
        elseif MyLevel == 400 or MyLevel <= 449 then
            Mon = "Fishman Commando"
            LevelQuest = 2
            NameQuest = "FishmanQuest"
            NameMon = "Fishman Commando"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(61922.6328125, 18.482830047607422, 1493.934326171875)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            end
        elseif MyLevel == 450 or MyLevel <= 474 then
            Mon = "God's Guard"
            LevelQuest = 1
            NameQuest = "SkyExp1Quest"
            NameMon = "God's Guard"
            CFrameQuest = CFrame.new(-4721.88867, 843.874695, -1949.96643, 0.996191859, -0, -0.0871884301, 0, 1, -0, 0.0871884301, 0, 0.996191859)
            CFrameMon = CFrame.new(-4710.04296875, 845.2769775390625, -1927.3079833984375)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
            end
        elseif MyLevel == 475 or MyLevel <= 524 then
            Mon = "Shanda"
            LevelQuest = 2
            NameQuest = "SkyExp1Quest"
            NameMon = "Shanda"
            CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)
            CFrameMon = CFrame.new(-7678.48974609375, 5566.40380859375, -497.2156066894531)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
            end
        elseif MyLevel == 525 or MyLevel <= 549 then
            Mon = "Royal Squad"
            LevelQuest = 1
            NameQuest = "SkyExp2Quest"
            NameMon = "Royal Squad"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-7624.25244140625, 5658.13330078125, -1467.354248046875)
        elseif MyLevel == 550 or MyLevel <= 624 then
            Mon = "Royal Soldier"
            LevelQuest = 2
            NameQuest = "SkyExp2Quest"
            NameMon = "Royal Soldier"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-7836.75341796875, 5645.6640625, -1790.6236572265625)
        elseif MyLevel == 625 or MyLevel <= 649 then
            Mon = "Galley Pirate"
            LevelQuest = 1
            NameQuest = "FountainQuest"
            NameMon = "Galley Pirate"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5551.02197265625, 78.90135192871094, 3930.412841796875)
        elseif MyLevel >= 650 then
            Mon = "Galley Captain"
            LevelQuest = 2
            NameQuest = "FountainQuest"
            NameMon = "Galley Captain"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5441.95166015625, 42.50205993652344, 4950.09375)
        end
    elseif World2 then
        if MyLevel == 700 or MyLevel <= 724 then
            Mon = "Raider"
            LevelQuest = 1
            NameQuest = "Area1Quest"
            NameMon = "Raider"
            CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
            CFrameMon = CFrame.new(-728.3267211914062, 52.779319763183594, 2345.7705078125)
        elseif MyLevel == 725 or MyLevel <= 774 then
            Mon = "Mercenary"
            LevelQuest = 2
            NameQuest = "Area1Quest"
            NameMon = "Mercenary"
            CFrameQuest = CFrame.new(-429.543518, 71.7699966, 1836.18188, -0.22495985, 0, -0.974368095, 0, 1, 0, 0.974368095, 0, -0.22495985)
            CFrameMon = CFrame.new(-1004.3244018554688, 80.15886688232422, 1424.619384765625)
        elseif MyLevel == 775 or MyLevel <= 799 then
            Mon = "Swan Pirate"
            LevelQuest = 1
            NameQuest = "Area2Quest"
            NameMon = "Swan Pirate"
            CFrameQuest = CFrame.new(638.43811, 71.769989, 918.282898, 0.139203906, 0, 0.99026376, 0, 1, 0, -0.99026376, 0, 0.139203906)
            CFrameMon = CFrame.new(1068.664306640625, 137.61428833007812, 1322.1060791015625)
        elseif MyLevel == 800 or MyLevel <= 874 then
            Mon = "Factory Staff"
            NameQuest = "Area2Quest"
            LevelQuest = 2
            NameMon = "Factory Staff"
            CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
            CFrameMon = CFrame.new(73.07867431640625, 81.86344146728516, -27.470672607421875)
        elseif MyLevel == 875 or MyLevel <= 899 then
            Mon = "Marine Lieutenant"
            LevelQuest = 1
            NameQuest = "MarineQuest3"
            NameMon = "Marine Lieutenant"
            CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.new(-2821.372314453125, 75.89727783203125, -3070.089111328125)
        elseif MyLevel == 900 or MyLevel <= 949 then
            Mon = "Marine Captain"
            LevelQuest = 2
            NameQuest = "MarineQuest3"
            NameMon = "Marine Captain"
            CFrameQuest = CFrame.new(-2440.79639, 71.7140732, -3216.06812, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.new(-1861.2310791015625, 80.17658233642578, -3254.697509765625)
        elseif MyLevel == 950 or MyLevel <= 974 then
            Mon = "Zombie"
            LevelQuest = 1
            NameQuest = "ZombieQuest"
            NameMon = "Zombie"
            CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
            CFrameMon = CFrame.new(-5657.77685546875, 78.96973419189453, -928.68701171875)
        elseif MyLevel == 975 or MyLevel <= 999 then
            Mon = "Vampire"
            LevelQuest = 2
            NameQuest = "ZombieQuest"
            NameMon = "Vampire"
            CFrameQuest = CFrame.new(-5497.06152, 47.5923004, -795.237061, -0.29242146, 0, -0.95628953, 0, 1, 0, 0.95628953, 0, -0.29242146)
            CFrameMon = CFrame.new(-6037.66796875, 32.18463897705078, -1340.6597900390625)
        elseif MyLevel == 1000 or MyLevel <= 1049 then
            Mon = "Snow Trooper"
            LevelQuest = 1
            NameQuest = "SnowMountainQuest"
            NameMon = "Snow Trooper"
            CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
            CFrameMon = CFrame.new(549.1473388671875, 427.3870544433594, -5563.69873046875)
        elseif MyLevel == 1050 or MyLevel <= 1099 then
            Mon = "Winter Warrior"
            LevelQuest = 2
            NameQuest = "SnowMountainQuest"
            NameMon = "Winter Warrior"
            CFrameQuest = CFrame.new(609.858826, 400.119904, -5372.25928, -0.374604106, 0, 0.92718488, 0, 1, 0, -0.92718488, 0, -0.374604106)
            CFrameMon = CFrame.new(1142.7451171875, 475.6398010253906, -5199.41650390625)
        elseif MyLevel == 1100 or MyLevel <= 1124 then
            Mon = "Lab Subordinate"
            LevelQuest = 1
            NameQuest = "IceSideQuest"
            NameMon = "Lab Subordinate"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.new(-5707.4716796875, 15.951709747314453, -4513.39208984375)
        elseif MyLevel == 1125 or MyLevel <= 1174 then
            Mon = "Horned Warrior"
            LevelQuest = 2
            NameQuest = "IceSideQuest"
            NameMon = "Horned Warrior"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.new(-6341.36669921875, 15.951770782470703, -5723.162109375)
        elseif MyLevel == 1175 or MyLevel <= 1199 then
            Mon = "Magma Ninja"
            LevelQuest = 1
            NameQuest = "FireSideQuest"
            NameMon = "Magma Ninja"
            CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
            CFrameMon = CFrame.new(-5449.6728515625, 76.65874481201172, -5808.20068359375)
        elseif MyLevel == 1200 or MyLevel <= 1249 then
            Mon = "Lava Pirate"
            LevelQuest = 2
            NameQuest = "FireSideQuest"
            NameMon = "Lava Pirate"
            CFrameQuest = CFrame.new(-5428.03174, 15.0622921, -5299.43457, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
            CFrameMon = CFrame.new(-5213.33154296875, 49.73788070678711, -4701.451171875)
        elseif MyLevel == 1250 or MyLevel <= 1274 then
            Mon = "Ship Deckhand"
            LevelQuest = 1
            NameQuest = "ShipQuest1"
            NameMon = "Ship Deckhand"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)         
            CFrameMon = CFrame.new(1212.0111083984375, 150.79205322265625, 33059.24609375)    
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            end
        elseif MyLevel == 1275 or MyLevel <= 1299 then
            Mon = "Ship Engineer"
            LevelQuest = 2
            NameQuest = "ShipQuest1"
            NameMon = "Ship Engineer"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)   
            CFrameMon = CFrame.new(919.4786376953125, 43.54401397705078, 32779.96875)   
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            end             
        elseif MyLevel == 1300 or MyLevel <= 1324 then
            Mon = "Ship Steward"
            LevelQuest = 1
            NameQuest = "ShipQuest2"
            NameMon = "Ship Steward"
            CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)         
            CFrameMon = CFrame.new(919.4385375976562, 129.55599975585938, 33436.03515625)      
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            end
        elseif MyLevel == 1325 or MyLevel <= 1349 then
            Mon = "Ship Officer"
            LevelQuest = 2
            NameQuest = "ShipQuest2"
            NameMon = "Ship Officer"
            CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125)
            CFrameMon = CFrame.new(1036.0179443359375, 181.4390411376953, 33315.7265625)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            end
        elseif MyLevel == 1350 or MyLevel <= 1374 then
            Mon = "Arctic Warrior"
            LevelQuest = 1
            NameQuest = "FrostQuest"
            NameMon = "Arctic Warrior"
            CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
            CFrameMon = CFrame.new(5966.24609375, 62.97002029418945, -6179.3828125)
            if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 5000.034996032715, -132.83953857422))
            end
        elseif MyLevel == 1375 or MyLevel <= 1424 then
            Mon = "Snow Lurker"
            LevelQuest = 2
            NameQuest = "FrostQuest"
            NameMon = "Snow Lurker"
            CFrameQuest = CFrame.new(5667.6582, 26.7997818, -6486.08984, -0.933587909, 0, -0.358349502, 0, 1, 0, 0.358349502, 0, -0.933587909)
            CFrameMon = CFrame.new(5407.07373046875, 69.19437408447266, -6880.88037109375)
        elseif MyLevel == 1425 or MyLevel <= 1449 then
            Mon = "Sea Soldier"
            LevelQuest = 1
            NameQuest = "ForgottenQuest"
            NameMon = "Sea Soldier"
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
            CFrameMon = CFrame.new(-3028.2236328125, 64.67451477050781, -9775.4267578125)
        elseif MyLevel >= 1450 then
            Mon = "Water Fighter"
            LevelQuest = 2
            NameQuest = "ForgottenQuest"
            NameMon = "Water Fighter"
            CFrameQuest = CFrame.new(-3054.44458, 235.544281, -10142.8193, 0.990270376, -0, -0.13915664, 0, 1, -0, 0.13915664, 0, 0.990270376)
            CFrameMon = CFrame.new(-3352.9013671875, 285.01556396484375, -10534.841796875)
        end
    elseif World3 then
        if MyLevel == 1500 or MyLevel <= 1524 then
            Mon = "Pirate Millionaire"
            LevelQuest = 1
            NameQuest = "PiratePortQuest"
            NameMon = "Pirate Millionaire"
            CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-245.9963836669922, 47.30615234375, 5584.1005859375)
        elseif MyLevel == 1525 or MyLevel <= 1574 then
            Mon = "Pistol Billionaire"
            LevelQuest = 2
            NameQuest = "PiratePortQuest"
            NameMon = "Pistol Billionaire"
            CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-187.3301544189453, 86.23987579345703, 6013.513671875)
        elseif MyLevel == 1575 or MyLevel <= 1599 then
            Mon = "Dragon Crew Warrior"
            LevelQuest = 1
            NameQuest = "AmazonQuest"
            NameMon = "Dragon Crew Warrior"
            CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
            CFrameMon = CFrame.new(6141.140625, 51.35136413574219, -1340.738525390625)
        elseif MyLevel == 1600 or MyLevel <= 1624 then 
            Mon = "Dragon Crew Archer"
            NameQuest = "AmazonQuest"
            LevelQuest = 2
            NameMon = "Dragon Crew Archer"
            CFrameQuest = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
            CFrameMon = CFrame.new(6616.41748046875, 441.7670593261719, 446.0469970703125)
        elseif MyLevel == 1625 or MyLevel <= 1649 then
            Mon = "Female Islander"
            NameQuest = "AmazonQuest2"
            LevelQuest = 1
            NameMon = "Female Islander"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(4685.25830078125, 735.8078002929688, 815.3425903320312)
        elseif MyLevel == 1650 or MyLevel <= 1699 then 
            Mon = "Giant Islander"
            NameQuest = "AmazonQuest2"
            LevelQuest = 2
            NameMon = "Giant Islander"
            CFrameQuest = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            CFrameMon = CFrame.new(4729.09423828125, 590.436767578125, -36.97627639770508)
        elseif MyLevel == 1700 or MyLevel <= 1724 then
            Mon = "Marine Commodore"
            LevelQuest = 1
            NameQuest = "MarineTreeIsland"
            NameMon = "Marine Commodore"
            CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
            CFrameMon = CFrame.new(2286.0078125, 73.13391876220703, -7159.80908203125)
        elseif MyLevel == 1725 or MyLevel <= 1774 then
            Mon = "Marine Rear Admiral"
            NameMon = "Marine Rear Admiral"
            NameQuest = "MarineTreeIsland"
            LevelQuest = 2
            CFrameQuest = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
            CFrameMon = CFrame.new(3656.773681640625, 160.52406311035156, -7001.5986328125)
        elseif MyLevel == 1775 or MyLevel <= 1799 then
            Mon = "Fishman Raider"
            LevelQuest = 1
            NameQuest = "DeepForestIsland3"
            NameMon = "Fishman Raider"
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
            CFrameMon = CFrame.new(-10407.5263671875, 331.76263427734375, -8368.5166015625)
        elseif MyLevel == 1800 or MyLevel <= 1824 then
            Mon = "Fishman Captain"
            LevelQuest = 2
            NameQuest = "DeepForestIsland3"
            NameMon = "Fishman Captain"
            CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)   
            CFrameMon = CFrame.new(-10994.701171875, 352.38140869140625, -9002.1103515625) 
        elseif MyLevel == 1825 or MyLevel <= 1849 then
            Mon = "Forest Pirate"
            LevelQuest = 1
            NameQuest = "DeepForestIsland"
            NameMon = "Forest Pirate"
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
            CFrameMon = CFrame.new(-13274.478515625, 332.3781433105469, -7769.58056640625)
        elseif MyLevel == 1850 or MyLevel <= 1899 then
            Mon = "Mythological Pirate"
            LevelQuest = 2
            NameQuest = "DeepForestIsland"
            NameMon = "Mythological Pirate"
            CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)   
            CFrameMon = CFrame.new(-13680.607421875, 501.08154296875, -6991.189453125)
        elseif MyLevel == 1900 or MyLevel <= 1924 then
            Mon = "Jungle Pirate"
            LevelQuest = 1
            NameQuest = "DeepForestIsland2"
            NameMon = "Jungle Pirate"
            CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
            CFrameMon = CFrame.new(-12256.16015625, 331.73828125, -10485.8369140625)
        elseif MyLevel == 1925 or MyLevel <= 1974 then
            Mon = "Musketeer Pirate"
            LevelQuest = 2
            NameQuest = "DeepForestIsland2"
            NameMon = "Musketeer Pirate"
            CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
            CFrameMon = CFrame.new(-13457.904296875, 391.545654296875, -9859.177734375)
        elseif MyLevel == 1975 or MyLevel <= 1999 then
            Mon = "Reborn Skeleton"
            LevelQuest = 1
            NameQuest = "HauntedQuest1"
            NameMon = "Reborn Skeleton"
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-8763.7236328125, 165.72299194335938, 6159.86181640625)
        elseif MyLevel == 2000 or MyLevel <= 2024 then
            Mon = "Living Zombie"
            LevelQuest = 2
            NameQuest = "HauntedQuest1"
            NameMon = "Living Zombie"
            CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-10144.1318359375, 138.62667846679688, 5838.0888671875)
        elseif MyLevel == 2025 or MyLevel <= 2049 then
            Mon = "Demonic Soul"
            LevelQuest = 1
            NameQuest = "HauntedQuest2"
            NameMon = "Demonic Soul"
            CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0) 
            CFrameMon = CFrame.new(-9505.8720703125, 172.10482788085938, 6158.9931640625)
        elseif MyLevel == 2050 or MyLevel <= 2074 then
            Mon = "Posessed Mummy"
            LevelQuest = 2
            NameQuest = "HauntedQuest2"
            NameMon = "Posessed Mummy"
            CFrameQuest = CFrame.new(-9516.99316, 172.017181, 6078.46533, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-9582.0224609375, 6.251527309417725, 6205.478515625)
        elseif MyLevel == 2075 or MyLevel <= 2099 then
            Mon = "Peanut Scout"
            LevelQuest = 1
            NameQuest = "NutsIslandQuest"
            NameMon = "Peanut Scout"
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-2143.241943359375, 47.72198486328125, -10029.9951171875)
        elseif MyLevel == 2100 or MyLevel <= 2124 then
            Mon = "Peanut President"
            LevelQuest = 2
            NameQuest = "NutsIslandQuest"
            NameMon = "Peanut President"
            CFrameQuest = CFrame.new(-2104.3908691406, 38.104167938232, -10194.21875, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-1859.35400390625, 38.10316848754883, -10422.4296875)
        elseif MyLevel == 2125 or MyLevel <= 2149 then
            Mon = "Ice Cream Chef"
            LevelQuest = 1
            NameQuest = "IceCreamIslandQuest"
            NameMon = "Ice Cream Chef"
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-872.24658203125, 65.81957244873047, -10919.95703125)
        elseif MyLevel == 2150 or MyLevel <= 2199 then
            Mon = "Ice Cream Commander"
            LevelQuest = 2
            NameQuest = "IceCreamIslandQuest"
            NameMon = "Ice Cream Commander"
            CFrameQuest = CFrame.new(-820.64825439453, 65.819526672363, -10965.795898438, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.new(-558.06103515625, 112.04895782470703, -11290.7744140625)
        elseif MyLevel == 2200 or MyLevel <= 2224 then
            Mon = "Cookie Crafter"
            LevelQuest = 1
            NameQuest = "CakeQuest1"
            NameMon = "Cookie Crafter"
            CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
            CFrameMon = CFrame.new(-2374.13671875, 37.79826354980469, -12125.30859375)
        elseif MyLevel == 2225 or MyLevel <= 2249 then
            Mon = "Cake Guard"
            LevelQuest = 2
            NameQuest = "CakeQuest1"
            NameMon = "Cake Guard"
            CFrameQuest = CFrame.new(-2021.32007, 37.7982254, -12028.7295, 0.957576931, -8.80302053e-08, 0.288177818, 6.9301187e-08, 1, 7.51931211e-08, -0.288177818, -5.2032135e-08, 0.957576931)
            CFrameMon = CFrame.new(-1598.3070068359375, 43.773197174072266, -12244.5810546875)
        elseif MyLevel == 2250 or MyLevel <= 2274 then
            Mon = "Baking Staff"
            LevelQuest = 1
            NameQuest = "CakeQuest2"
            NameMon = "Baking Staff"
            CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
            CFrameMon = CFrame.new(-1887.8099365234375, 77.6185073852539, -12998.3505859375)
        elseif MyLevel == 2275 or MyLevel <= 2299 then
            Mon = "Head Baker"
            LevelQuest = 2
            NameQuest = "CakeQuest2"
            NameMon = "Head Baker"
            CFrameQuest = CFrame.new(-1927.91602, 37.7981339, -12842.5391, -0.96804446, 4.22142143e-08, 0.250778586, 4.74911062e-08, 1, 1.49904711e-08, -0.250778586, 2.64211941e-08, -0.96804446)
            CFrameMon = CFrame.new(-2216.188232421875, 82.884521484375, -12869.2939453125)
        elseif MyLevel == 2300 or MyLevel <= 2324 then
            Mon = "Cocoa Warrior"
            LevelQuest = 1
            NameQuest = "ChocQuest1"
            NameMon = "Cocoa Warrior"
            CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
            CFrameMon = CFrame.new(-21.55328369140625, 80.57499694824219, -12352.3876953125)
        elseif MyLevel == 2325 or MyLevel <= 2349 then
            Mon = "Chocolate Bar Battler"
            LevelQuest = 2
            NameQuest = "ChocQuest1"
            NameMon = "Chocolate Bar Battler"
            CFrameQuest = CFrame.new(233.22836303710938, 29.876001358032227, -12201.2333984375)
            CFrameMon = CFrame.new(582.590576171875, 77.18809509277344, -12463.162109375)
        elseif MyLevel == 2350 or MyLevel <= 2374 then
            Mon = "Sweet Thief"
            LevelQuest = 1
            NameQuest = "ChocQuest2"
            NameMon = "Sweet Thief"
            CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
            CFrameMon = CFrame.new(165.1884765625, 76.05885314941406, -12600.8369140625)
        elseif MyLevel == 2375 or MyLevel <= 2399 then
            Mon = "Candy Rebel"
            LevelQuest = 2
            NameQuest = "ChocQuest2"
            NameMon = "Candy Rebel"
            CFrameQuest = CFrame.new(150.5066375732422, 30.693693161010742, -12774.5029296875)
            CFrameMon = CFrame.new(134.86563110351562, 77.2476806640625, -12876.5478515625)
        elseif MyLevel == 2400 or MyLevel <= 2424 then
            Mon = "Candy Pirate"
            LevelQuest = 1
            NameQuest = "CandyQuest1"
            NameMon = "Candy Pirate"
            CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)
            CFrameMon = CFrame.new(-1310.5003662109375, 26.016523361206055, -14562.404296875)
        elseif MyLevel == 2425 or MyLevel <= 2449 then
            Mon = "Snow Demon"
            LevelQuest = 2
            NameQuest = "CandyQuest1"
            NameMon = "Snow Demon"
            CFrameQuest = CFrame.new(-1150.0400390625, 20.378934860229492, -14446.3349609375)
            CFrameMon = CFrame.new(-880.2006225585938, 71.24776458740234, -14538.609375)
        elseif MyLevel == 2450 or MyLevel <= 2474 then
            Mon = "Isle Outlaw"
            LevelQuest = 1
            NameQuest = "TikiQuest1"
            NameMon = "Isle Outlaw"
            CFrameQuest = CFrame.new(-16545.9355, 55.6863556, -173.230499)
            CFrameMon = CFrame.new(-16120.6035, 116.520554, -103.038849)
        elseif MyLevel == 2475 or MyLevel <= 2499 then
            Mon = "Island Boy"
            LevelQuest = 2
            NameQuest = "TikiQuest1"
            NameMon = "Island Boy"
            CFrameQuest = CFrame.new(-16545.9355, 55.6863556, -173.230499)
            CFrameMon = CFrame.new(-16751.3125, 121.226219, -264.015015)
        elseif MyLevel == 2500 or MyLevel <= 2524 then
            Mon = "Sun-kissed Warrio"
            LevelQuest = 1
            NameQuest = "TikiQuest2"
            NameMon = "Sun-kissed Warrio"
            CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)
            CFrameMon = CFrame.new(-16294.6748, 32.7874393, 1062.4856)
        elseif MyLevel >= 2525 then
            Mon = "Isle Champion"
            LevelQuest = 2
            NameQuest = "TikiQuest2"
            NameMon = "Isle Champion"
            CFrameQuest = CFrame.new(-16539.078125, 55.68632888793945, 1051.5738525390625)
            CFrameMon = CFrame.new(-16933.2129, 93.3503036, 999.450989)
        end
    end
end


function UnEquipWeapon(Weapon)
    if game.Players.LocalPlayer.Character:FindFirstChild(Weapon) then
        _G.NotAutoEquip = true
        wait(.5)
        game.Players.LocalPlayer.Character:FindFirstChild(Weapon).Parent = game.Players.LocalPlayer.Backpack
        wait(.1)
        _G.NotAutoEquip = false
    end
end

function EquipWeapon(ToolSe)
    if not _G.NotAutoEquip then
        if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
            Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
            wait(.1)
            game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)
        end
    end
end
-----------------------------------------------------------------
loadstring(game:HttpGet("https://raw.githubusercontent.com/NaJaxHub/ser/main/OBF-Fast.lua"))() -- fast |  ตีเร็ว
-----------------------------------------------------------------

-- [Remove Mob]
spawn(function()
	while wait() do
		pcall(function()
		    if not _G.Settings.Raids["Auto Raids"] then
			for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
				if not string.find(v.Name,"Boss") and v.Humanoid.Health <= 0 and v:FindFirstChild("Humanoid") then
					v:Destroy()
				end
			end
			end
		end)
	end
end)

    spawn(function()
        while task.wait() do
            pcall(function()
                if _G.AutoBartilo and AutoBartiloBring then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if _G.AutoBartilo and AutoBartiloBring then
                            if v.Name == "Swan Pirate [Lv. 775]" and (v.HumanoidRootPart.Position - PosMonBarto.Position).Magnitude <= 280 and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                v.HumanoidRootPart.Size = Vector3.new(123,123,123)
                                v.Humanoid:ChangeState(12)
                                v.Humanoid:ChangeState(14)
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CFrame = PosMonBarto
                                if v.Humanoid:FindFirstChild("Animator") then
                                    v.Humanoid.Animator:Destroy()
                                end
                                sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRadius", math.huge)
                            end
                        end
                    end
                end
            end)
        end
    end)

-- [Check Notification]

function CheckNotifyComplete()
	for i, d in pairs(game:GetService("Players")["LocalPlayer"].PlayerGui:FindFirstChild("Notifications"):GetChildren()) do
		if d.Name == "NotificationTemplate" then
			if string.lower(d.Text):find("quest completed") or string.lower(d.Text):find("<เควสสำเร็จแล้ว!>") or string.lower(d.Text):find("เควสสำเร็จแล้ว!") then
				pcall(function()
					d:Destroy()
				end)
				return true
			end
		end
	end
	return false
end

local NoLoopDuplicate = false --false,true  --NoLoopDuplicate
local SubQuest = false --false,true  --SubQuest
local oldmob = Name --oldmob --Name
local oldcheckquest = NameMon --oldcheckquest --NameMon
--local L_27_ = NameBoss

--[[task.spawn(function()
	while task.wait() do
		pcall(function()
			if _G.Settings.Main["Auto Farm Level"] then
				if _G.Settings.Configs["Double Quest"] then 
					if SubQuest == true then
						if LevelFarm then --and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude >= 220 then --game.Players.LocalPlayer.Character.HumanoidRootPart.Position --CFrameQuest
							if tonumber(LevelFarm-1) ~= 0 then
								CheckOldQuest(tonumber(LevelFarm-1))
							end
						end
					else
						CheckQuest()
						oldmob = Name
						oldcheckquest = NameMon
						spawn(function()
							pcall(function()
								if NoLoopDuplicate == false then 
									if CheckNotifyComplete() and _G.Settings.Main["Auto Farm Level"] then
										NoLoopDuplicate = true 
										while wait() do
											SubQuest = true
											if CheckNotifyComplete() or _G.Settings.Main["Auto Farm Level"] == false then --false
												break
											end
										end
										SubQuest = false
										NoLoopDuplicate = false
									end
								end
							end)
						end)
						if SubQuest == true then  
							--if LevelFarm then 
							if LevelFarm then --and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude >= 220 then
								if tonumber(LevelFarm-1) ~= 0 then
									CheckOldQuest(tonumber(LevelFarm-1))
								end
							end
						end
					end
				else
					CheckQuest()
				end
				AutoFarmLevel()
			end
		end)
	end
end)]]


task.spawn(function()
	while task.wait() do
		pcall(function()
			if _G.Settings.Main["Auto Farm Level"] then
				if _G.Settings.Configs["Double Quest"] then 
					if SubQuest == true then
						if LevelFarm and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude >= 220 then --game.Players.LocalPlayer.Character.HumanoidRootPart.Position --CFrameQuest
							if tonumber(LevelFarm-1) ~= 0 then
								CheckOldQuest(tonumber(LevelFarm-1))
							end
						end
					else
						CheckQuest()
						oldmob = Name
						oldcheckquest = NameMon
						spawn(function()
							pcall(function()
								if NoLoopDuplicate == false then 
									if CheckNotifyComplete() and _G.Settings.Main["Auto Farm Level"] then
										NoLoopDuplicate = true 
										while wait() do
											SubQuest = true
											if CheckNotifyComplete() or _G.Settings.Main["Auto Farm Level"] == false then --false
												break
											end
										end
										SubQuest = false
										NoLoopDuplicate = false
									end
								end
							end)
						end)
						if SubQuest == true then  
							--if LevelFarm then 
							if LevelFarm and  (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude >= 220 then
								if tonumber(LevelFarm-1) ~= 0 then
									CheckOldQuest(tonumber(LevelFarm-1))
								end
							end
						end
					end
				else
					CheckQuest()
				end
				AutoFarmLevel()
			end
		end)
	end
end)
--[[game:GetService("UserInputService").WindowFocused:connect(function()
--game.RunService:Set3dRenderingEnabled(true)
setfpscap(30)
end)
game:GetService("UserInputService").WindowFocusReleased:connect(function()
--game.RunService:Set3dRenderingEnabled(false)
setfpscap(64)
end)]]

----------------------------------------------------------------------------------------------------------------------------------------------
print("UI.Lo")
----------------------------------------------------------------------------------------------------------------------------------------------
local Window = library:NaJa()

local A = Window:Tab("Main:Autofarm","6022668898")
local B = Window:Tab("AutoFarm:Stats","11155827783")
local C = Window:Tab("Teleport : PvP","11162889532")
local D = Window:Tab("Raid : Fruit","11155842453")
local E = Window:Tab("Shop : Misc","11156322986")

local L_16_ = A:Section("Main","Right")
local L_14_1 = A:Section("Other Auto Farm","Left")
local L_15_ = B:Section("Automatics","Left")
local L_17_ = B:Section("Stats","Right")
local L_18_ = C:Section("Teleport","Left")
local Combat = C:Section("PvP","Right")
local L_20_ = D:Section("Raid","Left")
local LLLL = D:Section("Fruit","Right")
local L_22_ = E:Section("Misc","Right")
local L_21_ = E:Section("Shop","Left")

print("UI.Ok")

function toTarget(targetPos, targetCFrame)
    local tweenfunc = {}
    local tween_s = game:service"TweenService"
    local info = TweenInfo.new((targetPos - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude/300, Enum.EasingStyle.Linear)
    local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = targetCFrame * CFrame.fromAxisAngle(Vector3.new(1,0,0), math.rad(0))})
    tween:Play()

    function tweenfunc:Stop()
        tween:Cancel()
        return tween
    end

    if not tween then return tween end
    return tweenfunc
end

getgenv().ToTargets = function(p)
    task.spawn(function()
        pcall(function()
            if game:GetService("Players").LocalPlayer:DistanceFromCharacter(p.Position) <= 250 then 
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = p
            elseif not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                local K = Instance.new("Part",game.Players.LocalPlayer.Character)
                K.Size = Vector3.new(1,0.5,1)
                K.Name = "Root"
                K.Anchored = true
                K.Transparency = 1
                K.CanCollide = false
                K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
            end
            local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude
            local z = game:service("TweenService")
            local B = TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)
            local S,g = pcall(function()
            local q = z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame = p})
            q:Play()
        end)
        if not S then 
            return g
        end
        game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            if S and game.Players.LocalPlayer.Character:FindFirstChild("Root") then 
                pcall(function()
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 then 
                        spawn(function()
                            pcall(function()
                                if (game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 150 then 
                                    game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                                else 
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame
                                end
                            end)
                        end)
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 10 then 
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                    end
                end)
            end
	    end)
    end)
end
    local r = game:GetService("Players").LocalPlayer
    getgenv().ToTarget = function(p)
        task.spawn(function()
            pcall(function()
                if r:DistanceFromCharacter(p.Position) <= 370 then 
                    r.Character.HumanoidRootPart.CFrame = p
                else
                    if not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                        local K = Instance.new("Part",game.Players.LocalPlayer.Character)
                        K.Size = Vector3.new(1,0.5,1)
                        K.Name = "Root"
                        K.Anchored = true
                        K.Transparency = 1
                        K.CanCollide = false
                        K.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
                    end
                    local U = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - p.Position).Magnitude
                    local z = game:service("TweenService")
                    local B = TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/370,Enum.EasingStyle.Linear)
                    local S , g = pcall(function()
                    local q = z:Create(game.Players.LocalPlayer.Character.Root,B,
                        {CFrame = p})
                        q:Play()
                    end)
                    if not S then 
                        return g
                    end
                    game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                    if S and game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
                        pcall(function()
                            if(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude >= 20 then 
                                spawn(function()
                                    pcall(function()
                                        if(game.Players.LocalPlayer.Character.Root.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 150 then
                                            game.Players.LocalPlayer.Character.Root.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.Root.CFrame
                                        end
                                    end)
                                end)
                            elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position - p.Position).Magnitude >= 10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude < 20 then 
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                            elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position - p.Position).Magnitude < 10 then 
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = p
                            end
                        end)
                    end
                end
            end)
        end)
    end
    
    function TP(Pos)
	pcall(function()
		game.Players.LocalPlayer.Character.Humanoid.Sit = false
	end)
	if (game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - Pos.Position).Magnitude <= 200 then
		pcall(function() 
			tween:Cancel()
		end)
		game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.CFrame = Pos
	else
		local tween_s = game:service"TweenService"
		local info = TweenInfo.new((game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart.Position - Pos.Position).Magnitude/300, Enum.EasingStyle.Linear)
		local tween, err = pcall(function()
			tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = Pos})
			tween:Play()
		end)
		if not tween then return err end
	end
end

local function L_3_func(...)
	local RealtargetPos = {
		...
	}
	local targetPos = RealtargetPos[1]
	local Pos
	if type(targetPos) == "vector" then
		Pos = CFrame.new(targetPos)
	elseif type(targetPos) == "userdata" then
		Pos = targetPos
	elseif type(targetPos) == "number" then
		Pos = CFrame.new(unpack(RealtargetPos))
	end

	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health == 0 then
		if tween then
			tween:Cancel()
		end
		repeat
			wait()
		until game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health > 0;
		wait(0.2)
	end

	local tweenfunc = {}
	local Distance = (Pos.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude

if getgenv().FarmModeRough then
	if Distance < 250 then
		Speed = 499
	elseif Distance < 330 then
		Speed = 378
	elseif Distance < 550 then
		Speed = 373
	elseif Distance < 800 then
		Speed = 370
	elseif Distance >= 1500 then
		Speed = 363
	end
end
if getgenv().FarmModeSmooth then
	if Distance < 850 then
		Speed = 350
	elseif Distance >= 850 then
		Speed = 350
	end
end
if getgenv().GoodVereNode then
    if Distance < 1000 then
		Speed = 999
	elseif Distance >= 1000 then
		Speed = 999
	end
end
	if _G.Settings.Configs["Bypass TP"] then
		if Distance > 3000 and not AutoFarmMaterial and not _G.Settings.FightingStyle["Auto God Human"] and not _G.Settings.Raids["Auto Raids"] and not (game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Backpack:FindFirstChild("God's Chalice") or game.Players.LocalPlayer.Character:FindFirstChild("God's Chalice") or game.Players.LocalPlayer.Backpack:FindFirstChild("Hallow Essence") or game.Players.LocalPlayer.Character:FindFirstChild("Hallow Essence") or game.Players.LocalPlayer.Character:FindFirstChild("Sweet Chalice") or game.Players.LocalPlayer.Backpack:FindFirstChild("Sweet Chalice")) and not (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") then
			pcall(function()
				tween:Cancel()
				fkwarp = false
				if game:GetService("Players")["LocalPlayer"].Data:FindFirstChild("spawnPoint").Value == tostring(L_2_func(Pos)) then 
					wait(.1)
					Com("F_", "TeleportTospawn")
				elseif game:GetService("Players")["LocalPlayer"].Data:FindFirstChild("LastspawnPoint").Value == tostring(L_2_func(Pos)) then
					game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
					wait(0.1)
					repeat
						wait()
					until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
				else
					if game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 then
						if fkwarp == false then
							game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						end
						fkwarp = true
					end
					wait(.08)
					game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
					repeat
						wait()
					until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
					wait(.1)
					Com("F_", "SetspawnPoint")
				end
				wait(0.2)
				return
			end)
		end
	end

	local tween_s = game:service"TweenService"
	local info = TweenInfo.new((Pos.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude / Speed, Enum.EasingStyle.Linear)
	local L_107_, L_108_ = pcall(function()
		tween = tween_s:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], info, {
			CFrame = Pos
		})
		tween:Play()
	end)

	function tweenfunc:Stop()
		tween:Cancel()
	end 

	function tweenfunc:Wait()
		tween.Completed:Wait()
	end 

	return tweenfunc
end
    WeaponList = {}
    
    for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do  
        if v:IsA("Tool") then
            table.insert(WeaponList, v.Name)
        end
    end
    
    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
        if v:IsA("Tool") then
            table.insert(WeaponList ,v.Name)
        end
    end
    
    local SelectP = L_16_:Dropdown("Select Weapon",WeaponList,_G.Settings.Configs["Select Weapon"],function(value)
        _G.Settings.Configs["Select Weapon"] = value
        print(value)
        SaveSettings()
    end)
    
    L_16_:Button("Refresh Weapon",function()
        SelectP:Clear()
        for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do  
            if v:IsA("Tool") then
                SelectP:Add(v.Name)
            end
        end
        
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
            if v:IsA("Tool") then
                SelectP:Add(v.Name)
            end
        end
    end)

    local Boss = {}

    for i, v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
        if string.find(v.Name, "Boss") then
            if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
                else
                table.insert(Boss, v.Name)
            end
        end
    end
    local BossName = L_16_:Dropdown("Select Boss",Boss,{""},function(value)
        _G.SelectBoss = value
    end)
    
    L_16_:Button("Refresh Boss",function()
        BossName:Clear()
            for i, v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
            if string.find(v.Name, "Boss") then
                BossName:Add(v.Name) 
            end
        end
    end)

L_16_:Label("Configs")

L_16_:Label("โปรดเลือกทุกครั้ง")
    _G.True = true
    _G.False = false
L_16_:Dropdown("Select Type Mode Farm",{"Mode : Rough","Mode : Smooth"},_G.Settings.Configs["SelectTypeModeFarm"],function(v)
    _G.Settings.Configs["SelectTypeModeFarm"] = v
    if _G.Settings.Configs["SelectTypeModeFarm"] == "Mode : Rough" then
        getgenv().FarmModeRough = _G.True
        getgenv().FarmModeSmooth = _G.False
    end
    if _G.Settings.Configs["SelectTypeModeFarm"] == "Mode : Smooth" then
        getgenv().FarmModeRough = _G.False
        getgenv().FarmModeSmooth = _G.True
    end
    SaveSettings()
end)
    spawn(function()
        while wait() do 
            pcall(function()
                if _G.Settings.Configs["SelectTypeModeFarm"] == "Mode : Rough" then
                    getgenv().FarmModeRough = _G.True
                    getgenv().FarmModeSmooth = _G.False
                end
                if _G.Settings.Configs["SelectTypeModeFarm"] == "Mode : Smooth" then
                    getgenv().FarmModeRough = _G.False
                    getgenv().FarmModeSmooth = _G.True
                end
            end)
        end
    end)

	local plr = game.Players.LocalPlayer
	local CbFw = getupvalues(require(plr.PlayerScripts.CombatFramework))
	local CbFw2 = CbFw[2]

    function GetCurrentBlade() 
        local p13 = CbFw2.activeController
        local ret = p13.blades[1]
        if not ret then return end
        while ret.Parent~=game.Players.LocalPlayer.Character do ret=ret.Parent end
        return ret
    end

    spawn(function()
        while task.wait(0.175) do
            if _G.FastAttackNormalPC then
                pcall(function()
                    local AC = CbFw2.activeController
                    for i = 1,1 do 
                        local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                            plr.Character,
                            {plr.Character.HumanoidRootPart},
                            60
                        )
                        local cac = {}
                        local hash = {}
                        for k, v in pairs(bladehit) do
                            if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                                table.insert(cac, v.Parent.HumanoidRootPart)
                                hash[v.Parent] = true
                            end
                        end
                        bladehit = cac
                        if #bladehit > 0 then
                            local u8 = debug.getupvalue(AC.attack, 5)
                            local u9 = debug.getupvalue(AC.attack, 6)
                            local u7 = debug.getupvalue(AC.attack, 4)
                            local u10 = debug.getupvalue(AC.attack, 7)
                            local u12 = (u8 * 798405 + u7 * 727595) % u9
                            local u13 = u7 * 798405
                            (function()
                                u12 = (u12 * u9 + u13) % 1099511627776
                                u8 = math.floor(u12 / u9)
                                u7 = u12 - u8 * u9
                            end)()
                            u10 = u10 + 1
                            debug.setupvalue(AC.attack, 5, u8)
                            debug.setupvalue(AC.attack, 6, u9)
                            debug.setupvalue(AC.attack, 4, u7)
                            debug.setupvalue(AC.attack, 7, u10)
                            if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then 
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                --game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "") 
                            end
                        end
                    end
                end)
            end
        end
    end)


L_16_:Toggle("Fast Attack [1] ดี ปลอดภัย -1%",_G.Settings.Configs["Fast Attack[1]"],function(value)
_G.Settings.Configs["Fast Attack[1]"] = value
_G.FastAttackNormalPC = value
	SaveSettings()
end)

spawn(function()
    while wait() do
		pcall(function()
			if getgenv().AccsF then
				Attack()
                Stpo()
			end
		end)
    end
end)

    local Client = game.Players.LocalPlayer
    local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
    local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
    spawn(function()
        while task.wait() do
            if getgenv().Fast then
                pcall(function()
                    if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
                    if not shared.cpc then shared.cpc = STOP.play end
                        STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                        local Hits = STOPRL.getBladeHits(b,c,d)
                        if Hits then
                            STOP.play = function() end
                            a:Play(0.01,0.01,0.01)
                            func(Hits)
                            STOP.play = shared.cpc
                            wait(a.length * 0.5)
                            a:Stop()
                        end
                    end
                end)
            end
        end
    end)

    local Module = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
    local CombatFramework = debug.getupvalues(Module)[2]
    local CameraShakerR = require(game.ReplicatedStorage.Util.CameraShaker)
spawn(function()
    while true do
        if getgenv().Fast then
            pcall(function()
                CameraShakerR:Stop()
                CombatFramework.activeController.attacking = false
                CombatFramework.activeController.timeToNextAttack = 0 --0
                CombatFramework.activeController.increment = 4  --3
                CombatFramework.activeController.hitboxMagnitude = 95
                CombatFramework.activeController.blocking = false
                CombatFramework.activeController.timeToNextBlock = 0 --0
                CombatFramework.activeController.focusStart = 0
                CombatFramework.activeController.humanoid.AutoRotate = true
            end)
        end
        task.wait(0.0)
    end
end)





local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
    local VirtualUser = game:GetService('VirtualUser')
    local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
    local Client = game:GetService("Players").LocalPlayer
    local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
    
    function SeraphFuckWeapon() 
        local p13 = SeraphFrame.activeController
        local wea = p13.blades[1]
        if not wea then return end
        while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
        return wea
    end
    
    function getHits(Size)
        local Hits = {}
        local Enemies = workspace.Enemies:GetChildren()
        local Characters = workspace.Characters:GetChildren()
        for i=1,#Enemies do local v = Enemies[i]
            local Human = v:FindFirstChildOfClass("Humanoid")
            if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                table.insert(Hits,Human.RootPart)
            end
        end
        for i=1,#Characters do local v = Characters[i]
            if v ~= game.Players.LocalPlayer.Character then
                local Human = v:FindFirstChildOfClass("Humanoid")
                if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                    table.insert(Hits,Human.RootPart)
                end
            end
        end
        return Hits
    end
    
    task.spawn(
        function()
        while wait(1) do
            if  getgenv().Fast then
                if SeraphFrame.activeController then
                    -- if v.Humanoid.Health > 0 then
                        SeraphFrame.activeController.timeToNextAttack = 1
                        SeraphFrame.activeController.focusStart = 0
                        SeraphFrame.activeController.hitboxMagnitude = 40
                        SeraphFrame.activeController.humanoid.AutoRotate = true
                        SeraphFrame.activeController.increment = 1 + 1 / 1
                    -- end
                end
            end
        end
    end)
    


    spawn(function()
        while wait() do
            if getgenv().Fast then
            for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
                if v.Name == "CurvedRing" or v.Name == "DamageCounter" or v.Name == "SwordSlash" or v.Name == "Damage" or v.Name == "Mon" or v.Name == "Sounds" then
                    v:Destroy() 
                end
            end
        end
        end
    end)
        
    spawn(function()
        while wait() do
        if getgenv().Fast then
            for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
                if v.Name == "CurvedRing" or v.Name == "SlashHit" or v.Name == "DamageCounter" or v.Name == "SwordSlash" or v.Name == "SlashTail" or v.Name == "Sounds" then
                    v:Destroy() 
                end
            end
        end
        end
    end) 


    function Boost()
        spawn(function()
        game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
        end)
    end
    
    function Unboost()
        spawn(function()
            game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
        end)
    end
    
    local cdnormal = 0
    local Animation = Instance.new("Animation")
    local CooldownFastAttack = 0
    Attack = function()
        local ac = SeraphFrame.activeController
        if ac and ac.equipped then
            task.spawn(
                function()
                if tick() - cdnormal > 0.5 then
                    ac:attack()
                    cdnormal = tick()
                else
                     Animation.AnimationId = ac.anims.basic[2]
                    ac.humanoid:LoadAnimation(Animation):Play(2, 2) --ท่าไม่ทำงานแก้เป็น (1,1)
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
                end
            end)
        end
    end
    
    b = tick()
    spawn(function()
        while wait(0) do
            if  getgenv().Fast then
                if b - tick() > 0.75 then
                    wait(.2)
                    b = tick()
                end
                pcall(function()
                    for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                        if v.Humanoid.Health > 0 then
                            if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                Attack()
                                wait(.5)
                                Boost()
                            end
                        end
                    end
                end)
            end
        end
    end)
    
    k = tick()
    spawn(function()
        while wait(0) do
            if  getgenv().Fast then
                if k - tick() > 0.75 then
                    wait()
                    k = tick()
                end
                pcall(function()
                    for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                        if v.Humanoid.Health > 0 then
                            if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                            wait()
                            Unboost()
                            end
                        end
                    end
                end)
            end
        end
    end)
    
    tjw1 = true
    task.spawn(
        function()
            local a = game.Players.LocalPlayer
            local b = require(a.PlayerScripts.CombatFramework.Particle)
            local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
            if not shared.orl then
                shared.orl = c.wrapAttackAnimationAsync
            end
            if not shared.cpc then
                shared.cpc = b.play
            end
            if tjw1 then
                pcall(
                    function()
                        c.wrapAttackAnimationAsync = function(d, e, f, g, h)
                            local i = c.getBladeHits(e, f, g)
                            if i then
                                b.play = function()
                                end
                                d:Play(1.175, 2.25, 3.25, 5.25)
                                h(i)
                                b.play = shared.cpc
                                wait()
                                d:Stop(0.0)
                            end
                        end
                    end
                )
            end
        end
    )
    
    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.Particle.SlashHit).playAt = function() return nil end;
    getgenv().A = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync 
    getgenv().B = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.Particle).play
    spawn(function()
        while wait() do
            if getgenv().AttackFunction then
                pcall(function()
                    require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync =function(a1,a2,a3,a4,a5)
                        local GetBladeHits = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).getBladeHits(a2,a3,a4)
                        if GetBladeHits then
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = function() end;
                            a1:Play(0.1, 0.1, 0.1);
                            a5(GetBladeHits);
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = getgenv().B 
                            wait(.5);
                            a1:Stop();
                        end;
                    end;
                end);
            end
        end;
    end);
    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.Particle.SlashHit).playAt = function() return nil end;
    getgenv().A = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync 
    getgenv().B = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.Particle).play
    spawn(function()
        while wait() do
            if getgenv().AttackFunction then
                pcall(function()
                    require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync =function(a1,a2,a3,a4,a5)
                        local GetBladeHits = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).getBladeHits(a2,a3,a4)
                        if GetBladeHits then
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = function() end;
                            a1:Play(0.1, 0.1, 0.1);
                            a5(GetBladeHits);
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = getgenv().B 
                            wait(.5);
                            a1:Stop();
                        end;
                    end;
                end);
            end
        end;
    end);
    
spawn(function()
    while wait(.10) do
        pcall(function()
            if getgenv().AttackFunction then
                repeat wait()
                    FastAttackNoCD()
                until not getgenv().AttackFunction
            end
        end)
    end
end)

	local plr = game.Players.LocalPlayer
	local CbFw = getupvalues(require(plr.PlayerScripts.CombatFramework))
	local CbFw2 = CbFw[2]

    function GetCurrentBlade() 
        local p13 = CbFw2.activeController
        local ret = p13.blades[1]
        if not ret then return end
        while ret.Parent~=game.Players.LocalPlayer.Character do ret=ret.Parent end
        return ret
    end

spawn(function()
        while task.wait(0) do
            if _G.FastAttackNormalSpeed then
                pcall(function()
                    local AC = CbFw2.activeController
                    for i = 1,1 do 
                        local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                            plr.Character,
                            {plr.Character.HumanoidRootPart},
                            60
                        )
                        local cac = {}
                        local hash = {}
                        for k, v in pairs(bladehit) do
                            if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                                table.insert(cac, v.Parent.HumanoidRootPart)
                                hash[v.Parent] = true
                            end
                        end
                        bladehit = cac
                        if #bladehit > 0 then
                            local u8 = debug.getupvalue(AC.attack, 5)
                            local u9 = debug.getupvalue(AC.attack, 6)
                            local u7 = debug.getupvalue(AC.attack, 4)
                            local u10 = debug.getupvalue(AC.attack, 7)
                            local u12 = (u8 * 798405 + u7 * 727595) % u9
                            local u13 = u7 * 798405
                            (function()
                                u12 = (u12 * u9 + u13) % 1099511627776
                                u8 = math.floor(u12 / u9)
                                u7 = u12 - u8 * u9
                            end)()
                            u10 = u10 + 1
                            debug.setupvalue(AC.attack, 5, u8)
                            debug.setupvalue(AC.attack, 6, u9)
                            debug.setupvalue(AC.attack, 4, u7)
                            debug.setupvalue(AC.attack, 7, u10)
                            if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then 
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                --game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "") 
                            end
                        end
                    end
                end)
            end
        end
end)

    function FastAttackNoCD()
        pcall(function()
                local AC = CbFw2.activeController
                for i = 1, 1 do 
                    local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                        plr.Character,
                        {plr.Character.HumanoidRootPart},
                        80
                    )
                    local cac = {}
                    local hash = {}
                    for k, v in pairs(bladehit) do
                        if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                            table.insert(cac, v.Parent.HumanoidRootPart)
                            hash[v.Parent] = true
                        end
                    end
                    bladehit = cac
                    if #bladehit > 0 then
                        local u8 = debug.getupvalue(AC.attack, 5)
                        local u9 = debug.getupvalue(AC.attack, 6)
                        local u7 = debug.getupvalue(AC.attack, 4)
                        local u10 = debug.getupvalue(AC.attack, 7)
                        local u12 = (u8 * 798405 + u7 * 727595) % u9
                        local u13 = u7 * 798405
                        (function()
                            u12 = (u12 * u9 + u13) % 1099511627776
                            u8 = math.floor(u12 / u9)
                            u7 = u12 - u8 * u9
                        end)()
                        u10 = u10 + (u8 + u9 + u7 + u10) * (798405 * u13 + 727595 * u12) / 1 + 1 -- % 1099511627776 - 16777215 / u12-- 1
                        debug.setupvalue(AC.attack, 5, u8)
                        debug.setupvalue(AC.attack, 6, u9)
                        debug.setupvalue(AC.attack, 4, u7)
                        debug.setupvalue(AC.attack, 7, u10)
                        --pcall(function()
                        --if  then--plr.Character:FindFirstChildOfClass("Tool") and
                            if _G.FastAttackNormalSpeed and plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then
                                AC.animator.anims.basic[1]:Play(0.01,0.01,0.01)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                --game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10 / 1099511627776 * 16777215)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "")
                                --AttackPlayersFunction() AttackOK()
                            end
                        --end
                        --end)
                    end
                end
        end)
    end


--[[
if getgenv().AttackFunction then
   -- Attack()
   -- AttackPlayersFunction()
   -- AttackOK()
   -- AttackAC()
   -- KoAttackOK()
    _G.FastAttackNormalSpeed = true
    _G.AutoGoGoGoFarm = true
    FastAttack = true
    AttackPlayersFunction()
    AttackOK()
end
]]

    b = tick()
    spawn(function()
        while wait(0) do
            if  getgenv().AttackFunction then
                if b - tick() > .75 then
                    pcall(function()
                        b = tick()
                    end)
                end
                pcall(function()
                    Attack()
                    for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                        if v.Humanoid.Health > 0 then
                            if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                Boost()
                            end
                        end
                    end
                end)
            end
        end
    end)










L_16_:Toggle("Fast Attack [2] แนะนำ โอกาศ 99.99%",_G.Settings.Configs["Fast Attack[2]"],function(value)
_G.Settings.Configs["Fast Attack[2]"] = value
_G.FastAttack = value
_G.Settings.Configs["Disabled Damage"] = value
--_G.DelEFX = value
	SaveSettings()
end)

L_16_:Toggle("Fast Attack [3] แนะนำเหมือนกัน โดนเตะ 100%",_G.Settings.Configs["Fast Attack[3]"],function(value)
_G.Settings.Configs["Fast Attack[3]"] = value


getgenv().Fast = value
_G.SupGodFastAttack = value
--FastAttack = value
getgenv().AttackFunction = value

_G.SupFastAttack = value
	SaveSettings()
end)

	------------ // Fast Attack 1 \\ ------------
	local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
	local VirtualUser = game:GetService('VirtualUser')
	local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
	local Client = game:GetService("Players").LocalPlayer
	local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
	
	function SeraphFuckWeapon() 
		local p13 = SeraphFrame.activeController
		local wea = p13.blades[1]
		if not wea then return end
		while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
		return wea
	end
	
	function getHits(Size)
		local Hits = {}
		local Enemies = workspace.Enemies:GetChildren()
		local Characters = workspace.Characters:GetChildren()
		for i=1,#Enemies do local v = Enemies[i]
			local Human = v:FindFirstChildOfClass("Humanoid")
			if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
				table.insert(Hits,Human.RootPart)
			end
		end
		for i=1,#Characters do local v = Characters[i]
			if v ~= game.Players.LocalPlayer.Character then
				local Human = v:FindFirstChildOfClass("Humanoid")
				if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
					table.insert(Hits,Human.RootPart)
				end
			end
		end
		return Hits
	end
	
	task.spawn(
		function()
		while wait(0) do
			if  _G.PlayGay then
				if SeraphFrame.activeController then
					if v.Humanoid.Health > 0 then
					SeraphFrame.activeController.attacking = false
						SeraphFrame.activeController.timeToNextBlock = 0
						SeraphFrame.activeController.humanoid.AutoRotate = true
						SeraphFrame.activeController.increment = 5
						SeraphFrame.activeController.blocking = false
						SeraphFrame.activeController.hitboxMagnitude = 150
						SeraphFrame.activeController.timeToNextAttack = 0
						SeraphFrame.activeController.focusStart = 0
						SeraphFrame.activeController.humanoid.AutoRotate = true
						SeraphFrame.activeController.increment = 1 + 1 / 1
					end
				end
			end
		end
	end)
	
	function Boost()
		spawn(function()
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
		end)
	end
	
	function Unboost()
		spawn(function()
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
		end)
	end
	
	local cdnormal = 8.0
	local Animation = Instance.new("Animation")
	local CooldownFastAttack = 0
	Attack = function()
		local ac = SeraphFrame.activeController
		if ac and ac.equipped then
			task.spawn(
				function()
				if tick() - cdnormal > 0.5 then
					ac:attack()
					cdnormal = tick()
				else
					Animation.AnimationId = ac.anims.basic[2]
					ac.humanoid:LoadAnimation(Animation):Play(0.05,0.05) --ท่าไม่ทำงานแก้เป็น (1,1)
					game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(1), 1, "")
				end
			end)
		end
	end
	
	b = tick()
	spawn(function()
		while wait(0) do
			if  _G.PlayGay then
				if b - tick() > 0.5 then
					wait(.2)
					b = tick()
				end
				pcall(function()
					for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Humanoid.Health > 0 then
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then
								Attack()
								wait(0)
								Boost()
							end
						end
					end
				end)
			end
		end
	end)
	
	k = tick()
	spawn(function()
		while wait(0) do
			if  _G.PlayGay then
				if k - tick() > 0.5 then
					wait(0)
					k = tick()
				end
				pcall(function()
					for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Humanoid.Health > 0 then
							if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then
							wait(0)
							Unboost()
							end
						end
					end
				end)
			end
		end
	end)
	
	tjw1 = true
	task.spawn(
		function()
			local a = game.Players.LocalPlayer
			local b = require(a.PlayerScripts.CombatFramework.Particle)
			local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
			if not shared.orl then
				shared.orl = c.wrapAttackAnimationAsync
			end
			if not shared.cpc then
				shared.cpc = b.play
			end
			if tjw1 then
				pcall(
					function()
						c.wrapAttackAnimationAsync = function(d, e, f, g, h)
							local i = c.getBladeHits(e, f, g)
							if i then
								b.play = function()
								end
								d:Play(0.25, 0.25, 0.25)
								h(i)
								b.play = shared.cpc
								wait(0)
								d:Stop()
							end
						end
					end
				)
			end
		end
	)
	
	local Client = game.Players.LocalPlayer
	local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
	local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
	task.spawn(function()
		pcall(function()
			if not shared.orl then
				shared.orl = STOPRL.wrapAttackAnimationAsync
			end
				if not shared.cpc then
					shared.cpc = STOP.play 
				end
			spawn(function()
				require(game.ReplicatedStorage.Util.CameraShaker):Stop()
				require(game.ReplicatedStorage.Util.CameraShaker):Stop()
				game:GetService("RunService").Stepped:Connect(function()
					STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
						local Hits = STOPRL.getBladeHits(b,c,d)
						if Hits then
							if _G.PlayGay then
								STOP.play = function() end
								a:Play(0.01,0.01,0.01)
								func(Hits)
								STOP.play = shared.cpc
								wait(.5)
								a:Stop()
							else
								func(Hits)
								STOP.play = shared.cpc
								wait(.5)
								a:Stop()
							end
						end
					end
				end)
			end)
		end)
	end)

L_16_:Toggle("Fast Attack [4]",_G.Settings.Configs["Fast Attack[4]"],function(value)
	_G.Settings.Configs["Fast Attack[4]"] = value
	_G.PlayGay = value
	SaveSettings()
end)

task.spawn(function()
	while wait() do
		pcall(function()
			game:GetService("ReplicatedStorage").Assets.GUI.DamageCounter.Enabled = true
		end)
	end
end)
task.spawn(function()
	local Camera = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
	while wait() do
		pcall(function()
			Camera.CameraShakeInstance.CameraShakeState.Inactive = 0
		end)
	end
end)

local YaY = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local CameraShakerR = require(game.ReplicatedStorage.Util.CameraShaker)
spawn(function()
	while task.wait() do
		if _G.FastAttack then
			pcall(function()
				for i,CombatFrameworkR in pairs(debug.getupvalues(YaY)) do
					if i == 2 then
						CameraShakerR:Stop()
						CombatFrameworkR.activeController.attacking = false
						CombatFrameworkR.activeController.timeToNextAttack = 0
						CombatFrameworkR.activeController.increment = 4
						CombatFrameworkR.activeController.increment = 2
						CombatFrameworkR.activeController.hitboxMagnitude = 60
						CombatFrameworkR.activeController.blocking = false
						CombatFrameworkR.activeController.timeToNextBlock = 0
						CombatFrameworkR.activeController.focusStart = 0
						CombatFrameworkR.activeController.humanoid.AutoRotate = true
					end
				end
			end)
		else
			for i,CombatFrameworkR in pairs(debug.getupvalues(YaY)) do
				if i == 2 then
					pcall(function()
						CameraShakerR:Stop()
						CombatFrameworkR.activeController.attacking = false
						CombatFrameworkR.activeController.hitboxMagnitude = 60
						CombatFrameworkR.activeController.blocking = false
						CombatFrameworkR.activeController.focusStart = 0
						CombatFrameworkR.activeController.humanoid.AutoRotate = true
					end)
				end
			end
		end
	end
end)
spawn(function()
	game:GetService('RunService').Stepped:Connect(function()
		if _G.FastAttack then
			for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
				if v.Name == "Sounds" then--or v.Name == "SlashHit"
					v:Destroy() 
				end
			end
		end
	end)
end)

--[[L_16_:Toggle("Fast Attack [4] โตรดแม่ Fast",_G.Settings.Configs["Fast Attack[4]"],function(value)
_G.Settings.Configs["Fast Attack[4]"] = value
_G.SupGodFastAttack = value
FastAttack = value
	SaveSettings()
end)]]

	local plr = game.Players.LocalPlayer
	local CbFw = getupvalues(require(plr.PlayerScripts.CombatFramework))
	local CbFw2 = CbFw[2]

    function GetCurrentBlade() 
        local p13 = CbFw2.activeController
        local ret = p13.blades[1]
        if not ret then return end
        while ret.Parent~=game.Players.LocalPlayer.Character do ret=ret.Parent end
        return ret
    end
    
    function AttackNoCDGod()
        if not Auto_Farm_Bounty and not Auto_Farm_Fruit or Mix_Farm then
            if not Auto_Raid then
                local AC = CbFw2.activeController
                for i = 1, 1 do 
                    local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                        plr.Character,
                        {plr.Character.HumanoidRootPart},
                        60
                    )
                    local cac = {}
                    local hash = {}
                    for k, v in pairs(bladehit) do
                        if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                            table.insert(cac, v.Parent.HumanoidRootPart)
                            hash[v.Parent] = true
                        end
                    end
                    bladehit = cac
                    if #bladehit > 0 then
                        local u8 = debug.getupvalue(AC.attack, 5)
                        local u9 = debug.getupvalue(AC.attack, 6)
                        local u7 = debug.getupvalue(AC.attack, 4)
                        local u10 = debug.getupvalue(AC.attack, 7)
                        local u12 = (u8 * 798405 + u7 * 727595) % u9
                        local u13 = u7 * 798405
                        (function()
                            u12 = (u12 * u9 + u13) % 1099511627776
                            u8 = math.floor(u12 / u9)
                            u7 = u12 - u8 * u9
                        end)()
                        u10 = u10 + 1
                        io = io + 1
                        debug.setupvalue(AC.attack, 5, u8)
                        debug.setupvalue(AC.attack, 6, u9)
                        debug.setupvalue(AC.attack, 4, u7)
                        debug.setupvalue(AC.attack, 7, u10)
                        pcall(function()
                            if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[2] then
                                for ixxx = 1,5 do
                                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                    --game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
                                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i + io / 1 + ixxx/5 , "")
                                end
                            end
                        end)
                    end
                end
            end
        end
    end
            function Boost()
                spawn(function()
                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
                end)
            end
            
            function Unboost()
                spawn(function()
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
                end)
            end
            
            b = tick()
            spawn(function()
                while wait(0) do
                    if  _G.SupGodFastAttack then
                        if b - tick() > 0.75 then
                            wait(.2)
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then
                                        Attack()
                                        wait(0)
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            k = tick()
            spawn(function()
                while wait(0) do
                    if  _G.SupGodFastAttack then
                        if k - tick() > 0.75 then
                            wait(0)
                            k = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then
                                    wait(0)
                                    Unboost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)


spawn(function()
	while true do wait()
		pcall(function()
			if _G.SupGodFastAttack then
				repeat wait()
				    AttackNoCDGod()
				until not _G.SupGodFastAttack
			end
		end)
		task.wait()
	end
end)

--[[L_16_:Toggle("Disabled Damage Effect",_G.Settings.Configs["Disabled Damage"],function(value)

	SaveSettings()
end)]]

spawn(function()
	pcall(function()
	    if _G.Settings.Configs["Disabled Damage"] then
		    while wait() do
				game:GetService("ReplicatedStorage").Effect.Container.Death:Destroy()
			end
		end
	end)
end)

--[[spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
	    if _G.Settings.Configs["Disabled Damage"] then
		if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
			setfflag("HumanoidParallelRemoveNoPhysics", "False")
			setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
			game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
		end
		end
	end)
end)]]

if game:IsLoaded() then
    if _G.Settings.Configs["Disabled Damage"] then
        pcall(function()
        repeat wait()
            game:GetService("ReplicatedStorage").Effect.Container.Death:Destroy()
        until not game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Death")
        end)
    end
end

spawn(function()
    if _G.Settings.Configs["Disabled Damage"] then
        game:GetService('RunService').Stepped:Connect(function()
            for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
                if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then
                    v:Destroy()
                end
            end
        end)
    end
end)

--[[local Client = game.Players.LocalPlayer
local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
task.spawn(function()
	pcall(function()
		if not shared.orl then
			shared.orl = STOPRL.wrapAttackAnimationAsync
		end
			if not shared.cpc then
				shared.cpc = STOP.play 
			end
		spawn(function()
			game:GetService("RunService").Stepped:Connect(function()
				STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
					local Hits = STOPRL.getBladeHits(b,c,d)
					if Hits then
						if _G.Settings.Configs["Disabled Damage"] then
							STOP.play = function() end
							a:Play(2.1,2.1,2.1)
							func(Hits)
							STOP.play = shared.cpc
							wait(a.length * 0.5)
							a:Stop()
						else
							func(Hits)
							STOP.play = shared.cpc
							wait(a.length * 0.5)
							a:Stop()
						end
					end
				end
			end)
		end)
	end)
end)]]
--[[
spawn(function()
	while wait(.5) do
		pcall(function()
			if _G.SupFastAttack then
			if getgenv().FarmModeRough then
				repeat wait(0.1)
					AttackNoCD()
				until not _G.SupFastAttack
			end
			end
		end)
	end
end)


spawn(function()
	while wait(.5) do
		pcall(function()
			if _G.SupFastAttack then 
			if getgenv().FarmModeSmooth then
				repeat wait(0.3)
					AttackNoCD()
				until not _G.SupFastAttack
			end
			end
		end)
	end
end)]]

L_16_:Label("Configs Farm Level")

L_16_:Toggle("Bypass รีตัวฟาร์ม โดนแบนแน่นอน 300%",_G.Settings.Configs["Bypass"],function(s)
    _G.Settings.Configs["Bypass"] = s
end)

spawn(function()
    while wait() do wait(2)
        pcall(function()
            CheckQuest()
            if _G.Settings.Configs["Bypass"] and not _G.Settings.Main["Fast Farm"] and Auto_Farm_Level and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1500 then
--            if getgenv().Bypass == true then
                game:GetService("RunService"):Set3dRenderingEnabled(false)
                BTP(CFrameQuest) --BTP(CFrameSetPoint)
                game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
				wait(0.1)
				repeat wait()
				    --game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameSetPoint
				    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
	                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest game:GetService("RunService"):Set3dRenderingEnabled(false)
				until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
				repeat wait()
				    game:GetService("RunService"):Set3dRenderingEnabled(false)
				until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
            end
            --end
        end)
    end
end)

L_16_:Toggle("Tween Quest",true,function(L_163_arg0)
    if L_163_arg0 == true then
        NoTweenQuest = false
        TweenQuest = true
    elseif L_163_arg0 == false then
        NoTweenQuest = true
        TweenQuest = false
    end
end)


    L_16_:Toggle("Bypass God Mode ใส่มาปั่นๆ โดนแบนแน่นวน",false,function(d)
        if d == false then
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetTeam","Marines")
        end
        getgenv().GoodVereNode = d
        spawn(function()
            while wait() do 
                pcall(function()
                    if getgenv().GoodVereNode then
                        game.Players.LocalPlayer.Character.Humanoid:SetStateEnabled(15, false)
                        game.Players.LocalPlayer.Character.Humanoid:SetStateEnabled(16, false)
                        game.Players.LocalPlayer.Character.Humanoid.Health = math.huge
                        game.Players.LocalPlayer.Character.Humanoid.Health = game.Players.LocalPlayer.Character.Humanoid.MaxHealth
                        game.Players.LocalPlayer.Character.Shirt:Destroy()
                        game.Players.LocalPlayer.Character.Pants:Destroy()
                        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 0
                        game.Players.LocalPlayer.Character.Animate.Disabled = true
                        for w, e in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                            if e.ClassName == "Accessory" then
                                e:Destroy()
                            end
                        end
                    end
                end)
            end
        end)
    end)

L_16_:Toggle("Auto Farm Fast Farm",_G.Settings.Main["Fast Farm"],function(L_163_arg0)
_G.Settings.Main["Fast Auto Farm Level"] = L_163_arg0
_G.Settings.Main["Fast Farm"] = L_163_arg0
	if L_163_arg0 == false then
		wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
	SaveSettings()
end)

L_16_:Label("Auto Skill Settings")

L_16_:Toggle("Skill Z",_G.Settings.Configs["SkillZ"],function(a)
	_G.Settings.Configs["SkillZ"] = a
	_G.SkillZ = a
end)

L_16_:Toggle("Skill X",_G.Settings.Configs["SkillX"],function(a)
	_G.Settings.Configs["SkillX"] = a
	_G.SkillX = a
end)

L_16_:Toggle("Skill C",_G.Settings.Configs["SkillC"],function(a)
	_G.Settings.Configs["SkillC"] = a
	_G.SkillC = a
end)

L_16_:Toggle("Skill V",_G.Settings.Configs["SkillV"],function(a)
	_G.Settings.Configs["SkillV"] = a
	_G.SkillV = a
end)

L_14_1:Label("Auto Farm Level")
function bypass(Point)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Point
end
L_14_1:Toggle("Auto Farm Level         *",_G.Settings.Main["Auto Farm Level"],function(s)
_G.Settings.Main["Auto Farm Level"] = s
Auto_Farm_Level = s
--getgenv().Bypass = s
	if s == false then
		wait()
		Com("F_", "AbandonQuest");
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
	SaveSettings()
end)

L_14_1:Button("Redeem All Code",function()
spawn(function()
    function Redeem(L_166_arg0)
		game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(L_166_arg0)
	end
	for d, t in pairs(L_4_) do
		Redeem(t) 
	end
end)
end)

--[[if World1 then
L_14_1:Toggle("Double Quest",_G.Settings.Configs["Double Quest"],function(a)
_G.Settings.Configs["Double Quest"] = a
	if a == false then
		wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
	SaveSettings()
end)
end]]

AttackRandomType = 1
spawn(function()
	while wait() do 
		AttackRandomType = math.random(1, 5)  --5
		wait(0.3)
	end
end)

spawn(function()
    while task.wait() do
        pcall(function()
            if _G.Settings.Main["Auto Farm Gun Mastery"] then
                CheckQuest()
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if _G.Settings.Main["Auto Farm Gun Mastery"] and StartMagnet and v.Name == Name and v.Name == NameBoss and (Name == "Factory Staff [Lv. 800]" or Name == "Monkey [Lv. 14]" or Name == "Dragon Crew Warrior [Lv. 1575]" or Name == "Dragon Crew Archer [Lv. 1600]" or Name == "Head Baker [Lv. 2275]" or Name == "Baking Staff [Lv. 2250]" or Name == "Cake Guard [Lv. 2225]") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 123 then
                        v.HumanoidRootPart.CFrame = PosMon
                        v.Humanoid:ChangeState(14)
                        v.HumanoidRootPart.CanCollide = false
                        v.Head.CanCollide = false
                        if v.Humanoid:FindFirstChild("Animator") then
                            v.Humanoid.Animator:Destroy()
                        end
                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                    elseif _G.Settings.Main["Auto Farm Gun Mastery"] and StartMagnet and v.Name == Name and v.Name == NameBoss and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 100 then
                        v.HumanoidRootPart.CFrame = PosMon
                        v.Humanoid:ChangeState(14)
                        v.HumanoidRootPart.CanCollide = false
                        v.Head.CanCollide = false
                        if v.Humanoid:FindFirstChild("Animator") then
                            v.Humanoid.Animator:Destroy()
                        end
                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while wait() do
        pcall(function()
        if AutoFarmLevel then
        if GetQuest.Visible == true then
			if game:GetService("Workspace").Enemies:FindFirstChild(Name).HumanoidRootPart then
				for L_188_forvar0, L_189_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if _G.Settings.Main["Auto Farm Level"] and L_189_forvar1.Name == Name and L_189_forvar1:FindFirstChild("HumanoidRootPart") and L_189_forvar1:FindFirstChild("Humanoid") and L_189_forvar1.Humanoid.Health > 0 and (L_189_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 220 then --220
						if string.find(GetQuestTitle.Text, NameMon) then
							repeat game:GetService("RunService").Heartbeat:wait()
							    game:GetService'VirtualUser':CaptureController()
							    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not AutoFarmLevel == false
						end
					end
				end
			end
        end
        end
        end)
    end
end)


_G.RedeemCodeLocalFastAutoFarm = false
function AutoFarmLevel()
	GetQuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title
	GetQuest = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest
	local L_165_ = game.Players.LocalPlayer.Data.Level.Value

	if _G.Settings.Main["Fast Farm"] and (L_165_ >= 15 and L_165_ <= 300) then
		if _G.Settings.Configs["Auto Haki"] then
			if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
			end
		end
		if _G.RedeemCodeLocalFastAutoFarm == false then
			function Redeem(L_166_arg0)
				game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(L_166_arg0)
			end
			for L_167_forvar0, L_168_forvar1 in pairs(L_4_) do
				Redeem(L_168_forvar1) 
			end
			wait()
			_G.RedeemCodeLocalFastAutoFarm = true
		end
		if L_165_ >= 15 and L_165_ <= 70 then
			local L_169_ = CFrame.new(- 4698, 845, - 1912)
			if game:GetService("Workspace").Enemies:FindFirstChild("God's Guard [Lv. 450]") then
				for L_170_forvar0, L_171_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if _G.Settings.Main["Fast Auto Farm Level"] and L_171_forvar1.Name == "God's Guard [Lv. 450]" and L_171_forvar1:FindFirstChild("HumanoidRootPart") and L_171_forvar1:FindFirstChild("Humanoid") and L_171_forvar1.Humanoid.Health > 0 then
						repeat
							wait()
							EquipWeapon(_G.Settings.Configs["Select Weapon"])
							FarmtoTarget = L_3_func(L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
							if L_171_forvar1:FindFirstChild("HumanoidRootPart") and L_171_forvar1:FindFirstChild("Humanoid") and (L_171_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
								if FarmtoTarget then
									FarmtoTarget:Stop()
								end
								game.ReplicatedStorage:WaitForChild("Remotes").CommF_:InvokeServer("AbandonQuest")
								for L_172_forvar0, L_173_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do 
									if _G.Settings.Main["Fast Auto Farm Level"] and L_173_forvar1.Name == "God's Guard [Lv. 450]" and L_173_forvar1:FindFirstChild("HumanoidRootPart") and L_173_forvar1:FindFirstChild("Humanoid") and L_173_forvar1.Humanoid.Health > 0 then
										if InMyNetWork(L_173_forvar1.HumanoidRootPart) then
											L_173_forvar1.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame
											L_173_forvar1.Humanoid.JumpPower = 0
											L_173_forvar1.Humanoid.WalkSpeed = 0
											L_173_forvar1.HumanoidRootPart.CanCollide = false
											L_173_forvar1.Humanoid:ChangeState(14)
											L_173_forvar1.Humanoid:ChangeState(11)
											L_173_forvar1.HumanoidRootPart.Size = Vector3.new(55, 55, 55)
										end
									end
								end
								if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
									game:service("VirtualInputManager"):SendKeyEvent(true, "V", false, game)
									game:service("VirtualInputManager"):SendKeyEvent(false, "V", false, game)
								end
								if AttackRandomType == 1 then
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 60, 1)
								elseif AttackRandomType == 2 then
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 1, 60)
								elseif AttackRandomType == 3 then
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(1, 1, - 60)
								elseif AttackRandomType == 4 then
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(60, 1, 0)
								elseif AttackRandomType == 5 then
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(- 60, 1, 0)
								else
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 60, 1)
								end
								local MonHealth2 = L_171_forvar1.Humanoid.MaxHealth * 35/100
								if L_171_forvar1.Humanoid.Health <= MonHealth2 then
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,10,0)
                                    _G.FastAttackNormalSpeed = true _G.AutoGoGoGoFarm =true AttackPlayersFunction() AttackOK()
                                else
                                    _G.FastAttackNormalSpeed = false _G.AutoGoGoGoFarm=false
                                end
								EquipWeapon(_G.Settings.Configs["Select Weapon"])
							end
						until not (game:GetService("Workspace").Enemies:FindFirstChild("God's Guard [Lv. 450]")) or not (_G.Settings.Main["Fast Auto Farm Level"] or _G.Settings.Main["Auto Farm Level"]) or L_171_forvar1.Humanoid.Health <= 0 or not L_171_forvar1.Parent
					end
				end
			else
				Modstween = L_3_func(L_169_)
				if World1 and (L_169_.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 1500 then
					if Modstween then
						Modstween:Stop()
					end
					wait(.5)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
				elseif (L_169_.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
					if Modstween then
						Modstween:Stop()
					end
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_169_
				end 
			end
		elseif L_165_ >= 70 and L_165_ <= 300 then
			if GetQuest.Visible == false then
				if not tostring(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")):find("We heard some") then 
					local L_174_ = CFrame.new(- 4698, 845, - 1912)
					if game:GetService("Workspace").Enemies:FindFirstChild("God's Guard [Lv. 450]") then
						for L_175_forvar0, L_176_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if _G.Settings.Main["Fast Auto Farm Level"] and L_176_forvar1.Name == "God's Guard [Lv. 450]" and L_176_forvar1:FindFirstChild("HumanoidRootPart") and L_176_forvar1:FindFirstChild("Humanoid") and L_176_forvar1.Humanoid.Health > 0 then
								repeat
									wait()
									EquipWeapon(_G.Settings.Configs["Select Weapon"])
									FarmtoTarget = L_3_func(L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
									if L_176_forvar1:FindFirstChild("HumanoidRootPart") and L_176_forvar1:FindFirstChild("Humanoid") and (L_176_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
										if FarmtoTarget then
											FarmtoTarget:Stop()
										end
										for L_177_forvar0, L_178_forvar1 in pairs(game:GetService("Workspace")["_WorldOrigin"].EnemySpawns:GetChildren()) do 
											if _G.Settings.Main["Fast Auto Farm Level"] and L_178_forvar1.Name == "God's Guard [Lv. 450]" and L_178_forvar1:FindFirstChild("HumanoidRootPart") and L_178_forvar1:FindFirstChild("Humanoid") and L_178_forvar1.Humanoid.Health > 0 then
												if InMyNetWork(L_178_forvar1.HumanoidRootPart) then
													L_178_forvar1.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame
													L_178_forvar1.Humanoid.JumpPower = 0
													L_178_forvar1.Humanoid.WalkSpeed = 0
													L_178_forvar1.HumanoidRootPart.CanCollide = false
													L_178_forvar1.Humanoid:ChangeState(14)
													L_178_forvar1.Humanoid:ChangeState(11)
													L_178_forvar1.HumanoidRootPart.Size = Vector3.new(55, 55, 55)
												end
											end
										end
										if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
											game:service("VirtualInputManager"):SendKeyEvent(true, "V", false, game)
											game:service("VirtualInputManager"):SendKeyEvent(false, "V", false, game)
										end
										if AttackRandomType == 1 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 60, 1)
										elseif AttackRandomType == 2 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 1, 60)
										elseif AttackRandomType == 3 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(1, 1, - 60)
										elseif AttackRandomType == 4 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(60, 1, 0)
										elseif AttackRandomType == 5 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(- 60, 1, 0)
										else
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 60, 1)
										end
										local MonHealth2 = L_176_forvar1.Humanoid.MaxHealth * 35/100
                                        if L_176_forvar1.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_176_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,10,0)
                                            _G.FastAttackNormalSpeed = true _G.AutoGoGoGoFarm =true AttackPlayersFunction() AttackOK()
                                        else
                                            _G.FastAttackNormalSpeed = false _G.AutoGoGoGoFarm=false
                                        end
										EquipWeapon(_G.Settings.Configs["Select Weapon"])
									end
								until not (game:GetService("Workspace").Enemies:FindFirstChild("God's Guard [Lv. 450]")) or not (_G.Settings.Main["Fast Auto Farm Level"] or _G.Settings.Main["Auto Farm Level"]) or L_176_forvar1.Humanoid.Health <= 0 or not L_176_forvar1.Parent
							end
						end
					else
						Modstween = L_3_func(L_174_)
						if World1 and (L_174_.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 1500 then
							if Modstween then
								Modstween:Stop()
							end
							wait(.5)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
						elseif (L_174_.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
							if Modstween then
								Modstween:Stop()
							end
							game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_174_
						end 
					end
				end
			elseif GetQuest.Visible == true then
				local L_179_ = {}
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki", "Buso")
				for L_180_forvar0, L_181_forvar1 in pairs(game:GetService("Workspace").Characters:GetChildren()) do
					table.insert(L_179_, L_181_forvar1.Name)
				end
				if table.find(L_179_, GetQuestTitle.Text:split(" ")[2]) then
					for L_182_forvar0, L_183_forvar1 in pairs(game:GetService("Workspace").Characters:GetChildren()) do
						if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, L_183_forvar1.Name) then
							if _G.Settings.Main["Auto Farm Level"] and _G.Settings.Main["Fast Auto Farm Level"] and L_183_forvar1.Name == GetQuestTitle.Text:split(" ")[2] and L_183_forvar1:FindFirstChild("HumanoidRootPart") and L_183_forvar1:FindFirstChild("Humanoid") and L_183_forvar1.Humanoid.Health > 0 then
								repeat
									wait()
									if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.PvpDisabled.Visible == true then
											local L_184_ = {
												[1] = "EnablePvp"
											}

											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_184_))
										end
									EquipWeapon(_G.Settings.Configs["Select Weapon"])
									if World1 and (Vector3.new(61163.8515625, 11.6796875, 1819.7841796875) - L_183_forvar1.HumanoidRootPart.Position).magnitude < 5000 then
										if FarmtoTarget then
											FarmtoTarget:Stop()
										end
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
									elseif (L_183_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 150 then
										FarmtoTarget = L_3_func(L_183_forvar1.HumanoidRootPart.CFrame)
									elseif L_183_forvar1:FindFirstChild("HumanoidRootPart") and L_183_forvar1:FindFirstChild("Humanoid") and (L_183_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
										if FarmtoTarget then
											FarmtoTarget:Stop()
										end
										if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.PvpDisabled.Visible == true then
											local L_184_ = {
												[1] = "EnablePvp"
											}

											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_184_))
										end
										if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
											local L_185_ = {
												[1] = "Buso"
											}
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_185_))
										end
										if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
											game:service("VirtualInputManager"):SendKeyEvent(true, "V", false, game)
											game:service("VirtualInputManager"):SendKeyEvent(false, "V", false, game)
										end
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, -7, 3)
										--[[if AttackRandomType == 1 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 7, 1)
										elseif AttackRandomType == 2 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 1, 7)
										elseif AttackRandomType == 3 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(1, 1, - 7)
										elseif AttackRandomType == 4 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(7, 1, 0)
										elseif AttackRandomType == 5 then
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(- 7, 1, 0)
										else
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_183_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 7, 1)
										end]]
										local MonHealth2 = L_171_forvar1.Humanoid.MaxHealth * 35/100
                                        if L_171_forvar1.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_171_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,10,0)
                                            _G.FastAttackNormalSpeed = true _G.AutoGoGoGoFarm =true AttackPlayersFunction() AttackOK()
                                        else
                                            _G.FastAttackNormalSpeed = false _G.AutoGoGoGoFarm=false
                                        end
										EquipWeapon(_G.Settings.Configs["Select Weapon"])
										AttackPlayers()
										wait(.1)
										-- game:service("VirtualInputManager"):SendKeyEvent(true, "Z", false, game)
										-- game:service("VirtualInputManager"):SendKeyEvent(false, "Z", false, game)
										game:service("VirtualInputManager"):SendKeyEvent(true, "X", false, game)
										game:service("VirtualInputManager"):SendKeyEvent(false, "X", false, game)
									end
								until not _G.Settings.Main["Auto Farm Level"] or not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, L_183_forvar1.Name) or L_183_forvar1.Humanoid.Health <= 0 or not L_183_forvar1.Parent or GetQuest.Visible == false
							end
						end
					end
				else
					if game:GetService("Workspace").Enemies:FindFirstChild(Name) then
						for L_186_forvar0, L_187_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if _G.Settings.Main["Auto Farm Level"] and L_187_forvar1.Name == Name and L_187_forvar1:FindFirstChild("HumanoidRootPart") and L_187_forvar1:FindFirstChild("Humanoid") and L_187_forvar1.Humanoid.Health > 0 then
								if string.find(GetQuestTitle.Text, QuestName) then
									repeat
										wait()
										EquipWeapon(_G.Settings.Configs["Select Weapon"])
										if (L_187_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 150 then
											FarmtoTarget = L_3_func(L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
										elseif L_187_forvar1:FindFirstChild("HumanoidRootPart") and L_187_forvar1:FindFirstChild("Humanoid") and (L_187_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
											if FarmtoTarget then
												FarmtoTarget:Stop()
											end
											StartMagnet = true
											PosMon = L_187_forvar1.HumanoidRootPart.CFrame
											if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
												game:service("VirtualInputManager"):SendKeyEvent(true, "V", false, game)
												game:service("VirtualInputManager"):SendKeyEvent(false, "V", false, game)
											end
											if AttackRandomType == 1 then
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1)
											elseif AttackRandomType == 2 then
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 1, 30)
											elseif AttackRandomType == 3 then
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(1, 1, - 30)
											elseif AttackRandomType == 4 then
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(30, 1, 0)
											elseif AttackRandomType == 5 then
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(- 30, 1, 0)
											else
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_187_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1)
											end
											EquipWeapon(_G.Settings.Configs["Select Weapon"])
										end
									until not game:GetService("Workspace").Enemies:FindFirstChild(Name) or not _G.Settings.Main["Auto Farm Level"] or not string.find(GetQuestTitle.Text, QuestName) or L_187_forvar1.Humanoid.Health <= 0 or not L_187_forvar1.Parent or GetQuest.Visible == false
									StartMagnet = false
								else
									Com("F_", "AbandonQuest");
								end
							end
						end
					else
						StartMagnet = false
						if not string.find(GetQuestTitle.Text, NameCheckQuest) then
							Com("F_", "AbandonQuest");
						end
						Modstween = L_3_func(CFrameMon)
						if World1 and (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
							if Questtween then
								Questtween:Stop()
							end
							wait(.5)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
						elseif World1 and not (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
							if Questtween then
								Questtween:Stop()
							end
							wait(.5)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
						elseif World2 and string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
							if Questtween then
								Questtween:Stop()
							end
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
						elseif World2 and not string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
							if Questtween then
								Questtween:Stop()
							end
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 6508.5581054688, 89.034996032715, - 132.83953857422))
						elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
							if Modstween then
								Modstween:Stop()
							end
							game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMon
						end 
					end
				end
			end
		end
	else
		if not string.find(GetQuestTitle.Text, NameMon) then
			game.ReplicatedStorage:WaitForChild("Remotes").CommF_:InvokeServer("AbandonQuest");
		end
		if GetQuest.Visible == false then
			StartMagnet = false
			if _G.Settings.Configs["Auto Haki"] then if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
			end end
			if NoTweenQuest then
                if GetQuest.Visible == false then
                    Com("F_", "StartQuest", QuestName, LevelQuest)
                    Com("F_", "SetspawnPoint")
                end
			elseif TweenQuest then
                if getgenv().FarmModeRough then
                        Questtween = L_3_func(CFrameQuest, CFrameQuest)
                    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 250 then
                        if Questtween then
                            Questtween:Stop()
                        end
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                        if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 10 then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                            Com("F_", "StartQuest", QuestName, LevelQuest)
                            Com("F_", "SetspawnPoint")
                        end
                    end
                end
                if getgenv().FarmModeSmooth then
                        Questtween = L_3_func(CFrameQuest, CFrameQuest)
                    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
                        if Questtween then
                            Questtween:Stop()
                        end
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                        if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 10 then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                            Com("F_", "StartQuest", QuestName, LevelQuest)
                            Com("F_", "SetspawnPoint")
                        end
                    end
                end
            end
			if World1 and (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
				if Questtween then Questtween:Stop() end
				wait(.5)
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
				wait(.2)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (CFrameQuest) -- -- -
				wait(.2)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (CFrameMon) -- -- -
		elseif World1 and not (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
				if Questtween then Questtween:Stop() end wait(.5)
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
		elseif World2 and string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
				if Questtween then Questtween:Stop() end
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
		elseif World2 and not string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
				if Questtween then Questtween:Stop() end
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 6508.5581054688, 89.034996032715, - 132.83953857422))
            end
		elseif GetQuest.Visible == true then
            if getgenv().FarmModeRough then
            CFrameMontween = L_3_func(CFrameMonPoD)
                if not game:GetService("Workspace").Enemies:FindFirstChild(Name) or not game:GetService("Workspace").Enemies[Name] then
                    StartMagnet = false
                    _G.FastAttackNormalSpeed = false _G.AutoGoGoGoFarm=false
                    CFrameMontween = L_3_func(CFrameMonPoD)
                    if (CFrameMonPoD.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 250 then
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMonPoD
                        if CFrameMontween then
                            CFrameMontween:Stop()
                        end
                    end
                end
            end
            if getgenv().FarmModeSmooth then
                CFrameMontween = L_3_func(CFrameMonPoD)
                if not game:GetService("Workspace").Enemies:FindFirstChild(Name) or not game:GetService("Workspace").Enemies[Name] then
                    StartMagnet = false
                    _G.FastAttackNormalSpeed = false _G.AutoGoGoGoFarm=false
                    CFrameMontween = L_3_func(CFrameMonPoD)
                    if (CFrameMonPoD.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMonPoD
                        if CFrameMontween then
                            CFrameMontween:Stop()
                        end
                    end
                end
            end
        if GetQuest.Visible == true then
			if game:GetService("Workspace").Enemies:FindFirstChild(Name).HumanoidRootPart then
				for L_188_forvar0, L_189_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if _G.Settings.Main["Auto Farm Level"] and L_189_forvar1.Name == Name and L_189_forvar1:FindFirstChild("HumanoidRootPart") and L_189_forvar1:FindFirstChild("Humanoid") and L_189_forvar1.Humanoid.Health > 0 and (L_189_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 220 then --220
						if string.find(GetQuestTitle.Text, NameMon) then
						    PosMon = L_189_forvar1.HumanoidRootPart.CFrame
							repeat game:GetService("RunService").Heartbeat:wait() --AttackOKKO()
                                if _G.Settings.Configs["Auto Haki"] then 
                                    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                    end
                                end
								if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
							 wait() EquipWeapon(_G.Settings.Configs["Select Weapon"])
								end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                if getgenv().FarmModeRough then StartMagnet = true
                                    _G.abcdefg = 335
                                    _G.abcdefgs = 55
                                    _G.abcdefgsas = 80
                                    FarmtoTarget = L_3_func(L_189_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 55, 0))
                                    game:GetService'VirtualUser':CaptureController()
                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                end
                                if getgenv().FarmModeSmooth then StartMagnet = true
                                    _G.abcdefg = 100
                                    _G.abcdefgs = 40
                                    _G.abcdefgsas = 90
                                    FarmtoTarget = L_3_func(L_189_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 45, 0))
                                    game:GetService'VirtualUser':CaptureController()
                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                end
								if game.Players.LocalPlayer.Data.Level.Value >= 20 and game.Players.LocalPlayer.Data.Level.Value <= 90 then end
								PosMon = L_189_forvar1.HumanoidRootPart.CFrame
								L_189_forvar1.HumanoidRootPart.Transparency = 1 
								L_189_forvar1.HumanoidRootPart.CanCollide = false
								--L_189_forvar1.Humanoid.JumpPower = 0 L_189_forvar1.Humanoid.WalkSpeed = 0
								if not string.find(L_189_forvar1.Name,"Boss") and L_189_forvar1.Humanoid.Health <= 0 and L_189_forvar1:FindFirstChild("Humanoid") then L_189_forvar1:Destroy() end
                                if L_189_forvar1:FindFirstChild("HumanoidRootPart") and L_189_forvar1:FindFirstChild("Humanoid") and (L_189_forvar1.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.abcdefg then
                                    if FarmtoTarget then FarmtoTarget:Stop() end
                                    local MonHealth = L_189_forvar1.Humanoid.MaxHealth * 49/100
                                    local MonHealth2 = L_189_forvar1.Humanoid.MaxHealth * _G.abcdefgs/100
                                    local MonHealth3 = L_189_forvar1.Humanoid.MaxHealth * _G.abcdefgsas/100
                                    if getgenv().FarmModeRough then
                                        if L_189_forvar1.Humanoid.Health <= MonHealth then
                                            --L_189_forvar1.HumanoidRootPart.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-25,0)
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_189_forvar1.HumanoidRootPart.CFrame * (PosOdslob)
                                        else 
                                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_189_forvar1.HumanoidRootPart.CFrame * (PosOds)
                                        end
                                        if L_189_forvar1.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_189_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,10,0)
                                            _G.FastAttackNormalSpeed = true
                                            _G.AutoGoGoGoFarm = true
                                            AttackPlayersFunction()
                                            AttackOK()
                                        else
                                            _G.FastAttackNormalSpeed = false
                                            _G.AutoGoGoGoFarm = false
                                        end
                                    end
                                    if getgenv().FarmModeSmooth then
                                        if L_189_forvar1.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_189_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,13,13)
                                            _G.FastAttackNormalSpeed = true
                                            _G.AutoGoGoGoFarm = true
                                            AttackAC()
                                            AttackOK()
                                            AttackPlayersFunction()
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = L_189_forvar1.HumanoidRootPart.CFrame * CFrame.new(0,20,20)
                                            _G.FastAttackNormalSpeed = false
                                            _G.AutoGoGoGoFarm = false
                                        end
                                    end
                                    if getgenv().FarmModeRough then
                                        if L_189_forvar1.Humanoid.Health <= MonHealth3 then
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        else
                                            AttackOK()
                                            KoAttackOK()
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        end
                                    end
                                    if getgenv().FarmModeSmooth then 
                                        if L_189_forvar1.Humanoid.Health <= MonHealth3 then
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        else
                                            AttackOK()
                                            KoAttackOK()
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        end
                                    end
                                end
                                StartMagnet = true
                                --L_189_forvar1.Humanoid:ChangeState(12)
                                L_189_forvar1.HumanoidRootPart.Size = Vector3.new(75, 75, 75)
                                game:GetService'VirtualUser':CaptureController()
                                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                --AttackOKKO()
                                if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
									game:service("VirtualInputManager"):SendKeyEvent(true, "V", false, game) game:service("VirtualInputManager"):SendKeyEvent(false, "V", false, game)
								end
							until not game:GetService("Workspace").Enemies:FindFirstChild(Name) or not _G.Settings.Main["Auto Farm Level"] or not string.find(GetQuestTitle.Text, NameMon) or L_189_forvar1.Humanoid.Health <= 0 or not L_189_forvar1.Parent or GetQuest.Visible == false
							StartMagnet = false
						else
                            Com("F_", "AbandonQuest");
						end
					end
				end
			end
		else if not string.find(GetQuestTitle.Text, NameMon) then Com("F_", "AbandonQuest"); end
			StartMagnet = false
			Modstween = L_3_func(CFrameMonPoD.Position, CFrameMonPoD)
			if game:GetService("ReplicatedStorage"):FindFirstChild(Name) or game:GetService("ReplicatedStorage"):FindFirstChild(Name).Humanoid.Health <= 0 then
                L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild(Name).HumanoidRootPart.CFrame * CFrame.new(0,30,0))
			end
            local Mob = game:GetService("ReplicatedStorage"):FindFirstChild(Name) 
            if Mob then
                L_3_func(Mob.HumanoidRootPart.CFrame * CFrame.new(5,10,7))
            else
                if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Y <= 1 then
                    game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = true
                    task.wait()
                    game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = false
                end
            end
				if World1 and (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
					if Modstween then
						Modstween:Stop()
					end
					wait(.5)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
				elseif World1 and not (Name == "Fishman Commando [Lv. 400]" or Name == "Fishman Warrior [Lv. 375]") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
					if Modstween then
						Modstween:Stop()
					end
					wait(.5)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
				elseif World2 and string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
					if Modstween then
						Modstween:Stop()
					end
					wait(.5)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
				elseif World2 and not string.find(Name, "Ship") and (CFrameQuest.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 30000 then
					if Modstween then
						Modstween:Stop()
					end
					wait(.5)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 6508.5581054688, 89.034996032715, - 132.83953857422))
				elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 250 then --250
					if Modstween then
						Modstween:Stop()
						if getgenv().FarmModeSmooth then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMonPoD
						end
                        if getgenv().FarmModeSmooth then
                            getgenv().ToTarget = (CFrameMonPoD)
                        end
                        _G.FastAttackNormalSpeed = false
                    end
				end
			end
        end
	end
end

Type = getgenv().Mode
Type2 = getgenv().Mode
    spawn(function()
        while task.wait(.01) do
            if Type2 == 1 then
                CFrameMonPoD = CFrameMon
            elseif Type2 == 2 then
                CFrameMonPoD = CFrameMon1
            elseif Type2 == 3 then
                for i , v in pairs(game:GetService("Workspace")._WorldOrigin.EnemySpawns:GetChildren()) do
                    if v.Name == Name then
                        CFrameMonPoD = v.CFrame * CFrame.new(0,30,0)
                    end
                end
            end
        end
    end)
    
    spawn(function()
        while wait(.1) do
            if Type == 1 then
                PosOds = CFrame.new(0, 7, 17)
            elseif Type == 2 then
                PosOds = CFrame.new(17, 7, 0)
            elseif Type == 3 then
                PosOds = CFrame.new(0, 7, -17)
            elseif Type == 4 then
                PosOds = CFrame.new(-17, 7, 0)
            end
        end
    end)

    spawn(function()
        while wait(.1) do
            if Type == 1 then
                PosOdslob = CFrame.new(0, -4.5, 15)
            elseif Type == 2 then
                PosOdslob = CFrame.new(15, -10, 0)
            elseif Type == 3 then
                PosOdslob = CFrame.new(0, -15, -15)
            elseif Type == 4 then
                PosOdslob = CFrame.new(-0, -15, 0)
            end
        end
    end)

    spawn(function()
        while wait(.15) do  --1
            Type = 1
            task.wait(.15)  --1
            Type = 2
            task.wait(.15)  --1
            Type = 3
            task.wait(.15)   --1
            Type = 4
            task.wait(.15)  --1
        end
    end)

    spawn(function()
        while task.wait(.1) do
            Type2 = 1
            wait(3)
            Type2 = 2
            wait(3)
            Type2 = 3
            wait(3.5)
        end
    end)
a = 1
spawn(function()
	while wait() do 
		a = math.random(1, 2)
		wait(0.3)
	end
end)

c = 1
spawn(function()
	while wait() do 
		c = math.random(1, 2)
		task.wait(.1)
	end
end)

task.spawn(function()
	while task.wait() do
		pcall(function()
			if StartMagnet then
				if DbQ then
					if _G.Settings.Main["Auto Farm Level"] then
						if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
							for i,v in pairs(game:GetService("Workspace").Enemies()) do
								if v.Parent == Enemies and (v.HumanoidRootPart.Position-PosMon.Position).Magnitude <= 350 then
									v.Humanoid:ChangeState(8)
									v.Humanoid.JumpPower = 0
									v.Humanoid.WalkSpeed = 0
									v.HumanoidRootPart.CanCollide = false
									v.HumanoidRootPart.Size = Vector3.new(5,5,5)
									v.HumanoidRootPart.CFrame = PosMon
									v.Humanoid:ChangeState(11)
									v.Humanoid:ChangeState(12)
									sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
									Attack = true
								end
							end
						end
					else
						for i,v in pairs(game:GetService("Workspace").Enemies()) do
							if (v.HumanoidRootPart.Position-PosMon.Position).Magnitude <= 350 then
								v.Humanoid:ChangeState(8)
							    v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								v.HumanoidRootPart.CanCollide = false
								v.HumanoidRootPart.Size = Vector3.new(5,5,5)
								v.HumanoidRootPart.CFrame = PosMon
								v.Humanoid:ChangeState(11)
								v.Humanoid:ChangeState(12)
								sethiddenproperty(game.Players.LocalPlayer, "MaximumSimulationRadius",  math.huge)
								sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  9e20)
							end
						end
					end
				else
					if _G.Settings.Main["Auto Farm Level"] then
						if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
							for i,v in pairs(game:GetService("Workspace").Enemies()) do
								if v.Name == Name and (v.HumanoidRootPart.Position-PosMon.Position).Magnitude <= 350 then
									v.Humanoid:ChangeState(8)
									v.Humanoid.JumpPower = 0
									v.Humanoid.WalkSpeed = 0
									v.HumanoidRootPart.CanCollide = false
									v.HumanoidRootPart.Size = Vector3.new(5,5,5)
									v.HumanoidRootPart.CFrame = PosMon
									v.Humanoid:ChangeState(11)
									v.Humanoid:ChangeState(12)
									sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
									Attack = true
								end
							end
						end
					else
						for i,v in pairs(game:GetService("Workspace").Enemies()) do
							if (v.HumanoidRootPart.Position-PosMon.Position).Magnitude <= 350 then
								v.Humanoid:ChangeState(8)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								v.HumanoidRootPart.CanCollide = false
								v.HumanoidRootPart.Size = Vector3.new(5,5,5)
								v.HumanoidRootPart.CFrame = PosMon
								v.Humanoid:ChangeState(11)
								v.Humanoid:ChangeState(12)
								sethiddenproperty(game.Players.LocalPlayer, "MaximumSimulationRadius",  math.huge)
								sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  9e20)
							end
						end
					end
				end
			end
		end)
	end
end)
    spawn(function()
        pcall(function()
            while wait() do
                for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do  
                    if v:IsA("Tool") then
                        if v:FindFirstChild("RemoteFunctionShoot") then 
                            WeaponGun = v.Name
                        end
                    end
                end
            end
        end)
    end)
    
--[[    game:GetService("Players").LocalPlayer.Idled:connect(function()
        game:GetService("VirtualUser"):Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
        wait(1)
        game:GetService("VirtualUser"):Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    end)]]
    L_14_1:Label("Auto Farm Mastery Fruits")

    L_14_1:Toggle("Auto Farm Mastery Fruits",_G.Settings.Mastery["Auto Farm Fruits Mastery"],function(value)
        _G.Settings.Mastery["Auto Farm Fruits Mastery"] = value
        getgenv().AuToFarmMasFruits = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)

--_G.Settings.Mastery["Mob Health (%)"] = 10
local HealthMon = {
    "5",
    "10",
    "15",
    "20",
    "25",
    "30",
    "35",
    "40",
    "45",
    "50",
    "55",
    "60",
    "70",
    "80",
    "90",
    "100"
}
L_14_1:Dropdown("Select Health (%)",HealthMon,_G.Settings.Mastery["MobFruits Health (%)"],function(value)
    _G.Settings.Mastery["MobFruits Health (%)"] = value
    --MobHealthFruits
    SaveSettings()
end)

spawn(function()
    while wait() do
        if _G.Settings.Mastery["MobFruits Health (%)"] ~= nil then
            pcall(function()
                if _G.Settings.Mastery["MobFruits Health (%)"] == "5" then
                    MobHealthFruits = 5
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "10" then
                    MobHealthFruits = 10
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "15" then
                    MobHealthFruits = 15
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "20" then
                    MobHealthFruits = 20
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "25" then
                    MobHealthFruits = 25
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "30" then
                    MobHealthFruits = 30
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "35" then
                    MobHealthFruits = 35
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "40" then
                    MobHealthFruits = 40
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "45" then
                    MobHealthFruits = 45
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "50" then
                    MobHealthFruits = 50
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "55" then
                    MobHealthFruits = 55
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "60" then
                    MobHealthFruits = 60
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "70" then
                    MobHealthFruits = 70
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "80" then
                    MobHealthFruits = 80
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "90" then
                    MobHealthFruits = 90
                elseif _G.Settings.Mastery["MobFruits Health (%)"] == "100" then
                    MobHealthFruits = 100
                end
            end)
        end
    end
end)

spawn(function()
    while task.wait() do
        pcall(function()
            if getgenv().AuToFarmMasFruits then
                CheckQuest()
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if v.Name == Name then
                        if v:FindFirstChild("HumanoidRootPart") then
                            repeat task.wait()
                                StartMagnet = true
                                PosMon = v.HumanoidRootPart.CFrame
								--getgenv().BringMobs(v.HumanoidRootPart.CFrame , v.Name)
                                if v.Humanoid.Health <= v.Humanoid.MaxHealth * MobHealthFruits/100 then
									EquipWeapon(game.Players.LocalPlayer.Data.DevilFruit.Value)
                                    getgenv().UseSkill = true
                                    FruitPos = v.HumanoidRootPart.CFrame
									getgenv().ToTargets(v.HumanoidRootPart.CFrame * CFrame.new(0,0,25))
                                    --SkillUse()
                                else
                                    getgenv().UseSkill = false
                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
									getgenv().ToTargets(v.HumanoidRootPart.CFrame * CFrame.new(0,0,25))
									AttackOK()
                                end
                            until not getgenv().AuToFarmMasFruits or not v.Parent or v.Humanoid.Health <= 0
                        end
					else
						getgenv().ToTargets(CFrameMon)
						EquipWeapon(_G.Settings.Configs["Select Weapon"])
						StartMagnet = false
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while task.wait() do
        pcall(function()
            if getgenv().AuToFarmMasFruits then
                local On = {
                    [1] = FruitPos.Position
                }
                game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Data.DevilFruit.Value].RemoteEvent:FireServer(unpack(On))
            else
               local Off = {
                    [1] = nil
                }
                game:GetService("Players").LocalPlayer.Character[game:GetService("Players").LocalPlayer.Data.DevilFruit.Value].RemoteEvent:FireServer(unpack(Off)) 
            end
        end)
    end
end)

spawn(function()
    while task.wait() do
        pcall(function()
            if getgenv().UseSkill then --CheckQuest()
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and (v.CFrame.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 30 then --250
                if _G.SkillZ then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
					wait()
                end
                if _G.SkillX then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
					wait()
                end
                if _G.SkillC then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
					wait()
                end
                if _G.SkillV then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
					wait()
                end
                    end
                end
            end
        end)
    end
    
end)
spawn(function()
    while wait() do
        pcall(function()
    function SkillUse()
        if _G.SkillZ then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"Z",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"Z",false,game)
					wait()
                end
                if _G.SkillX then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"X",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"X",false,game)
					wait()
                end
                if _G.SkillC then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"C",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"C",false,game)
					wait()
                end
                if _G.SkillV then
					wait()
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,"V",false,game)
                    wait(.1)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,"V",false,game)
					wait()
                end
    end
        end)
    end
end)


spawn(function()
	if getgenv().AuToFarmMasFruits == false then
		_G.UseSkill = false
	end
end)

    L_14_1:Label("Auto Farm Mastery Gun")

    L_14_1:Toggle("Auto Farm Mastery Gun",_G.Settings.Mastery["Auto Farm Gun Mastery"],function(value)
        _G.Settings.Mastery["Auto Farm Gun Mastery"] = value
        getgenv().AutoFarmGunMastery = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    spawn(function()
        pcall(function() if getgenv().AutoFarmGunMastery then
            if GetQuest.Visible == true then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name == Name and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 220 then --220 --getgenv().AutoFarmGunMastery and  and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 
                    repeat task.wait()
                        HealthMin = v.Humanoid.MaxHealth * MobHealth/100
                        if v.Humanoid.Health <= HealthMin then
                            EquipWeapon(WeaponGun)
                            if game:GetService("Players").LocalPlayer.Character:FindFirstChild(WeaponGun) then
                                game:GetService("Players").LocalPlayer.Character[WeaponGun].Cooldown.Value = 0
                            end
                            game:GetService("Players").LocalPlayer.Character[WeaponGun].Cooldown.Value = 0
                            local args = { 
                                [1] = v.HumanoidRootPart.Position, 
                                [2] = v.HumanoidRootPart 
                            }
                            game:GetService("Players").LocalPlayer.Character[WeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(10, 10, 10)
                            v.HumanoidRootPart.Transparency = 0.75
                            v.HumanoidRootPart.Size = Vector3.new(2,2,1)
                            game:GetService'VirtualUser':CaptureController()
                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                            if game.Players.LocalPlayer.Character[WeaponGun].Level.Value >= 125 then
                                wait(1) 
                                game:service("VirtualInputManager"):SendKeyEvent(true, "Z", false, game)
                                game:service("VirtualInputManager"):SendKeyEvent(false, "Z", false, game)
                            end
                        else
                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                            game:GetService'VirtualUser':CaptureController()
                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                            v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                            v.HumanoidRootPart.Transparency = 1
                        end
                    until v.Humanoid.Health <= 0 or getgenv().AutoFarmGunMastery == false or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                end
            end
            end
        end end)
    end)
    
    spawn(function()
        pcall(function()
            while wait() do
                if getgenv().AutoFarmGunMastery then
                    GetQuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title
                    GetQuest = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest
                    CheckQuest()
                    local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
                    if not string.find(GetQuestTitle.Text, NameMon) then
                        game.ReplicatedStorage:WaitForChild("Remotes").CommF_:InvokeServer("AbandonQuest");
                    end
                    if GetQuest.Visible == false then
                        if GetQuest.Visible == false then
                            CheckQuest()
                            Com("F_", "StartQuest", QuestName, LevelQuest)
                            Com("F_", "SetspawnPoint")
                        end
                    elseif GetQuest.Visible == true then
                        if not game:GetService("Workspace").Enemies:FindFirstChild(Name) then
                            CheckQuest()
                                CFrameMontween = L_3_func(CFrameMon, CFrameMon)
                            if (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 300 then
                                if CFrameMontween then
                                    CFrameMontween:Stop()
                                end
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (CFrameMon)
                            end
                        end
                    end
                    CheckQuest()
                if GetQuest.Visible == true then
                    if game:GetService("Workspace").Enemies:FindFirstChild(Name) then
                        pcall(function()
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == Name and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 220 then --220 --getgenv().AutoFarmGunMastery and  and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 
                                    repeat task.wait()
                                        if string.find(GetQuestTitle.Text, NameMon) then
                                            --AutoHaki()
                                            FarmtoTarget = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(5,10,7))
                                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 220 then
                                                if FarmtoTarget then
                                                    FarmtoTarget:Stop()
                                                end
                                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(30, 2, 0)
                                                v.Humanoid:ChangeState(12)
                                                v.HumanoidRootPart.Size = Vector3.new(80,80,80)
                                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                                HealthMin = v.Humanoid.MaxHealth * MobHealth/100
                                                if v.Humanoid.Health <= HealthMin then
                                                    EquipWeapon(WeaponGun)
                                                    if game:GetService("Players").LocalPlayer.Character:FindFirstChild(WeaponGun) then
                                                        game:GetService("Players").LocalPlayer.Character[WeaponGun].Cooldown.Value = 0
                                                    end
                                                    game:GetService("Players").LocalPlayer.Character[WeaponGun].Cooldown.Value = 0
                                                    local args = { 
                                                        [1] = v.HumanoidRootPart.Position, 
                                                        [2] = v.HumanoidRootPart 
                                                    }
                                                    game:GetService("Players").LocalPlayer.Character[WeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(10, 10, 10)
                                                    
                                                    v.HumanoidRootPart.Transparency = 0.75
                                                    v.HumanoidRootPart.Size = Vector3.new(2,2,1)--Vector3.new(2,2,1)
                                                    game:GetService'VirtualUser':CaptureController()
                                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                    if game.Players.LocalPlayer.Character[WeaponGun].Level.Value >= 125 then
                                                        wait(1) 
                                                        game:service("VirtualInputManager"):SendKeyEvent(true, "Z", false, game)
                                                        game:service("VirtualInputManager"):SendKeyEvent(false, "Z", false, game)
                                                    end
                                                else
                                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                    game:GetService'VirtualUser':CaptureController()
                                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                    v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                                    --game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(-6, -3, 18)
                                                    v.HumanoidRootPart.Transparency = 1
                                                end
                                            end
                                        else
                                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                                        end
                                        StartMagnet = true
                                        PosMon = v.HumanoidRootPart.CFrame
                                        v.Humanoid.WalkSpeed = 0
                                        v.HumanoidRootPart.CanCollide = false
                                        v.Head.CanCollide = false
                                    until v.Humanoid.Health <= 0 or getgenv().AutoFarmGunMastery == false or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                    StartMagnet = false
                                end
                            end
                        end)
                    
                    else
                        local Mob = game:GetService("ReplicatedStorage"):FindFirstChild(Name) 
                        if Mob then
                            L_3_func(Mob.HumanoidRootPart.CFrame * CFrame.new(5,10,7))
                        else
                            if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Y <= 1 then
                                game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = true
                                task.wait()
                                game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = false
                            end
                        end
                    end
                end
                end
            end
        end)
    end)

task.spawn(function()
	while wait() do
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
			if v:IsA("Tool") then
				if v:FindFirstChild("RemoteFunctionShoot") then 
					WeaponGun = v.Name
				end
			end
		end
	end
end)

    spawn(function()
        while task.wait() do
            if getgenv().AutoFarmGunMastery and game:GetService("Players").LocalPlayer.Character:FindFirstChild(WeaponGun) then
                pcall(function()
                    game:GetService("Players").LocalPlayer.Character[WeaponGun].Cooldown.Value = 0
                    local args = {
                        [1] = game:GetService("Players"):FindFirstChild(Name).HumanoidRootPart.Position,
                        [2] = game:GetService("Players"):FindFirstChild(Name).HumanoidRootPart
                    }
                    game:GetService("Players").LocalPlayer.Character[WeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                    game:GetService'VirtualUser':CaptureController()
                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                end)
            end
        end
    end)
    spawn(function()
        pcall(function()
            game:GetService("RunService").RenderStepped:Connect(function()
                if getgenv().AutoFarmGunMastery then
                    local args = {
                        [1] = PosMon.Position
                    }
                    game:GetService("Players").LocalPlayer.Character[WeaponGun].RemoteEvent:FireServer(unpack(args))
                end
            end)
        end)
    end)

spawn(function()
	while wait(.5) do
		pcall(function()
			if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 or not game.Players.LocalPlayer then
				StopTween()
			end
		end)
	end
end)

--_G.Settings.Mastery["Mob Health (%)"] = 10
local HealthMon = {
    "5",
    "10",
    "15",
    "20",
    "25",
    "30",
    "35",
    "40",
    "45",
    "50",
    "55",
    "60",
    "70",
    "80",
    "90",
    "100"
}
L_14_1:Dropdown("Select Health (%)",HealthMon,_G.Settings.Mastery["Mob Health (%)"],function(value)
    _G.Settings.Mastery["Mob Health (%)"] = value
    --MobHealth
    SaveSettings()
end)

spawn(function()
    while wait() do
        if _G.Settings.Mastery["Mob Health (%)"] ~= nil then
            pcall(function()
                if _G.Settings.Mastery["Mob Health (%)"] == "5" then
                    MobHealth = 5
                elseif _G.Settings.Mastery["Mob Health (%)"] == "10" then
                    MobHealth = 10
                elseif _G.Settings.Mastery["Mob Health (%)"] == "15" then
                    MobHealth = 15
                elseif _G.Settings.Mastery["Mob Health (%)"] == "20" then
                    MobHealth = 20
                elseif _G.Settings.Mastery["Mob Health (%)"] == "25" then
                    MobHealth = 25
                elseif _G.Settings.Mastery["Mob Health (%)"] == "30" then
                    MobHealth = 30
                elseif _G.Settings.Mastery["Mob Health (%)"] == "35" then
                    MobHealth = 35
                elseif _G.Settings.Mastery["Mob Health (%)"] == "40" then
                    MobHealth = 40
                elseif _G.Settings.Mastery["Mob Health (%)"] == "45" then
                    MobHealth = 45
                elseif _G.Settings.Mastery["Mob Health (%)"] == "50" then
                    MobHealth = 50
                elseif _G.Settings.Mastery["Mob Health (%)"] == "55" then
                    MobHealth = 55
                elseif _G.Settings.Mastery["Mob Health (%)"] == "60" then
                    MobHealth = 60
                elseif _G.Settings.Mastery["Mob Health (%)"] == "70" then
                    MobHealth = 70
                elseif _G.Settings.Mastery["Mob Health (%)"] == "80" then
                    MobHealth = 80
                elseif _G.Settings.Mastery["Mob Health (%)"] == "90" then
                    MobHealth = 90
                elseif _G.Settings.Mastery["Mob Health (%)"] == "100" then
                    MobHealth = 100
                end
            end)
        end
    end
end)
    L_14_1:Label("Auto Farm Boss")

    L_14_1:Toggle("Auto Farm Boss [BUG]",_G.Settings.Boss["Auto Boss Select"],function(value)
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
        _G.Settings.Boss["Auto Boss Select"] = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    spawn(function()
        while wait() do
            if _G.Settings.Boss["Auto Boss Select"] then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild(_G.SelectBoss) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == _G.SelectBoss then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
										wait()
										StartMagnet = true
										if _G.Settings.Configs["Auto Haki"] then
											if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
											end
										end
										if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
											wait()
											EquipWeapon(_G.Settings.Configs["Select Weapon"])
										end
                                        v.HumanoidRootPart.CanCollide = false
                                        v.Humanoid.WalkSpeed = 0
                                        --FastAttack = true
                                        v.HumanoidRootPart.Size = Vector3.new(80,80,80)                             
                                        FarmtoTarget = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,-20,2))
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until not _G.Settings.Boss["Auto Boss Select"] or not v.Parent or v.Humanoid.Health <= 0
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild(_G.SelectBoss) then
                            L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild(_G.SelectBoss).HumanoidRootPart.CFrame * CFrame.new(2,-20,2))
                            --FastAttack = false
                        end
                    end
                end)
            end
        end
    end)
    L_14_1:Toggle("Auto Farm All Boss",_G.Settings.Boss["Auto Farm All Boss"],function(value)
        getgenv().AutoAllBoss = value
        _G.Settings.Boss["Auto Farm All Boss"] = value
        SaveSettings()
        if value == false then
            wait()
            StopTween(getgenv().AutoAllBoss)
            wait()
        end
    end)

spawn(function()
	while wait() do
		if getgenv().AutoAllBoss then
			pcall(function()
				for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
					if string.find(v.Name , "Boss") then
						repeat wait()
                            local magnitude = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                            if magnitude < 250 then
								if _G.Settings.Configs["Auto Haki"] then
								    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
								        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
								    end
								end
								EquipWeapon(_G.Settings.Configs["Select Weapon"])
								v.Humanoid.WalkSpeed = 0
								v.HumanoidRootPart.CanCollide = true
								v.Head.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(1,2,3)
								game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(-20,5,-25)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
								--[[if wait(40) then
								    v.Humanoid.Health = 0
								end]]
							else
								L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(-35,-1,-1))
							end
						until v.Humanoid.Health <= 0 or getgenv().AutoAllBoss == false --or not v.Parent
				    else
						if _G.AutoAllBossHop then
							Hop()
						end
					end
				end
			end)
		end
	end
end)

if World1 then
    
    local L_14_12 = A:Section("Other Auto Farm World 1","Left")

    L_14_12:Label("-「 Auto New World 」-")

    L_14_12:Toggle("Auto New World",_G.Settings.Main["Auto New World"],function(value)
        _G.Settings.Main["Auto New World"] = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)

spawn(function()
    while task.wait() do
        pcall(function()
            if _G.Settings.Main["Auto New World"] then
                while task.wait() do
                    if game:GetService("Players").LocalPlayer.Data.Level.Value >= 700 and World1 then
                    if _G.Settings.Main["Auto New World"] then
                        if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress").UsedKey == false then
                            if not game.Players.LocalPlayer.Backpack:FindFirstChild("Key") or game.Players.LocalPlayer.Character:FindFirstChild("Key") then
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress","Detective")
                            end
                            if game.Players.LocalPlayer.Backpack:FindFirstChild("Key") or game.Players.LocalPlayer.Character:FindFirstChild("Key") then
                                EquipWeapon("Key")
                                L_3_func(CFrame.new(1349.697265625, 37.34928512573242, -1328.8309326171875))
                                game:GetService("Workspace").Map.Ice.Door.Size = Vector3.new(30,30,30)
                            end
                        end
                        if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress").UsedKey == true and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress").KilledIceBoss == false then
                            for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
                                    if v:FindFirstChild("HumanoidRootPart") then
                                        repeat task.wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                            local magnitude = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                                            if magnitude < 250 then
                                                v.HumanoidRootPart.CanCollide = false
                                                v.Humanoid.WalkSpeed = 0
                                                v.Head.CanCollide = false
                                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(-20,5,-25)
                                                game:GetService("VirtualUser"):CaptureController()
                                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                                sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
                                            else
                                                L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
                                            end
                                        until not _G.Settings.Main["Auto New World"]
                                    end
                                end
                            end
                            for x,y in pairs(game.ReplicatedStorage:GetChildren()) do
                                if y.Name == "Ice Admiral [Lv. 700] [Boss]" then
                                    if y:FindFirstChild("HumanoidRootPart") then
                                        repeat task.wait()
                                            L_3_func(y.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
                                        until not _G.Settings.Main["Auto New World"]
                                    end
                                end
                            end
                        end
                        if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress").KilledIceBoss == true then
                            if game.PlaceId == 2753915549 then
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
                            end
                        end
                    end
                    end
                end
            end
        end)
    end
end)
    
    L_14_12:Label("-「 Auto Pole 」-")
    
    
    
    local CFrameMonPole = CFrame.new(-7619.54736, 5618.8335, -2453.61938, -0.260018349, 0, 0.965603709, 0, 1.00000012, 0, -0.965603948, 0, -0.26001817)
    
    L_14_12:Toggle("Auto Pole",_G.Settings.Main["Auto Pole"],function(value)
        _G.Settings.Main["Auto Pole"] = value
        _G.AutoPole = value
        SaveSettings()
        if value == true then
            if _G.Settings.Main["Auto Pole"] and (CFrameMonPole.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1500 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
            end
        end
		if value == false then
			wait(.5)
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    L_14_12:Toggle("Auto Pole HopServer",_G.Settings.Main["Auto Pole Hop"],function(value)
        _G.Settings.Main["Auto Pole Hop"] = value
        _G.AutoPoleHop = value
        SaveSettings()
    end)
spawn(function()
    while task.wait() do
        pcall(function()
            if _G.AutoPole then
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                    if v.Name == "Thunder God [Lv. 575] [Boss]" then
                        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                            repeat task.wait()
                                
                                EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                if _G.Settings.Configs["Auto Haki"] then
                                    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                    end
                                end
                                EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                v.HumanoidRootPart.CanCollide = false
                                v.Humanoid.WalkSpeed = 0
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(70,70,70)
                                v.HumanoidRootPart.Transparency = 1
                                L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,35,5))
                                game:GetService'VirtualUser':CaptureController()
                                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                            until not _G.AutoPole or not v.Parent or v.Humanoid.Health <= 0
                        end
                    end 
                end
                L_3_func(CFrameMonPole)
                for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do 
                    if v.Name == "Thunder God [Lv. 575] [Boss]"  then
                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,35,5))
                    end
                    if _G.AutoPoleHop and (CFrameMonPole.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 1 then
                        wait(.5)
                        L_3_func(CFrameMonPole)
                        Hop()
                    end
                end
            end
        end)
    end
end)
    
    L_14_12:Label("-「 Auto Saber 」-")

    L_14_12:Toggle("Auto Saber",_G.Settings.Main["Auto Saber"],function(value)
        _G.Settings.Main["Auto Saber"] = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    -- [Auto Saber]
spawn(function()
    while task.wait() do
        pcall(function()
            if _G.Settings.Main["Auto Saber"] then
                if game.Players.LocalPlayer.Data.Level.Value >= 200 then
                    local QPlates = game:GetService("Workspace").Map.Jungle.QuestPlates
                    if QPlates["Plate1"].Button.BrickColor ~= BrickColor.new("Camo") then
                        L_3_func(QPlates["Plate1"].Button.CFrame)
                    elseif QPlates["Plate2"].Button.BrickColor ~= BrickColor.new("Camo") then
                        L_3_func(QPlates["Plate2"].Button.CFrame)
                    elseif QPlates["Plate3"].Button.BrickColor ~= BrickColor.new("Camo") then
                        L_3_func(QPlates["Plate3"].Button.CFrame)
                    elseif QPlates["Plate4"].Button.BrickColor ~= BrickColor.new("Camo") then
                        L_3_func(QPlates["Plate4"].Button.CFrame)
                    elseif QPlates["Plate5"].Button.BrickColor ~= BrickColor.new("Camo") then
                        L_3_func(QPlates["Plate5"].Button.CFrame)
                    end
                    if game:GetService("Workspace").Map.Jungle.QuestPlates.Door.CanCollide == false and game:GetService("Workspace").Map.Desert.Burn.Part.CanCollide == true then
                        if not game.Players.LocalPlayer.Backpack:FindFirstChild("Torch") or game.Players.LocalPlayer.Character:FindFirstChild("Torch") then
                            L_3_func(CFrame.new(-1611.04834, 14.1642542, 163.084183, -0.735830009, 9.42659852e-08, -0.677166283, 8.9578748e-08, 1, 4.18674873e-08, 0.677166283, -2.98523553e-08, -0.735830009))--(-1610.245, 12.6660957, 163.670731, -0.984807968, -0.167722315, 0.0449818224, -0.17364946, 0.951244235, -0.254912257, -3.42372805e-05, -0.258850574, -0.965917826))
                        end
                        if game.Players.LocalPlayer.Backpack:FindFirstChild("Torch") or game.Players.LocalPlayer.Character:FindFirstChild("Torch") then
                            EquipWeapon("Torch")
                            game:GetService("Workspace").Map.Desert.Burn.Fire.Size = Vector3.new(10,10,10)
                            game:GetService("Workspace").Map.Desert.Burn.Fire.CanCollide = false
                            L_3_func(CFrame.new(1112.41394, 4.94926691, 4351.87061, 0.589851618, 0.00181679102, -0.807509601, -0.000830773904, 0.999998331, 0.00164302031, 0.80751121, -0.000298280298, 0.589852154))
                        end
                    end
                    if game:GetService("Workspace").Map.Desert.Burn.Part.CanCollide == false and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") ~= 0 then
                        if not game.Players.LocalPlayer.Backpack:FindFirstChild("Cup") or game.Players.LocalPlayer.Character:FindFirstChild("Cup") then
                            L_3_func(CFrame.new(1113.9412841796875, 7.207527160644531, 4365.94921875))
                        end
                        if game.Players.LocalPlayer.Backpack:FindFirstChild("Cup") or game.Players.LocalPlayer.Character:FindFirstChild("Cup") then
                            EquipWeapon("Cup")
                            game:GetService("Workspace").Map.Ice.ParticleDrop.Water.Size = Vector3.new(40,40,40)
                            game:GetService("Workspace").Map.Ice.ParticleDrop.Water.Transparency = 0
                            L_3_func(CFrame.new(1397.471435546875, 37.47333908081055, -1321.564208984375))
                        end
                    end
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").UsedCup == false then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan")
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon")
                    end
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").TalkedSon == true and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").UsedRelic == false then
                        for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                            if v.Name == "Mob Leader [Lv. 120] [Boss]" then
                                if v:FindFirstChild("HumanoidRootPart") then
                                    repeat task.wait()
                                        
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
                                        v.HumanoidRootPart.Transparency = 0.5
                                        v.Humanoid.WalkSpeed = 0
                                        v.Humanoid.JumpPower = 0
                                        game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										--AttackOKKO()
                                        if sethiddenproperty then
                                            sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                        end
                                    until not _G.Settings.Main["Auto Saber"]
                                end
                            end
                        end
                        for x,y in pairs(game.ReplicatedStorage:GetChildren()) do
                            if y.Name == "Mob Leader [Lv. 120] [Boss]" then
                                if y:FindFirstChild("HumanoidRootPart") then
                                    repeat task.wait()
                                        
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										--AttackOKKO()
                                        L_3_func(y.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
                                    until not _G.Settings.Main["Auto Saber"]
                                end
                            end
                        end
                    else
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon")
                    end
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").UsedRelic == false and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").KilledMob == true then
                        if not game.Players.LocalPlayer.Backpack:FindFirstChild("Relic") or game.Players.LocalPlayer.Character:FindFirstChild("Relic") then
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon")
                            wait(.1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress")
                        end
                        if game.Players.LocalPlayer.Backpack:FindFirstChild("Relic") or game.Players.LocalPlayer.Character:FindFirstChild("Relic") then
                            game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Relic"])
                            game:GetService("Workspace").Map.Jungle.Final.Invis.Size = Vector3.new(20,20,20)
                            game:GetService("Workspace").Map.Jungle.Final.Invis.CanCollide = false
                            L_3_func(CFrame.new(-1407.0384521484375, 29.977327346801758, 4.923530578613281))
                        end
                    end
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").UsedRelic == true and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress").KilledShanks == false then
                        for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                            if v.Name == "Saber Expert [Lv. 200] [Boss]" then
                                if v:FindFirstChild("HumanoidRootPart") or v:FindFirstChild("Humanoid") then
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
                                        v.HumanoidRootPart.Transparency = 0.5
                                        v.Humanoid.WalkSpeed = 0
                                        v.Humanoid.JumpPower = 0
                                        game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										--AttackOKKO()
                                    until not _G.Settings.Main["Auto Saber"]
                                    if sethiddenproperty then
                                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                    end
                                end
                            end
                        end
                        for x,y in pairs(game.ReplicatedStorage:GetChildren()) do
                            if y.Name == "Saber Expert [Lv. 200] [Boss]" then
                                if y:FindFirstChild("HumanoidRootPart") then
                                    repeat task.wait()
                                        
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										--AttackOKKO()
                                        L_3_func(y.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
                                    until not _G.Settings.Main["Auto Saber"]
                                end
                            end
                        end
                    end
                end
            end
        end)
    end
end)

    L_14_12:Label("-「 Enchancement Colour 」-")
    
    L_14_12:Toggle("Auto Enchancement Colour",_G.Settings.Main["AutoBuyEnchancementColour"],function(value)
        _G.Settings.Main["AutoBuyEnchancementColour"] = value
        getgenv().AutoBuyEnchancementColour = value
        SaveSettings()
    end)
    
    spawn(function()
        while wait() do
            if getgenv().AutoBuyEnchancementColour then
                local args = {
                    [1] = "ColorsDealer",
                    [2] = "2"
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end 
        end
    end)





end


if World2 then

local L_14_   = A:Section("Other Auto Farm World 2","Left")

    L_14_:Label("-「 Auto Bartlio Quest 」-")

    L_14_:Toggle("Auto Bartlio Quest",_G.Settings.Main["Auto Bartilo Quest"],function(value)
        _G.Settings.Main["Auto Bartilo Quest"] = value
        getgenv().AutoBartilo = value
        SaveSettings()
        if value == false then
            wait()
            L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
            wait()
        end
    end)

spawn(function()
    while wait(.1) do
        if getgenv().AutoBartilo then
            if game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 0 then
                if string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Swan Pirates") and string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "50") and game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then 
                    if game:GetService("Workspace").Enemies:FindFirstChild("Swan Pirate [Lv. 775]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Swan Pirate [Lv. 775]" then
                                pcall(function()
                                    repeat wait(.1)
                                        
                                        if getgenv().Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                            wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end
										game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
										require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
										OldCFrameBartlio = v.HumanoidRootPart.CFrame
										AutoBartiloBring = true
                                    until not v.Parent or v.Humanoid.Health <= 0 or getgenv().AutoBartilo == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
									AutoBartiloBring = false
                                end)
                            end
                        end
                    else
						AutoBartiloBring = false
						L_3_func(CFrame.new(1057.92761, 137.614319, 1242.08069))
                    end
                else
					L_3_func(CFrame.new(-456.28952, 73.0200958, 299.895966))
					if (Vector3.new(-456.28952, 73.0200958, 299.895966) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
						wait(1.1)
                    	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","BartiloQuest",1)
					end
                end
            elseif game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 1 then
                if QuestBartilo == nil then
				    L_3_func(CFrame.new(-456.28952, 73.0200958, 299.895966))
                end
                if (Vector3.new(-456.28952, 73.0200958, 299.895966) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
                    wait(1.1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo")
                    QuestBartilo = 1
                end
				if game.Workspace.Enemies:FindFirstChild("Jeremy [Lv. 850] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Name == "Jeremy [Lv. 850] [Boss]" then
							repeat wait(.1)
							    
								sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
								require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
								if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                            wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end
								L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,15,6))
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not v.Parent or v.Humanoid.Health <= 0 or _G.AutoBartilo == false
						end
					end
                else
                    if QuestBartilo == 1 then
                        L_3_func(CFrame.new(1931.5931396484, 402.67391967773, 956.52215576172))
                    end
				end
            elseif game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 2 then
                L_3_func(game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate1.CFrame)
                wait(5)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate2.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate2.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate3.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate3.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate4.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate4.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate5.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate5.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate6.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate6.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate7.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate7.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate8.CFrame)
                wait(3)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate8.CFrame)
            end
        end 
    end
end)

    L_14_:Label("-「 Auto Farm Law Sword 」-")

    L_14_:Button("Buy Microchip law",function()
    local args = {
       [1] = "BlackbeardReward",
       [2] = "Microchip",
       [3] = "2"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end)

    L_14_:Toggle("Auto Farm law Sword",_G.Settings.Main["Auto Farm law Sword"],function(value)
        _G.Settings.Main["Auto Farm law Sword"] = value
    end)
    
    spawn(function()
        while wait() do
            if _G.Settings.Main["Auto Farm law Sword"] then
                pcall(function()
                    local CFrameAutoFarmlaw = CFrame.new(-6376.86523, 36.8663483, -4916.42578, -0.666728556, 9.02954369e-08, -0.745300651, 2.75599383e-08, 1, 9.64985674e-08, 0.745300651, 4.37979075e-08, -0.666728556)--(-5856.8501, 19.1629562, -5029.56934, -0.0522800684, 0, -0.998632431, 0, 1, 0, 0.998632431, 0, -0.0522800684)
                    if _G.Settings.Main["Auto Farm law Sword"] and (CFrameAutoFarmlaw.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1200 then
                        game:GetService("RunService"):Set3dRenderingEnabled(false)
                        BTP(CFrameAutoFarmlaw) --BTP(CFrameSetPoint)
                        game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
                        wait()
                        repeat wait()
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmlaw game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmlaw game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmlaw game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint") game:GetService("RunService"):Set3dRenderingEnabled(false)
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmlaw game:GetService("RunService"):Set3dRenderingEnabled(false)
                        until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
                        repeat wait()
                            game:GetService("RunService"):Set3dRenderingEnabled(false)
                        until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
                    end
                    if game.Players.LocalPlayer.Backpack:FindFirstChild("BlackbeardReward") or game.Players.LocalPlayer.Backpack:FindFirstChild("Microchip")  then
                        fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon.Button.Main.ClickDetector)
                    end
                    if game:GetService("Workspace").Enemies:FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Order [Lv. 1250] [Raid Boss]" then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(25,30,25))
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                            wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        v.Humanoid:ChangeState(20)
                                        v.HumanoidRootPart.CanCollide = false
                                        v.Humanoid.WalkSpeed = 0
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                    until not  _G.Settings.Main["Auto Farm law Sword"] or not v.Parent or v.Humanoid.Health <= 0
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
                            L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                        else
                            if  _G.AutoOderSwordHop then
                                Hop()
                            end
                        end
                    end
                end)
            end
        end
    end)



L_14_:Label("-「 Auto Dark Coat 」-")

--local L_C = L_14_:Label("Chest : "..C_H_H.."50")

L_14_:Toggle("Auto Dark Coat",_G.Settings.Main["Auto Dark Coat"],function(vu)
    _G.Settings.Main["Auto Dark Coat"] = vu
	Auto_Dark_Coat = vu
	_G.Auto_Dark_Coat = vu
	SaveSettings()
end)
if _G.Chest_Lock == nil then
	_G.Chest_Lock = 50
end
C_H_H = 0
if _G.Auto_Dark_Coat then
	Auto_Dark_Coat = true
end
function Chest_100()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 100 then
			_G.Chest_100 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 100 then
			_G.Chest_100 = v
			return
		end
	end
end
function Chest_500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
			_G.Chest_500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
			_G.Chest_500 = v
			return
		end
	end
end
function Chest_1000()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1000 then
			_G.Chest_1000 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1000 then
			_G.Chest_1000 = v
			return
		end
	end
end
function Chest_1500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1500 then
			_G.Chest_1500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1500 then
			_G.Chest_1500 = v
			return
		end
	end
end
function Chest_2000()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 2000 then
			_G.Chest_2000 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 2000 then
			_G.Chest_2000 = v
			return
		end
	end
end
function Chest_2500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 2500 then
			_G.Chest_2500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 2500 then
			_G.Chest_2500 = v
			return
		end
	end
end
function Chest_3500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3500 then
			_G.Chest_3500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3500 then
			_G.Chest_3500 = v
			return
		end
	end
end
function Chest_4500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4500 then
			_G.Chest_4500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4500 then
			_G.Chest_4500 = v
			return
		end
	end
end
function Chest_5500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5500 then
			_G.Chest_5500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5500 then
			_G.Chest_5500 = v
			return
		end
	end
end
function Chest_6500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 6500 then
			_G.Chest_6500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 6500 then
			_G.Chest_6500 = v
			return
		end
	end
end
function Chest_7500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 7500 then
			_G.Chest_7500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 7500 then
			_G.Chest_7500 = v
			return
		end
	end
end
function Chest_9500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 9500 then
			_G.Chest_9500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 9500 then
			_G.Chest_9500 = v
			return
		end
	end
end
function Chest_10500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10500 then
			_G.Chest_10500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10500 then
			_G.Chest_10500 = v
			return
		end
	end
end
function Chest_12500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 12500 then
			_G.Chest_12500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 12500 then
			_G.Chest_12500 = v
			return
		end
	end
end
function Chest_15500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 15500 then
			_G.Chest_15500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 15500 then
			_G.Chest_15500 = v
			return
		end
	end
end
function Chest_17500()
	for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		if v.Name == "Chest1" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 17500 then
			_G.Chest_17500 = v
			return
		elseif v.Name == "Chest2" and (v.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 17500 then
			_G.Chest_17500 = v
			return
		end
	end
end
spawn(function()
	while wait(.5) do
		pcall(function()
			if Auto_Dark_Coat then
				if game.Workspace.Enemies:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") or game.ReplicatedStorage:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") then
					H_F_T = true
					if game.Workspace.Enemies:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") then
                        for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                            if v.Name == "Darkbeard [Lv. 1000] [Raid Boss]" and v.Humanoid.Health > 0 then
                                repeat wait()
                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                    L_3_func(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                                until v.Humanoid.Health <= 0 or not v.Parent or not Auto_Dark_Coat
								H_F_T = nil
								if _G.Setting_table.Auto_Dark_Coat_Hop then
									HopServer()
									wait(50)
								end
							end
                        end
                    elseif game.ReplicatedStorage:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") then
                        L_3_func(game.ReplicatedStorage:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]").HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                    end
				elseif game.Players.LocalPlayer.Backpack:FindFirstChild("Fist of Darkness") or game.Players.LocalPlayer.Character:FindFirstChild("Fist of Darkness") then
					H_F_T = true
					repeat wait(.5)
                        EquipWeapon("Fist of Darkness")
                        L_3_func(CFrame.new(3778.0603, 15.0511189, -3499.95801, -0.0148028014, 1.28971422e-07, -0.999890447, 3.63752335e-08, 1, 1.28447041e-07, 0.999890447, -3.44698741e-08, -0.0148028014))
                    until game.Workspace.Enemies:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") or game.ReplicatedStorage:FindFirstChild("Darkbeard [Lv. 1000] [Raid Boss]") or not Auto_Dark_Coat
				else
					
					H_F_T = nil
					_G.Chest_100 = nil
						_G.Chest_500 = nil
						_G.Chest_1000 = nil
						_G.Chest_1500 = nil
						_G.Chest_2000 = nil
						_G.Chest_2500 = nil
						_G.Chest_3500 = nil
						_G.Chest_4500 = nil
						_G.Chest_5500 = nil
						_G.Chest_6500 = nil
						_G.Chest_7500 = nil
						_G.Chest_9500 = nil
						_G.Chest_10500 = nil
						_G.Chest_12500 = nil
						_G.Chest_15500 = nil
						_G.Chest_17500 = nil
						Chest_100()
						Chest_500()
						Chest_1000()
						Chest_1500()
						Chest_2000()
						Chest_2500()
						Chest_3500()
						Chest_4500()
						Chest_5500()
						Chest_6500()
						Chest_7500()
						Chest_9500()
						Chest_10500()
						Chest_12500()
						Chest_15500()
						Chest_17500()
						if _G.Chest_100 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_100.CFrame)
							until not _G.Chest_100.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_500.CFrame)
							until not _G.Chest_500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_1000 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_1000.CFrame)
							until not _G.Chest_1000.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_1500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_1500.CFrame)
							until not _G.Chest_1500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_2000 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_2000.CFrame)
							until not _G.Chest_2000.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_2500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_2500.CFrame)
							until not _G.Chest_2500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_3500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_3500.CFrame)
							until not _G.Chest_3500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_4500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_4500.CFrame)
							until not _G.Chest_4500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_5500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_5500.CFrame)
							until not _G.Chest_5500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_6500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_6500.CFrame)
							until not _G.Chest_6500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_7500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_7500.CFrame)
							until not _G.Chest_7500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_9500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_9500.CFrame)
							until not _G.Chest_9500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_10500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_10500.CFrame)
							until not _G.Chest_10500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_12500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_12500.CFrame)
							until not _G.Chest_12500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_15500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_15500.CFrame)
							until not _G.Chest_15500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						elseif _G.Chest_17500 ~= nil then
							repeat wait(.3)
								L_3_func(_G.Chest_17500.CFrame)
							until not _G.Chest_17500.Parent or not Auto_Dark_Coat
							if Auto_Dark_Coat then
								C_H_H = C_H_H + 1
								L_C:Change('Chest : '..tostring(C_H_H).."/".._G.Chest_Lock)
							end
						end
				end
			else
				wait(2)
			end
		end)
	end
end)

L_14_:Label("-「 Auto Evo Race V2」-")

L_14_:Toggle("Auto Evo Race V2",_G.Settings.Main["Evo Race V2"],function(value)
    _G.Settings.Main["Evo Race V2"] = value
SaveSettings()
if value == false then
	wait()
	L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
	wait()
end
end)

        spawn(function()
            game:GetService("RunService").Heartbeat:Connect(function()
                pcall(function()
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if _G.Settings.Main["Evo Race V2"] and StartEvoMagnet and v.Name == "Swan Pirate [Lv. 775]" and (v.HumanoidRootPart.Position - PosMonEvo.Position).magnitude <= 350 then
                            v.HumanoidRootPart.CFrame = PosMonEvo
                            v.HumanoidRootPart.CanCollide = false
                            v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                            if v.Humanoid:FindFirstChild("Animator") then
                                v.Humanoid.Animator:Destroy()
                            end
                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
                        end
                    end
                end)
            end)
        end)
    
        spawn(function()
            pcall(function()
                while wait() do
                    if _G.Settings.Main["Evo Race V2"] then
                        if not game:GetService("Players").LocalPlayer.Data.Race:FindFirstChild("Evolved") then
                            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 0 then
                                L_3_func(CFrame.new(-2779.83521, 72.9661407, -3574.02002, -0.730484903, 6.39014104e-08, -0.68292886, 3.59963224e-08, 1, 5.50667032e-08, 0.68292886, 1.56424669e-08, -0.730484903))
                                if (Vector3.new(-2779.83521, 72.9661407, -3574.02002) - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
                                    wait(1.3)
                                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","2")
                                end
                            elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 1 then
                                pcall(function()
                                    if not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 1") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 1") then
                                        L_3_func(game:GetService("Workspace").Flower1.CFrame)
                                    elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 2") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 2") then
                                        L_3_func(game:GetService("Workspace").Flower2.CFrame)
                                    elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 3") then
                                        if game:GetService("Workspace").Enemies:FindFirstChild("Swan Pirate [Lv. 775]") then
                                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                                if v.Name == "Swan Pirate [Lv. 775]" then
                                                    repeat wait()
                                                        
                                                        if _G.Settings.Configs["Auto Haki"] then
                                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                                            end
                                                        end
                                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                                            wait()
                                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,30,3))
                                                        v.HumanoidRootPart.CanCollide = false
                                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                                        game:GetService'VirtualUser':CaptureController()
                                                        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                        PosMonEvo = v.HumanoidRootPart.CFrame
                                                        StartEvoMagnet = true
                                                    until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") or not v.Parent or v.Humanoid.Health <= 0 or _G.Settings.Main["Evo Race V2"] == false
                                                    StartEvoMagnet = false
                                                end
                                            end
                                        else
                                            StartEvoMagnet = false
                                            L_3_func(CFrame.new(980.0985107421875, 121.331298828125, 1287.2093505859375))
                                        end
                                    end
                                end)
                            elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 2 then
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","3")
                            end
                        end
                    end
                end
            end)
        end)

--L_14_:Label("-「 Auto Evo Race V3」-")

--[[L_14_:Toggle("Auto Evo Race V3",_G.Settings.Main["Evo Race V3"],function(value)
    _G.Settings.Main["Evo Race V3"] = value
SaveSettings()
if value == false then
	wait()
	L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
	wait()
end
end)
]]
--[[    L_14_:Toggle("Auto Evo Race Human",getgenv().Human,function()
        getgenv().Human = value
    end)
    
    L_14_:Toggle("Auto Evo Race Mink",getgenv().Mink,function()
        getgenv().Mink = value
    end)
    
    L_14_:Toggle("Auto Evo Sky",getgenv().Sky,function()
        getgenv().Sky = value
    end)
    
    L_14_:Toggle("Auto Evo Shark",getgenv().Shark,function()
        getgenv().Shark = value
    end)
    
    L_14_:Toggle("Auto Evo Cybrog",getgenv().Cybrog,function()
        getgenv().Cybrog = value
    end)
    
    L_14_:Toggle("Auto Evo Ghoul",getgenv().Ghoul,function()
        getgenv().Ghoul = value
    end)
--]]

L_14_:Label("-「 Auto Rengoko 」-")

L_14_:Toggle("Auto Rengoku",_G.Settings.Main["Auto Rengoku"],function(value)
    _G.Settings.Main["Auto Rengoku"] = value
SaveSettings()
if value == false then
	wait()
	L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
	wait()
end
end)

    spawn(function()
        while wait() do
            if _G.Settings.Main["Auto Rengoku"] then
                pcall(function()
                    if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hidden Key") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Hidden Key") then
                        EquipWeapon("Hidden Key")
                        L_3_func(CFrame.new(6571.1201171875, 299.23028564453, -6967.841796875))
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Snow Lurker [Lv. 1375]") or game:GetService("Workspace").Enemies:FindFirstChild("Arctic Warrior [Lv. 1350]") or game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") then
                            if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                                if game:GetService("Players").LocalPlayer.Data.Level.Value then
                                    local Level = game.Players.LocalPlayer.Data.Level.Value
                                    if Level == 1350 or Level <= 1374 then
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","FrostQuest",1)
                                    elseif Level == 1375 or Level >= 1374 then
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","FrostQuest",2)
                                    end
                                end
                            end
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]" or v.Name ==  "Awakened Ice Admiral [Lv. 1400] [Boss]") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        
                                        wait()
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                            wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end
                                        --FastAttack = true
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                        RengokuMon = v.HumanoidRootPart.CFrame
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(10,20,30))
                                        game:GetService'VirtualUser':CaptureController()
                                        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        StartRengokuMagnet = true
                                    until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hidden Key") or _G.Settings.Main["Auto Rengoku"] == false or not v.Parent or v.Humanoid.Health <= 0
                                else
                                StartRengokuMagnet = false
                            end
                            end
                        end
                    else
                        StartRengokuMagnet = false
                        L_3_func(CFrame.new(5886.29834, 164.744598, -6693.71826, -0.731755793, -9.70470069e-08, -0.681566894, -1.0142292e-07, 1, -3.34966295e-08, 0.681566894, 4.46151525e-08, -0.731755793)) --5439.716796875, 84.420944213867, -6715.1635742188))
                    end
                end)
            end
        end
    end)

    spawn(function()
        while task.wait() do
            pcall(function()
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if _G.Settings.Main["Auto Rengoku"] and StartRengokuMagnet then
                        if (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]" or v.Name ==  "Awakened Ice Admiral [Lv. 1400] [Boss]" ) and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 220 then
                            v.HumanoidRootPart.Size = Vector3.new(70,70,70)
                            v.HumanoidRootPart.CFrame = RengokuMon
                            v.Humanoid:ChangeState(12)
                            v.Humanoid:ChangeState(13)
                            v.HumanoidRootPart.CanCollide = false
                            v.Head.CanCollide = false
                            if v.Humanoid:FindFirstChild("Animator") then
                                v.Humanoid.Animator:Destroy()
                            end
                            sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                        elseif _G.Settings.Main["Auto Rengoku"] and StartRengokuMagnet then
                            if (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]" or v.Name == "Awakened Ice Admiral [Lv. 1400] [Boss]") and (v.HumanoidRootPart.Position - RengokuMon.Position).Magnitude <= 250 and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                v.HumanoidRootPart.Size = Vector3.new(123,123,123)
                                v.Humanoid:ChangeState(12)
                                v.Humanoid:ChangeState(13)
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CFrame = RengokuMon
                                if v.Humanoid:FindFirstChild("Animator") then
                                    v.Humanoid.Animator:Destroy()
                                end
                                sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRadius", math.huge)
                            end
                        end
                    end
                end
            end)
        end
    end)

    L_14_:Label("-「 Auto Farm Ectoplasm 」-")
    
    L_14_:Toggle("Start Auto Ectoplasm",_G.Settings.Main["Auto Ectoplasm"],function(L_271_arg0)
		_G.Settings.Main["Auto Ectoplasm"] = L_271_arg0
		if L_271_arg0 == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
		SaveSettings()
		spawn(function()
			while wait() do
			    if _G.Settings.Main["Auto Ectoplasm"] then
				    if World1 or World3 then
					    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
				    end
				end
				pcall(function()
					if _G.Settings.Main["Auto Ectoplasm"] then
						if game:GetService("Workspace").Enemies:FindFirstChild("Ship Deckhand [Lv. 1250]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Engineer [Lv. 1275]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Steward [Lv. 1300]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Officer [Lv. 1325]") or game:GetService("Workspace").Enemies:FindFirstChild("Arctic Warrior [Lv. 1350]") then
							for L_272_forvar0, L_273_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if L_273_forvar1.Name == "Ship Deckhand [Lv. 1250]" or L_273_forvar1.Name == "Ship Engineer [Lv. 1275]" or L_273_forvar1.Name == "Ship Steward [Lv. 1300]" or L_273_forvar1.Name == "Ship Officer [Lv. 1325]" or L_273_forvar1.Name == "Arctic Warrior [Lv. 1350]" then
									if L_273_forvar1:FindFirstChild("Humanoid") and L_273_forvar1:FindFirstChild("HumanoidRootPart") and L_273_forvar1.Humanoid.Health > 0 then
										repeat
											wait()
											StartMagnet = true
											if _G.Settings.Configs["Auto Haki"] then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
												wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end
											PosMon = L_273_forvar1.HumanoidRootPart.CFrame
											game:GetService"VirtualUser":CaptureController()
											game:GetService"VirtualUser":Button1Down(Vector2.new(1280, 672))
											L_273_forvar1.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
											if _G.Settings.Configs["Show Hitbox"] then
												L_273_forvar1.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												L_273_forvar1.HumanoidRootPart.Transparency = 1
											end
											L_273_forvar1.Humanoid.JumpPower = 0
											L_273_forvar1.Humanoid.WalkSpeed = 0
											L_273_forvar1.HumanoidRootPart.CanCollide = false
											L_273_forvar1.Humanoid:ChangeState(11)
											L_3_func(L_273_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
										until not _G.Settings.Main["Auto Ectoplasm"] or not L_273_forvar1.Parent or L_273_forvar1.Humanoid.Health <= 0
										StartMagnet = false
									end
								end
							end
						else
							StartMagnet = false
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
						end
					end
				end)
			end
		end)
    end)

    L_14_:Label("-「 Legendary Sword 」-")
        
    L_14_:Toggle("Auto Legendary Sword",_G.Settings.Main["AutoBuyLegendarySword"],function(value)
        _G.Settings.Main["AutoBuyLegendarySword"] = value
        getgenv().AutoBuyLegendarySword = value
        SaveSettings()
    end)
    
    spawn(function()
        while wait() do
            if getgenv().AutoBuyLegendarySword then
                pcall(function()
                    local args = {
                        [1] = "LegendarySwordDealer",
                        [2] = "1"
                    }
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                    local args = {
                        [1] = "LegendarySwordDealer",
                        [2] = "2"
                    }
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                    local args = {
                        [1] = "LegendarySwordDealer",
                        [2] = "3"
                    }
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                    if _G.AutoBuyLegendarySword_Hop and _G.AutoBuyLegendarySword and World2 then
                        wait(10)
                        Hop()
                    end
                end)
            end 
        end
    end)


end

if World3 then

local L_14_11 = A:Section("Other Auto Farm World 3","Left")

L_14_11:Label("Auto Katakuri")

L_14_11:Toggle("Auto Cake Prince",_G.Settings.Main["Auto Cake Prince"],function(L_262_arg0)
	local CFrameMonCakePrince = CFrame.new(-1977.36768, 252.041473, -12380.4189, 1, -5.32872733e-08, 1.73125154e-05, 5.32856532e-08, 1, 9.34740285e-08, -1.73125154e-05, -9.34731048e-08, 1)
	a = L_3_func(CFrameMonCakePrince)
	if (CFrameMonCakePrince.Position - CFrameMonCakePrince.Position).magnitude <= 1 then
        L_3_func(CFrameMonCakePrince)
        _G.Settings.Main["Auto Cake Prince"] = true
        if a then
            a:Stop()
        end
    end
	SaveSettings()
	if L_262_arg0 == false then
	    _G.Settings.Main["Auto Cake Prince"] = false
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
	end
end)
spawn(function()
    while wait() do
        pcall(function()
            if string.len(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner")) == 88 then
                KillMob = (tonumber(string.sub(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner"),39,41)) - 500)
            elseif string.len(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner")) == 87 then
                KillMob = (tonumber(string.sub(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner"),40,41)) - 500)
            elseif string.len(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner")) == 86 then
                KillMob = (tonumber(string.sub(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner"),41,41)) - 500)
            end
        end)
    end
end)

spawn(function()
    while wait() do
        if _G.Settings.Main["Auto Cake Prince"] then
            pcall(function()
                if game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if v.Name == "Cake Prince [Lv. 2300] [Raid Boss]" then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                repeat task.wait()
                                    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                    end
                                    if _G.FastAttack then
                                        AttackNoCDPlayMode()
                                    end
                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                    v.HumanoidRootPart.CanCollide = false
                                    v.Humanoid.WalkSpeed = 0
                                    v.Humanoid:ChangeState(12)
                                    L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,-35,20))
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                    sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                until not _G.Settings.Main["Auto Cake Prince"] or not v.Parent or v.Humanoid.Health <= 0
                            end
                        end
                    end
                else
                    if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
                        L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
					else
                        if KillMob == 0 then
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CakePrinceSpawner",true)
                        end                    
                        if game:GetService("Workspace").Map.CakeLoaf.BigMirror.Other.Transparency == 1 then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Cookie Crafter [Lv. 2200]") or game:GetService("Workspace").Enemies:FindFirstChild("Cake Guard [Lv. 2225]") or game:GetService("Workspace").Enemies:FindFirstChild("Baking Staff [Lv. 2250]") or game:GetService("Workspace").Enemies:FindFirstChild("Head Baker [Lv. 2275]") then
                                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == "Cookie Crafter [Lv. 2200]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]" then
                                        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                            repeat task.wait()
                                                
                                                Questtween = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
                                                MagnetDought = true
                                                EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                v.Humanoid:ChangeState(12)
                                                v.Humanoid.JumpPower = 0
                                                if _G.FastAttack then
                                        AttackNoCDPlayMode()
                                    end
                                                v.Humanoid.WalkSpeed = 0
                                                v.HumanoidRootPart.CanCollide = false
                                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                                if _G.Settings.Configs["Auto Haki"] then
                                                    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                                    end
                                                end
                                                if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                                    wait()
                                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                end
                                                if getgenv().FarmModeRough then MagnetDought = true
                                                    _G.abcdefg = 335
                                                    _G.abcdefgs = 55
                                                    _G.abcdefgsas = 80
                                                    Questtween = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0, 55, 0))
                                                    game:GetService'VirtualUser':CaptureController()
                                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                end
                                                if getgenv().FarmModeSmooth then MagnetDought = true
                                                    _G.abcdefg = 100
                                                    _G.abcdefgs = 40
                                                    _G.abcdefgsas = 90
                                                    Questtween = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0, 45, 0))
                                                    game:GetService'VirtualUser':CaptureController()
                                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                end
                                            if (v.HumanoidRootPart.CFrame.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 340 then
                                                if Questtween then
                                                    Questtween:Stop()
                                                end
                                    local MonHealth = v.Humanoid.MaxHealth * 49/100
                                    local MonHealth2 = v.Humanoid.MaxHealth * _G.abcdefgs/100
                                    local MonHealth3 = v.Humanoid.MaxHealth * _G.abcdefgsas/100
                                    if getgenv().FarmModeRough then
                                        if v.Humanoid.Health <= MonHealth then
                                            --v.HumanoidRootPart.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-25,0)
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * (PosOdslob)
                                        else 
                                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * (PosOds)
                                        end
                                        if v.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,10,0)
                                            _G.FastAttackNormalSpeed = true
                                            --FastAttack = true
                                            _G.AutoGoGoGoFarm = true
                                            AttackPlayersFunction()
                                            AttackOK()
                                        else
                                            --FastAttack = false
                                            _G.FastAttackNormalSpeed = false
                                            _G.AutoGoGoGoFarm = false
                                        end
                                    end
                                    if getgenv().FarmModeSmooth then
                                        if v.Humanoid.Health <= MonHealth2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,13,13)
                                            _G.FastAttackNormalSpeed = true
                                            _G.AutoGoGoGoFarm = true
                                            --FastAttack = true
                                            AttackAC()
                                            AttackOK()
                                            AttackPlayersFunction()
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,20,20)
                                            _G.FastAttackNormalSpeed = false
                                            _G.AutoGoGoGoFarm = false
                                            --FastAttack = false
                                        end
                                    end
                                    if getgenv().FarmModeRough then
                                        if v.Humanoid.Health <= MonHealth3 then
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        else
                                            AttackOK()
                                            KoAttackOK()
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        end
                                    end
                                    if getgenv().FarmModeSmooth then 
                                        if v.Humanoid.Health <= MonHealth3 then
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        else
                                            AttackOK()
                                            KoAttackOK()
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                        end
                                    end
                                                --game.Players.localPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(15,35,25)
                                                --v.HumanoidRootPart.Transparency = 1
                                                game:GetService("VirtualUser"):CaptureController()
                                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                            end
                                            PosMon = v.HumanoidRootPart.CFrame
                                            until not _G.Settings.Main["Auto Cake Prince"] or not v.Parent or v.Humanoid.Health <= 0 or game:GetService("Workspace").Map.CakeLoaf.BigMirror.Other.Transparency == 0 or game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") or KillMob == 0
                                        end
                                    end
                                end
                            else
                                MagnetDought = false
                                if game:GetService("ReplicatedStorage"):FindFirstChild("Cookie Crafter [Lv. 2200]") then
                                    L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Cookie Crafter [Lv. 2200]").HumanoidRootPart.CFrame * CFrame.new(0,35,0)) 
                                else
                                    if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Guard [Lv. 2225]") then
                                        L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Guard [Lv. 2225]").HumanoidRootPart.CFrame * CFrame.new(0,35,0)) 
                                    else
                                        if game:GetService("ReplicatedStorage"):FindFirstChild("Baking Staff [Lv. 2250]") then
                                            L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Baking Staff [Lv. 2250]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                                        else
                                            if game:GetService("ReplicatedStorage"):FindFirstChild("Head Baker [Lv. 2275]") then
                                                L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Head Baker [Lv. 2275]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                                            end
                                        end
                                    end
                                end                       
                            end
                        else
                            if game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
                                L_3_func(game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                            else
                                if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
                                    L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                                end
                            end
                        end
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while task.wait() do
        pcall(function()
            if _G.Settings.Main["Auto Cake Prince"] then
                CheckQuest()
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if _G.Settings.Main["Auto Cake Prince"] and MagnetDought then
                        if (v.Name == "Cookie Crafter [Lv. 2200]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]") and (v.HumanoidRootPart.Position - PosMon.Position).Magnitude <= 220 and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                            v.Humanoid:ChangeState(12)
                            v.HumanoidRootPart.CanCollide = false
                            v.Head.CanCollide = false
                            v.HumanoidRootPart.CFrame = PosMon
                            if v.Humanoid:FindFirstChild("Animator") then
                                v.Humanoid.Animator:Destroy()
                            end
                            sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRadius", math.huge)
                        end
                    end
                end
            end
        end)
    end
end)

    L_14_11:Label("Auto Farm Buddy Swords")
    
    L_14_11:Toggle("Auto Buddy Swords",_G.Settings.Main["Auto Buddy Swords"],function(L_267_arg0)
		_G.Settings.Main["Auto Buddy Swords"] = L_267_arg0
		if L_267_arg0 == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait(5)
			AnimateText("KZ hub | ยินดีบริการ")
		end
    end)

spawn(function()
    while wait() do
        if _G.Settings.Main["Auto Buddy Swords"] then
            pcall(function()
                if game:GetService("Workspace").Enemies:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if v.Name == "Cake Queen [Lv. 2175] [Boss]" then
                            if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                repeat task.wait()
                                    if _G.Settings.Configs["Auto Haki"] then
                                        if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                        end
                                    end
                                    if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
                                        wait()
                                        EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                    end
                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                    v.Humanoid.JumpPower = 0
									v.Humanoid.WalkSpeed = 0
									v.HumanoidRootPart.CanCollide = false
									v.Humanoid:ChangeState(11)
									v.Humanoid:ChangeState(14)
									v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                    L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                    sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                until not _G.Settings.Main["Auto Buddy Swords"] or not v.Parent or v.Humanoid.Health <= 0
                            end
                        end
                    end
                else
                    if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
                        L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]").HumanoidRootPart.CFrame * CFrame.new(0,35,0))
                    else
                        L_3_func(CFrame.new(-690.954773, 415.099091, -11113.0576, -0.999929309, -0, -0.0118914554, -0, 1, -0, 0.0118914554, 0, -0.999929309))
                        AnimateText("Auto Buddy Swords")
                        wait(.2)
                        AnimateText("The monster hasn't been born yet. |บอสยังไม่เกิด")
                        AnimateText("")
                    end
                end
            end)
        end
    end
end)

    L_14_11:Label("Auto Farm Bone")
    
    L_14_11:Toggle("Start Auto Bone",_G.Settings.Main["Auto Farm Bone"],function(to)
		_G.Settings.Main["Auto Farm Bone"] = to
		if to == true then
		local CFrameAutoFarmBone = CFrame.new(-9547.74316, 142.530609, 5535.24561, 0.0930483043, 4.66031445e-08, 0.995661616, 6.28906065e-08, 1, -5.26835713e-08, -0.995661616, 6.75198777e-08, 0.0930483043)
            if _G.Settings.Main["Auto Farm Bone"] == true and (CFrameAutoFarmBone.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude >= 2300 then
                BTP(CFrameAutoFarmBone) --BTP(CFrameSetPoint)
                game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
                wait(0.1)
                repeat wait()
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmBone
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint")
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmBone
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint")
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmBone
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetspawnPoint")
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameAutoFarmBone
                    until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
            end
        end
		if to == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
		SaveSettings()
    end)

		spawn(function()
			while wait() do
				if World1 or World2 then
					Com("F_", "TravelZou")
				end
				pcall(function()
					if _G.Settings.Main["Auto Farm Bone"] then
						if game:GetService("Workspace").Enemies:FindFirstChild("Reborn Skeleton [Lv. 1975]") or game:GetService("Workspace").Enemies:FindFirstChild("Living Zombie [Lv. 2000]") or game:GetService("Workspace").Enemies:FindFirstChild("Demonic Soul [Lv. 2025]") or game:GetService("Workspace").Enemies:FindFirstChild("Posessed Mummy [Lv. 2050]") then
							for ddt, s in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if s.Name == "Reborn Skeleton [Lv. 1975]" or s.Name == "Living Zombie [Lv. 2000]" or s.Name == "Demonic Soul [Lv. 2025]" or s.Name == "Posessed Mummy [Lv. 2050]" then
									if s:FindFirstChild("Humanoid") and s:FindFirstChild("HumanoidRootPart") and s.Humanoid.Health > 0 then
										repeat wait() --AttackOKKO()
										    
                                            Questtween = L_3_func(s.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
                                            s.Humanoid:ChangeState(11)
                                            if (s.HumanoidRootPart.CFrame.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 220 then
                                                if Questtween then
                                                    Questtween:Stop()
                                                end
                                            game.Players.localPlayer.Character.HumanoidRootPart.CFrame = s.HumanoidRootPart.CFrame * CFrame.new(1, 30, 1)
                                            local MonHealth11 = s.Humanoid.MaxHealth * 100/100 
                                            local MonHealth22 = s.Humanoid.MaxHealth * 40/100 
                                            local MonHealth33 = s.Humanoid.MaxHealth * 90/100
											StartMagnet = true
											if _G.Settings.Configs["Auto Haki"] then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
												wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end EquipWeapon(_G.Settings.Configs["Select Weapon"])
											PosMon = s.HumanoidRootPart.CFrame
											game:GetService"VirtualUser":CaptureController()
											game:GetService"VirtualUser":Button1Down(Vector2.new(1280, 672))
											s.HumanoidRootPart.Size = Vector3.new(50, 50, 50)
											if _G.Settings.Configs["Show Hitbox"] then
												s.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												s.HumanoidRootPart.Transparency = 1
											end
											s.Humanoid.JumpPower = 0
											s.Humanoid.WalkSpeed = 0
											s.HumanoidRootPart.CanCollide = false
											s.Humanoid:ChangeState(12)
											if s.Humanoid.Health <= MonHealth11 then
                                                game.Players.localPlayer.Character.HumanoidRootPart.CFrame = s.HumanoidRootPart.CFrame * CFrame.new(1, 30, 1)
                                            else
                                                game.Players.localPlayer.Character.HumanoidRootPart.CFrame = s.HumanoidRootPart.CFrame * CFrame.new(1, 30, 1)
                                            end
                                            if s.Humanoid.Health <= MonHealth22 then
                                                _G.AutoGoGoGoFarm = true 
                                                _G.FastAttackNormalSpeed = true
                                                AttackPlayersFunction()
                                                AttackOK()
                                            else
                                                _G.FastAttackNormalSpeed = false
                                                _G.AutoGoGoGoFarm = false
                                            end
                                            if s.Humanoid.Health <= MonHealth33 then
                                                game:GetService'VirtualUser':CaptureController() game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                            else
                                                AttackOK()
                                                KoAttackOK()
                                                if s.Humanoid.Health <= 0 then
                                                    wait(0.05)
                                                    s:Destroy()
                                                end
                                                game:GetService'VirtualUser':CaptureController() game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                            end
											game.Players.localPlayer.Character.HumanoidRootPart.CFrame = s.HumanoidRootPart.CFrame * CFrame.new(1, 30, 1)
										end
										until not _G.Settings.Main["Auto Farm Bone"] or s.Humanoid.Health <= 0 or not s.Parent or s.Humanoid.Health <= 0
										StartMagnet = false
										_G.FastAttackNormalSpeed = false
									end
								end
							end
						else
							L_3_func(CFrame.new(- 9504.8564453125, 172.14292907714844, 6057.259765625))
						end
					end
				end)
			end
		end)

    L_14_11:Toggle("Auto Random Surprise",_G.Settings.Main["Auto Random Bone"],function(L_270_arg0)
		_G.Settings.Main["Auto Random Bone"] = L_270_arg0
		SaveSettings()
	end)

spawn(function()
	while wait(.1) do
		if _G.Settings.Main["Auto Random Bone"] then
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones", "Buy", 1, 1)
		end
	end
end)

    L_14_11:Toggle("Auto Farm Boss Hallow",_G.Settings.Main["Auto Farm Boss Hallow"],function(L_267_arg0)
		_G.Settings.Main["Auto Farm Boss Hallow"] = L_267_arg0
		if L_267_arg0 == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
		SaveSettings()
    end)
    
    spawn(function()
        while wait() do
            if _G.Settings.Main["Auto Farm Boss Hallow"] then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
                        for i, v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if string.find(v.Name , "Soul Reaper") then
                                repeat task.wait()
                                    EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                    if _G.Settings.Configs["Auto Haki"] then
										if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
										end
									end
                                    v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                    v.Humanoid.JumpPower = 0
									v.Humanoid.WalkSpeed = 0
                                    topos(v.HumanoidRootPart.CFrame * CFrame.new(3,25,5))
                                    v.Humanoid:ChangeState(14)
									v.Humanoid:ChangeState(12)
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670))
                                    v.HumanoidRootPart.Transparency = 1
                                    sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                until v.Humanoid.Health <= 0 or _G.Settings.Main["Auto Farm Boss Hallow"] == false
                            end
                        end
                    elseif game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hallow Essence") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Hallow Essence") then
                        repeat wait(.3) 
                            L_3_func(CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125)) wait()
                            L_3_func(CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125) * CFrame.new(0,-1.5,0)) wait()
                            until (CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 8                        
                        EquipWeapon("Hallow Essence")
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
                            L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(3,25,5))
                        end
                    end
                end)
            end
        end
    end)


end

------

local AutoFarmChest = A:Section("Auto Farm Chest","Left")

AutoFarmChest:Label("-「 Auto Farm Chest 」-")

AutoFarmChest:Toggle("Auto Farm Chest Tween",_G.Settings.Main["TweenChest"],function(dddd)
	_G.Settings.Main["TweenChest"] = dddd
	getgenv().Auto_Farm_Chest = dddd
	SaveSettings()
	if dddd == false then
		wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
end)

getgenv().Poggo = 1500

spawn(function()
	while wait() do 
		if getgenv().Auto_Farm_Chest then
			for i,v in pairs(game:GetService("Workspace"):GetChildren()) do 
				if v.Name:find("Chest") then
					if game:GetService("Workspace"):FindFirstChild(v.Name) then
						if (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5000+ getgenv().Poggo then
							repeat wait()
								if game:GetService("Workspace"):FindFirstChild(v.Name) then
									L_3_func(v.CFrame)
								end
							until getgenv().Auto_Farm_Chest == false or not v.Parent
							getgenv().Poggo = getgenv().Poggo + 1000
							break
						end
					end
				end
			end
		end
	end
end)

AutoFarmChest:Toggle("[Main] Auto Farm Chest Tween",_G.Settings.Main["TweenChest[1]"],function(c)
	_G.Settings.Main["TweenChest[1]"] = c
	getgenv().FarmChestTween = c
	SaveSettings()
	if c == false then
		wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
end)

game:GetService("RunService").Heartbeat:Connect(function()
    pcall(function()
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
            if getgenv().FarmChestTween then
				L_3_func(ModeFarmChest)
            end
        end
    end)
end)

AutoFarmChest:Toggle("Auto Farm Chest Tween (Ban Risk)",_G.Settings.Main["TweenChest[2]"],function(c)
	_G.Settings.Main["TweenChest[2]"] = c
	getgenv().TweenChest = c
	SaveSettings()
end)

spawn(function()
	while wait() do
		if getgenv().TweenChest == true then
			pcall(function()
				for i,v in pairs(game.Workspace:GetDescendants()) do
					if v.Name == "Chest2" or v.Name == "Chest1" or v.Name == "Chest3" then
						tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(2,Enum.EasingStyle.Quad)
						tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.CFrame})
						tween:Play()
						v.CanCollide = false
						game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(15)
					end
				end
			end)
		end
		wait(3)
	end
end)

AutoFarmChest:Toggle("[Main] Auto Farm Chest",_G.Settings.Main["Auto Farm Chest [Main]"],function(value)
	_G.Settings.Main["Auto Farm Chest [Main]"] = value
	getgenv().ChestFarm = value
	SaveSettings()
	if value == false then
		wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
end)

AutoFarmChest:Label("- Settings Auto Farm Chest -")

AutoFarmChest:Toggle("White Screen for Auto Farm Chest",_G.Settings.Main["FarmChestWhite"],function(value)
	_G.Settings.Main["FarmChestWhite"] = value
	getgenv().FarmChestWhite = value
	SaveSettings()
end)

AutoFarmChest:Toggle("[]for Main Chest 1",_G.Settings.Main["Chest1"],function(value)
	_G.Settings.Main["Chest1"] = value
	getgenv().Chest1 = value
	SaveSettings()
end)
AutoFarmChest:Toggle("[]for Main Chest 2",_G.Settings.Main["Chest2"],function(value)
	_G.Settings.Main["Chest2"] = value
	getgenv().Chest2 = value
	SaveSettings()
end)
AutoFarmChest:Toggle("[]for Main Chest 3",_G.Settings.Main["Chest3"],function(value)
	_G.Settings.Main["Chest3"] = value
	getgenv().Chest3 = value
	SaveSettings()
end)

spawn(function()
	while wait() do 
		pcall(function()
			if getgenv().Chest1 then
				ModeFarmChest = "Chest1"
			elseif getgenv().Chest2 then
				ModeFarmChest = "Chest2"
			elseif getgenv().Chest3 then
				ModeFarmChest = "Chest3"
			end
		end)
	end
end)

spawn(function()
	while wait() do 
		pcall(function()
			if getgenv().Chest1 then
				ModeFarmChest = game:GetService("Workspace").Chest1.CFrame * CFrame.new(0,0,0)
			elseif getgenv().Chest2 then
				ModeFarmChest = game:GetService("Workspace").Chest2.CFrame * CFrame.new(0,0,0)
			elseif getgenv().Chest3 then
				ModeFarmChest = game:GetService("Workspace").Chest3.CFrame * CFrame.new(0,0,0)
			end
		end)
	end
end)

game:GetService("RunService").Heartbeat:Connect(function()
	pcall(function()
		if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
			if getgenv().ChestFarm then
				if getgenv().Chest1 then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Chest1.CFrame * CFrame.new(0,0,0)
				end
			end
		end
	end)
end)

game:GetService("RunService").Heartbeat:Connect(function()
	pcall(function()
		if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
			if getgenv().ChestFarm then
				if getgenv().Chest2 then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Chest2.CFrame * CFrame.new(0,0,0)
				end
			end
		end
	end)
end)

game:GetService("RunService").Heartbeat:Connect(function()
	pcall(function()
		if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
			if getgenv().ChestFarm then
				if getgenv().Chest3 then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Chest3.CFrame * CFrame.new(0,0,0)
				end
			end
		end
	end)
end)

game:GetService("RunService").Heartbeat:Connect(function()
	pcall(function()
		if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
			if getgenv().ChestFarm then
				game.Players.LocalPlayer.Character.Humanoid.Health = 0
			end
		end
	end)
end)

spawn(function()
    while wait() do 
        pcall(function()
			if getgenv().ChestFarm then
            	if getgenv().FarmChestWhite == true then
                	game:GetService("RunService"):Set3dRenderingEnabled(false)
            	elseif getgenv().FarmChestWhite == false then
                	game:GetService("RunService"):Set3dRenderingEnabled(true)
            	end
			end
        end)
    end
end)

    local AutoFarmOthers = A:Section("Auto Farm Others","Left")
    
    AutoFarmOthers:Label("-「 Auto Farm Observation 」-")

    AutoFarmOthers:Toggle("Auto Farm Observation",_G.Settings.Main["Auto Observation"],function(value)
        _G.Settings.Main["Auto Observation"] = value
        getgenv().AutoObservation = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    AutoFarmOthers:Button("Buy Observation",function()
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("KenTalk","Buy")
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if getgenv().AutoObservation then
                    repeat task.wait()
                        if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                            game:GetService('VirtualUser'):CaptureController()
                            game:GetService('VirtualUser'):SetKeyDown('0x65')
                            wait(2)
                            game:GetService('VirtualUser'):SetKeyUp('0x65')
                        end
                    until game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") or not getgenv().AutoObservation
                end
            end)
        end
    end)
    
    AutoFarmOthers:Toggle("Auto Farm Observation [Hop]",_G.Settings.Main["Auto Observation Hop"],function(value)
        _G.Settings.Main["Auto Observation Hop"] = value
        getgenv().AutoObservation_Hop = value
        SaveSettings()
		if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if getgenv().AutoObservation then
                    if game:GetService("Players").LocalPlayer.VisionRadius.Value >= 3000 then
                        game:GetService("StarterGui"):SetCore("SendNotification", {
                            Icon = "rbxassetid://0";
                            Title = "Observation", 
                            Text = "You Have Max Points"
                        })
                        wait(2)
                    else
                        if World2 then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Lava Pirate [Lv. 1200]") then
                                if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                    repeat task.wait()
                                        L_3_func(game:GetService("Workspace").Enemies:FindFirstChild("Lava Pirate [Lv. 1200]").HumanoidRootPart.CFrame * CFrame.new(2.5,0,0))
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Lava Pirate [Lv. 1200]").HumanoidRootPart.CFrame * CFrame.new(0,0,0)
                                    until getgenv().AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                else
                                    repeat task.wait()
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Lava Pirate [Lv. 1200]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                            wait(1)
                                        if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and getgenv().AutoObservation_Hop == true then
                                            game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                        end
                                    until getgenv().AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                end
                            else
                                L_3_func(CFrame.new(-5478.39209, 15.9775667, -5246.9126))
                            end
                        elseif World1 then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]") then
                                if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                    repeat task.wait()
                                        L_3_func(game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(2.5,0,0))
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame
                                    until getgenv().AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                else
                                    repeat task.wait()
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Galley Captain [Lv. 650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                        wait(1)
                                        if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and getgenv().AutoObservation_Hop == true then
                                            game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                        end
                                    until getgenv().AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                end
                            else
                                L_3_func(CFrame.new(5533.29785, 88.1079102, 4852.3916))
                            end
                        elseif World3 then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]") then
                                if game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") then
                                    repeat task.wait()
                                        L_3_func(game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(2.5,0,0))
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(0,0,0)
                                    until getgenv().AutoObservation == false or not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                else
                                    repeat task.wait()
                                        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Enemies:FindFirstChild("Giant Islander [Lv. 1650]").HumanoidRootPart.CFrame * CFrame.new(0,50,0)
                                        wait(1)
                                        if not game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel") and getgenv().AutoObservation_Hop == true then
                                            game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
                                        end
                                    until getgenv().AutoObservation == false or game:GetService("Players").LocalPlayer.PlayerGui.ScreenGui:FindFirstChild("ImageLabel")
                                end
                            else
                                L_3_func(CFrame.new(4602.13672, 657.096741, -44.6182175, -0.174396217, 0, -0.984675586, 0, 1, 0, 0.984675586, 0, -0.174396217))
                            end
                        end
                    end
                end
            end)
        end
    end)

    local ObservationRange = AutoFarmOthers:Label("Observation Range Level : ?")
    
    AutoFarmOthers:Button("Update Label Observation",function()
        ObservationRange:Change("Observation Range Level : "..math.floor(game:GetService("Players").LocalPlayer.VisionRadius.Value))
    end)
    AutoFarmOthers:Toggle("Auto Update Label Observation",_G.Settings.Main["Auto Update Label Observation"],function(v)
        _G.Settings.Main["Auto Update Label Observation"] = v
        SaveSettings()
        getgenv().UpdateLabelObservation = v
    end)

    spawn(function()
        while wait() do
            pcall(function()
                if getgenv().UpdateLabelObservation then
                    ObservationRange:Change("Observation Range Level : "..math.floor(game:GetService("Players").LocalPlayer.VisionRadius.Value))
                end
            end)
        end
    end)

    local AutoMusketeerHat = A:Section("Auto Musketeer Hat","Left")

    AutoMusketeerHat:Label("Auto Musketeer Hat")

    AutoMusketeerHat:Toggle("Auto Musketeer Hat",_G.Settings.Main["Auto Musketeer Hat"],function(value)
        _G.Settings.Main["Auto Musketeer Hat"] = value
        _G.AutoMusketeerHat = value
        SaveSettings()
        if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild("Forest Pirate [Lv. 1825]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if _G.AutoMusketeerHat and StartMagnetMusketeerhat and v.Name == "Forest Pirate [Lv. 1825]"and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and (v.HumanoidRootPart.Position - MusketeerHatMon.Position).Magnitude <= 250  then
                                v.HumanoidRootPart.Size = Vector3.new(80,80,80)
                                v.Humanoid:ChangeState(14)
                                v.HumanoidRootPart.CanCollide = false
                                v.Head.CanCollide = false
                                v.Humanoid.JumpPower = 0
                                v.Humanoid.WalkSpeed = 0
                                v.HumanoidRootPart.CFrame = MusketeerHatMon
                                if v.Humanoid:FindFirstChild("Animator") then
                                    v.Humanoid.Animator:Destroy()
                                end
                                v.Humanoid:ChangeState(12)
                                sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRadius", math.huge)
                            end
                        end
                    end
            end)
        end
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if _G.AutoMusketeerHat then
                    if game:GetService("Players").LocalPlayer.Data.Level.Value >= 1800 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress").KilledBandits == false then
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                            local logdd = {
                                [1] = "requestEntrance",
                                [2] = Vector3.new(- 12548.595703125, 337.17001342773, - 7554.6103515625)
                            }
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(logdd))
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-12443.8671875, 332.40396118164, -7675.4892578125)
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-13206.452148438, 425.89199829102, -7964.5537109375)
                            --L_3_func(CFrame.new(-13206.452148438, 425.89199829102, -7964.5537109375))
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","CitizenQuest",1)
                            
                        end
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then --string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Forest Pirate") and string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "50") and
                            if not game:GetService("Workspace").Enemies["Forest Pirate [Lv. 1825]"] and game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                                L_3_func(CFrame.new(-13206.452148438, 425.89199829102, -7964.5537109375))
                            end
                            if game:GetService("Workspace").Enemies:FindFirstChild("Forest Pirate [Lv. 1825]") then
                                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == "Forest Pirate [Lv. 1825]" then
                                        repeat wait()
                                            
                                            --pcall(function()
                                                EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                v.HumanoidRootPart.CanCollide = false
                                                L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(0,5,31))
                                                MusketeerHatMon = v.HumanoidRootPart.CFrame
                                                game:GetService'VirtualUser':CaptureController()
                                                game:GetService'VirtualUser':Button1Down(Vector2.new(0.9, 0.9))
                                                v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                                StartMagnetMusketeerhat = true
                                            --end)
                                        until _G.AutoMusketeerHat == false or not v.Parent or v.Humanoid.Health <= 0 --or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                        StartMagnetMusketeerhat = false
                                    end
                                end
                            end
                        end
                    elseif game:GetService("Players").LocalPlayer.Data.Level.Value >= 1800 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress").KilledBoss == false then
                        if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible and string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Captain Elephant") and game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Captain Elephant [Lv. 1875] [Boss]") then
                                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == "Captain Elephant [Lv. 1875] [Boss]" then
                                        OldCFrameElephant = v.HumanoidRootPart.CFrame
                                        repeat task.wait()
                                            
                                            --pcall(function()
                                                 EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                                v.HumanoidRootPart.CanCollide = false
                                                v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                                L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                                v.HumanoidRootPart.CanCollide = false
                                                v.HumanoidRootPart.CFrame = OldCFrameElephant
                                                game:GetService("VirtualUser"):CaptureController()
                                                game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                                sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                            --end)
                                        until _G.AutoMusketeerHat == false or v.Humanoid.Health <= 0 or not v.Parent-- or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                    end
                                end
                            else
                                L_3_func(CFrame.new(-13374.889648438, 421.27752685547, -8225.208984375))
                            end
                        else
                            L_3_func(CFrame.new(-12443.8671875, 332.40396118164, -7675.4892578125))
                            if (CFrame.new(-12443.8671875, 332.40396118164, -7675.4892578125).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
                                wait(1.5)
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress","Citizen")
                            end
                        end
                    elseif game:GetService("Players").LocalPlayer.Data.Level.Value >= 1800 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress","Citizen") == 2 then
                        L_3_func(CFrame.new(-12512.138671875, 340.39279174805, -9872.8203125))
                    end
                end
            end)
        end
    end)
    
    local AutoRainbowHaki = A:Section("Auto Rainbow Haki","Left")
    
    AutoRainbowHaki:Label("Auto Rainbow Haki")
    
    AutoRainbowHaki:Toggle("Auto Rainbow Haki",_G.Settings.Main["Auto Rainbow Haki"],function(value)
        _G.Auto_Rainbow_Haki = value
        _G.Settings.Main["Auto Rainbow Haki"] = value
        SaveSettings()
        if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    spawn(function()
        pcall(function()
            while wait(.1) do
                if _G.Auto_Rainbow_Haki then
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                        L_3_func(CFrame.new(-11892.0703125, 930.57672119141, -8760.1591796875))
                        if (Vector3.new(-11892.0703125, 930.57672119141, -8760.1591796875) - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
                            wait(1.5)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("HornedMan","Bet")
                        end
                    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true and string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Stone") then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Stone [Lv. 1550] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "Stone [Lv. 1550] [Boss]" then
                                    OldCFrameRainbow = v.HumanoidRootPart.CFrame
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.CFrame = OldCFrameRainbow
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until _G.Auto_Rainbow_Haki == false or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                end
                            end
                        else
                            L_3_func(CFrame.new(-1086.11621, 38.8425903, 6768.71436, 0.0231462717, -0.592676699, 0.805107772, 2.03251839e-05, 0.805323839, 0.592835128, -0.999732077, -0.0137055516, 0.0186523199))
                        end
                    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true and string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Island Empress") then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Island Empress [Lv. 1675] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "Island Empress [Lv. 1675] [Boss]" then
                                    OldCFrameRainbow = v.HumanoidRootPart.CFrame
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.CFrame = OldCFrameRainbow
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until _G.Auto_Rainbow_Haki == false or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                end
                            end
                        else
                            L_3_func(CFrame.new(5713.98877, 601.922974, 202.751251, -0.101080291, -0, -0.994878292, -0, 1, -0, 0.994878292, 0, -0.101080291))
                        end
                    elseif string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Kilo Admiral") then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Kilo Admiral [Lv. 1750] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "Kilo Admiral [Lv. 1750] [Boss]" then
                                    OldCFrameRainbow = v.HumanoidRootPart.CFrame
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        v.HumanoidRootPart.CFrame = OldCFrameRainbow
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until _G.Auto_Rainbow_Haki == false or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                end
                            end
                        else
                            L_3_func(CFrame.new(2877.61743, 423.558685, -7207.31006, -0.989591599, -0, -0.143904909, -0, 1.00000012, -0, 0.143904924, 0, -0.989591479))
                        end
                    elseif string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Captain Elephant") then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Captain Elephant [Lv. 1875] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "Captain Elephant [Lv. 1875] [Boss]" then
                                    OldCFrameRainbow = v.HumanoidRootPart.CFrame
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
                                        if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then wait()
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        v.HumanoidRootPart.CFrame = OldCFrameRainbow
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until _G.Auto_Rainbow_Haki == false or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                end
                            end
                        else
                            L_3_func(CFrame.new(-13485.0283, 331.709259, -8012.4873, 0.714521289, 7.98849911e-08, 0.69961375, -1.02065748e-07, 1, -9.94383065e-09, -0.69961375, -6.43015241e-08, 0.714521289))
                        end
                    elseif string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Beautiful Pirate") then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Beautiful Pirate [Lv. 1950] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "Beautiful Pirate [Lv. 1950] [Boss]" then
                                    OldCFrameRainbow = v.HumanoidRootPart.CFrame
                                    repeat task.wait()
                                        
                                        if _G.Settings.Configs["Auto Haki"] then
                                            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                                            end
                                        end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                        L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                        v.HumanoidRootPart.CFrame = OldCFrameRainbow
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(0.9, 0.9))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until _G.Auto_Rainbow_Haki == false or v.Humanoid.Health <= 0 or not v.Parent or game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false
                                end
                            end
                        else
                            L_3_func(CFrame.new(5312.3598632813, 20.141201019287, -10.158538818359))
                        end
                    else
                        L_3_func(CFrame.new(-11892.0703125, 930.57672119141, -8760.1591796875))
                        if (Vector3.new(-11892.0703125, 930.57672119141, -8760.1591796875) - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
                            wait(1.5)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("HornedMan","Bet")
                        end
                    end
                end
            end
        end)
    end)
    
    local AutoObservationv2 = A:Section("Auto Observation Haki v2","Left")
    
    AutoObservationv2:Label("Auto Observation Haki v2")

    AutoObservationv2:Toggle("Auto Observation Haki v2",_G.Settings.Main["Auto Observation Haki v2"],function(value)
        _G.Settings.Main["Auto Observation Haki v2"] = value
        _G.AutoObservationv2 = value
        SaveSettings()
        if value == false then
			wait()
			L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if _G.AutoObservationv2 then
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress","Citizen") == 3 then
                        _G.AutoMusketeerHat = false
                        if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Banana") and  game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Apple") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Pineapple") then
                            repeat 
                                
                                L_3_func(CFrame.new(-12444.78515625, 332.40396118164, -7673.1806640625)) 
                                wait() 
                            until not _G.AutoObservationv2 or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position-Vector3.new(-12444.78515625, 332.40396118164, -7673.1806640625)).Magnitude <= 10
                            wait(.5)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("CitizenQuestProgress","Citizen")
                        elseif game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fruit Bowl") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fruit Bowl") then
                            repeat 
                                L_3_func(CFrame.new(-10920.125, 624.20275878906, -10266.995117188)) 
                                wait() 
                            until not _G.AutoObservationv2 or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position-Vector3.new(-10920.125, 624.20275878906, -10266.995117188)).Magnitude <= 10
                            wait(.5)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("KenTalk2","Start")
                            wait(1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("KenTalk2","Buy")
                        else
                            for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
                                if v.Name == "Apple" or v.Name == "Banana" or v.Name == "Pineapple" then
                                    v.Handle.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,1,10)
                                    wait()
                                    firetouchinterest(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,v.Handle,0)    
                                    wait()
                                end
                            end   
                        end
                    else
                        _G.AutoMusketeerHat = true
                    end
                end
            end)
        end
    end)

L_15_:Label("Auto Get Fighting Styles")

L_15_:Toggle("Auto Electric Claw",_G.Settings.FightingStyle["Auto Electric Claw"],function(L_287_arg0)
		_G.Settings.FightingStyle["Auto Electric Claw"] = L_287_arg0
		SaveSettings()
		if _G.Settings.FightingStyle["Auto Electric Claw"] then
			Com("F_", "BuyElectro")
		end
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto Electric Claw"] then
						if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value < 400 then
								_G.Settings.Configs["Select Weapon"] = "Electro"
							end  
							if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value < 400 then
								_G.Settings.Configs["Select Weapon"] = "Electro"
							end  
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
								local L_288_ = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyElectricClaw", true);
								if L_288_ == 4 then
									local L_289_ = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyElectricClaw", "Start");
									if L_289_ == nil then
										game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(- 12548, 337, - 7481)
									end
								else
									local L_290_ = "BuyElectricClaw";
									local L_291_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_291_:InvokeServer(L_290_);
								end
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
								local L_292_ = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyElectricClaw", true);
								if L_292_ == 4 then
									local L_293_ = game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyElectricClaw", "Start");
									if L_293_ == nil then
										game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(- 12548, 337, - 7481)
									end
								else
									local L_294_ = "BuyElectricClaw";
									local L_295_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_295_:InvokeServer(L_294_);
								end
							end
						end
					end
				end)
			end
		end)
	end
)

L_15_:Toggle("Auto Death Step",_G.Settings.FightingStyle["Auto Death Step"],function(L_296_arg0)
		_G.Settings.FightingStyle["Auto Death Step"] = L_296_arg0
		SaveSettings()
		if _G.Settings.FightingStyle["Auto Death Step"] then
			Com("F_", "BuyBlackLeg")
		end
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto Death Step"] then
						if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 400 then
								local L_297_ = {
									[1] = "BuyDeathStep"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_297_))
								_G.Settings.Configs["Select Weapon"] = "Death Step"
							end  
							if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 400 then
								local L_298_ = {
									[1] = "BuyDeathStep"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_298_))

								_G.Settings.Configs["Select Weapon"] = "Death Step"
							end  
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value < 400 then
								_G.Settings.Configs["Select Weapon"] = "Black Leg"
							end
						end
					elseif _G.Settings.FightingStyle["Auto Fully Death Step"] then
						if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 400 or game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 400 then
							if game:GetService("Workspace").Map.IceCastle.Hall.LibraryDoor.PhoeyuDoor.Transparency == 0 then  
								if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Library Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Library Key") then
									EquipWeapon("Library Key")
									repeat
										wait()
										L_3_func(CFrame.new(6371.2001953125, 296.63433837890625, - 6841.18115234375))
									until (CFrame.new(6371.2001953125, 296.63433837890625, - 6841.18115234375).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not _G.Settings.FightingStyle["Auto Death Step"]
									if (CFrame.new(6371.2001953125, 296.63433837890625, - 6841.18115234375).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
										wait(1.2)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep", true)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
										wait(0.5)
									end
								elseif game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 450 or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 450 then   
									if game:GetService("ReplicatedStorage"):FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") then
										if game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") then 	
											for L_299_forvar0, L_300_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
												if L_300_forvar1.Name == "Awakened Ice Admiral [Lv. 1400] [Boss]" then    
													repeat
														wait()
														if game.Workspace.Enemies:FindFirstChild(L_300_forvar1.Name) then
															if (L_300_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 200 then
																Farmtween = L_3_func(L_300_forvar1.HumanoidRootPart.CFrame)
															elseif (L_300_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 200 then
																if Farmtween then
																	Farmtween:Stop()
																end
																if _G.Settings.Configs["Auto Haki"] then
																	if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
																		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
																	end
																end
																if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
																	wait()
																	EquipWeapon(_G.Settings.Configs["Select Weapon"])
																end
																game:GetService'VirtualUser':CaptureController()
																game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
																L_300_forvar1.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
																if _G.Settings.Configs["Show Hitbox"] then
																	L_300_forvar1.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
																else
																	L_300_forvar1.HumanoidRootPart.Transparency = 1
																end
																L_300_forvar1.Humanoid.JumpPower = 0
																L_300_forvar1.Humanoid.WalkSpeed = 0
																L_300_forvar1.HumanoidRootPart.CanCollide = false
																L_300_forvar1.Humanoid:ChangeState(11)
																L_3_func(L_300_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
																if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
																	game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
																	game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
																end
															end
														end
													until not L_300_forvar1.Parent or L_300_forvar1.Humanoid.Health <= 0 or _G.Settings.FightingStyle["Auto Death Step"] == false or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Library Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Library Key")
												end
											end
										else
											L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]").HumanoidRootPart.CFrame)
										end
									end
								end
							end
						else
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
						end
					end
				end)
			end
		end)
    end
)


L_15_:Toggle("Auto SharkMan Karate",_G.Settings.FightingStyle["Auto SharkMan Karate"],function(L_301_arg0)
		_G.Settings.FightingStyle["Auto SharkMan Karate"] = L_301_arg0
		SaveSettings()
		if _G.Settings.FightingStyle["Auto SharkMan Karate"] then
			Com("F_", "BuySharkmanKarate")
		end
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto SharkMan Karate"] then
						if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
							if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Sharkman Karate") then
								if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 400 then
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
									_G.Settings.Configs["Select Weapon"] = "Sharkman Karate"
								end  
								if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 400 then
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
									_G.Settings.Configs["Select Weapon"] = "Sharkman Karate"
								end  
								if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 400 then
									_G.Settings.Configs["Select Weapon"] = "Fishman Karate"
								end 
							else 
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
							end
						end
					elseif _G.Settings.FightingStyle["Auto Fully SharkMan Karate"] then
						if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 400 or game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 400 then
							if string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate"), "keys") then  
								if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Water Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Water Key") then
									repeat
										wait()
										L_3_func(- 2604.6958, 239.432526, - 10315.1982, 0.0425701365, 0, - 0.999093413, 0, 1, 0, 0.999093413, 0, 0.0425701365)
									until (CFrame.new(- 2604.6958, 239.432526, - 10315.1982, 0.0425701365, 0, - 0.999093413, 0, 1, 0, 0.999093413, 0, 0.0425701365).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not _G.Auto_Fully_SharkMan_Karate
									if (CFrame.new(- 2604.6958, 239.432526, - 10315.1982, 0.0425701365, 0, - 0.999093413, 0, 1, 0, 0.999093413, 0, 0.0425701365).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
										wait(1.2)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
										wait(0.5)
									end
								elseif game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 400 or game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 400 then   
									if game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
										if game:GetService("Workspace").Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then 	
											for L_302_forvar0, L_303_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
												if L_303_forvar1.Name == "Tide Keeper [Lv. 1475] [Boss]" then    
													repeat
														wait()
														if game.Workspace.Enemies:FindFirstChild(L_303_forvar1.Name) then
															if (L_303_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 200 then
																Farmtween = L_3_func(L_303_forvar1.HumanoidRootPart.CFrame)
															elseif (L_303_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 200 then
																if Farmtween then
																	Farmtween:Stop()
																end
																if _G.Settings.Configs["Auto Haki"] then
																	if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
																		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
																	end
																end
																if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
																	wait()
																	EquipWeapon(_G.Settings.Configs["Select Weapon"])
																end
																game:GetService'VirtualUser':CaptureController()
																game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
																L_303_forvar1.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
																if _G.Settings.Configs["Show Hitbox"] then
																	L_303_forvar1.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
																else
																	L_303_forvar1.HumanoidRootPart.Transparency = 1
																end
																L_303_forvar1.Humanoid.JumpPower = 0
																L_303_forvar1.Humanoid.WalkSpeed = 0
																L_303_forvar1.HumanoidRootPart.CanCollide = false
																L_303_forvar1.Humanoid:ChangeState(11)
																L_3_func(L_303_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
																if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
																	game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
																	game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
																end
															end
														end
													until not L_303_forvar1.Parent or L_303_forvar1.Humanoid.Health <= 0 or _G.Settings.FightingStyle["Auto Death Step"] == false or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Library Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Library Key")
												end
											end
										else
											L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]").HumanoidRootPart.CFrame)
										end
									end
								end
							else 
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
							end
						else
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
						end
					end
				end)
			end
		end)
	end
)

L_15_:Toggle("Auto Dragon Talon",_G.Settings.FightingStyle["Auto Dragon Talon"],function(L_304_arg0)
		_G.Settings.FightingStyle["Auto Dragon Talon"] = L_304_arg0
		SaveSettings()
		if _G.Settings.FightingStyle["Auto Dragon Talon"] then
			Com("F_", "BlackbeardReward", "DragonClaw", "2")
		end
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto Dragon Talon"] then
						if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 399 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
								_G.Settings.Configs["Select Weapon"] = "Dragon Claw"
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value <= 399 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
								_G.Settings.Configs["Select Weapon"] = "Dragon Claw"
							end

							if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 400 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
								_G.Settings.Configs["Select Weapon"] = "Dragon Claw"
								if game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 3 then
									local L_305_ = "Bones";
									local L_306_ = "Buy";
									local L_307_ = 1;
									local L_308_ = 1;
									local L_309_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_309_:InvokeServer(L_305_, L_306_, L_307_, L_308_);

									local L_310_ = "BuyDragonTalon";
									local L_311_ = true;
									local L_312_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_312_:InvokeServer(L_310_, L_311_);
								elseif game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 1 then
									game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon")
								else
									local L_313_ = "BuyDragonTalon";
									local L_314_ = true;
									local L_315_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_315_:InvokeServer(L_313_, L_314_);
									local L_316_ = "BuyDragonTalon";
									local L_317_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_317_:InvokeServer(L_316_);
								end 
							end

							if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 400 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
								_G.Settings.Configs["Select Weapon"] = "Dragon Claw"
								if game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 3 then
									local L_318_ = "Bones";
									local L_319_ = "Buy";
									local L_320_ = 1;
									local L_321_ = 1;
									local L_322_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_322_:InvokeServer(L_318_, L_319_, L_320_, L_321_);

									local L_323_ = "BuyDragonTalon";
									local L_324_ = true;
									local L_325_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_325_:InvokeServer(L_323_, L_324_);
								elseif game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 1 then
									game.ReplicatedStorage.Remotes.CommF_:InvokeServer("BuyDragonTalon")
								else
									local L_326_ = "BuyDragonTalon";
									local L_327_ = true;
									local L_328_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_328_:InvokeServer(L_326_, L_327_);
									local L_329_ = "BuyDragonTalon";
									local L_330_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
									L_330_:InvokeServer(L_329_);
								end 
							end
						end
					end
				end)
			end
		end)
	end
)

L_15_:Toggle("Auto Superhuman",_G.Settings.FightingStyle["Auto Superhuman"],function(L_274_arg0)
		_G.Settings.FightingStyle["Auto Superhuman"] = L_274_arg0
		SaveSettings()
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto Superhuman"] then
						if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
							if not game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") and not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
								if not game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and not game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") then
									if not game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and not game.Players.LocalPlayer.Character:FindFirstChild("Electro") then
										if not game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and not game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") then
											if not game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and not game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") then
												if not game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") and not game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") then
													local L_275_ = {
														[1] = "BuyElectro"
													}
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_275_))
												end
											end
										end
									end
								end
							end

							_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")

							if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
								local L_276_ = {
									[1] = "BuyElectro"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_276_))
							end
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 then
								local L_277_ = {
									[1] = "BuyBlackLeg"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_277_))
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 then
								local L_278_ = {
									[1] = "BuyBlackLeg"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_278_))
							end
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 then
								local L_279_ = {
									[1] = "BuyFishmanKarate"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_279_))
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 then
								local L_280_ = {
									[1] = "BuyFishmanKarate"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_280_))
							end
							if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 then
								local L_281_ = {
									[1] = "BlackbeardReward",
									[2] = "DragonClaw",
									[3] = "2"
								}
								HaveDragonClaw = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_281_))
								if _G.Settings.FightingStyle["Auto Superhuman"] and game.Players.LocalPlayer.Data.Fragments.Value <= 1500 and HaveDragonClaw == 0 then
									if game.Players.LocalPlayer.Data.Level.Value > 1100 then
										_G.Settings.Raids["Select Raids"] = "Flame"
										_G.Settings.Raids["Auto Raids"] = true
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = false
										end
									end
								else
									_G.Settings.Raids["Auto Raids"] = false
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
									local L_282_ = {
										[1] = "BlackbeardReward",
										[2] = "DragonClaw",
										[3] = "2"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_282_))
									_G.Settings.Raids["Auto Raids"] = false
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
								end
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 then
								local L_283_ = {
									[1] = "BlackbeardReward",
									[2] = "DragonClaw",
									[3] = "2"
								}
								HaveDragonClaw = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_283_))
								if _G.Settings.FightingStyle["Auto Superhuman"] and game.Players.LocalPlayer.Data.Fragments.Value <= 1500 and HaveDragonClaw == 0 then
									if game.Players.LocalPlayer.Data.Level.Value > 1100 then
										_G.Settings.Raids["Select Raids"] = "Flame"
										_G.Settings.Raids["Auto Raids"] = true
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = false
										end
									end
								else
									_G.Settings.Raids["Auto Raids"] = false
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
									local L_284_ = {
										[1] = "BlackbeardReward",
										[2] = "DragonClaw",
										[3] = "2"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_284_))
									_G.Settings.Raids["Auto Raids"] = false
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
								end
							end

							if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 then
								Auto_Farm_Level = _G.Settings.Main["Auto Farm Level"]
								local L_285_ = {
									[1] = "BuySuperhuman"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_285_))
							end
							if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 then
								Auto_Farm_Level = _G.Settings.Main["Auto Farm Level"]
								local L_286_ = {
									[1] = "BuySuperhuman"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_286_))
							end 
						end
					end
				end)
			end
		end)
	end
)

L_15_:Toggle("Auto God Human",_G.Settings.FightingStyle["Auto God Human"],function(L_331_arg0)
		_G.Settings.FightingStyle["Auto God Human"] = L_331_arg0
		BuyGodhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman", true))
		if BuyGodhuman then
			if BuyGodhuman ~= 1 then
				GetAllMeleeFarm()
			end
		end
		SaveSettings()
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.FightingStyle["Auto God Human"] then
						BuyGodhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman", true))
						if BuyGodhuman then
							if BuyGodhuman == 1 then
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman")
								_G.Settings.FightingStyle["Auto God Human"] = false
							end
						end
						if not HasTalon then
							BuyDragonTalon = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true))

							if BuyDragonTalon then
								if BuyDragonTalon == 1 then
									HasTalon = true
								end
							end
						end
						if not HasSuperhuman then
							BuySuperhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman", true))

							if BuySuperhuman then
								if BuySuperhuman == 1 then
									HasSuperhuman = true
								end
							end
						end
						if not HasKarate then
							BuySharkmanKarate = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true))

							if BuySharkmanKarate then
								if BuySharkmanKarate == 1 then
									HasKarate = true
								end
							end
						end
						if not HasDeathStep then
							BuyDeathStep = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep", true))

							if BuyDeathStep then
								if BuyDeathStep == 1 then
									HasDeathStep = true
								end
							end
						end
						if not HasElectricClaw then
							BuyElectricClaw = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", true))
							if BuyElectricClaw then
								if BuyElectricClaw == 1 then
									HasElectricClaw = true
								end
							end
						end

						if not HasSuperhuman then
							if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
								if not game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") and not game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
									if not game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and not game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") then
										if not game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and not game.Players.LocalPlayer.Character:FindFirstChild("Electro") then
											if not game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and not game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") then
												if not game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and not game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") then
													if not game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") and not game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") then
														local L_332_ = {
															[1] = "BuyElectro"
														}
														game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_332_))
													end
												end
											end
										end
									end
								end
								_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")

								if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
									local L_333_ = {
										[1] = "BuyElectro"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_333_))
								end
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 then
									local L_334_ = {
										[1] = "BuyBlackLeg"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_334_))
								end
								if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 then
									local L_335_ = {
										[1] = "BuyBlackLeg"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_335_))
								end
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 then
									local L_336_ = {
										[1] = "BuyFishmanKarate"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_336_))
								end
								if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 then
									local L_337_ = {
										[1] = "BuyFishmanKarate"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_337_))
								end
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 then
									local L_338_ = {
										[1] = "BlackbeardReward",
										[2] = "DragonClaw",
										[3] = "2"
									}
									HaveDragonClaw = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_338_))
									if _G.Settings.FightingStyle["Auto God Human"] and game.Players.LocalPlayer.Data.Fragments.Value <= 1500 and HaveDragonClaw == 0 then
										if game.Players.LocalPlayer.Data.Level.Value > 1100 then
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = false
											end
										end
									else
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_339_ = {
											[1] = "BlackbeardReward",
											[2] = "DragonClaw",
											[3] = "2"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_339_))
									end
								end
								if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 then
									local L_340_ = {
										[1] = "BlackbeardReward",
										[2] = "DragonClaw",
										[3] = "2"
									}
									HaveDragonClaw = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_340_))
									if _G.Settings.FightingStyle["Auto God Human"] and game.Players.LocalPlayer.Data.Fragments.Value <= 1500 and HaveDragonClaw == 0 then
										if game.Players.LocalPlayer.Data.Level.Value > 1100 then
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = false
											end
										end
									else
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_341_ = {
											[1] = "BlackbeardReward",
											[2] = "DragonClaw",
											[3] = "2"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_341_))
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
									end
								end

								if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 then
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
									local L_342_ = {
										[1] = "BuySuperhuman"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_342_))
								end
								if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 then
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = true
									end
									local L_343_ = {
										[1] = "BuySuperhuman"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_343_))
								end 
							end
						elseif not HasKarate then
							if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
								if not game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and not game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") then
									if not game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") and not game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate") then
										local L_344_ = {
											[1] = "BuyFishmanKarate"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_344_))
									end
								end

								if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 400 then
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks." and not game.Players.LocalPlayer.Character:FindFirstChild("Water Key") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key") then
										if World2 then
											KillSharkMan = true
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = false
											end
										else
											KillSharkMan = false
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = true
											end
										end
									elseif tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true)) == 1 then
										KillSharkMan = false
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_345_ = {
											[1] = "BuySharkmanKarate"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_345_))
									elseif game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key") then
										KillSharkMan = false
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_346_ = {
											[1] = "BuySharkmanKarate"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_346_))
									end
								end

								if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 400 then
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks." and not game.Players.LocalPlayer.Character:FindFirstChild("Water Key") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key") then
										if World2 then
											KillSharkMan = true
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = false
											end
										else
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = true
											end
											KillSharkMan = false
										end
									elseif tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true)) == 1 then
										KillSharkMan = false
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_347_ = {
											[1] = "BuySharkmanKarate"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_347_))
									elseif game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key") then
										KillSharkMan = false
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = true
										end
										local L_348_ = {
											[1] = "BuySharkmanKarate"
										}
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_348_))
									end
								end
								_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")
							end
						elseif not HasDeathStep then
							if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 400 then
									local L_349_ = {
										[1] = "BuyDeathStep"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_349_))

								end  
								if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 400 then
									local L_350_ = {
										[1] = "BuyDeathStep"
									}
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_350_))

								end  
								_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")
							end
						elseif not HasTalon then
							if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
								_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")

								if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 400 and game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 then
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 3 then
										local L_351_ = "Bones";
										local L_352_ = "Buy";
										local L_353_ = 1;
										local L_354_ = 1;
										local L_355_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_355_:InvokeServer(L_351_, L_352_, L_353_, L_354_);

										local L_356_ = "BuyDragonTalon";
										local L_357_ = true;
										local L_358_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_358_:InvokeServer(L_356_, L_357_);
									elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 1 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
									else
										local L_359_ = "Bones";
										local L_360_ = "Buy";
										local L_361_ = 1;
										local L_362_ = 1;
										local L_363_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_363_:InvokeServer(L_359_, L_360_, L_361_, L_362_);
									end 
								end

								if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 400 and game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health > 0 then
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 3 then
										local L_364_ = "Bones";
										local L_365_ = "Buy";
										local L_366_ = 1;
										local L_367_ = 1;
										local L_368_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_368_:InvokeServer(L_364_, L_365_, L_366_, L_367_);

										local L_369_ = "BuyDragonTalon";
										local L_370_ = true;
										local L_371_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_371_:InvokeServer(L_369_, L_370_);
									elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 1 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
									else
										local L_372_ = "Bones";
										local L_373_ = "Buy";
										local L_374_ = 1;
										local L_375_ = 1;
										local L_376_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_376_:InvokeServer(L_372_, L_373_, L_374_, L_375_);
									end 
								end
							end
						elseif not HasElectricClaw then
							if game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
								_G.Settings.Configs["Select Weapon"] = GetFightingStyle("Melee")
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
									local L_377_ = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", true);
									if L_377_ == 4 then
										local L_378_ = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", "Start");
										if L_378_ == nil then
											game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(- 12548, 337, - 7481)
										end
									else
										local L_379_ = "BuyElectricClaw";
										local L_380_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_380_:InvokeServer(L_379_);
									end
								end

								if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
									local L_381_ = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", true);
									if L_381_ == 4 then
										local L_382_ = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", "Start");
										if L_382_ == nil then
											game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(- 12548, 337, - 7481)
										end
									else
										local L_383_ = "BuyElectricClaw";
										local L_384_ = game:GetService("ReplicatedStorage").Remotes["CommF_"];
										L_384_:InvokeServer(L_383_);
									end
								end
							end
						end
						if BuyGodhuman ~= 1 and HasSuperhuman and HasTalon and HasKarate and HasDeathStep and HasElectricClaw then
							if HasSuperhuman and not SupComplete then
								local L_385_ = {
									[1] = "BuySuperhuman"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_385_))
								wait(0.2)
								if CheckMasteryWeapon("Superhuman", 400) == "true UpTo" or CheckMasteryWeapon("Superhuman", 400) == "true" and SupComplete == false then
									SupComplete = true
								end
							elseif HasTalon and not TalComplete then
								local L_386_ = {
									[1] = "BuyDragonTalon"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_386_))
								wait(0.2)
								if CheckMasteryWeapon("Dragon Talon", 400) == "true UpTo" or CheckMasteryWeapon("Superhuman", 400) == "true" and TalComplete == false then
									TalComplete = true
								end
							elseif HasKarate and not SharkComplete then
								local L_387_ = {
									[1] = "BuySharkmanKarate"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_387_))
								wait(0.2)
								if CheckMasteryWeapon("Sharkman Karate", 400) == "true UpTo" or CheckMasteryWeapon("Superhuman", 400) == "true" and SharkComplete == false then
									SharkComplete = true
								end
							elseif HasDeathStep and not DeathComplete then
								local L_388_ = {
									[1] = "BuyDeathStep"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_388_))
								wait(0.2)
								if CheckMasteryWeapon("Death Step", 400) == "true UpTo" or CheckMasteryWeapon("Superhuman", 400) == "true" and DeathComplete == false then
									DeathComplete = true
								end
							elseif HasElectricClaw and not EClawComplete then
								local L_389_ = {
									[1] = "BuyElectricClaw"
								}
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_389_))
								wait(0.2)
								if CheckMasteryWeapon("Electric Claw", 400) == "true UpTo" or CheckMasteryWeapon("Superhuman", 400) == "true" and EClawComplete == false then
									EClawComplete = true
								end
							end
						end

						if BuyGodhuman ~= 1 and SupComplete and EClawComplete and TalComplete and SharkComplete and DeathComplete and (not game.Players.LocalPlayer.Character:FindFirstChild("Godhuman") or not game.Players.LocalPlayer.Backpack:FindFirstChild("Godhuman")) then
							if GetMaterial("Fish Tail") >= 20 then
								if GetMaterial("Magma Ore") >= 20 then
									if GetMaterial("Dragon Scale") >= 10 then
										if GetMaterial("Mystic Droplet") >= 10 then
											Com("F_", "BuyGodhuman")
											BuyGodhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman", true))

											if BuyGodhuman then
												if BuyGodhuman == 1 then
													_G.Settings.FightingStyle["Auto God Human"] = false
												end
											end
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = true
											end
										elseif not World2 then
											Com("F_", "TravelDressrosa")
										elseif World2 then
											if Auto_Farm_Level then
												_G.Settings.Main["Auto Farm Level"] = false
											end
											L_11_func("Mystic Droplet")
											if L_7_func(MaterialMob) then
												for L_390_forvar0, L_391_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
													if _G.Settings.FightingStyle["Auto God Human"] and table.find(MaterialMob, L_391_forvar1.Name) and L_391_forvar1:FindFirstChild("HumanoidRootPart") and L_391_forvar1:FindFirstChild("Humanoid") and L_391_forvar1.Humanoid.Health > 0 then
														repeat
															wait()
															FarmtoTarget = L_3_func(L_391_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, 30, 1))
															if L_391_forvar1:FindFirstChild("HumanoidRootPart") and L_391_forvar1:FindFirstChild("Humanoid") and (L_391_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
																if FarmtoTarget then
																	FarmtoTarget:Stop()
																end
																EquipWeapon(_G.Settings.Configs["Select Weapon"])
																spawn(function()
																	for L_392_forvar0, L_393_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
																		if L_393_forvar1.Name == L_391_forvar1.Name then
																			spawn(function()
																				if InMyNetWork(L_393_forvar1.HumanoidRootPart) then
																					L_393_forvar1.HumanoidRootPart.CFrame = L_391_forvar1.HumanoidRootPart.CFrame
																					L_393_forvar1.Humanoid.JumpPower = 0
																					L_393_forvar1.Humanoid.WalkSpeed = 0
																					L_393_forvar1.HumanoidRootPart.CanCollide = false
																					L_393_forvar1.Humanoid:ChangeState(11)
																					L_393_forvar1.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
																				end
																			end)
																		end
																	end
																end)
																if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
																	game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
																	game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
																end
																L_3_func(L_391_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
															end
														until not L_7_func(MaterialMob) or not _G.Settings.FightingStyle["Auto God Human"] or L_391_forvar1.Humanoid.Health <= 0 or not L_391_forvar1.Parent
													end
												end
											else
												Modstween = L_3_func(CFrameMon.Position, CFrameMon)
												if World1 and (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
													if Modstween then
														Modstween:Stop()
													end
													wait(.5)
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
												elseif World1 and not (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
													if Modstween then
														Modstween:Stop()
													end
													wait(.5)
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
												elseif World1 and (table.find(MaterialMob, "God's Guard [Lv. 450]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 3000 then
													if Modstween then
														Modstween:Stop()
													end
													wait(.5)
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
												elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
													if Modstween then
														Modstween:Stop()
													end
													game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMon
												end 
											end
										end
									elseif not World3 then
										Com("F_", "TravelZou")
									elseif World3 then
										if Auto_Farm_Level then
											_G.Settings.Main["Auto Farm Level"] = false
										end
										L_11_func("Dragon Scale")
										if L_7_func(MaterialMob) then
											for L_394_forvar0, L_395_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
												if _G.Settings.FightingStyle["Auto God Human"] and table.find(MaterialMob, L_395_forvar1.Name) and L_395_forvar1:FindFirstChild("HumanoidRootPart") and L_395_forvar1:FindFirstChild("Humanoid") and L_395_forvar1.Humanoid.Health > 0 then
													repeat
														wait()
														FarmtoTarget = L_3_func(L_395_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
														if L_395_forvar1:FindFirstChild("HumanoidRootPart") and L_395_forvar1:FindFirstChild("Humanoid") and (L_395_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
															if FarmtoTarget then
																FarmtoTarget:Stop()
															end
															EquipWeapon(_G.Settings.Configs["Select Weapon"])
															spawn(function()
																for L_396_forvar0, L_397_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
																	if L_397_forvar1.Name == L_395_forvar1.Name then
																		spawn(function()
																			if InMyNetWork(L_397_forvar1.HumanoidRootPart) then
																				L_397_forvar1.HumanoidRootPart.CFrame = L_395_forvar1.HumanoidRootPart.CFrame
																				L_397_forvar1.Humanoid.JumpPower = 0
																				L_397_forvar1.Humanoid.WalkSpeed = 0
																				L_397_forvar1.HumanoidRootPart.CanCollide = false
																				L_397_forvar1.Humanoid:ChangeState(11)
																				L_397_forvar1.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
																			end
																		end)
																	end
																end
															end)
															if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
																game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
																game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
															end
															L_3_func(L_395_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
														end
													until not L_7_func(MaterialMob) or not _G.Settings.FightingStyle["Auto God Human"] or L_395_forvar1.Humanoid.Health <= 0 or not L_395_forvar1.Parent
												end
											end
										else
											Modstween = L_3_func(CFrameMon.Position, CFrameMon)
											if World1 and (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
												if Modstween then
													Modstween:Stop()
												end
												wait(.5)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
											elseif World1 and not (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
												if Modstween then
													Modstween:Stop()
												end
												wait(.5)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
											elseif World1 and (table.find(MaterialMob, "God's Guard [Lv. 450]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 3000 then
												if Modstween then
													Modstween:Stop()
												end
												wait(.5)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
											elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
												if Modstween then
													Modstween:Stop()
												end
												game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMon
											end 
										end
									end
								elseif not World1 then
									Com("F_", "TravelMain")
								elseif World1 then
									if Auto_Farm_Level then
										_G.Settings.Main["Auto Farm Level"] = false
									end
									L_11_func("Magma Ore")
									if L_7_func(MaterialMob) then
										for L_398_forvar0, L_399_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
											if _G.Settings.FightingStyle["Auto God Human"] and table.find(MaterialMob, L_399_forvar1.Name) and L_399_forvar1:FindFirstChild("HumanoidRootPart") and L_399_forvar1:FindFirstChild("Humanoid") and L_399_forvar1.Humanoid.Health > 0 then
												repeat
													wait()
													FarmtoTarget = L_3_func(L_399_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
													if L_399_forvar1:FindFirstChild("HumanoidRootPart") and L_399_forvar1:FindFirstChild("Humanoid") and (L_399_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
														if FarmtoTarget then
															FarmtoTarget:Stop()
														end
														EquipWeapon(_G.Settings.Configs["Select Weapon"])
														spawn(function()
															for L_400_forvar0, L_401_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
																if L_401_forvar1.Name == L_399_forvar1.Name then
																	spawn(function()
																		if InMyNetWork(L_401_forvar1.HumanoidRootPart) then
																			L_401_forvar1.HumanoidRootPart.CFrame = L_399_forvar1.HumanoidRootPart.CFrame
																			L_401_forvar1.Humanoid.JumpPower = 0
																			L_401_forvar1.Humanoid.WalkSpeed = 0
																			L_401_forvar1.HumanoidRootPart.CanCollide = false
																			L_401_forvar1.Humanoid:ChangeState(11)
																			L_401_forvar1.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
																		end
																	end)
																end
															end
														end)
														if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
															game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
															game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
														end
														L_3_func(L_399_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
													end
												until not L_7_func(MaterialMob) or not _G.Settings.FightingStyle["Auto God Human"] or L_399_forvar1.Humanoid.Health <= 0 or not L_399_forvar1.Parent
											end
										end
									else
										Modstween = L_3_func(CFrameMon.Position, CFrameMon)
										if World1 and (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
											if Modstween then
												Modstween:Stop()
											end
											wait(.5)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
										elseif World1 and not (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
											if Modstween then
												Modstween:Stop()
											end
											wait(.5)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
										elseif World1 and (table.find(MaterialMob, "God's Guard [Lv. 450]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 3000 then
											if Modstween then
												Modstween:Stop()
											end
											wait(.5)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
										elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
											if Modstween then
												Modstween:Stop()
											end
											game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMon
										end 
									end
								end
							elseif not World1 then
								Com("F_", "TravelMain")
							elseif World1 then
								if Auto_Farm_Level then
									_G.Settings.Main["Auto Farm Level"] = false
								end
								L_11_func("Fish Tail")
								if L_7_func(MaterialMob) then
									for L_402_forvar0, L_403_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
										if _G.Settings.FightingStyle["Auto God Human"] and table.find(MaterialMob, L_403_forvar1.Name) and L_403_forvar1:FindFirstChild("HumanoidRootPart") and L_403_forvar1:FindFirstChild("Humanoid") and L_403_forvar1.Humanoid.Health > 0 then
											repeat
												wait()
												FarmtoTarget = L_3_func(L_403_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
												if L_403_forvar1:FindFirstChild("HumanoidRootPart") and L_403_forvar1:FindFirstChild("Humanoid") and (L_403_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
													if FarmtoTarget then
														FarmtoTarget:Stop()
													end
													EquipWeapon(_G.Settings.Configs["Select Weapon"])
													spawn(function()
														for L_404_forvar0, L_405_forvar1 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
															if L_405_forvar1.Name == L_403_forvar1.Name then
																spawn(function()
																	if InMyNetWork(L_405_forvar1.HumanoidRootPart) then
																		L_405_forvar1.HumanoidRootPart.CFrame = L_403_forvar1.HumanoidRootPart.CFrame
																		L_405_forvar1.Humanoid.JumpPower = 0
																		L_405_forvar1.Humanoid.WalkSpeed = 0
																		L_405_forvar1.HumanoidRootPart.CanCollide = false
																		L_405_forvar1.Humanoid:ChangeState(11)
																		L_405_forvar1.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
																	end
																end)
															end
														end
													end)
													if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
														game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
														game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
													end
													L_3_func(L_403_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
												end
											until not L_7_func(MaterialMob) or not _G.Settings.FightingStyle["Auto God Human"] or L_403_forvar1.Humanoid.Health <= 0 or not L_403_forvar1.Parent
										end
									end
								else
									Modstween = L_3_func(CFrameMon.Position, CFrameMon)
									if World1 and (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
										if Modstween then
											Modstween:Stop()
										end
										wait(.5)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
									elseif World1 and not (table.find(MaterialMob, "Fishman Commando [Lv. 400]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 50000 then
										if Modstween then
											Modstween:Stop()
										end
										wait(.5)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(3864.8515625, 6.6796875, - 1926.7841796875))
									elseif World1 and (table.find(MaterialMob, "God's Guard [Lv. 450]")) and (CFrameMon.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).magnitude > 3000 then
										if Modstween then
											Modstween:Stop()
										end
										wait(.5)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(- 4607.8227539063, 872.54248046875, - 1667.5568847656))
									elseif (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 150 then
										if Modstween then
											Modstween:Stop()
										end
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameMon
									end 
								end
							end
						end
					end
				end)
			end
		end)
	end
)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Settings.FightingStyle["Auto God Human"] and World2 then
				if game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") or game.ReplicatedStorage:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
					if (KillSharkMan == true and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks.") then
						if KillFish then
							KillFish:Stop()
						end
						Com("F_", "SetspawnPoint")
						for L_406_forvar0, L_407_forvar1 in pairs(game.Workspace.Enemies:GetChildren()) do 
							if L_407_forvar1.Name == "Tide Keeper [Lv. 1475] [Boss]" then
								repeat
									wait()
									if game.Workspace.Enemies:FindFirstChild(L_407_forvar1.Name) then
										if (L_407_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 200 then
											Farmtween = L_3_func(L_407_forvar1.HumanoidRootPart.CFrame)
										elseif (L_407_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 200 then
											if Farmtween then
												Farmtween:Stop()
											end
											if _G.Settings.Configs["Auto Haki"] then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
												wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											L_407_forvar1.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
											if _G.Settings.Configs["Show Hitbox"] then
												L_407_forvar1.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												L_407_forvar1.HumanoidRootPart.Transparency = 1
											end
											L_407_forvar1.Humanoid.JumpPower = 0
											L_407_forvar1.Humanoid.WalkSpeed = 0
											L_407_forvar1.HumanoidRootPart.CanCollide = false
											L_407_forvar1.Humanoid:ChangeState(11)
											L_3_func(L_407_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
											if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
												game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
												game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
											end
										end
									end
								until not L_407_forvar1.Parent or not _G.Settings.FightingStyle["Auto God Human"] or KillSharkMan == false or L_407_forvar1.Humanoid.Health == 0 or game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key")
							end
						end
					end
				else
					if game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
						KillFish = L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]").HumanoidRootPart.CFrame)
					else
						if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks." then
							ServerHop:Teleport()
						end
					end
				end
			end
		end)
	end
end)

spawn(function()
	while wait() do
		pcall(function()
			if _G.Settings.FightingStyle["Auto God Human"] and World2 then
				if game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") or game.ReplicatedStorage:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
					if (KillSharkMan == true and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks.") then
						if KillFish then
							KillFish:Stop()
						end
						Com("F_", "SetspawnPoint")
						for L_408_forvar0, L_409_forvar1 in pairs(game.Workspace.Enemies:GetChildren()) do 
							if L_409_forvar1.Name == "Tide Keeper [Lv. 1475] [Boss]" then
								repeat
									wait()
									if game.Workspace.Enemies:FindFirstChild(L_409_forvar1.Name) then
										if (L_409_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 200 then
											Farmtween = L_3_func(L_409_forvar1.HumanoidRootPart.CFrame)
										elseif (L_409_forvar1.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 200 then
											if Farmtween then
												Farmtween:Stop()
											end
											if _G.Settings.Configs["Auto Haki"] then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
												wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											L_409_forvar1.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
											if _G.Settings.Configs["Show Hitbox"] then
												L_409_forvar1.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												L_409_forvar1.HumanoidRootPart.Transparency = 1
											end
											L_409_forvar1.Humanoid.JumpPower = 0
											L_409_forvar1.Humanoid.WalkSpeed = 0
											L_409_forvar1.HumanoidRootPart.CanCollide = false
											L_409_forvar1.Humanoid:ChangeState(11)
											L_3_func(L_409_forvar1.HumanoidRootPart.CFrame * CFrame.new(0, _G.Settings.Configs["Distance Auto Farm"], 0))
											if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
												game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
												game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
											end
										end
									end
								until not L_409_forvar1.Parent or not _G.Settings.FightingStyle["Auto God Human"] or KillSharkMan == false or L_409_forvar1.Humanoid.Health == 0 or game.Players.LocalPlayer.Character:FindFirstChild("Water Key") or game.Players.LocalPlayer.Backpack:FindFirstChild("Water Key")
							end
						end
					end
				else
					if game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
						KillFish = L_3_func(game:GetService("ReplicatedStorage"):FindFirstChild("Tide Keeper [Lv. 1475] [Boss]").HumanoidRootPart.CFrame)
					else
						if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == "I lost my house keys, could you help me find them? Thanks." then
							ServerHop:Teleport()
						end
					end
				end
			end
		end)
	end
end)

L_15_:Label("Fully")

L_15_:Toggle("Auto Fully Death Step",_G.Settings.FightingStyle["Auto Fully Death Step"],function(L_410_arg0)
		_G.Settings.FightingStyle["Auto Fully Death Step"] = L_410_arg0
		SaveSettings()
	end
)

L_15_:Toggle("Auto Fully SharkMan Karate",_G.Settings.FightingStyle["Auto Fully SharkMan Karate"],function(L_411_arg0)
		_G.Settings.FightingStyle["Auto Fully SharkMan Karate"] = L_411_arg0
		SaveSettings()
	end
)

_G.SelectPoint = 1
PointStats = 1
--L_16_
L_17_:Label("Auto Stats Kaitan")
L_17_:Toggle("Auto Stats Kaitan",_G.Settings.Stat["Auto Stats Kaitun"],function(a)
	_G.Settings.Stat["Auto Stats Kaitun"] = a
	SaveSettings()
end)

L_17_:Toggle("Auto MaxPoint Stats Kaitun",_G.Settings.Stat["MaxPoint Stats Kaitun"],function(value)
	_G.Settings.Stat["MaxPoint Stats Kaitun"] = value
	SaveSettings()
end)
L_17_:Label("Auto Stats Normal Mode")
L_17_:Toggle("Auto Stats [Select Mode]",_G.Settings.Stat["Enabled Auto Stats"],function(a)
	_G.Settings.Stat["Enabled Auto Stats"] = a
	SaveSettings()
end)

L_17_:Dropdown("Select Stats",{"Melee","Defense","Sword","Gun","Devil Fruits"},"Melee",function(L_413_arg0)
	_G.Settings.Stat["Select Stats"] = L_413_arg0
	spawn(function()
		pcall(function()
			while task.wait(1) do
                if _G.Settings.Stat["MaxPoint Stats"] then
                    _G.SelectPoint = game:GetService("Players").LocalPlayer.Data.Points.Value
                end
				if _G.Settings.Stat["Enabled Auto Stats"] then
					if _G.Settings.Stat["Select Stats"] == "Melee" then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",_G.SelectPoint)
					elseif _G.Settings.Stat["Select Stats"] == "Defense" then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",_G.SelectPoint)
					elseif _G.Settings.Stat["Select Stats"] == "Sword" then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",_G.SelectPoint)
					elseif _G.Settings.Stat["Select Stats"] == "Gun" then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",_G.SelectPoint)
					elseif _G.Settings.Stat["Select Stats"] == "Devil Fruits" then
                        local args = {
                            [1] = "AddPoint",
                            [2] = "Demon Fruit",
                            [3] = _G.SelectPoint
                        }
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					else
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",_G.SelectPoint)
					end
				end
			end
		end)
	end)
end)

L_17_:Toggle("MaxPoint Stats",_G.Settings.Stat["MaxPoint Stats"],function(value)
	_G.Settings.Stat["MaxPoint Stats"] = value
	SaveSettings()
end)

-- [Stats Kaitan]
spawn(function()
	while task.wait(1) do
		if _G.Settings.Stat["Auto Stats Kaitun"] then
            if _G.Settings.Stat["MaxPoint Stats Kaitun"] then
                PointStats = game:GetService("Players").LocalPlayer.Data.Points.Value
            end
			if game:GetService("Players").LocalPlayer.Data.Stats.Melee.Level.Value < 2450 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",PointStats)
			elseif game:GetService("Players").LocalPlayer.Data.Stats.Defense.Level.Value < 2450 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",PointStats)
			end
		end
	end
end)


if World1 then

	L_18_:Label("Status : World 1")

	L_18_:Button("Teleport to World 2",function()
	        local args = {
                [1] = "TravelDressrosa" -- NEW WORLD to OLD WORLD
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
		end
	)
	L_18_:Button("Teleport to World 3",function()
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
		end
	)

elseif World2 then

	L_18_:Label("Status : World 2")

	L_18_:Button("Teleport to World 1",function()
			local args = {
                [1] = "TravelMain" -- OLD WORLD to NEW WORLD
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelMain")
		end
	)
	L_18_:Button("Teleport to World 3",function()
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
		end
	)

elseif World3 then

	L_18_:Label("Status : World 3"
	)

	L_18_:Button("Teleport to World 1",function()
			local args = {
                [1] = "TravelMain" -- OLD WORLD to NEW WORLD
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelMain")
		end
	)
	L_18_:Button("Teleport to World 2",function()
	        local args = {
                [1] = "TravelDressrosa" -- NEW WORLD to OLD WORLD
            }
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
		end
	)
end

L_18_:Label("Teleport To Island")

TeleportTable = {}

if World1 then
	TeleportTable = {
		"Jones Salad",
		"Marine1",
		"Marine2",
		"Midle Town",
		"Jungle",
		"Pirate Village",
		"Desert",
		"Frozen Village",
		"Colosseum",
		"Prison",
		"Mob Leader",
		"Magma Village",
		"UnderWater Gate",
		"UnderWater City",
		"Fountain City",
		"Sky1",
		"Sky2",
		"Sky3"
	}
elseif World2 then
	TeleportTable = {
		"Dock",
		"Mansion",
		"Kingdom Of Rose",
		"Cafe",
		"Sunflower Field",
		"Jeramy Mountain",
		"Colossuem",
		"Factory",
		"The Bridge",
		"Green Bit",
		"Graveyard",
		"Dark Area",
		"Snow Mountain",
		"Hot Island",
		"Cold Island",
		"Ice Castle",
		"Usopp's Island",
		"inscription Island",
		"Forgotten Island",
		"Ghost Ship"
	}
elseif World3 then
	TeleportTable = {
		"Port Town",
		"Hydra Island",
		"Gaint Tree",
		"Mansion",
		"Castle on the Sea",
		"Graveyard Island",
		"Icecream Island",
		"Peanut Island",
		"Lab",
		"Cake Loaf"
	}
end

L_18_:Dropdown("Select Place",TeleportTable,"",function(L_421_arg0)
		_G.SelectLocalTeleport = L_421_arg0
end)

function ByPass(Position)
game.Players.LocalPlayer.Character.Head:Destroy()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position 
wait(.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position
wait(.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5555,5555,5555)
end

  spawn(function()
	game:GetService("RunService").Stepped:Connect(function()
		if getgenv().XX then
			if not game:GetService("Workspace"):FindFirstChild("PartPart") then
				local PartPart = Instance.new("Part")
				PartPart.Name = "PartPart"
				PartPart.Parent = game.Workspace
				PartPart.Anchored = true
				PartPart.Transparency = 0.8
				PartPart.Size = Vector3.new(50,0.5,50)
			elseif game:GetService("Workspace"):FindFirstChild("PartPart") then
				game.Workspace["PartPart"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.8,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)
			end
		end
		--[[for _, v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if v:IsA("BasePart") then
				v.CanCollide = false
			end
		end]]
	end)
end)

function DP(Pos)
    Distance = (Pos.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
if DP then
    if Distance < 45 then
        Speed = 250.000
	elseif Distance < 379 then
        Speed = 299.99
	elseif Distance < 383 then
        Speed = 380.00
	elseif Distance < 400 then
        Speed = 375.95
	elseif Distance < 500 then
        Speed = 370.99
    elseif Distance >= 850 then
        Speed = 365.00
    else
        if Distance < 80 then
        Speed = 250.00 --100
    elseif Distance < 200 then
        Speed = 500.00 --100
    elseif Distance < 450 then
        Speed = 379.50 --385
    elseif Distance < 750 then
        Speed = 380.00 --385
    elseif Distance >= 850 then
        Speed =  379.00 --378.5--379
    elseif Distance > 100 then
        Speed = 380.00 --100
    elseif Distance < 200 then
        Speed = 800.00 --100
    elseif Distance < 300 then
        Speed = 800.00 --385
    elseif Distance < 500 then
        Speed = 800.00 --385
    elseif Distance >= 800 then
        Speed =  800.00 --378.5--379
    end
end
end
    game:GetService("TweenService"):Create(
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = Pos}
    ):Play()
    getgenv().XX = true
    wait(Distance/Speed)
    getgenv().XX = false
end
L_18_:Button("Teleport Select",function(L_422_arg0)
    
		if World1 then
			if _G.SelectLocalTeleport == "Jones Salad" then
				gg=DP(CFrame.new(1042.1501464844, 16.299360275269, 1444.3442382813))
			end

			if _G.SelectLocalTeleport == "Marine1" then
				gg=DP(CFrame.new(- 2599.6655273438, 6.9146227836609, 2062.2216796875))
			end

			if _G.SelectLocalTeleport == "Marine2" then
				gg=DP(CFrame.new(- 5081.3452148438, 85.221641540527, 4257.3588867188))
			end

			if _G.SelectLocalTeleport == "Midle Town" then
				gg=DP(CFrame.new(- 655.97088623047, 7.878026008606, 1573.7612304688))
			end

			if _G.SelectLocalTeleport == "Jungle" then
				gg=DP(CFrame.new(- 1499.9877929688, 22.877912521362, 353.87060546875))
			end

			if _G.SelectLocalTeleport == "Pirate Village" then
				gg=DP(CFrame.new(- 1163.3889160156, 44.777843475342, 3842.8276367188))
			end

			if _G.SelectLocalTeleport == "Desert" then
				gg=DP(CFrame.new(954.02056884766, 6.6275520324707, 4262.611328125))
			end

			if _G.SelectLocalTeleport == "Frozen Village" then
				gg=DP(CFrame.new(1144.5270996094, 7.3292083740234, - 1164.7322998047))
			end

			if _G.SelectLocalTeleport == "Colosseum" then
				gg=DP(CFrame.new(- 1667.5869140625, 39.385631561279, - 3135.5817871094))
			end

			if _G.SelectLocalTeleport == "Prison" then
				gg=DP(CFrame.new(4857.6982421875, 5.6780304908752, 732.75750732422))
			end

			if _G.SelectLocalTeleport == "Mob Leader" then
				gg=DP(CFrame.new(- 2841.9604492188, 7.3560485839844, 5318.1040039063))
			end

			if _G.SelectLocalTeleport == "Magma Village" then
				gg=DP(CFrame.new(- 5328.8740234375, 8.6164798736572, 8427.3994140625))
			end

			if _G.SelectLocalTeleport == "UnderWater Gate" then
				gg=DP(CFrame.new(3893.953125, 5.3989524841309, - 1893.4851074219))
			end

			if _G.SelectLocalTeleport == "UnderWater City" then
				gg=DP(CFrame.new(61191.12109375, 18.497436523438, 1561.8873291016))
			end

			if _G.SelectLocalTeleport == "Fountain City" then
				gg=DP(CFrame.new(5244.7133789063, 38.526943206787, 4073.4987792969))
			end

			if _G.SelectLocalTeleport == "Sky1" then
				gg=DP(CFrame.new(- 4878.0415039063, 717.71246337891, - 2637.7294921875))
			end

			if _G.SelectLocalTeleport == "Sky2" then
				gg=DP(CFrame.new(- 7899.6157226563, 5545.6030273438, - 422.21798706055))
			end

			if _G.SelectLocalTeleport == "Sky3" then
				gg=DP(CFrame.new(- 7868.5288085938, 5638.205078125, - 1482.5548095703))
			end
		elseif World2 then
			if _G.SelectLocalTeleport == "Dock" then
				gg=DP(CFrame.new(- 12.519311904907, 19.302536010742, 2827.853515625))
			end

			if _G.SelectLocalTeleport == "Mansion" then
				gg=DP(CFrame.new(- 390.34829711914, 321.89730834961, 869.00506591797))
			end

			if _G.SelectLocalTeleport == "Kingdom Of Rose" then
				ByPass(CFrame.new(- 388.29895019531, 138.35575866699, 1132.1662597656))
				wait(.5)
				gg=DP(CFrame.new(- 388.29895019531, 138.35575866699, 1132.1662597656))
			end

			if _G.SelectLocalTeleport == "Cafe" then
				gg=DP(CFrame.new(- 379.70889282227, 73.0458984375, 304.84692382813))
			end

			if _G.SelectLocalTeleport == "Sunflower Field" then
				gg=DP(CFrame.new(- 1576.7171630859, 198.61849975586, 13.725157737732))
			end

			if _G.SelectLocalTeleport == "Jeramy Mountain" then
				gg=DP(CFrame.new(1986.3519287109, 448.95678710938, 796.70239257813))
			end

			if _G.SelectLocalTeleport == "Colossuem" then
				gg=DP(CFrame.new(- 1871.8974609375, 45.820514678955, 1359.6843261719))
			end

			if _G.SelectLocalTeleport == "Factory" then
				gg=DP(CFrame.new(349.53750610352, 74.446998596191, - 355.62420654297))
			end

			if _G.SelectLocalTeleport == "The Bridge" then
				gg=DP(CFrame.new(- 1860.6354980469, 88.384948730469, - 1859.1593017578))
			end

			if _G.SelectLocalTeleport == "Green Bit" then
				gg=DP(CFrame.new(- 2202.3706054688, 73.097663879395, - 2819.2687988281))
			end

			if _G.SelectLocalTeleport == "Graveyard" then
				gg=DP(CFrame.new(- 5617.5927734375, 492.22183227539, - 778.3017578125))
			end

			if _G.SelectLocalTeleport == "Dark Area" then
				gg=DP(CFrame.new(3464.7700195313, 13.375151634216, - 3368.90234375))
			end

			if _G.SelectLocalTeleport == "Snow Mountain" then
				gg=DP(CFrame.new(561.23834228516, 401.44781494141, - 5297.14453125))
			end

			if _G.SelectLocalTeleport == "Hot Island" then
				gg=DP(CFrame.new(- 5505.9633789063, 15.977565765381, - 5366.6123046875))
			end

			if _G.SelectLocalTeleport == "Cold Island" then
				gg=DP(CFrame.new(- 5924.716796875, 15.977565765381, - 4996.427734375))
			end

			if _G.SelectLocalTeleport == "Ice Castle" then
				gg=DP(CFrame.new(6111.7109375, 294.41259765625, - 6716.4829101563))
			end

			if _G.SelectLocalTeleport == "Usopp's Island" then
				gg=DP(CFrame.new(4760.4985351563, 8.3444719314575, 2849.2426757813))
			end

			if _G.SelectLocalTeleport == "inscription Island" then
				gg=DP(CFrame.new(- 5099.01171875, 98.241539001465, 2424.4035644531))
			end

			if _G.SelectLocalTeleport == "Forgotten Island" then
				gg=DP(CFrame.new(- 3051.9514160156, 238.87203979492, - 10250.807617188))
			end

			if _G.SelectLocalTeleport == "Ghost Ship" then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance", Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
			end
		elseif World3 then
			if _G.SelectLocalTeleport == "Port Town" then
				ByPass(CFrame.new(- 275.21615600586, 43.755737304688, 5451.0659179688))
				wait(.5)
				gg=DP(CFrame.new(- 275.21615600586, 43.755737304688, 5451.0659179688))
			end

			if _G.SelectLocalTeleport == "Hydra Island" then
				gg=DP(CFrame.new(5541.2685546875, 668.30456542969, 195.48069763184))
			end

			if _G.SelectLocalTeleport == "Gaint Tree" then
				gg=DP(CFrame.new(2276.0859375, 25.87850189209, - 6493.03125))
			end

			if _G.SelectLocalTeleport == "Mansion" then
				local L_423_ = {
					[1] = "requestEntrance",
					[2] = Vector3.new(- 12548.595703125, 337.17001342773, - 7554.6103515625)
				}

				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_423_))
			end

			if _G.SelectLocalTeleport == "Castle on the Sea" then
				local L_424_ = {
					[1] = "requestEntrance",
					[2] = Vector3.new(- 5079.44677734375, 313.7293395996094, - 3151.065185546875)
				}

				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_424_))
			end

			if _G.SelectLocalTeleport == "Graveyard Island" then
				gg=DP(CFrame.new(- 9515.07324, 142.130615, 5537.58398))
			end

			if _G.SelectLocalTeleport == "Icecream Island" then
				gg=DP(CFrame.new(- 880.894531, 118.245354, - 11030.7607, - 0.867174983, 1.48501234e-09, 0.498003572, 2.70457789e-08, 1, 4.41129586e-08, - 0.498003572, 5.1722548e-08, - 0.867174983))
			end

			if _G.SelectLocalTeleport == "Peanut Island" then
				gg=DP(CFrame.new(- 2124.06738, 44.0723495, - 10179.8281, - 0.623125494, - 2.55908191e-07, - 0.782121837, - 1.40530574e-07, 1, - 2.15235005e-07, 0.782121837, - 2.42063933e-08, - 0.623125494))
			end

			if _G.SelectLocalTeleport == "Lab" then
				gg=DP(CFrame.new(- 5057.146484375, 314.54132080078, - 2934.7995605469))
			end

			if _G.SelectLocalTeleport == "Cake Loaf" then
				gg=DP(CFrame.new(- 1977.36767578125, 251.509521484375, - 12380.4189453125))
			end
		end
        if (_G.SelectLocalTeleport.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 1 then  --250
            if gg then
                gg:Stop()
            end
        end
	end)

L_18_:Button("Stop Teleport",function(L_425_arg0)
		DP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
		--Stop()
    end
)

--  Esp Function 

function isnil(L_426_arg0)
	return (L_426_arg0 == nil)
end
local function L_52_func(L_427_arg0)
	return math.floor(tonumber(L_427_arg0) + 0.5)
end
Number = math.random(1, 1000000)
function UpdateEspPlayer()
	for L_428_forvar0, L_429_forvar1 in pairs(game:GetService'Players':GetChildren()) do
		pcall(function()
			if not isnil(L_429_forvar1.Character) then
				if ESPPlayer then
					if not isnil(L_429_forvar1.Character.Head) and not L_429_forvar1.Character.Head:FindFirstChild('NameEsp' .. Number) then
						local L_430_ = Instance.new('BillboardGui', L_429_forvar1.Character.Head)
						L_430_.Name = 'NameEsp' .. Number
						L_430_.ExtentsOffset = Vector3.new(0, 1, 0)
						L_430_.Size = UDim2.new(1, 200, 1, 30)
						L_430_.Adornee = L_429_forvar1.Character.Head
						L_430_.AlwaysOnTop = true
						local L_431_ = Instance.new('TextLabel', L_430_)
						L_431_.Font = "GothamBold"
						L_431_.FontSize = "Size14"
						L_431_.TextWrapped = true
						L_431_.Text = (L_429_forvar1.Name .. ' \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_429_forvar1.Character.Head.Position).Magnitude / 3) .. ' M')
						L_431_.Size = UDim2.new(1, 0, 1, 0)
						L_431_.TextYAlignment = 'Top'
						L_431_.BackgroundTransparency = 1
						L_431_.TextStrokeTransparency = 0.5
						if L_429_forvar1.Team == game:GetService("Teams").Pirates then
							L_431_.TextColor3 = Color3.new(255, 0, 0)
						else
							L_431_.TextColor3 = Color3.new(0, 255, 255)
						end
					else
						L_429_forvar1.Character.Head['NameEsp' .. Number].TextLabel.Text = (L_429_forvar1.Name .. ' | ' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_429_forvar1.Character.Head.Position).Magnitude / 3) .. ' M\nHealth : ' .. L_52_func(L_429_forvar1.Character.Humanoid.Health * 100 / L_429_forvar1.Character.Humanoid.MaxHealth) .. '%')
					end
				else
					if L_429_forvar1.Character.Head:FindFirstChild('NameEsp' .. Number) then
						L_429_forvar1.Character.Head:FindFirstChild('NameEsp' .. Number):Destroy()
					end
				end
			end
		end)
	end
end

function UpdateIslandESP()
	for L_432_forvar0, L_433_forvar1 in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do
		pcall(function()
			if IslandESP then
				if L_433_forvar1.Name ~= "Sea" then
					if not L_433_forvar1:FindFirstChild('NameEsp') then
						local L_434_ = Instance.new('BillboardGui', L_433_forvar1)
						L_434_.Name = 'NameEsp'
						L_434_.ExtentsOffset = Vector3.new(0, 1, 0)
						L_434_.Size = UDim2.new(1, 200, 1, 30)
						L_434_.Adornee = L_433_forvar1
						L_434_.AlwaysOnTop = true
						local L_435_ = Instance.new('TextLabel', L_434_)
						L_435_.Font = "Michroma" --"GothamBold"
						L_435_.FontSize = "Size14"
						L_435_.TextWrapped = true
						L_435_.Size = UDim2.new(1, 0, 1, 0)
						L_435_.TextYAlignment = 'Top'
						L_435_.BackgroundTransparency = 1
						L_435_.TextStrokeTransparency = 0.5
						L_435_.TextColor3 = Color3.fromRGB(80, 245, 245)
					else
						L_433_forvar1['NameEsp'].TextLabel.Text = (L_433_forvar1.Name .. '   \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_433_forvar1.Position).Magnitude / 3) .. ' M')
					end
				end
			else
				if L_433_forvar1:FindFirstChild('NameEsp') then
					L_433_forvar1:FindFirstChild('NameEsp'):Destroy()
				end
			end
		end)
	end
end

function UpdateChestEsp()
	for L_436_forvar0, L_437_forvar1 in pairs(game.Workspace:GetChildren()) do
		pcall(function()
			if L_437_forvar1.Name == "Chest1" or L_437_forvar1.Name == "Chest2" or L_437_forvar1.Name == "Chest3" then
				if ChestESP then
					if (L_437_forvar1.Name == "Chest1" or L_437_forvar1.Name == "Chest2" or L_437_forvar1.Name == "Chest3") and (L_437_forvar1.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 60000 then
						if not L_437_forvar1:FindFirstChild("ChestESP" .. Number) then
							local L_438_ = Instance.new("BillboardGui", L_437_forvar1)
							L_438_.Name = "ChestESP" .. Number
							L_438_.ExtentsOffset = Vector3.new(0, 1, 0)
							L_438_.Size = UDim2.new(1, 200, 1, 30)
							L_438_.Adornee = L_437_forvar1
							L_438_.AlwaysOnTop = true
							local L_439_ = Instance.new("TextLabel", L_438_)
							L_439_.Font = "GothamBold"
							L_439_.FontSize = "Size14"
							L_439_.Size = UDim2.new(1, 0, 1, 0)
							L_439_.BackgroundTransparency = 1
							L_439_.TextStrokeTransparency = 0.5
							if L_437_forvar1.Name == "Chest1" then
								L_439_.TextColor3 = Color3.fromRGB(174, 123, 47)
								L_439_.Text = "Bronze Chest" .. "\n" .. math.round((L_437_forvar1.Position - game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.Position).Magnitude / 3) .. " m."
							end
							if L_437_forvar1.Name == "Chest2" then
								L_439_.TextColor3 = Color3.fromRGB(255, 255, 127)
								L_439_.Text = "Gold Chest" .. "\n" .. math.round((L_437_forvar1.Position - game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.Position).Magnitude / 3) .. " m."
							end
							if L_437_forvar1.Name == "Chest3" then
								L_439_.Text = "Diamond Chest" .. "\n" .. math.round((L_437_forvar1.Position - game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.Position).Magnitude / 3) .. " m."
								L_439_.TextColor3 = Color3.fromRGB(5, 243, 255)
							end
						else
							L_437_forvar1["ChestESP" .. Number].TextLabel.Text = L_437_forvar1.Name .. "\n" .. math.round((L_437_forvar1.Position - game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.Position).Magnitude / 3) .. " m."
						end
					end
				else
					if L_437_forvar1:FindFirstChild("ChestESP" .. Number) then
						L_437_forvar1:FindFirstChild("ChestESP" .. Number):Destroy()
					end
				end
			end
		end)
	end
end

function UpdateBfEsp()
	for L_440_forvar0, L_441_forvar1 in pairs(game:GetService("Workspace"):GetChildren()) do
		pcall(function()
			if DevilFruitESP then
				if string.find(L_441_forvar1.Name, "Fruit") then
					if not L_441_forvar1.Handle:FindFirstChild('NameEsp' .. Number) then
						local L_442_ = Instance.new('BillboardGui', L_441_forvar1.Handle)
						L_442_.Name = 'NameEsp' .. Number
						L_442_.ExtentsOffset = Vector3.new(0, 1, 0)
						L_442_.Size = UDim2.new(1, 200, 1, 30)
						L_442_.Adornee = L_441_forvar1.Handle
						L_442_.AlwaysOnTop = true
						local L_443_ = Instance.new('TextLabel', L_442_)
						L_443_.Font = "GothamBold"
						L_443_.FontSize = "Size14"
						L_443_.TextWrapped = true
						L_443_.Size = UDim2.new(1, 0, 1, 0)
						L_443_.TextYAlignment = 'Top'
						L_443_.BackgroundTransparency = 1
						L_443_.TextStrokeTransparency = 0.5
						L_443_.TextColor3 = Color3.fromRGB(255, 0, 0)
						L_443_.Text = (L_441_forvar1.Name .. ' \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_441_forvar1.Handle.Position).Magnitude / 3) .. ' M')
					else
						L_441_forvar1.Handle['NameEsp' .. Number].TextLabel.Text = (L_441_forvar1.Name .. '   \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_441_forvar1.Handle.Position).Magnitude / 3) .. ' M')
					end
				end
			else
				if L_441_forvar1.Handle:FindFirstChild('NameEsp' .. Number) then
					L_441_forvar1.Handle:FindFirstChild('NameEsp' .. Number):Destroy()
				end
			end
		end)
	end
end

function UpdateFlowerEsp()
	for L_444_forvar0, L_445_forvar1 in pairs(game:GetService("Workspace"):GetChildren()) do
		pcall(function()
			if L_445_forvar1.Name == "Flower2" or L_445_forvar1.Name == "Flower1" then
				if FlowerESP then
					if not L_445_forvar1:FindFirstChild('NameEsp' .. Number) then
						local L_446_ = Instance.new('BillboardGui', L_445_forvar1)
						L_446_.Name = 'NameEsp' .. Number
						L_446_.ExtentsOffset = Vector3.new(0, 1, 0)
						L_446_.Size = UDim2.new(1, 200, 1, 30)
						L_446_.Adornee = L_445_forvar1
						L_446_.AlwaysOnTop = true
						local L_447_ = Instance.new('TextLabel', L_446_)
						L_447_.Font = "GothamBold"
						L_447_.FontSize = "Size14"
						L_447_.TextWrapped = true
						L_447_.Size = UDim2.new(1, 0, 1, 0)
						L_447_.TextYAlignment = 'Top'
						L_447_.BackgroundTransparency = 1
						L_447_.TextStrokeTransparency = 0.5
						L_447_.TextColor3 = Color3.fromRGB(255, 0, 0)
						if L_445_forvar1.Name == "Flower1" then
							L_447_.Text = ("Blue Flower" .. ' \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_445_forvar1.Position).Magnitude / 3) .. ' M')
							L_447_.TextColor3 = Color3.fromRGB(255, 0, 0)
						end
						if L_445_forvar1.Name == "Flower2" then
							L_447_.Text = ("Red Flower" .. ' \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_445_forvar1.Position).Magnitude / 3) .. ' M')
							L_447_.TextColor3 = Color3.fromRGB(255, 0, 0)
						end
					else
						L_445_forvar1['NameEsp' .. Number].TextLabel.Text = (L_445_forvar1.Name .. '   \n' .. L_52_func((game:GetService('Players').LocalPlayer.Character.Head.Position - L_445_forvar1.Position).Magnitude / 3) .. ' M')
					end
				else
					if L_445_forvar1:FindFirstChild('NameEsp' .. Number) then
						L_445_forvar1:FindFirstChild('NameEsp' .. Number):Destroy()
					end
				end
			end
		end)
	end
end

L_18_:Label("Esp [มอง]")

L_18_:Label("ESP Players V.1")
L_18_:Toggle("Esp Player",false,function(L_448_arg0)
		ESPPlayer = L_448_arg0
		while ESPPlayer do
			wait()
			UpdateEspPlayer()
		end
		SaveSettings()
	end
)

L_18_:Toggle("Esp Chest",false,function(L_449_arg0)
		ChestESP = L_449_arg0
		while ChestESP do
			wait()
			UpdateChestEsp()
		end
		SaveSettings()
	end
)

L_18_:Toggle("Esp Fruit",false,function(L_450_arg0)
		DevilFruitESP = L_450_arg0
		while DevilFruitESP do
			wait()
			UpdateBfEsp()
		end
		SaveSettings()
	end
)

if World2 then
	L_18_:Toggle("Esp Flower",false,function(L_451_arg0)
			FlowerESP = L_451_arg0
			while FlowerESP do
				wait()
				UpdateFlowerEsp()
			end
			SaveSettings()
		end
	)
end

L_18_:Toggle("Esp Island",false,function(L_452_arg0)
		IslandESP = L_452_arg0
		while IslandESP do
			wait()
			UpdateIslandESP()
		end
		SaveSettings()
	end
)
--local ESP = loadstring(game:HttpGet("https://kiriot22.com/releases/ESP.lua"))()
--Settings--
if getgenv().PCMode then
local ESP = {
    Enabled = false,
    Boxes = true,
    BoxShift = CFrame.new(0,-1.5,0),
	BoxSize = Vector3.new(4,6,0),
    Color = Color3.fromRGB(255, 170, 0),
    FaceCamera = false,
    Names = true,
    TeamColor = true,
    Thickness = 2,
    AttachShift = 1,
    TeamMates = true,
    Players = true,
    
    Objects = setmetatable({}, {__mode="kv"}),
    Overrides = {}
}

--Declarations--
local cam = workspace.CurrentCamera
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local mouse = plr:GetMouse()

local V3new = Vector3.new
local WorldToViewportPoint = cam.WorldToViewportPoint

--Functions--
local function Draw(obj, props)
	local new = Drawing.new(obj)
	
	props = props or {}
	for i,v in pairs(props) do
		new[i] = v
	end
	return new
end

function ESP:GetTeam(p)
	local ov = self.Overrides.GetTeam
	if ov then
		return ov(p)
	end
	
	return p and p.Team
end

function ESP:IsTeamMate(p)
    local ov = self.Overrides.IsTeamMate
	if ov then
		return ov(p)
    end
    
    return self:GetTeam(p) == self:GetTeam(plr)
end

function ESP:GetColor(obj)
	local ov = self.Overrides.GetColor
	if ov then
		return ov(obj)
    end
    local p = self:GetPlrFromChar(obj)
	return p and self.TeamColor and p.Team and p.Team.TeamColor.Color or self.Color
end

function ESP:GetPlrFromChar(char)
	local ov = self.Overrides.GetPlrFromChar
	if ov then
		return ov(char)
	end
	
	return plrs:GetPlayerFromCharacter(char)
end

function ESP:Toggle(bool)
    self.Enabled = bool
    if not bool then
        for i,v in pairs(self.Objects) do
            if v.Type == "Box" then --fov circle etc
                if v.Temporary then
                    v:Remove()
                else
                    for i,v in pairs(v.Components) do
                        v.Visible = false
                    end
                end
            end
        end
    end
end

function ESP:GetBox(obj)
    return self.Objects[obj]
end

function ESP:AddObjectListener(parent, options)
    local function NewListener(c)
        if type(options.Type) == "string" and c:IsA(options.Type) or options.Type == nil then
            if type(options.Name) == "string" and c.Name == options.Name or options.Name == nil then
                if not options.Validator or options.Validator(c) then
                    local box = ESP:Add(c, {
                        PrimaryPart = type(options.PrimaryPart) == "string" and c:WaitForChild(options.PrimaryPart) or type(options.PrimaryPart) == "function" and options.PrimaryPart(c),
                        Color = type(options.Color) == "function" and options.Color(c) or options.Color,
                        ColorDynamic = options.ColorDynamic,
                        Name = type(options.CustomName) == "function" and options.CustomName(c) or options.CustomName,
                        IsEnabled = options.IsEnabled,
                        RenderInNil = options.RenderInNil
                    })
                    --TODO: add a better way of passing options
                    if options.OnAdded then
                        coroutine.wrap(options.OnAdded)(box)
                    end
                end
            end
        end
    end

    if options.Recursive then
        parent.DescendantAdded:Connect(NewListener)
        for i,v in pairs(parent:GetDescendants()) do
            coroutine.wrap(NewListener)(v)
        end
    else
        parent.ChildAdded:Connect(NewListener)
        for i,v in pairs(parent:GetChildren()) do
            coroutine.wrap(NewListener)(v)
        end
    end
end

local boxBase = {}
boxBase.__index = boxBase

function boxBase:Remove()
    ESP.Objects[self.Object] = nil
    for i,v in pairs(self.Components) do
        v.Visible = false
        v:Remove()
        self.Components[i] = nil
    end
end

function boxBase:Update()
    if not self.PrimaryPart then
        --warn("not supposed to print", self.Object)
        return self:Remove()
    end

    local color
    if ESP.Highlighted == self.Object then
       color = ESP.HighlightColor
    else
        color = self.Color or self.ColorDynamic and self:ColorDynamic() or ESP:GetColor(self.Object) or ESP.Color
    end

    local allow = true
    if ESP.Overrides.UpdateAllow and not ESP.Overrides.UpdateAllow(self) then
        allow = false
    end
    if self.Player and not ESP.TeamMates and ESP:IsTeamMate(self.Player) then
        allow = false
    end
    if self.Player and not ESP.Players then
        allow = false
    end
    if self.IsEnabled and (type(self.IsEnabled) == "string" and not ESP[self.IsEnabled] or type(self.IsEnabled) == "function" and not self:IsEnabled()) then
        allow = false
    end
    if not workspace:IsAncestorOf(self.PrimaryPart) and not self.RenderInNil then
        allow = false
    end

    if not allow then
        for i,v in pairs(self.Components) do
            v.Visible = false
        end
        return
    end

    if ESP.Highlighted == self.Object then
        color = ESP.HighlightColor
    end

    --calculations--
    local cf = self.PrimaryPart.CFrame
    if ESP.FaceCamera then
        cf = CFrame.new(cf.p, cam.CFrame.p)
    end
    local size = self.Size
    local locs = {
        TopLeft = cf * ESP.BoxShift * CFrame.new(size.X/2,size.Y/2,0),
        TopRight = cf * ESP.BoxShift * CFrame.new(-size.X/2,size.Y/2,0),
        BottomLeft = cf * ESP.BoxShift * CFrame.new(size.X/2,-size.Y/2,0),
        BottomRight = cf * ESP.BoxShift * CFrame.new(-size.X/2,-size.Y/2,0),
        TagPos = cf * ESP.BoxShift * CFrame.new(0,size.Y/2,0),
        Torso = cf * ESP.BoxShift
    }

    if ESP.Boxes then
        local TopLeft, Vis1 = WorldToViewportPoint(cam, locs.TopLeft.p)
        local TopRight, Vis2 = WorldToViewportPoint(cam, locs.TopRight.p)
        local BottomLeft, Vis3 = WorldToViewportPoint(cam, locs.BottomLeft.p)
        local BottomRight, Vis4 = WorldToViewportPoint(cam, locs.BottomRight.p)

        if self.Components.Quad then
            if Vis1 or Vis2 or Vis3 or Vis4 then
                self.Components.Quad.Visible = true
                self.Components.Quad.PointA = Vector2.new(TopRight.X, TopRight.Y)
                self.Components.Quad.PointB = Vector2.new(TopLeft.X, TopLeft.Y)
                self.Components.Quad.PointC = Vector2.new(BottomLeft.X, BottomLeft.Y)
                self.Components.Quad.PointD = Vector2.new(BottomRight.X, BottomRight.Y)
                self.Components.Quad.Color = color
            else
                self.Components.Quad.Visible = false
            end
        end
    else
        self.Components.Quad.Visible = false
    end

    if ESP.Names then
        local TagPos, Vis5 = WorldToViewportPoint(cam, locs.TagPos.p)
        
        if Vis5 then
            self.Components.Name.Visible = true
            self.Components.Name.Position = Vector2.new(TagPos.X, TagPos.Y)
            self.Components.Name.Text = self.Name
            self.Components.Name.Color = color
            
            self.Components.Distance.Visible = true
            self.Components.Distance.Position = Vector2.new(TagPos.X, TagPos.Y + 14)
            self.Components.Distance.Text = math.floor((cam.CFrame.p - cf.p).magnitude) .." M."
            self.Components.Distance.Color = color
        else
            self.Components.Name.Visible = false
            self.Components.Distance.Visible = false
        end
    else
        self.Components.Name.Visible = false
        self.Components.Distance.Visible = false
    end
    
    if ESP.Tracers then
        local TorsoPos, Vis6 = WorldToViewportPoint(cam, locs.Torso.p)

        if Vis6 then
            self.Components.Tracer.Visible = true
            self.Components.Tracer.From = Vector2.new(TorsoPos.X, TorsoPos.Y)
            self.Components.Tracer.To = Vector2.new(cam.ViewportSize.X/2,cam.ViewportSize.Y/ESP.AttachShift)
            self.Components.Tracer.Color = color
        else
            self.Components.Tracer.Visible = false
        end
    else
        self.Components.Tracer.Visible = false
    end
end

function ESP:Add(obj, options)
    if not obj.Parent and not options.RenderInNil then
        return warn(obj, "has no parent")
    end

    local box = setmetatable({
        Name = options.Name or obj.Name,
        Type = "Box",
        Color = options.Color ,
        Size = options.Size or self.BoxSize,
        Object = obj,
        Player = options.Player or plrs:GetPlayerFromCharacter(obj),
        PrimaryPart = options.PrimaryPart or obj.ClassName == "Model" and (obj.PrimaryPart or obj:FindFirstChild("HumanoidRootPart") or obj:FindFirstChildWhichIsA("BasePart")) or obj:IsA("BasePart") and obj,
        Components = {},
        IsEnabled = options.IsEnabled,
        Temporary = options.Temporary,
        ColorDynamic = options.ColorDynamic,
        RenderInNil = options.RenderInNil
    }, boxBase)

    if self:GetBox(obj) then
        self:GetBox(obj):Remove()
    end

    box.Components["Quad"] = Draw("Quad", {
        Thickness = self.Thickness,
        Color = color,
        Transparency = 1,
        Filled = false,
        Visible = self.Enabled and self.Boxes
    })
    box.Components["Name"] = Draw("Text", {
		Text = box.Name,
		Color = box.Color,
		Center = true,
		Outline = true,
        Size = 19,
        Visible = self.Enabled and self.Names
	})
	box.Components["Distance"] = Draw("Text", {
		Color = box.Color,
		Center = true,
		Outline = true,
        Size = 19,
        Visible = self.Enabled and self.Names
	})
	
	box.Components["Tracer"] = Draw("Line", {
		Thickness = ESP.Thickness,
		Color = box.Color,
        Transparency = 1,
        Visible = self.Enabled and self.Tracers
    })
    self.Objects[obj] = box
    
    obj.AncestryChanged:Connect(function(_, parent)
        if parent == nil and ESP.AutoRemove ~= false then
            box:Remove()
        end
    end)
    obj:GetPropertyChangedSignal("Parent"):Connect(function()
        if obj.Parent == nil and ESP.AutoRemove ~= false then
            box:Remove()
        end
    end)

    local hum = obj:FindFirstChildOfClass("Humanoid")
	if hum then
        hum.Died:Connect(function()
            if ESP.AutoRemove ~= false then
                box:Remove()
            end
		end)
    end

    return box
end

local function CharAdded(char)
    local p = plrs:GetPlayerFromCharacter(char)
    if not char:FindFirstChild("HumanoidRootPart") then
        local ev
        ev = char.ChildAdded:Connect(function(c)
            if c.Name == "HumanoidRootPart" then
                ev:Disconnect()
                ESP:Add(char, {
                    Name = p.Name,
                    Player = p,
                    PrimaryPart = c
                })
            end
        end)
    else
        ESP:Add(char, {
            Name = p.Name,
            Player = p,
            PrimaryPart = char.HumanoidRootPart
        })
    end
end
local function PlayerAdded(p)
    p.CharacterAdded:Connect(CharAdded)
    if p.Character then
        coroutine.wrap(CharAdded)(p.Character)
    end
end
plrs.PlayerAdded:Connect(PlayerAdded)
for i,v in pairs(plrs:GetPlayers()) do
    if v ~= plr then
        PlayerAdded(v)
    end
end

game:GetService("RunService").RenderStepped:Connect(function()
    cam = workspace.CurrentCamera
    for i,v in (ESP.Enabled and pairs or ipairs)(ESP.Objects) do
        if v.Update then
            local s,e = pcall(v.Update, v)
            if not s then warn("[EU]", e, v.Object:GetFullName()) end
        end
    end
end)

ESP:Toggle(true)
ESP.Players = false
ESP.Tracers = false
ESP.Boxes = false
ESP.Names = false

L_18_:Label("ESP Players V.2")

L_18_:Toggle("Show ESP Players", true, function(Value)
   ESP.Players = Value
end)
L_18_:Toggle("ESP Nametags Players", false, function(Value)
   ESP.Names = Value
end)
L_18_:Toggle("ESP Tracers Players", false, function(Value)
   ESP.Tracers = Value
end)
L_18_:Toggle("ESP Box Players", false, function(Value)
   ESP.Boxes = Value
end)
end


local plyserv = Combat:Label("Players")
    
    spawn(function()
        while wait() do
            pcall(function()
                for i,v in pairs(game:GetService("Players"):GetPlayers()) do
                    if i == 12 then
                        plyserv:Change("Players :".." "..i.." ".."/".." ".."12".." ".."(Max)")
                    elseif i == 1 then
                        plyserv:Change("Player :".." "..i.." ".."/".." ".."12")
                    else
                        plyserv:Change("Players :".." "..i.." ".."/".." ".."12")
                    end
                end
            end)
        end
    end)
    
    Combat:Toggle("Spectate Player",false,function(value)
        SpectatePlys = value
        local plr1 = game:GetService("Players").LocalPlayer.Character.Humanoid
        local plr2 = game:GetService("Players"):FindFirstChild(_G.SelectPly)
        repeat wait(.1)
            game:GetService("Workspace").Camera.CameraSubject = game:GetService("Players"):FindFirstChild(_G.SelectPly).Character.Humanoid
        until SpectatePlys == false 
        game:GetService("Workspace").Camera.CameraSubject = game:GetService("Players").LocalPlayer.Character.Humanoid
    end)
    
    Playerslist = {}
    
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
        table.insert(Playerslist,v.Name)
    end
    
    local SelectedPly = Combat:Dropdown("Select Players",Playerslist,"",function(value)
        _G.SelectPly = value
    end)
    
    Combat:Button("Refresh Player",function()
        Playerslist = {}
        SelectedPly:Clear()
        for i,v in pairs(game:GetService("Players"):GetChildren()) do  
            SelectedPly:Add(v.Name)
        end
    end)
    
    Combat:Toggle("Teleport to Players",false,function(value)
        _G.TeleportPly = value
        pcall(function()
            if _G.TeleportPly then
                repeat wait()
                    topos(game:GetService("Players")[_G.SelectPly].Character.HumanoidRootPart.CFrame * CFrame.new(1,30,15)) wait() 
                until _G.TeleportPly == false
            end
            StopTween(_G.TeleportPly)
        end)
    end)
    Combat:Label("warn : 1 item, replay the game again")
    Combat:Toggle("Auto Kill Player t Select",_G.Auto_Kill_Ply,function(value)
        _G.Auto_Kill_Ply = value
        StopTween(_G.Auto_Kill_Ply)
    end)

    task.spawn(function()
        while task.wait() do
            if _G.Auto_Kill_Ply then
                pcall(function()
                    _G.Aimbot_Gun = true
                    Aimbot = true
                    EquipWeapon(SelectToolWeaponGun)
                    if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                    end
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.PvpDisabled.Visible == true then
                        EquipWeapon(SelectToolWeaponGun)
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EnablePvp")
                    end
                    if _G.SelectPly ~= nil then 
                        for i,v in pairs(game:GetService("Workspace").Characters:GetChildren()) do
                            if v.Name == _G.SelectPly then
                                repeat task.wait()
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 250 then  -- >
                                        Farmtween = L_3_func(v.HumanoidRootPart.CFrame * CFrame.new(-15,-30,-1))
                                    elseif (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then  -- <=
                                        MinHealth = v.Humanoid.MaxHealth * 90 / 100
                                        if Farmtween then Farmtween:Stop() end
                                        if v.Humanoid.Health > MinHealth then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(-0,40,55)
                                            EquipWeapon(SelectToolWeaponGun)
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(- 0, -3, 7)
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                            --game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,-5,5)
                                            EquipWeapon(_G.Settings.FightingStyle["Auto Superhuman"])
                                            -- if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") and game.Players.LocalPlayer.Character:FindFirstChild("Superhuman").Level.Value >= 220 then
                                                -- game:service("VirtualInputManager"):SendKeyEvent(true, "X", false, game)
                                                -- game:service("VirtualInputManager"):SendKeyEvent(false, "X", false, game)
                                            -- end
                                        end
                                    end
                                    local args = {
                                      [1] = game.Players[v.Name].Character.HumanoidRootPart.Position,
                                      [2] = game.Players[v.Name].Character.HumanoidRootPart
                                      }
                                    game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                                    Click()
                                    Aimbot = true
                                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                    v.HumanoidRootPart.CanCollide = false
                                until v.Humanoid.Health <= 0 or _G.Auto_Kill_Ply == false
                                if v.Humanoid.Health <= 0 then
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,363,0)
                                end
                                --FastAttack = false
                                Aimbot = false
                                _G.Aimbot_Gun = false
                            end
                        end
                    end
                end)
            end
        end
    end)
    
    Combat:Button("Get Kill Player Quest",function()
        local args = {
        [1] = "PlayerHunter"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end)
    
    Combat:Label("Aimbot")

    Combat:Toggle("Aimbot Gun",_G.Aimbot_Gun,function(value)
        _G.Aimbot_Gun = value
        Aimbot = value
    end)
    
spawn(function()
	while wait() do
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
			if v:IsA("Tool") then
				if v:FindFirstChild("RemoteFunctionShoot") then 
					SelectToolWeaponGun = v.Name
				end
			end
		end
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do  
			if v:IsA("Tool") then
				if v:FindFirstChild("RemoteFunctionShoot") then 
					SelectToolWeaponGun = v.Name
				end
			end
		end
	end
end)

spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
        if _G.Aimbot_Gun then
			pcall(function()
                for i,v in pairs(game:GetService("Workspace").Characters:GetChildren()) do
                    if v.Name == _G.SelectPly then
                        repeat wait()
                        local args = {
                            [1] = v.HumanoidRootPart.Position,
                            [2] = v.HumanoidRootPart
                        }
                        game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                        game:GetService'VirtualUser':CaptureController()
                        game:GetService'VirtualUser':Button1Down(Vector2.new(0.9, 0.9))
                        until _G.Aimbot_Gun == false
                    end
                end
            end)
        end
    end)
end)

local lp = game:GetService('Players').LocalPlayer
local mouse = lp:GetMouse()
mouse.Button1Down:Connect(function()
    if Aimbot and game.Players.LocalPlayer.Character:FindFirstChild(SelectToolWeaponGun) and game:GetService("Players"):FindFirstChild(_G.SelectPly) then
        tool = game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun]
        v17 = workspace:FindPartOnRayWithIgnoreList(Ray.new(tool.Handle.CFrame.p, (game:GetService("Players"):FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.Position - tool.Handle.CFrame.p).unit * 100), { game.Players.LocalPlayer.Character, workspace._WorldOrigin });
        game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun].RemoteFunctionShoot:InvokeServer(game:GetService("Players"):FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.Position, (require(game.ReplicatedStorage.Util).Other.hrpFromPart(v17)));
    end 
end)

    Combat:Toggle("Aimbot Skill [Bug]",Skillaimbot,function(value)
        _G.AimbotSkill = value
        Skillaimbot = value
        AimbotSkillRange = value
        if Skillaimbot then
			if game.Players:FindFirstChild(_G.SelectPly) and game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("HumanoidRootPart") and game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("Humanoid") and game.Players:FindFirstChild(_G.SelectPly).Character.Humanoid.Health > 0 then
				AimBotSkillPosition = game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("HumanoidRootPart").Position
			end
		end
    end)
    
    spawn(function()
game:GetService("RunService").Heartbeat:Connect(function()
  if AimbotSkillRange then
    pcall(function()
       for i,v in pairs(game:GetService("Players"):GetChildren()) do
          if v.Character:FindFirstChild("HumanoidRootPart") and v.Character:FindFirstChild("Humanoid") then
             if (v.Character.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude/3 <= SkillRange then
                if v.Name == game.Players.LocalPlayer.Name then
                else
                   if game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and game.Players.LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name]:FindFirstChild("MousePos") then
                      local args = {
                         [1] = v.Character.HumanoidRootPart.Position
                      }
                      game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
                   end
                end
             end
          end
       end
    end)
  end
end)
end)

 spawn(function()
    pcall(function()
    while game:GetService("RunService").RenderStepped:wait() do
       if _G.AimbotSkill then
          pcall(function()
             if game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and game.Players.LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name]:FindFirstChild("MousePos") then
                 local args = {
                     [1] = game:GetService("Players"):FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.Position
                 }
                 game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
             end
         end)
     end
    end
    end)
 end)

local gg = getrawmetatable(game)
local old = gg.namecall
setreadonly(gg,false)
gg.namecall = newcclosure(function(...)
    local method = getnamecallmethod()
    local args = {...}
    if tostring(method) == "FireServer" then
        if tostring(args[1]) == "RemoteEvent" then
            if tostring(args[2]) ~= "true" and tostring(args[2]) ~= "false" then
                if Skillaimbot then
                    args[2] = AimBotSkillPosition
                    return old(unpack(args))
                end
            end
        end
    end
    return old(...)
end)

task.spawn(function()
    while wait() do
        if Skillaimbot then
            if game.Players:FindFirstChild(_G.SelectPly) and game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("HumanoidRootPart") and game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("Humanoid") and game.Players:FindFirstChild(_G.SelectPly).Character.Humanoid.Health > 0 then
                AimBotSkillPosition = game.Players:FindFirstChild(_G.SelectPly).Character:FindFirstChild("HumanoidRootPart").Position
            end
        end
    end
end)

    Combat:Label("PvP")
    
    Combat:Toggle("Enabled PvP",_G.EnabledPvP,function(value)
        _G.EnabledPvP = value
    end)
    
    spawn(function()
        pcall(function()
            while wait(.1) do
                if _G.EnabledPvP then
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.PvpDisabled.Visible == true then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EnablePvp")
                    end
                end
            end
        end)
    end)

    Combat:Toggle("Safe Mode",false,function(value)
        _G.Safe_Mode = value
        StopTween(_G.Safe_Mode)
    end)
    Combat:Button("Safe Mode",function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,300,0))
    end)
    spawn(function()
        pcall(function()
            while wait() do
                if _G.Safe_Mode then
                    topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,300,0))
                end
            end
        end)
    end)
    
    Combat:Button("Respawn",function()
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetTeam","Pirates") 
        wait()
    end)
    
    Combat:Label("Bounty")
    
    local Current = Combat:Label("Current Bounties :")
    
    local Bounty = tostring(game:GetService("Players").LocalPlayer.leaderstats["Bounty/Honor"].Value)
    local sub = string.sub 
    local len = string.len
    spawn(function()
        while wait() do
            pcall(function()
                if len(Bounty) == 4 then
                    Bounty1 = sub(Bounty,1,1).."."..sub(Bounty,2,3).."K"
                elseif len(Bounty) == 5 then
                    Bounty1 = sub(Bounty,1,2).."."..sub(Bounty,3,4).."K"
                elseif len(Bounty) == 6 then
                    Bounty1 = sub(Bounty,1,3).."."..sub(Bounty,4,5).."K"
                elseif len(Bounty) == 7 then
                    Bounty1 = sub(Bounty,1,1).."."..sub(Bounty,2,3).."M"
                elseif len(Bounty) == 8 then
                    Bounty1 = sub(Bounty,1,2).."."..sub(Bounty,3,4).."M"
                elseif len(Bounty) <= 3 then
                    Bounty1 = Bounty
                end
                if tonumber(Bounty) == 25000000 then
                    Current:Change("Current Bounties : "..Bounty1.." [ Max ]")
                elseif tonumber(Bounty) < 25000000 then
                    Current:Change("Current Bounties : "..Bounty1)
                end
            end)
        end
    end)
Skip_S = 10
    Combat:Toggle("Auto Farm Bounty [Bug]",_G.AutoFarmBounty,function(value)
        Auto_Farm_Bounty = value
        _G.AutoFarmBounty = value
        StopTween(_G.AutoFarmBounty)
    end)
function Get_Mon(vu)    
	for i,v in pairs(game.Workspace.Characters:GetChildren()) do
		if v.Name ~= game.Players.LocalPlayer.Name and v.Name ~= "Sapab" then
			if (v.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= tonumber(vu) then
				_G.Players_Mon = v
				return
			end
		end
	end
end

spawn(function()
        while wait() do
            pcall(function()
                if Auto_Farm_Bounty then
                    _G.Players_Mon = nil
                    for i = 10000,500,-500 do
                        Get_Mon(i)
                    end
                    if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                    end
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.PvpDisabled.Visible == true then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EnablePvp")
                    end
                    if _G.Players_Mon ~= nil then
                        print("Player : "..tostring(_G.Players_Mon.Name))
                        SelectedKillPlayer = _G.Players_Mon.Name
                        Start_Kill = true
                        repeat wait(.1)
                        until Kop
                            if _G.Players_Mon:WaitForChild("Humanoid").Health > 0 and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - _G.Players_Mon.HumanoidRootPart.Position).Magnitude <= 17000 then
                                plyselecthunthelpold = _G.Players_Mon.Humanoid.Health
                                repeat task.wait()
                                    if (_G.Players_Mon.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 250 then  -- >
                                        Farmtween = L_3_func(_G.Players_Mon.HumanoidRootPart.CFrame * CFrame.new(-15,-30,-1))
                                        EquipWeapon(SelectToolWeaponGun)
                                    elseif (_G.Players_Mon.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 250 then  -- <=
                                        MinHealth = _G.Players_Mon.Humanoid.MaxHealth * 90 / 100
                                        if Farmtween then Farmtween:Stop() end
                                        if _G.Players_Mon.Humanoid.Health > MinHealth then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = _G.Players_Mon.HumanoidRootPart.CFrame * CFrame.new(-0,40,55)
                                            EquipWeapon(SelectToolWeaponGun)
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = _G.Players_Mon.HumanoidRootPart.CFrame * CFrame.new(- 0, -10, 2)
                                            EquipWeapon(_G.Settings.Configs["Select Weapon"])
                                            --game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,-5,5)
                                            EquipWeapon(_G.Settings.FightingStyle["Auto Superhuman"])
                                            -- if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") and game.Players.LocalPlayer.Character:FindFirstChild("Superhuman").Level.Value >= 220 then
                                                -- game:service("VirtualInputManager"):SendKeyEvent(true, "X", false, game)
                                                -- game:service("VirtualInputManager"):SendKeyEvent(false, "X", false, game)
                                            -- end
                                        end
                                    end
                                    spawn(function()
                                        if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 150 then
                                            StartCheckTarget = true
                                        end
                                    end)
                                    Click()
                                    _G.Aimbot_Gun1 = true
                                    --game:GetService'VirtualUser':Button1Down(Vector2.new(1280,600))
                                    --_G.Players_Mon.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                    --_G.Players_Mon.HumanoidRootPart.CanCollide = false
                                TargetSelectHunt = v.Humanoid
                                until _G.Players_Mon == nil or not _G.Players_Mon.Parent or _G.Players_Mon.Humanoid.Health <= 0 or not Auto_Farm_Bounty or game.Players.LocalPlayer.Character.Humanoid.Health <= 0
                                if _G.Players_Mon ~= nil then
                                    print("Kill : "..tostring(_G.Players_Mon.Name))
                                end
                                _G.Players_Mon.Name = "Sapab"
                                if _G.Players_Mon.Humanoid.Health <= 0 then
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = _G.Players_Mon.HumanoidRootPart.CFrame * CFrame.new(0,363,0)
                                end
                                --FastAttack = false
                                _G.Aimbot_Gun1 = false
                            end
                    end
                end
            end)
        end
    end)
spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
        if _G.Aimbot_Gun1 then
			pcall(function()
                SelectedKillPlayer = _G.Players_Mon.Name
                    --if _G.Players_Mon.Name == _G.Players_Mon then
                        repeat wait()
                        local args = {
                            [1] = _G.Players_Mon.HumanoidRootPart.Position,
                            [2] = _G.Players_Mon.HumanoidRootPart
                        }
                        game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                        game:GetService'VirtualUser':CaptureController()
                        game:GetService'VirtualUser':Button1Down(Vector2.new(0.9, 0.9))
                        until _G.Aimbot_Gun1 == false
                    --end
                
            end)
        end
    end)
end)

spawn(function()
	while wait(.5) do
		pcall(function()
			if Start_Kill then
				Kop = true
				Kip = 0
				repeat wait()
					if (_G.Players_Mon.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
						if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.InCombat.Visible == true then
						else
							wait(1)
							Kip = Kip + 1
							print("Skip : "..tostring(Kip))
						end
					end
				until Kip >= Skip_S or not _G.Players_Mon.Parent or _G.Players_Mon.Humanoid.Health <= 0 or not Auto_Farm_Bounty
				Start_Kill = false
				Kop = false
				if Kip >= Skip_S then
					_G.Players_Mon.Name = "Sapab"
					_G.Players_Mon = nil
				end
			end
		end)
	end
end)

spawn(function()
	while wait(.5) do
		pcall(function()
			if Start_Kill then
				Kop = true
				Kip = 0
				repeat wait()
					if (_G.Players_Mon.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
						if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.InCombat.Visible == true then
						else
							wait(1)
							Kip = Kip + 1
							print("Skip : "..tostring(Kip))
						end
					end
				until Kip >= Skip_S or not _G.Players_Mon.Parent or _G.Players_Mon.Humanoid.Health <= 0 or not _G.Auto_Kill_Ply
				Start_Kill = false
				Kop = false
				if Kip >= Skip_S then
					_G.Players_Mon.Name = "Sapab"
					_G.Players_Mon = nil
				end
			end
		end)
	end
end)
    spawn(function()
        while wait() do
            pcall(function()
                if _G.AutoFarmBounty then
                    for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
                        if v:IsA("Shirt") then
                            v:Destroy()
                        end
                        if v:IsA("Pants") then
                            v:Destroy()
                        end
                        if v:IsA("Accessory") then
                            v:Destroy()
                        end
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        pcall(function()
            if _G.AutoFarmBounty then
                while wait() do
                    if game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
                    end
                end
            end
        end)
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if _G.AutoFarmBounty then
                    if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while task.wait() do
            pcall(function()
                if _G.AutoFarmBounty then
                    game:GetService("Players").LocalPlayer.Character[SelectWeaponGun].Cooldown.Value = 0
                    spawn(function()
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Beli.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.HP.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Energy.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.StatsButton.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.ShopButton.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Skills.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Level.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.MenuButton.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Code.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Settings.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Mute.Visible = false
                        game:GetService("Players")["LocalPlayer"].PlayerGui.Main.CrewButton.Visible = false
                        game.Players.LocalPlayer.Character.Animate.Disabled = true
                    end)
                end
            end)
        end
    end)

    spawn(function()
        pcall(function()
            while task.wait() do
                if _G.AutoFarmBounty then
                    game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible = false
                    game:GetService("Players").LocalPlayer.PlayerGui.Main.SafeZone.Visible = false
                end
            end
        end)
    end)

    spawn(function()
        pcall(function()
            while wait() do
                if _G.AutoFarmBounty  then
                    if TargetSelectHunt ~= nil then
                        if StartCheckTarget then
                            wait(6.5)
                            if TargetSelectHunt.Health == TargetSelectHunt.MaxHealth or TargetSelectHunt.Health >= plyselecthunthelpold then
                                NextplySelect = true
                                TargetSelectHunt = nil
                            end
                        end
                    end
                end
            end
        end)
    end)

    spawn(function()
        pcall(function()
            while wait(.1) do
                if _G.AutoFarmBounty then
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.PvpDisabled.Visible == true then
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EnablePvp")
                    end
                end
            end
        end)
    end)
    


if World2 then
    L_20_:Button("Teleport to Lab",function()
        L_3_func(CFrame.new(- 6438.73535, 250.645355, - 4501.50684))
        end)
elseif World3 then
    L_20_:Button("Teleport to Lab",function()
        L_3_func(CFrame.new(- 5057.146484375, 314.54132080078, - 2934.7995605469))
    end)
end

L_20_:Label("Raid")
    
L_20_:Toggle("Auto Raids",_G.Settings.Raids["Auto Raids"],function(L_453_arg0)
	_G.Settings.Raids["Auto Raids"] = L_453_arg0
	if L_453_arg0 == false then
	wait()
		L_3_func(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
	end
	SaveSettings()
end)

L_20_:Toggle("Auto Buy Chips",_G.Settings.Raids["Auto Buy Chips"],function(L_453_arg0)
	_G.Settings.Raids["Auto Buy Chips"] = L_453_arg0
	SaveSettings()
end)
    spawn(function()
        pcall(function()
            while wait() do
                if _G.Settings.Raids["Auto Buy Chips"] then
                    if not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Special Microchip") or not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Special Microchip") then
                        if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc", "Select", _G.Settings.Raids["Select Raids"])
                        end
                    end
                end
            end
        end)
    end)
    spawn(function()
        while wait(.1) do
            pcall(function()
                if _G.Settings.Raids["Auto Raids"] then
                    if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == false then
                        if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Special Microchip") then
                            if World2 then
                                fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
                            elseif World3 then
                                fireclickdetector(game:GetService("Workspace").Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
                            end
                        end
                    end
                end
            end)
        end
    end)
L_20_:Dropdown("Select Raids",{"Flame","Ice","Quake","Light",
    "Dark","String","Rumble","Magma","Human: Buddha","Sand",
    "Bird: Phoenix","Dough"
	},_G.Settings.Raids["Select Raids"] ,function(L_454_arg0)
	_G.Settings.Raids["Select Raids"] = L_454_arg0
	SaveSettings()
end)

L_20_:Label("Raids Configs")

L_20_:Toggle("Kill Aura [Bug]",_G.Settings.Raids["Kill Aura"],function(L_455_arg0)
		_G.Settings.Raids["Kill Aura"] = L_455_arg0
		SaveSettings()
end)

L_20_:Toggle("Auto Awakened | ออโต้ผลตื่น",_G.Settings.Raids["Auto Awakened"],function(L_456_arg0)
		_G.Settings.Raids["Auto Awakened"] = L_456_arg0
		SaveSettings()
end)

L_20_:Toggle("Auto Next Place | ออโตย้ายเกาะ",_G.Settings.Raids["Auto Next Place"],function(L_457_arg0)
		_G.Settings.Raids["Auto Next Place"] = L_457_arg0
		SaveSettings()
end)

---
local function TPxnxx(...)
	local L_100_ = {
		...
	}
	local L_101_ = L_100_[1]
	local Pos
	if type(L_101_) == "vector" then
		Pos = CFrame.new(L_101_)
	elseif type(L_101_) == "userdata" then
		Pos = L_101_
	elseif type(L_101_) == "number" then
		Pos = CFrame.new(unpack(L_100_))
	end

	if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health == 0 then
		if tween then
			tween:Cancel()
		end
		repeat
			wait()
		until game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health > 0;
		wait(0.2)
	end

	local L_103_ = {}
	local L_104_ = (Pos.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude
	if L_104_ < 250 then
		Speed = 499
	elseif L_104_ < 350 then
		Speed = 380
	elseif L_104_ < 401 then
		Speed = 370
	elseif L_104_ < 405 then
		Speed = 400
	elseif L_104_ < 406 then
		Speed = 363
	elseif L_104_ < 550 then
		Speed = 363
	elseif L_104_ < 560 then
		Speed = 450
	elseif L_104_ < 600 then
		Speed = 377
	elseif L_104_ < 800 then
		Speed = 363
	elseif L_104_ >= 1500 then
		Speed = 363
	else
	    if L_104_ <= 500 then
	    	Speed = 600
	    end
	end

	local L_105_ = game:service"TweenService"
	local L_106_ = TweenInfo.new((Pos.Position - game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart").Position).Magnitude / Speed, Enum.EasingStyle.Linear)
	local L_107_, L_108_ = pcall(function()
		tween = L_105_:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], L_106_, {
			CFrame = Pos
		})
		tween:Play()
	end)

	function L_103_:Stop()
		tween:Cancel()
	end 

	function L_103_:Wait()
		tween.Completed:Wait()
	end 

	return L_103_
end
spawn(function()
	while wait() do
		if _G.Settings.Raids["Auto Raids"] and not _G.Settings.Main["Auto Farm Level"] then 
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip") and game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == false then
					if World2 then
						fireclickdetector(Workspace.Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
					end
					if World3 then
						fireclickdetector(Workspace.Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
					end
				end
				    if game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == true then				
					pcall(function()
						repeat wait()
							if game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == false then 
							elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
								game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame = CFrame.new(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame.x, 60, game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame.z)
								if (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 350 then
									Farmtween = L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame)
									if _G.Settings.Raids["Auto Raids"] and ((game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1200 then
                                        L_3_func((game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame))
                                    end
								elseif (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 350 then
									if Farmtween then
										Farmtween:Stop()
									end
									if _G.Settings.Raids["Auto Raids"] and ((game:GetService("Workspace")["_WorldOrigin"].Locations["Island 5"].CFrame * CFrame.new(4, 65, 10)).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1200 then
                                        L_3_func((game:GetService("Workspace")["_WorldOrigin"].Locations["Island 5"].CFrame * CFrame.new(4, 65, 10)))
                                    end
									L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 5"].CFrame * CFrame.new(4, 65, 10))
								end
							elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
								game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame = CFrame.new(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame.x, 60, game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame.z)
								if (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 350 then
									Farmtween = L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame)
								elseif (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 350 then
									if Farmtween then
										Farmtween:Stop()
									end
									L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 4"].CFrame * CFrame.new(4, 65, 10))
								end
							elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
								game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame = CFrame.new(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame.x, 60, game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame.z)
								if (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 350 then
									Farmtween = L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame)
								elseif (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 350 then
									if Farmtween then
										Farmtween:Stop()
									end
									L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 3"].CFrame * CFrame.new(4, 65, 10))
								end
							elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
								game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame = CFrame.new(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame.x, 60, game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame.z)
								if (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 350 then
									Farmtween = L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame)
								elseif (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 350 then
									if Farmtween then
										Farmtween:Stop()
									end
									L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 2"].CFrame * CFrame.new(4, 65, 10))
								end
							elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
								game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame = CFrame.new(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame.x, 60, game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame.z)
								if (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude > 350 then
									Farmtween = L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame)
								elseif (game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 350 then
									if Farmtween then
										Farmtween:Stop()
									end
									L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 1"].CFrame * CFrame.new(4, 65, 10))
								end
							end
							for i, L_459_forvar1 in pairs(game.Workspace.Enemies:GetChildren()) do
								if _G.Settings.Raids["Auto Raids"] and game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == true and L_459_forvar1:FindFirstChild("Humanoid") and L_459_forvar1:FindFirstChild("HumanoidRootPart") and (L_459_forvar1.HumanoidRootPart.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= 400 then
									--[[pcall(function()
                                        for i,L_459_forvar1 in pairs(game.Workspace.Enemies:GetChildren()) do
                                            if not string.find(L_459_forvar1.Name,"Boss") and L_459_forvar1.Humanoid.Health <= 0 and L_459_forvar1:FindFirstChild("Humanoid") then
                                                wait(.9)
                                                L_459_forvar1:Destroy()
                                            end
                                        end
                                    end)]]
									repeat wait(.3)
										InMyNetWork(L_459_forvar1.HumanoidRootPart)
                                        L_459_forvar1.HumanoidRootPart.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-35,0)
                                        L_459_forvar1.Humanoid:ChangeState(12)
										L_459_forvar1.Humanoid.Health = 0
										L_459_forvar1.HumanoidRootPart.CanCollide = false
                                        L_459_forvar1.HumanoidRootPart.Size = Vector3.new(80,80,80)
                                        L_459_forvar1.HumanoidRootPart.Transparency = 0.9
										--L_459_forvar1:BreakJoints()
										--[[if L_459_forvar1.Humanoid:FindFirstChild("Animator") then
                                            wait(1)
                                            L_459_forvar1.Humanoid.Animator:Destroy()
                                        end]]
										sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
									until not _G.Settings.Raids["Auto Raids"] or L_459_forvar1.Humanoid.Health <= 0 or not L_459_forvar1.Parent
								end
							end
							if _G.Settings.Raids["Auto Awakened"] then	
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Awakener", "Awaken")
							end
						until not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") or not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") or not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") or not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") or not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") or game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == false
						if _G.Settings.Raids["Auto Awakened"] then	
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Awakener", "Awaken")
						end
					end)
				end           
			else
				if _G.Settings.Raids["Auto Awakened"] then	
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Awakener", "Awaken")
				end
				local L_460_ = {
					[1] = "RaidsNpc",
					[2] = "Select",
					[3] = tostring(_G.Settings.Raids["Select Raids"])
				}
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(L_460_))
			end
		end
	end
end)

spawn(function()
    while wait() do
        if _G.Settings.Raids["Kill Aura"] then
            for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                    pcall(function()
                        repeat wait(.3)
                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            v.Humanoid.Health = 0
                            --v:BreakJoints()
                            v.Humanoid:ChangeState(8)
                            v.HumanoidRootPart.CanCollide = false
                            v.HumanoidRootPart.Size = Vector3.new(80,80,80)
                            v.HumanoidRootPart.Transparency = 0 --1
                            if v.Humanoid:FindFirstChild("Animator") then
                                v.Humanoid.Animator:Destroy()
						    end
                        until not _G.Settings.Raids["Kill Aura"] or not _G.Settings.Raids["Auto Raids"] or not RaidSuperhuman or not v.Parent or v.Humanoid.Health <= 0
                    end)
                end
            end
        end
    end
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.Settings.Raids["Auto Next Place"] then
				if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == true and game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
					if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
						L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 5"].CFrame * CFrame.new(4, 65, 10))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
						L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 4"].CFrame * CFrame.new(4, 65, 10))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
						L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 3"].CFrame * CFrame.new(4, 65, 10))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
						L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 2"].CFrame * CFrame.new(4, 65, 10))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						L_3_func(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 1"].CFrame * CFrame.new(4, 65, 10))
					end
				elseif World2 then
					L_3_func(CFrame.new(- 6438.73535, 250.645355, - 4501.50684))
				elseif World3 then
					L_3_func(CFrame.new(- 5057.146484375, 314.54132080078, - 2934.7995605469))
				end
			end
		end
	end)
end)
--
LLLL:Label(" Open Menu ")

LLLL:Button("Fruit Inventory",function()
    local args = {
      [1] = "getInventoryFruits"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    game.Players.localPlayer.PlayerGui.Main.FruitInventory.Visible = true
end)

LLLL:Button("Devil Fruit Shop",function()
 local args = {
			[1] = "GetFruits"
		}
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
		game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)

LLLL:Label(" Auto Other ")

LLLL:Toggle("Auto Random Fruit",_G.Settings.Fruits["Auto Buy Random Fruits"],function(a)
	_G.Settings.Fruits["Auto Buy Random Fruits"] = a
	_G.AutoRandomFruit = a
	SaveSettings()
end)

spawn(function()
    while wait(1) do
        if _G.AutoRandomFruit then wait()
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
        end
    end
end)

LLLL:Button("Random Fruit", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
end)

LLLL:Toggle("Auto Store Fruit",_G.Settings.Fruits["Auto Store Fruits"],function(a)
	_G.Settings.Fruits["Auto Store Fruits"] = a
	getgenv().AutoStoreFruit = a
	SaveSettings()
end)

function DropFruit()
	pcall(function()
		game.Players.LocalPlayer.PlayerGui.Main.FruitInventory.Position = UDim2.new(10.100, 0, 0.100, 0) -- HideUi
		game.Players.LocalPlayer.PlayerGui.Main.FruitInventory.Visible = true -- เปิดไว้ถึงจะเช็คได้
		local invenfruit = game.Players.LocalPlayer.PlayerGui.Main.FruitInventory.Container.Stored.ScrollingFrame.Frame
		wait(.3)
		for i,v in pairs(invenfruit:GetChildren()) do
			if string.find(v.Name,"-") then
				for _,Backpack in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
					FruitStoreF = string.split(Backpack.Name, " ")[1]
					FruitStoreR = FruitStoreF.."-"..FruitStoreF
					if v.Name == FruitStoreR then
						game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(Backpack.Name):Destroy()
					end												
				end
			end
		end
		for i,v in pairs(invenfruit:GetChildren()) do
			if string.find(v.Name,"-") then
				for _,Character in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
					FruitStoreF = string.split(Character.Name, " ")[1]
					FruitStoreR = FruitStoreF.."-"..FruitStoreF
					if v.Name == FruitStoreR then
						game:GetService("Players").LocalPlayer.Character:FindFirstChild(Character.Name):Destroy()
					end												
				end
			end
		end
	end)
end
-- [AutoStoreFruit]
spawn(function()
	while wait(.1) do
		if getgenv().AutoStoreFruit then
			pcall(function()
				DropFruit()
				wait()
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bomb Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bomb Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Bomb-Bomb",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bomb Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bomb Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spike Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spike Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Spike-Spike",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spike Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spike Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Chop Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Chop Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Chop-Chop",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Chop Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Chop Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spring Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spring Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Spring-Spring",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spring Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spring Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Kilo Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Kilo Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Kilo-Kilo",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Kilo Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Kilo Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Smoke Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Smoke Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Smoke-Smoke",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Smoke Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Smoke Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spin Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spin Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Spin-Spin",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Spin Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Spin Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flame Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flame Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Flame-Flame",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flame Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flame Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bird: Falcon Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bird: Falcon Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Bird-Bird: Falcon",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bird: Falcon Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bird: Falcon Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Ice Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Ice Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Ice-Ice",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Ice Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Ice Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Sand Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Sand Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Sand-Sand",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Sand Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Sand Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dark Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dark Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Dark-Dark",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dark Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dark Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Revive Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Revive Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Revive-Revive",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Revive Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Revive Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Diamond Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Diamond Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Diamond-Diamond",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Diamond Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Diamond Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Light Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Light Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Light-Light",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Light Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Light Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Love Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Love Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Love-Love",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Love Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Love Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Rubber Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Rubber Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Rubber-Rubber",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Rubber Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Rubber Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Barrier Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Barrier Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Barrier-Barrier",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Barrier Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Barrier Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Magma Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Magma Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Magma-Magma",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Magma Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Magma Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Door Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Door Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Door-Door",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Door Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Door Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Quake Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Quake Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Quake-Quake",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Quake Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Quake Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Human-Human: Buddha Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Human-Human: Buddha Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Human-Human: Buddha",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Human-Human: Buddha Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Human-Human: Buddha Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("String Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("String Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","String-String",game:GetService("Players").LocalPlayer.Character:FindFirstChild("String Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("String Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bird: Phoenix Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bird: Phoenix Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Bird-Bird: Phoenix",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Bird: Phoenix Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Bird: Phoenix Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Rumble Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Rumble Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Rumble-Rumble",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Rumble Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Rumble Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Paw Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Paw Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Paw-Paw",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Paw Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Paw Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Gravity Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Gravity Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Gravity-Gravity",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Gravity Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Gravity Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dough Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dough Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Dough-Dough",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dough Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dough Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Shadow Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Shadow Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Shadow-Shadow",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Shadow Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Shadow Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Venom Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Venom Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Venom-Venom",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Venom Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Venom Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Control Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Control Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Control-Control",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Control Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Control Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Dragon-Dragon",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Fruit"))
				end
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Leopard Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Leopard Fruit") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit","Leopard-Leopard",game:GetService("Players").LocalPlayer.Character:FindFirstChild("Leopard Fruit") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Leopard Fruit"))
				end
			end)
		end
	end
end)

    FruitList = {
        "Bomb-Bomb",
        "Spike-Spike",
        "Chop-Chop",
        "Spring-Spring",
        "Kilo-Kilo",
        "Spin-Spin",
        "Bird: Falcon",
        "Smoke-Smoke",
        "Flame-Flame",
        "Ice-Ice",
        "Sand-Sand",
        "Dark-Dark",
        "Revive-Revive",
        "Diamond-Diamond",
        "Light-Light",
        "Love-Love",
        "Rubber-Rubber",
        "Barrier-Barrier",
        "Magma-Magma",
        "Door-Door",
        "Quake-Quake",
        "Human-Human: Buddha",
        "String-String",
        "Bird-Bird: Phoenix",
        "Rumble-Rumble",
        "Paw-Paw",
        "Gravity-Gravity",
        "Dough-Dough",
        "Venom-Venom",
        "Shadow-Shadow",
        "Control-Control",
        "Soul-Soul",
        "Dragon-Dragon",
        "Leopard Fruit"
    }
    
-- [AutoStoreFruit]
    spawn(function()
        pcall(function()
            while wait(.1) do
                if getgenv().AutoStoreFruit then
                    for i,v in pairs(FruitList) do
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StoreFruit",v)
                    end
                end
            end
        end)
    end)

if World1 then
    LLLL:Button("Tp to Npc Fruit", function()
        ByPass(CFrame.new(-1440.37183, 61.8519554, 5.73646641, -0.411858976, 2.60187889e-08, 0.911247611, 2.28359838e-08, 1, -1.82316917e-08, -0.911247611, 1.33003502e-08, -0.411858976))
        wait(5)
        L_3_func(CFrame.new(-1440.37183, 61.8519554, 5.73646641, -0.411858976, 2.60187889e-08, 0.911247611, 2.28359838e-08, 1, -1.82316917e-08, -0.911247611, 1.33003502e-08, -0.411858976))
    end)
end
if World2 then
    LLLL:Button("Tp to Npc Fruit", function()
        ByPass(CFrame.new(-423.566193, 73.8077087, 385.660858, -1, 0, 0, 0, 1, 0, 0, 0, -1))
        wait(5)
        L_3_func(CFrame.new(-423.566193, 73.8077087, 385.660858, -1, 0, 0, 0, 1, 0, 0, 0, -1))
    end)
end
if World3 then
    LLLL:Button("Tp to Npc Fruit", function()
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-12471.169921875, 374.94024658203, -7551.677734375))
        --ByPass(CFrame.new(-423.566193, 73.8077087, 385.660858, -1, 0, 0, 0, 1, 0, 0, 0, -1))
        wait(0.1)
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-12488.1338, 337.125702, -7445.08496, 0.707134247, 0, 0.707079291, 0, 1, 0, -0.707079291, 0, 0.707134247)
    end)
end

 LLLL:Toggle("Bring Fruit",_G.BringFruit,function(value)
 _G.BringFruit = value
    pcall(function()
        while _G.BringFruit do wait(.1)
            for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
                if v:IsA("Tool") then
                    local OldCFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame
                    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Handle.CFrame * CFrame.new(0,0,8)
                    v.Handle.CFrame = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame
                    wait(.1)
                    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = OldCFrame
                end
            end
        end
    end)
end)

 LLLL:Toggle("Teleport To Spawn Fruit",false,function(value)
 _G.Grabfruit = value
end)

spawn(function()
    while wait(.1) do
        if _G.Grabfruit then
            for i,v in pairs(game.Workspace:GetChildren()) do
                if string.find(v.Name, "Fruit") then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Handle.CFrame
                end
            end
        end
    end
end)

LLLL:Toggle("Bring All Fruit",_G.BringFruitBF,function(value)
  _G.BringFruitBF = value
end)
 
spawn(function()
    while wait() do
        if _G.BringFruitBF then
            pcall(function()
                for i,v in pairs(game.Workspace:GetChildren()) do
                    if v:IsA("Tool") then
                        v.Handle.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                    end
                end
            end)
        end
    end
end)
 
L_21_:Label("Fragments")

L_21_:Button("Buy Refund Stat",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Refund","1")
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Refund","2")
end)
L_21_:Button("Buy Random Race",function()
    local args = {
        [1] = "BlackbeardReward",
        [2] = "Reroll",
        [3] = "2"
    }
    
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
L_21_:Button("Buy Color Buso Haki",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ColorsDealer", "2")
end)

L_21_:Label("Bones")

    L_21_:Button("Buy Random Surprise",function()
        local args = {
            [1] = "Bones",
            [2] = "Check"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

        local args = {
            [1] = "Bones",
            [2] = "Buy",
            [3] = 1,
            [4] = 1
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end)
    
L_21_:Label("Buy Figthing Styles")

L_21_:Button("Electro",function(L_464_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
end)

L_21_:Button("Dark Step",function(L_463_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
end)

L_21_:Button("Water Kungfu",function(L_465_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
end)

L_21_:Label("Buy Figthing Styles v2")

L_21_:Button("Super Human",function(L_466_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
end)

L_21_:Button("Death Step",function(L_467_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)

L_21_:Button("Shark Man Karate",function(L_468_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
end)

L_21_:Button("Electric Claw",function(L_469_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
end)

L_21_:Button("Dragon Talon",function(L_470_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
end)

L_21_:Button("God Human",function(L_471_arg0)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman")
end)

L_21_:Label("Ability")

L_21_:Button("Buy SkyJump",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Geppo"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
L_21_:Button("Buy Soru",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Soru"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
L_21_:Button("Buy Haki",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Buso"
    }

    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))    
end)
L_21_:Button("Buy KenHaki",function()
    local args = {
        [1] = "KenTalk",
        [2] = "Buy"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

L_21_:Label("Sword")

L_21_:Button("Buy Katana",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Katana")
end)
L_21_:Button("Buy Cutlass",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cutlass")
end)
L_21_:Button("Buy Duel Katana",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Duel Katana")
end)
L_21_:Button("Buy Iron Mace",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Iron Mace")
end)
L_21_:Button("Buy Pipe",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Pipe")
end)
L_21_:Button("Buy Triple Katana",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Triple Katana")
end)
L_21_:Button("Buy Dual-Headed Blade",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Dual-Headed Blade")
end)
L_21_:Button("Buy Bisento",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Bisento")
end)
L_21_:Button("Buy Soul Cane",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Soul Cane")
end)

L_21_:Label("Gun")

L_21_:Button("Buy Slingshot",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Slingshot")
end)
L_21_:Button("Buy Musket",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Musket")
end)
L_21_:Button("Buy Fintlock",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Flintlock")
end)
L_21_:Button("Buy Refined Flintlock",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Refined Flintlock")
end)
L_21_:Button("Buy Cannon",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyItem","Cannon")
end)
L_21_:Button("Buy Kabucha",function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","1")
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","Slingshot","2")
end)

L_22_:Label("Server")

L_22_:Button("Rejoin Server",function()
    game.StarterGui:SetCore("SendNotification", {
        Title = "ReJoin Server", 
        Text = "Ready Go!",
        Icon = "http://www.roblox.com/asset/?id=12940626152",
        Duration = 10
    })
		game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").localPlayer)
end)

L_22_:Button("join Server",function()
    game.StarterGui:SetCore("SendNotification", {
        Title = "ReJoin Server", 
        Text = "Ready Go!",
        Icon = "http://www.roblox.com/asset/?id=12940626152",
        Duration = 10
    })
		game:GetService("TeleportService"):Teleport(game.PlaceId,game:GetService("Players").LocalPlayer)
end)

L_22_:Button("Hop Server",function()
    game.StarterGui:SetCore("SendNotification", {
        Title = "Hop Server", 
        Text = "Ready Go!",
        Icon = "http://www.roblox.com/asset/?id=12940626152",
        Duration = 10
    })
	Hop()
end)

-- [ Hop Function ]

function Hop()
	local L_70_ = game.PlaceId
	local L_71_ = {}
	local L_72_ = ""
	local L_73_ = os.date("!*t").hour
	local L_74_ = false
	function TPReturner()
		local L_75_;
		if L_72_ == "" then
			L_75_ = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. L_70_ .. '/servers/Public?sortOrder=Asc&limit=100'))
		else
			L_75_ = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. L_70_ .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. L_72_))
		end
		local L_76_ = ""
		if L_75_.nextPageCursor and L_75_.nextPageCursor ~= "null" and L_75_.nextPageCursor ~= nil then
			L_72_ = L_75_.nextPageCursor
		end
		local L_77_ = 0;
		for L_78_forvar0, L_79_forvar1 in pairs(L_75_.data) do
			local L_80_ = true
			L_76_ = tostring(L_79_forvar1.id)
			if tonumber(L_79_forvar1.maxPlayers) > tonumber(L_79_forvar1.playing) then
				for L_81_forvar0, L_82_forvar1 in pairs(L_71_) do
					if L_77_ ~= 0 then
						if L_76_ == tostring(L_82_forvar1) then
							L_80_ = false
						end
					else
						if tonumber(L_73_) ~= tonumber(L_82_forvar1) then
							local L_83_ = pcall(function()
								L_71_ = {}
								table.insert(L_71_, L_73_)
							end)
						end
					end
					L_77_ = L_77_ + 1
				end
				if L_80_ == true then
					table.insert(L_71_, L_76_)
					wait()
					pcall(function()
						wait()
						game:GetService("TeleportService"):TeleportToPlaceInstance(L_70_, L_76_, game.Players.LocalPlayer)
					end)
					wait(4)
				end
			end
		end
	end
	function Teleport()
		while wait() do
			pcall(function()
				TPReturner()
				if L_72_ ~= "" then
					TPReturner()
				end
			end)
		end
	end
	Teleport()
end

L_22_:Button("Hop Server Low Player",function()
    game.StarterGui:SetCore("SendNotification", {
        Title = "Hop Server Low Player", 
        Text = "Ready Go!",
        Icon = "http://www.roblox.com/asset/?id=12940626152",
        Duration = 10
    })
		getgenv().AutoTeleport = true
		getgenv().DontTeleportTheSameNumber = true
		getgenv().CopytoClipboard = false
		if not game:IsLoaded() then
			print("Game is loading waiting...")
		end
		local L_475_ = math.huge
		local L_476_;
		local L_477_;
		local L_478_ = "https://games.roblox.com/v1/games/" .. game.PlaceId .. "/servers/Public?sortOrder=Asc&limit=100"
		function serversearch()
			for L_479_forvar0, L_480_forvar1 in pairs(game:GetService("HttpService"):JSONDecode(game:HttpGetAsync(L_478_)).data) do
				if type(L_480_forvar1) == "table" and L_480_forvar1.playing ~= nil and L_475_ > L_480_forvar1.playing then
					L_476_ = L_480_forvar1.maxPlayers
					L_475_ = L_480_forvar1.playing
					L_477_ = L_480_forvar1.id
				end
			end
		end
		function getservers()
			serversearch()
			for L_481_forvar0, L_482_forvar1 in pairs(game:GetService("HttpService"):JSONDecode(game:HttpGetAsync(L_478_))) do
				if L_481_forvar0 == "nextPageCursor" then
					if L_478_:find("&cursor=") then
						local L_483_ = L_478_:find("&cursor=")
						local L_484_ = L_478_:sub(L_483_)
						L_478_ = L_478_:gsub(L_484_, "")
					end
					L_478_ = L_478_ .. "&cursor=" .. L_482_forvar1
					getservers()
				end
			end
		end
		getservers()
		if AutoTeleport then
			if DontTeleportTheSameNumber then
				if # game:GetService("Players"):GetPlayers() - 4 == L_475_ then
					return warn("It has same number of players (except you)")
				elseif L_477_ == game.JobId then
					return warn("Your current server is the most empty server atm")
				end
			end
			game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, L_477_)
		end
	end
)

L_22_:Label("Optimize Game")

L_22_:Button("Boost Fps",function(L_485_arg0)
		if not game:IsLoaded() then
			repeat
				wait()
			until game:IsLoaded()
		end
		if hookfunction and setreadonly then
			local L_490_ = getrawmetatable(game)
			local L_491_ = L_490_.__newindex
			setreadonly(L_490_, false)
			local L_492_
			L_492_ = hookfunction(L_491_, function(L_493_arg0, L_494_arg1, L_495_arg2)
				if L_494_arg1 == "Material" then
					if L_495_arg2 ~= Enum.Material.Neon and L_495_arg2 ~= Enum.Material.Plastic and L_495_arg2 ~= Enum.Material.ForceField then
						L_495_arg2 = Enum.Material.Plastic
					end
				elseif L_494_arg1 == "TopSurface" then
					L_495_arg2 = "Smooth"
				elseif L_494_arg1 == "Reflectance" or L_494_arg1 == "WaterWaveSize" or L_494_arg1 == "WaterWaveSpeed" or L_494_arg1 == "WaterReflectance" then
					L_495_arg2 = 0
				elseif L_494_arg1 == "WaterTransparency" then
					L_495_arg2 = 1
				elseif L_494_arg1 == "GlobalShadows" then
					L_495_arg2 = false
				end
				return L_492_(L_493_arg0, L_494_arg1, L_495_arg2)
			end)
			setreadonly(L_490_, true)
		end
		local L_486_ = game
		local L_487_ = L_486_.Workspace
		local L_488_ = L_486_:GetService"Lighting"
		local L_489_ = L_487_:WaitForChild"Terrain"
		L_489_.WaterWaveSize = 0
		L_489_.WaterWaveSpeed = 0
		L_489_.WaterReflectance = 0
		L_489_.WaterTransparency = 1
		L_488_.GlobalShadows = false
		function change(L_496_arg0)
			pcall(function()
				if L_496_arg0.Material ~= Enum.Material.Neon and L_496_arg0.Material ~= Enum.Material.Plastic and L_496_arg0.Material ~= Enum.Material.ForceField then
					pcall(function()
						L_496_arg0.Reflectance = 0
					end)
					pcall(function()
						L_496_arg0.Material = Enum.Material.Plastic
					end)
					pcall(function()
						L_496_arg0.TopSurface = "Smooth"
					end)
				end
			end)
		end
		game.DescendantAdded:Connect(function(L_497_arg0)
			pcall(function()
				if L_497_arg0:IsA"Part" then
					change(L_497_arg0)
				elseif L_497_arg0:IsA"MeshPart" then
					change(L_497_arg0)
				elseif L_497_arg0:IsA"TrussPart" then
					change(L_497_arg0)
				elseif L_497_arg0:IsA"UnionOperation" then
					change(L_497_arg0)
				elseif L_497_arg0:IsA"CornerWedgePart" then
					change(L_497_arg0)
				elseif L_497_arg0:IsA"WedgePart" then
					change(L_497_arg0)
				end
			end)
		end)
		for L_498_forvar0, L_499_forvar1 in pairs(game:GetDescendants()) do
			pcall(function()
				if L_499_forvar1:IsA"Part" then
					change(L_499_forvar1)
				elseif L_499_forvar1:IsA"MeshPart" then
					change(L_499_forvar1)
				elseif L_499_forvar1:IsA"TrussPart" then
					change(L_499_forvar1)
				elseif L_499_forvar1:IsA"UnionOperation" then
					change(L_499_forvar1)
				elseif L_499_forvar1:IsA"CornerWedgePart" then
					change(L_499_forvar1)
				elseif L_499_forvar1:IsA"WedgePart" then
					change(L_499_forvar1)
				end
			end)
		end
	end
)

L_22_:Button("Ultra Boost Fps",function(L_500_arg0)
		local Boost = true
		local krnl = game
		local work = krnl.Workspace
		local light = krnl.Lighting
		local L_505_ = work.Terrain
		L_505_.WaterWaveSize = 0
		L_505_.WaterWaveSpeed = 0
		L_505_.WaterReflectance = 0
		L_505_.WaterTransparency = 0
		light.GlobalShadows = false
		light.FogEnd = 9e9
		light.Brightness = 0
		settings().Rendering.QualityLevel = "Level01"
		for L_506_forvar0, L_507_forvar1 in pairs(krnl:GetDescendants()) do
			if L_507_forvar1:IsA("Part") or L_507_forvar1:IsA("Union") or L_507_forvar1:IsA("CornerWedgePart") or L_507_forvar1:IsA("TrussPart") then
				L_507_forvar1.Material = "Plastic"
				L_507_forvar1.Reflectance = 0
			elseif L_507_forvar1:IsA("Decal") or L_507_forvar1:IsA("Texture") and Boost then
				L_507_forvar1.Transparency = 1
			elseif L_507_forvar1:IsA("ParticleEmitter") or L_507_forvar1:IsA("Trail") then
				L_507_forvar1.Lifetime = NumberRange.new(0)
			elseif L_507_forvar1:IsA("Explosion") then
				L_507_forvar1.BlastPressure = 1
				L_507_forvar1.BlastRadius = 1
			elseif L_507_forvar1:IsA("Fire") or L_507_forvar1:IsA("SpotLight") or L_507_forvar1:IsA("Smoke") then
				L_507_forvar1.Enabled = false
			elseif L_507_forvar1:IsA("MeshPart") then
				L_507_forvar1.Material = "Plastic"
				L_507_forvar1.Reflectance = 0
				L_507_forvar1.TextureID = 10385902758728957
			end
		end
		for L_508_forvar0, L_509_forvar1 in pairs(L_504_:GetChildren()) do
			if L_509_forvar1:IsA("BlurEffect") or L_509_forvar1:IsA("SunRaysEffect") or L_509_forvar1:IsA("ColorCorrectionEffect") or L_509_forvar1:IsA("BloomEffect") or L_509_forvar1:IsA("DepthOfFieldEffect") then
				L_509_forvar1.Enabled = false
			end
		end
	end
)

L_22_:Button("Ultra ๆ Boost Fps",function(d)
    TextureLow()
    InvisibleObject()
    ObjectRemvoe()
    WaterRemvoe()
end)

function TextureLow()
	if not game:IsLoaded() then repeat wait() until game:IsLoaded() end
	if hookfunction and setreadonly then
		local mt = getrawmetatable(game)
		local old = mt.__newindex
		setreadonly(mt, false)
		local sda
		sda = hookfunction(old, function(t, k, v)
			if k == "Material" then
				if v ~= Enum.Material.Neon and v ~= Enum.Material.Plastic and v ~= Enum.Material.ForceField then v = Enum.Material.Plastic end
			elseif k == "TopSurface" then v = "Smooth"
			elseif k == "Reflectance" or k == "WaterWaveSize" or k == "WaterWaveSpeed" or k == "WaterReflectance" then v = 0
			elseif k == "WaterTransparency" then v = 1
			elseif k == "GlobalShadows" then v = false end
			return sda(t, k, v)
		end)
		setreadonly(mt, true)
	end
	local g = game
	local w = g.Workspace
	local l = g:GetService"Lighting"
	local t = w:WaitForChild"Terrain"
	t.WaterWaveSize = 0
	t.WaterWaveSpeed = 0
	t.WaterReflectance = 0
	t.WaterTransparency = 1
	l.GlobalShadows = false
	function change(v)
		pcall(function()
			if v.Material ~= Enum.Material.Neon and v.Material ~= Enum.Material.Plastic and v.Material ~= Enum.Material.ForceField then
				pcall(function() v.Reflectance = 0 end)
				pcall(function() v.Material = Enum.Material.Plastic end)
				pcall(function() v.TopSurface = "Smooth" end)
			end
		end)
	end
	game.DescendantAdded:Connect(function(v)
		pcall(function()
			if v:IsA"Part" then change(v)
			elseif v:IsA"MeshPart" then change(v)
			elseif v:IsA"TrussPart" then change(v)
			elseif v:IsA"UnionOperation" then change(v)
			elseif v:IsA"CornerWedgePart" then change(v)
			elseif v:IsA"WedgePart" then change(v) end
		end)
	end)
	for i, v in pairs(game:GetDescendants()) do
		pcall(function()
			if v:IsA"Part" then change(v)
			elseif v:IsA"MeshPart" then change(v)
			elseif v:IsA"TrussPart" then change(v)
			elseif v:IsA"UnionOperation" then change(v)
			elseif v:IsA"CornerWedgePart" then change(v)
			elseif v:IsA"WedgePart" then change(v) end
		end)
	end
end

function WaterRemvoe()
	for i,v in pairs(workspace:GetDescendants()) do
		if string.find(v.Name,"Water") then
			v:Destroy()
		end
	end
end

function ObjectRemvoe()
	for i,v in pairs(workspace:GetDescendants()) do
		if string.find(v.Name,"Tree") or string.find(v.Name,"House") then
			v:Destroy()
		end
	end
end

function InvisibleObject()
	for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
        if  (v:IsA("Part") or v:IsA("MeshPart") or v:IsA("BasePart")) and v.Transparency then
            v.Transparency = 1
        end
    end
end

L_22_:Toggle("White Screen | จอขาว",_G.Settings.Configs["White|Screen"],function(v)
	_G.Settings.Configs["White|Screen"] = v
	SaveSettings()
end)

spawn(function()
	while wait() do
		if _G.Settings.Configs["White|Screen"] then
			game:GetService("RunService"):Set3dRenderingEnabled(false)
		else
			game:GetService("RunService"):Set3dRenderingEnabled(true)
		end
	end
end)

L_22_:Toggle("Black Screen | จอดำ",_G.Settings.Configs["Black|Screen"],function(v)
	_G.Settings.Configs["Black|Screen"] = v
	SaveSettings()
end)

spawn(function()
	while wait() do
		if _G.Settings.Configs["Black|Screen"] then
			game:GetService("Players").LocalPlayer.PlayerGui.Main.Blackscreen.Size = UDim2.new(500, 0, 500, 500)
		else
			game:GetService("Players").LocalPlayer.PlayerGui.Main.Blackscreen.Size = UDim2.new(1, 0, 500, 500)
		end
	end
end)

L_22_:Label("Community")

L_22_:Button("Click to Copy Link Youtube",function(L_512_arg0)
	setclipboard("https://www.youtube.com/@MrMaxNaJaa")
end)

L_22_:Button("Click to Copy Link Facebook",function(L_514_arg0)
	setclipboard("https://www.facebook.com/MrMaxNaJa")
end)

L_22_:Button("Click to Copy Link Discord",function(L_513_arg0)
	setclipboard("https://discord.gg/6qwRAxNfpz")
end)

--[[

function SetupCharCollide(Char)
    CharParts = {}
    Char:WaitForChild("Head")
    for i, v in pairs(Char:GetChildren()) do
        if v:IsA("BasePart") then
            table.insert(CharParts, v)
        end
    end
end

if game.Players.LocalPlayer.Character then
    SetupCharCollide(game.Players.LocalPlayer.Character)
end
game.Players.LocalPlayer.CharacterAdded:connect(function(Ch)
    SetupCharCollide(Ch)
end)]]

local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
_G.Settings.Misc['Auto Rejoin'] = true
spawn(function()
	while wait() do
		if _G.Settings.Misc['Auto Rejoin'] then
			_G.Settings.Misc['Auto Rejoin'] = game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(v)
				if v.Name == 'ErrorPrompt' and v:FindFirstChild('MessageArea') and v.MessageArea:FindFirstChild("ErrorFrame") then
					print("Auto Rejoin!")
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end
end)

-- [Remove Quest Dead]
spawn(function()
	while wait() do
		pcall(function()
			if game.Players.LocalPlayer.Character:WaitForChild("Humanoid"):GetState() == Enum.HumanoidStateType.Dead then 
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
					repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
				end
			end
		end)
	end
end)
----------------------------------------------------------------------------------------------------------------------------------------------

    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.Particle.SlashHit).playAt = function() return nil end;
    getgenv().A = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync 
    getgenv().B = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.Particle).play
    spawn(function()
        while wait() do
            if _G.FastAttackNormalSpeed then
                pcall(function()
                    require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync =function(a1,a2,a3,a4,a5)
                        local GetBladeHits = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).getBladeHits(a2,a3,a4)
                        if GetBladeHits then
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = function() end;
                            a1:Play(0.1, 0.1, 0.1);
                            a5(GetBladeHits);
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = getgenv().B 
                            wait(.5);
                            a1:Stop();
                        end;
                    end;
                end);
            end
        end;
    end);
    
-- [[ Fast Attack Fixed / Shadow Hub / Dont edit , or ur will be messed up! ]]

-- [[ Properties ]]

require(game.ReplicatedStorage.Util.CameraShaker):Stop()

xShadowFastAttackx = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)

xShadowx = debug.getupvalues(xShadowFastAttackx)[2]

spawn(function()
    game:GetService("RunService").RenderStepped:Connect(function()
        if _G.FastAttackNormalSpeed or _G.FastAttack then
            if typeof(xShadowx) == "table" then
                pcall(function()
                    xShadowx.activeController.timeToNextAttack = (math.huge^math.huge^math.huge)
                    xShadowx.activeController.timeToNextAttack = 0
                    xShadowx.activeController.hitboxMagnitude = 200
                    xShadowx.activeController.active = false
                    xShadowx.activeController.timeToNextBlock = 0
                    xShadowx.activeController.focusStart = 0
                    xShadowx.activeController.increment = 4
                    xShadowx.activeController.blocking = false
                    xShadowx.activeController.attacking = false
                    xShadowx.activeController.humanoid.AutoRotate = 50
                    game:GetService'VirtualUser':CaptureController()
					game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                end)
            end
        end
    end)
end)


            local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
            local VirtualUser = game:GetService('VirtualUser')
            local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
            local Client = game:GetService("Players").LocalPlayer
            local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
            
            function SeraphFuckWeapon() 
                local p13 = SeraphFrame.activeController
                local wea = p13.blades[1]
                if not wea then return end
                while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
                return wea
            end
            
            function getHits(Size)
                local Hits = {}
                local Enemies = workspace.Enemies:GetChildren()
                local Characters = workspace.Characters:GetChildren()
                for i=1,#Enemies do local v = Enemies[i]
                    local Human = v:FindFirstChildOfClass("Humanoid")
                    if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
                        table.insert(Hits,Human.RootPart)
                    end
                end
                for i=1,#Characters do local v = Characters[i]
                    if v ~= game.Players.LocalPlayer.Character then
                        local Human = v:FindFirstChildOfClass("Humanoid")
                        if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
                            table.insert(Hits,Human.RootPart)
                        end
                    end
                end
                return Hits
            end
            
            task.spawn(
                function()
                while wait(0) do
                    if  _G.FastAttackNormalSpeed or _G.FastAttack then
                        if SeraphFrame.activeController then
                            if v.Humanoid.Health > 0 then
                              SeraphFrame.activeController.attacking = false
                                SeraphFrame.activeController.timeToNextBlock = 0
                               SeraphFrame.activeController.humanoid.AutoRotate = true
                               SeraphFrame.activeController.increment = 3
                               SeraphFrame.activeController.blocking = false
                               SeraphFrame.activeController.hitboxMagnitude = 150
                                SeraphFrame.activeController.timeToNextAttack = 0
                                SeraphFrame.activeController.focusStart = 0
                                SeraphFrame.activeController.humanoid.AutoRotate = true
                                SeraphFrame.activeController.increment = 1 + 1 / 1
                             end
                        end
                    end
                end
            end)
            
            function Boost()
                spawn(function()
                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
                end)
            end
            
            function Unboost()
                spawn(function()
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
                end)
            end
            
            local cdnormal = 9e9
            local Animation = Instance.new("Animation")
            local CooldownFastAttack = 0
            Attack = function()
                local ac = SeraphFrame.activeController
                if ac and ac.equipped then
                    task.spawn(
                        function()
                        if tick() - cdnormal > 9e9 then
                            ac:attack()
                            cdnormal = tick()
                        else
                             Animation.AnimationId = ac.anims.basic[2]
                            ac.humanoid:LoadAnimation(Animation):Play(100, 99) --(1,1)
                            game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
                        end
                    end)
                end
            end
            
            b = tick()
            spawn(function()
                while wait(0) do
                    if  _G.FastAttack then
                        if b - tick() > 0.3 then
                            wait(.1)
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then
                                        Attack()
                                        wait(0)
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            b = tick()
            spawn(function()
                while wait(0) do
                    if  _G.FastAttackNormalSpeed then
                        if b - tick() > 0.75 then
                            wait(.2)
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then
                                        Attack()
                                        wait(0)
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            k = tick()
            spawn(function()
                while wait(0) do
                    if  _G.FastAttackNormalSpeed then
                        if k - tick() > 0.75 then
                            wait(0)
                            k = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then
                                    wait(0)
                                    Unboost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            --_G.FastAttackNormalSpeed = true
            task.spawn(
                function()
                    local a = game.Players.LocalPlayer
                    local b = require(a.PlayerScripts.CombatFramework.Particle)
                    local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
                    if not shared.orl then
                        shared.orl = c.wrapAttackAnimationAsync
                    end
                    if not shared.cpc then
                        shared.cpc = b.play
                    end
                    if _G.FastAttackNormalSpeed then
                        pcall(
                            function()
                                c.wrapAttackAnimationAsync = function(d, e, f, g, h)
                                    local i = c.getBladeHits(e, f, g)
                                    if i then
                                        b.play = function()
                                        end
                                        d:Play(15.25, 15.25, 15.25)
                                        h(i)
                                        b.play = shared.cpc
                                        wait(0)
                                        d:Stop()
                                    end
                                end
                            end
                        )
                    end
                end
            )
            
            
            local Client = game.Players.LocalPlayer
            local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
            local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
            task.spawn(function()
                pcall(function()
                    if not shared.orl then
                        shared.orl = STOPRL.wrapAttackAnimationAsync
                    end
                        if not shared.cpc then
                            shared.cpc = STOP.play 
                        end
                    spawn(function()
                    require(game.ReplicatedStorage.Util.CameraShaker):Stop()
                  require(game.ReplicatedStorage.Util.CameraShaker):Stop()
                        game:GetService("RunService").Stepped:Connect(function()
                            STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                                local Hits = STOPRL.getBladeHits(b,c,d)
                                if Hits then
                                    if  _G.FastAttackNormalSpeed then
                                        STOP.play = function() end
                                        a:Play(20.1,15.1,10.1)
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * .0)
                                        a:Stop()
                                    else
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * .0)
                                        a:Stop()
                                    end
                                end
                            end
                        end)
                    end)
                end)
                end)


            local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
            local VirtualUser = game:GetService('VirtualUser')
            local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
            local Client = game:GetService("Players").LocalPlayer
            local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
            
            function SeraphFuckWeapon() 
                local p13 = SeraphFrame.activeController
                local wea = p13.blades[1]
                if not wea then return end
                while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
                return wea
            end
            
            function getHits(Size)
                local Hits = {}
                local Enemies = workspace.Enemies:GetChildren()
                local Characters = workspace.Characters:GetChildren()
                for i=1,#Enemies do local v = Enemies[i]
                    local Human = v:FindFirstChildOfClass("Humanoid")
                    if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
                        table.insert(Hits,Human.RootPart)
                    end
                end
                for i=1,#Characters do local v = Characters[i]
                    if v ~= game.Players.LocalPlayer.Character then
                        local Human = v:FindFirstChildOfClass("Humanoid")
                        if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+55 then
                            table.insert(Hits,Human.RootPart)
                        end
                    end
                end
                return Hits
            end
            
            task.spawn(
                function()
                while wait() do
                    if  _G.FastAttackNormalSpeed then
                        if SeraphFrame.activeController then
                            if v.Humanoid.Health > 0 then
                                SeraphFrame.activeController.timeToNextAttack = 2
                                SeraphFrame.activeController.focusStart = 0
                                SeraphFrame.activeController.hitboxMagnitude = 110
                                SeraphFrame.activeController.humanoid.AutoRotate = true
                                SeraphFrame.activeController.increment = 3 + 3 / 3
                             end
                        end
                    end
                end
            end)
            
            function Boost()
                spawn(function()
                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
                end)
            end
            
            function Unboost()
                spawn(function()
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
                end)
            end
            
            local cdnormal = 9e9
            local Animation = Instance.new("Animation")
            local CooldownFastAttack = 0
            Attack = function()
                local ac = SeraphFrame.activeController
                if ac and ac.equipped then
                    task.spawn(
                        function()
                        if tick() - cdnormal > 9e9 then
                            ac:attack()
                            cdnormal = tick()
                        else
                             Animation.AnimationId = ac.anims.basic[2]
                            ac.humanoid:LoadAnimation(Animation):Play(0, 0) --ท่าไม่ทำงานแก้เป็น (1,1)
                            game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
                        end
                    end)
                end
            end
            
            b = tick()
            spawn(function()
                while _G.FastAttackNormalSpeed do
                    if _G.FastAttackNormalSpeed then
                        if b - tick() > 9e9 then
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 50 then
                                        Attack()
                                        wait()
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            k = tick()
            spawn(function()
                while wait() do
                    if  _G.FastAttackNormalSpeed then
                        if k - tick() > 9e9 then
                            k = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 50 then
                                    Unboost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            --_G.FastAttackNormalSpeed = true
            task.spawn(
                function()
                    local a = game.Players.LocalPlayer
                    local b = require(a.PlayerScripts.CombatFramework.Particle)
                    local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
                    if not shared.orl then
                        shared.orl = c.wrapAttackAnimationAsync
                    end
                    if not shared.cpc then
                        shared.cpc = b.play
                    end
                    if _G.FastAttackNormalSpeed then
                        pcall(
                            function()
                                c.wrapAttackAnimationAsync = function(d, e, f, g, h)
                                    local i = c.getBladeHits(e, f, g)
                                    if i then
                                        b.play = function()
                                        end
                                        d:Play(25.25, 20.25, 23)
                                        h(i)
                                        b.play = shared.cpc
                                        wait(9e9)
                                        d:Stop()
                                    end
                                end
                            end
                        )
                    end
                end
            )
            
            
function AttackFunction()
	local ac = CombatFrameworkR.activeController
	if ac and ac.equipped then
		for indexincrement = 1, 1 do
			local bladehit = getAllBladeHits(60)
			if #bladehit > 0 then
				local AcAttack8 = debug.getupvalue(ac.attack, 5)
				local AcAttack9 = debug.getupvalue(ac.attack, 6)
				local AcAttack7 = debug.getupvalue(ac.attack, 4)
				local AcAttack10 = debug.getupvalue(ac.attack, 7)
				local NumberAc12 = (AcAttack8 * 798405 + AcAttack7 * 727595) % AcAttack9
				local NumberAc13 = AcAttack7 * 798405
				(function()
					NumberAc12 = (NumberAc12 * AcAttack9 + NumberAc13) % 1099511627776
					AcAttack8 = math.floor(NumberAc12 / AcAttack9)
					AcAttack7 = NumberAc12 - AcAttack8 * AcAttack9
				end)()
				AcAttack10 = AcAttack10 + 1
				debug.setupvalue(ac.attack, 5, AcAttack8)
				debug.setupvalue(ac.attack, 6, AcAttack9)
				debug.setupvalue(ac.attack, 4, AcAttack7)
				debug.setupvalue(ac.attack, 7, AcAttack10)
				for k, v in pairs(ac.animator.anims.basic) do
					v:Play(20,10.01,10)
				end                 
				if game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and ac.blades and ac.blades[1] then 
					game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(CurrentWeapon()))
					game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(NumberAc12 / 1099511627776 * 16777215), AcAttack10)
					game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, 2, "") 
				end
			end
		end
	end
end

            local Client = game.Players.LocalPlayer
            local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
            local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
            task.spawn(function()
                pcall(function()
                    if not shared.orl then
                        shared.orl = STOPRL.wrapAttackAnimationAsync
                    end
                        if not shared.cpc then
                            shared.cpc = STOP.play 
                        end
                    spawn(function()
                    require(game.ReplicatedStorage.Util.CameraShaker):Stop()
                  require(game.ReplicatedStorage.Util.CameraShaker):Stop()
                        game:GetService("RunService").Stepped:Connect(function()
                            STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                                local Hits = STOPRL.getBladeHits(b,c,d)
                                if Hits then
                                    if  _G.FastAttackNormalSpeed then
                                        STOP.play = function() end
                                        a:Play(21,29,30)
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0)
                                        a:Stop()
                                    else
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0)
                                        a:Stop()
                                    end
                                end
                            end
                        end)
                    end)
                end)
                end)

if World3 then
local Moon = {
['8'] = "http://www.roblox.com/asset/?id=9709149431", -- 🌕
['7'] = "http://www.roblox.com/asset/?id=9709149052", -- 🌖
['6'] = "http://www.roblox.com/asset/?id=9709143733", -- 🌗
['5'] = "http://www.roblox.com/asset/?id=9709150401", -- 🌘
['4'] = "http://www.roblox.com/asset/?id=9709135895",  -- 🌑
['3'] = "http://www.roblox.com/asset/?id=9709139597", -- 🌒
['2'] = "http://www.roblox.com/asset/?id=9709150086", -- 🌓
['1'] = "http://www.roblox.com/asset/?id=9709149680", -- 🌔
};
for i,v in pairs(Moon) do
	if game:GetService("Lighting").Sky.MoonTextureId == v then
		MoonPercent = i / 8 * 100
	end
end

for i,v in pairs(game.Players:GetPlayers()) do
	PlayersMin = i
end

if game:GetService("Lighting").Sky.MoonTextureId == Moon['1'] then
	MoonIcon = '🌔'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['2'] then
	MoonIcon = '🌓'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['3'] then
	MoonIcon = '🌒'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['4'] then
	MoonIcon = '🌑'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['5'] then
	MoonIcon = '🌘'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['6'] then
	MoonIcon = '🌗'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['7'] then
	MoonIcon = '🌖'
elseif game:GetService("Lighting").Sky.MoonTextureId == Moon['8'] then
	MoonIcon = '🌕'
end
if game.Workspace._WorldOrigin.Locations:FindFirstChild('Mirage Island') then
	MirageMessage = '```Mirage is spawing : ✔```'
else
	MirageMessage = '```Mirage isn\'t spawn : ❌```'
end
local UserPy = game.Players.LocalPlayer.Name
--local pfp = "https://www.roblox.com/headshot-thumbnail/image?userId=".. game.Players.LocalPlayer.UserId .."&width=420&height=420&format=png"
MoonMessage = '```'..tostring(MoonPercent..'%'..' : '..MoonIcon)..'```'
JoinServer = 'game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId,'..'\''..tostring(game.JobId)..'\''..')'
print('\n'..MoonMessage..'\n'..MirageMessage..'\n'..JoinServer.. '\n' ..UserPy)

local url = "https://discord.com/api/webhooks/1097750498368561214/rBW7WhpCGXrgWCKa0qLb_Qxn4B2cB8jKZwxYC1wt_GRQW136j2L16wkK4t51XDhv8Kkh" --"https://discord.com/api/webhooks/1097750498368561214/rBW7WhpCGXrgWCKa0qLb_Qxn4B2cB8jKZwxYC1wt_GRQW136j2L16wkK4t51XDhv8Kkh" -- ur webhook url
local data = {
	["username"] = 'NaJa Hub', -- Webhook name here
	['content'] = '<@&1010573035306229893>', -- ping everyone if you want to ping role use this <@&1007291553074647132> 
	["avatar_url"] = "https://cdn.discordapp.com/attachments/948603231192363058/1088077196997955704/Untitled-1_copy.png", -- ur discord logo url
	["embeds"] = {
		{
			["description"] = "**__Moon and Mirage Webhook__**",
			["color"] = tonumber(0x00ff00), -- color id		
			["type"] = "rich",
			["fields"] =  {
			    {
					["name"] = "[🕑] Moon Check",
					["value"] = MoonMessage,
					["inline"] = true
				},
				{
					["name"] = "[🌲] Mirage Check",
					["value"] = MirageMessage,
					["inline"] = true
				},
				{
					["name"] = "[👥] Players Active",
					["value"] = '```'..tostring(PlayersMin)..'/12```'
				},
				{
					["name"] = "[📃] JobID",
					["value"] = '```'..tostring(game.JobId)..'```'
				},
				{
					["name"] = "[📁] Join Server",
					["value"] = '```'..JoinServer..'```',
				}
				
			},
			["footer"] = {
				["text"] = 'ผู้ค้นเจอ '..UserPy, -- you can remove this but it will hurt "Webhook By Toshi#2667"
			},
			["timestamp"] = DateTime.now():ToIsoDate(),
		}
	},
}
local newdata = game:GetService("HttpService"):JSONEncode(data)
local headers = {["content-type"] = "application/json"}
request = http_request or request or HttpPost or syn.request
local abcdef = {Url = url, Body = newdata, Method = "POST", Headers = headers}
request(abcdef)
end

----------------------------------------------------------------------------------------------------------------------------------------------
print("UI.ok")
print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")print("ok all")

    local requesthttps
    if syn then
        requesthttps = syn.request
        print("syn")
    elseif KRNL_LOADED then
        requesthttps = request
        print("KRNL_LOADED")
    else
        requesthttps = fluxus.request
        print("fluxus")
    end
