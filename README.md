local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/zxciaz/VenyxUI/main/Reuploaded"))() --someone reuploaded it so I put it in place of the original back up so guy can get free credit.
local venyx = library.new("J hub", 5013109572)

local page = venyx:addPage("Menu", 5012544693)
local section1 = page:addSection("Menu")

section1:addToggle("Auto click", nil, function(value)
_G.click = value
while _G.click do wait()
local A_1 = "Click" local Event = game:GetService("Players").MAC50656.PlayerGui.SCRIPTS.PunchV2.Function Event:FireServer(A_1)
end
end)
section1:addToggle("Auto win", nil, function(value)
_G.TPwin = value
while _G.TPwin do wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1.64244461, 0.913009644, 984497.375, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end
end)
section1:addToggle("Auto rebirth", nil, function(value)
_G.rebirth = value
while _G.rebirth do wait()
local Event = game:GetService("ReplicatedStorage").GameClient.Events.RemoteEvent.UpdateRebirth
Event:FireServer()
end
end)
