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
        Main1=Window:AddTab({ Title="Script Blox Fruit" }),
        Main2=Window:AddTab({ Title="Script Grow A Garden" }),
        Main3=Window:AddTab({ Title="Script Steal A Brainot" }),
        Main4=Window:AddTab({ Title="Script 99 Night" }),
		Main5=Window:AddTab({ Title="Script Plants Vs Brainot" }),
		Main6=Window:AddTab({ Title="KEY HUB VV" }),
}
    Tabs.Main0:AddButton({
    Title = "Discord",
    Description = "DUCZ GROUP",
    Callback = function()
        setclipboard("https://discord.gg/tboyroblox-community-1253927333920899153")
    end
})

    Tabs.Main0:AddButton({
    Title = "Youtuber",
    Description = "DUCZ Roblox",
    Callback = function()
        setclipboard("https://www.youtube.com/@TBoyRoblox08")
    end
})

    Tabs.Main0:AddButton({
    Title = "Youtuber",
    Description = "DUCZ ROBLOX",
    Callback = function()
        setclipboard("https://www.youtube.com/@TBoyGamer08")
    end
})
    
    Tabs.Main1:AddButton({
    Title="W Azure Hub",
    Description="",
    Callback=function()
	 loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/85e904ae1ff30824c1aa007fc7324f8f.lua"))()
  end
})

Tabs.Main1:AddButton({
    Title="Speed Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
	end
}) 

Tabs.Main3:AddButton({
    Title="Lurk Hub",
    Description="",
    Callback=function() 
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/egor2078f/lurkhackv4/refs/heads/main/main.lua", true))()
    end    
})
	
Tabs.Main3:AddButton({
    Title=" Chill Hub",
    Description="",
    Callback=function() 
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/tienkhanh1/spicy/main/Chilli.lua"))()
	end
})	

Tabs.Main6:AddButton({
    Title = "key speed hub vv(cs thể bị fix)",
    Description = "",
    Callback = function()
        setclipboard("rMChVgMZYJYHMGNtMvYkvDKasUFztRuG")
    end
})

Tabs.Main2:AddButton({
    Title="Speed Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
	end
}) 

Tabs.Main4:AddButton({
    Title="Speed Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
	end
}) 

Tabs.Main3:AddButton({
    Title="HoHo Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))() 
    end
})

Tabs.Main3:AddButton({
    Title="Makal Hub",
    Description="",
    Callback=function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/DoliScriptz/loader/refs/heads/main/main.lua",true))()
    end 
})

Tabs.Main2:AddButton({
    Title="Lumin Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://lumin-hub.lol/loader.lua",true))()
    end
})

Tabs.Main2:AddButton({
    Title="Vxeze Hub",
    Description="",
    Callback=function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/Dex-Bear/Vxezehub/refs/heads/main/VxezeHubMain"))()
	end
})

Tabs.Main4:AddButton({
    Title="Than Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/thantzy/thanhub/refs/heads/main/thanv1"))()
	end
})

Tabs.Main5:AddButton({
    Title="Speed Hub",
    Description="",
    Callback=function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
	end
}) 
