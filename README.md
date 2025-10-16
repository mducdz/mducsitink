local ScreenGui = Instance.new("ScreenGui")
local ImageButton = Instance.new("ImageButton")
local UICorner = Instance.new("UICorner")

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageButton.Parent = ScreenGui
ImageButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.10615778, 0, 0.16217947, 0)
ImageButton.Size = UDim2.new(0, 40, 0, 40)
ImageButton.Draggable = true
ImageButton.Image = "http://www.roblox.com/asset/?id=83190276951914"

UICorner.CornerRadius = UDim.new(1, 10) 
UICorner.Parent = ImageButton

ImageButton.MouseButton1Down:Connect(function()
    game:GetService("VirtualInputManager"):SendKeyEvent(true, Enum.KeyCode.End, false, game)
end)

local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
repeat wait() until game:IsLoaded()
local Window = Fluent:CreateWindow({
    Title = "MducDepZai Hub",
    SubTitle = "by realmduc",
    TabWidth = 157,
    Size = UDim2.fromOffset(450, 300),
    Acrylic = true,
    Theme = "Blue",
    MinimizeKey = Enum.KeyCode.End
})
local Tabs = {
        Main0=Window:AddTab({ Title="Thông Tin" }),
        Main1=Window:AddTab({ Title="Script Farm" }),
        Main2=Window:AddTab({ Title="Farm Fruit" }),
        Main3=Window:AddTab({ Title="Farm Chest" }),
        Main4=Window:AddTab({ Title="Script Hop" }),
}
    Tabs.Main0:AddButton({
    Title = "Discord",
    Description = "TBoyRoblox Community",
    Callback = function()
        setclipboard("https://discord.gg/tboyroblox-community-1253927333920899153")
    end
})

    Tabs.Main0:AddButton({
    Title = "Youtuber",
    Description = "TBoy Roblox",
    Callback = function()
        setclipboard("https://www.youtube.com/@TBoyRoblox08")
    end
})

    Tabs.Main0:AddButton({
    Title = "Youtuber",
    Description = "TBoy Gamer",
    Callback = function()
        setclipboard("https://www.youtube.com/@TBoyGamer08")
    end
})
    
    Tabs.Main1:AddButton({
    Title="maru Hub",
    Description="",
    Callback=function()
	 getgenv().Key = "MARU-CQSXE-C5SH-RNNL-63PPP-Q12TI"
getgenv().id = "1402257125400514651"
loadstring(game:HttpGet("https://raw.githubusercontent.com/xshiba/MaruBitkub/main/Mobile.lua"))()
  end
})

Tabs.Main1:AddButton({
    Title="Speed Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
	end
}) 

Tabs.Main1:AddButton({
    Title="Matsune New Hub",
    Description="",
    Callback=function() 
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Yatsuraa/Matsune/main/Matsunebeta.lua"))()
    end    
})
	
Tabs.Main2:AddButton({
    Title=" New Hub",
    Description="",
    Callback=function() 
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/GalaxyTeamHub/Galaxy-Hub/main/GalaxyBloxFruit.lua"))()
	end
})	

Tabs.Main0:AddButton({
    Title = "key speed hub vv(cs thể bị fix)",
    Description = "",
    Callback = function()
        setclipboard(rMChVgMZYJYHMGNtMvYkvDKasUFztRuG)
