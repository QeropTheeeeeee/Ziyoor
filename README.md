	-- Loaded9999

local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Loaded9999", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Loaded9999",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Universal"
})

Tab:AddButton({
	Name = "The Upgrade Tree Of Tree",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/Moligrafi001/Hallow-Hub/main/games/The%20Upgrade%20Tree%20Of%20Tree.lua",true))()
		end    
})

Tab:AddButton({
	Name = "Every Second You Get +1 IQ🧠",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/ghostiki/Every_Sec_1iq_slower/refs/heads/main/every_sec_1iq.lua"))()
		end    
})

Tab:AddButton({
	Name = "🎁 XMAS &amp; SHELBY! Car Dealership Tycoon",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraScript/Script/main/CarDealershipXMAS"))()
		end    
})

Tab:AddButton({
	Name = "1 minute tower",
	Callback = function()
      		print("button pressed")
			  game:GetService("ReplicatedStorage").ApplyTime:FireServer("55.001")
		end    
})

Tab:AddButton({
	Name = "Snow Plow Simulator",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/Moligrafi001/Hallow-Hub/main/Loader.lua",true))()
		end    
})

Tab:AddButton({
	Name = "Egg Empire 🐣 [UPD]",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/VateqS/MinionHub/main/egg_empire_v2"))()
		end    
})

Tab:AddButton({
	Name = "🧸TOY STORY! Brawl Stars RNG",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet(('https://raw.githubusercontent.com/Subjoel/subjoel-s-script-hub/refs/heads/main/brawlstarsRNG.lua')))()
		end    
})

Tab:AddButton({
	Name = "STEAL DA KITTY",
	Callback = function()
      		print("button pressed")
			  game:GetService("ReplicatedStorage").GivePoints:FireServer(99999999999999)
		end    
})

Tab:AddButton({
	Name = "[⭐X5] Clicking Masters",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet(("https://raw.githubusercontent.com/AppleScript001/Clicking_Masters/refs/heads/main/README.md"),true))()
		end    
})

Tab:AddButton({
	Name = "Make and Sell Cars",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://pastefy.app/S8ARweEz/raw"))()
		end    
})

Tab:AddButton({
	Name = "Punch Tha Santa",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/SpineWare/UniversalLoader/refs/heads/main/Load"))()
		end    
})

Tab:AddButton({
	Name = "[🎅CHRISTMAS!🎅] Clicking Universe!",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet(("https://raw.githubusercontent.com/AppleScript001/Clicking-Universe-/refs/heads/main/README.md"),true))()
		end    
})

Tab:AddButton({
	Name = "⚡Ninja Legends",
	Callback = function()
      		print("button pressed")
			  --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Verified Scripter/Badge ECT",
    SubTitle = "by dawid",
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true,
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main", Icon = "" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

local autoSellEnabled = false
local autoSwingEnabled = false

Tabs.Main:AddToggle("Auto Sell", {
    Title = "Auto Sell",
    Description = "Toggles Auto Sell functionality.",
    Default = false,
    Callback = function(state)
        autoSellEnabled = state
        if state then
            print("Auto Sell Enabled")
        else
            print("Auto Sell Disabled")
        end
    end
})

Tabs.Main:AddToggle("Auto Swing", {
    Title = "Auto Swing",
    Description = "Toggles Auto Swing functionality.",
    Default = false,
    Callback = function(state)
        autoSwingEnabled = state
        if state then
            print("Auto Swing Enabled")
        else
            print("Auto Swing Disabled")
        end
    end
})

spawn(function()
    while true do
        task.wait(0.1)
        if autoSellEnabled then
            local player = game:GetService("Players").LocalPlayer
            local playerGui = player:FindFirstChild("PlayerGui")
            local gameGui = playerGui and playerGui:FindFirstChild("gameGui")
            local maxNinjitsuMenu = gameGui and gameGui:FindFirstChild("maxNinjitsuMenu")

            if maxNinjitsuMenu then
                local sellAreaCircle = workspace:FindFirstChild("sellAreaCircles") and
                                       workspace.sellAreaCircles:FindFirstChild("sellAreaCircle") and
                                       workspace.sellAreaCircles.sellAreaCircle:FindFirstChild("circleInner")
                
                if sellAreaCircle and sellAreaCircle:FindFirstChild("TouchInterest") then
                    firetouchinterest(player.Character.HumanoidRootPart, sellAreaCircle, 0)
                    task.wait(0.1)
                    firetouchinterest(player.Character.HumanoidRootPart, sellAreaCircle, 1)
                end
            end
        end
    end
end)

spawn(function()
    while true do
        task.wait()
        if autoSwingEnabled then
            local args = {
                [1] = "swingKatana"
            }
            game:GetService("Players").LocalPlayer:WaitForChild("ninjaEvent"):FireServer(unpack(args))
        end
    end
end)
		end    
})

Tab:AddButton({
	Name = "",
	Callback = function()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "[❄UPDATE 6.1] Anime Power Defense",
	Callback = function()
      		print("button pressed")
			  loadstring(game:HttpGet("https://raw.githubusercontent.com/LosHUB/L-HUB/refs/heads/main/L-HUB-ON-TOP"))()
		end    
})
