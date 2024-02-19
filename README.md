local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
--local failsafe = false
local Window = OrionLib:MakeWindow({Name = "Junin scripts| OMNI X", HidePremium = false, SaveConfig = true, ConfigFolder = "JUNINSCRIPTS"})


function Teleportplayer1(x, y, z)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(x, y, z))
end


local Tab = Window:MakeTab({
	Name = "Aliens",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Aliens Infinitos"
})


--------------aliens--------------
local Chama = {
    [1] = "OS",
    [2] = "heatblast",
    [3] = 120,
    [4] = true
}


local Besta = {
    [1] = "OS",
    [2] = "wildmutt",
    [3] = 120,
    [4] = true
}


local Diamante = {
    [1] = "OS",
    [2] = "diamond",
    [3] = 120,
    [4] = true
}


local Xrl8 = {
    [1] = "OS",
    [2] = "xrl8",
    [3] = 120,
    [4] = true
}


local MCinzenta = {
    [1] = "OS",
    [2] = "graymatter",
    [3] = 120,
    [4] = true
}


local fourarms = {
    [1] = "OS",
    [2] = "fourarms",
    [3] = 120,
    [4] = true
}


local insectoid = {
    [1] = "OS",
    [2] = "stinkfly",
    [3] = 120,
    [4] = true
}


local Aquatico = {
    [1] = "OS",
    [2] = "ripjaws",
    [3] = 120,
    [4] = true
}


local ultrat = {
    [1] = "OS",
    [2] = "ultrat",
    [3] = 120,
    [4] = true
}


local fantasmatico = {
    [1] = "OS",
    [2] = "ghostfreak",
    [3] = 120,
    [4] = true
}


local boladecanhao = {
    [1] = "OS",
    [2] = "cannonbolt",
    [3] = 120,
    [4] = true
}


local siposelvagem = {
    [1] = "OS",
    [2] = "wildvine",
    [3] = 120,
    [4] = true
}


local lobisben = {
    [1] = "OS",
    [2] = "blitzwolfer",
    [3] = 120,
    [4] = true
}


local benmumia = {
    [1] = "OS",
    [2] = "snareoh",
    [3] = 120,
    [4] = true
}


local frankenstrike = {
    [1] = "OS",
    [2] = "frankenstrike",
    [3] = 120,
    [4] = true
}


local glutao = {
    [1] = "OS",
    [2] = "upchuck",
    [3] = 120,
    [4] = true
}


local megaolhos = {
    [1] = "OS",
    [2] = "eyeguy",
    [3] = 120,
    [4] = true
}


local gigante = {
    [1] = "OS",
    [2] = "waybig",
    [3] = 120,
    [4] = true
}


local ditto = {
    [1] = "OS",
    [2] = "ditto",
    [3] = 120,
    [4] = true
}


local feedback = {
    [1] = "OS",
    [2] = "feedback",
    [3] = 120,
    [4] = true
}


local chocante = {
    [1] = "OS",
    [2] = "buzzshock",
    [3] = 120,
    [4] = true
}


local iguanartica = {
    [1] = "OS",
    [2] = "articguana",
    [3] = 120,
    [4] = true
}


local cuspidor = {
    [1] = "OS",
    [2] = "spitter",
    [3] = 120,
    [4] = true
}


local contratempo = {
    [1] = "OS",
    [2] = "clockwork",
    [3] = 120,
    [4] = true
}





----------Transformar nos aliens----------
--[[Tab:AddButton({
	Name = "Ativar/Desativar FailSafe",
	Callback = function()
      		if failsafe == true then
				failsafe = false
				
				OrionLib:MakeNotification({
	Name = "FailSafe Desativado",
	Content = "Notification content... what will it say??",
	Image = "rbxassetid://4483345998",
	Time = 5
})
			else
				failsafe = true
				
				
								OrionLib:MakeNotification({
	Name = "FailSafe Ativado",
	Content = "Notification content... what will it say??",
	Image = "rbxassetid://4483345998",
	Time = 5
  	--end    
})
]]
Tab:AddButton({
	Name = "Chama",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(Chama))
         

	end    
})
  

Tab:AddButton({
	Name = "Besta",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(Besta))
         

	end    
})


Tab:AddButton({
	Name = "Diamante",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(Diamante))
         

	end    
})


Tab:AddButton({
	Name = "Xrl8",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(Xrl8))
         

	end    
})


Tab:AddButton({
	Name = "MCinzenta",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(MCinzenta))
         

	end    
})


Tab:AddButton({
	Name = "4 BraÃ§os",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(fourarms))
         

	end    
})


Tab:AddButton({
	Name = "Insectoid",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(insectoid))
         

	end    
})


Tab:AddButton({
	Name = "AquÃ¡tico",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(Aquatico))
         

	end    
})


Tab:AddButton({
	Name = "Ultra-t",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(ultrat))
         

	end    
})


Tab:AddButton({
	Name = "FantasmÃ¡tico",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(fantasmatico))
         

	end    
})

  
Tab:AddButton({
	Name = "Bola de CanhÃ£o",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(boladecanhao))
         

	end    
})


Tab:AddButton({
	Name = "SipÃ³ Selvagem",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(siposelvagem))
         

	end    
})


Tab:AddButton({
 	Name = "Lobisben",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(lobisben))
         

	end    
})


Tab:AddButton({
	Name = "BenmÃºmia",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(benmumia))
         

	end    
})


Tab:AddButton({
	Name = "Frankenstrike",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(frankenstrike))
         

	end    
})


Tab:AddButton({
	Name = "GlutÃ£o",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(glutao))
         

	end    
})


Tab:AddButton({
	Name = "Mega Olhos",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(megaolhos))
         

	end    
})


Tab:AddButton({
	Name = "Gigante",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(gigante))
         

	end    
})


Tab:AddButton({
	Name = "Ditto",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(ditto))
         

	end    
})


Tab:AddButton({
	Name = "FeedBack",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(feedback))
         

	end    
})


Tab:AddButton({
	Name = "Chocante",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(chocante))
         

	end    
})


Tab:AddButton({
	Name = "Iguana Ãrtica",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(iguanartica))
         

	end    
})


Tab:AddButton({
	Name = "Cuspidor",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(cuspidor))
         

	end    
})


Tab:AddButton({
	Name = "Contra-Tempo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(contratempo))
         

	end    
})





-----Destranformar--------
local Tab = Window:MakeTab({
	Name = "Destranformar",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})



local Section = Tab:AddSection({
	Name = "Destranformar"
})


Tab:AddButton({
	Name = "Destranformar",
	Callback = function()
local args = {
    [1] = false
}

game:GetService("ReplicatedStorage").Remotes.UnMorph:FireServer(unpack(args))

end
})




------Omnitrix Recalibrado------------

local Tab = Window:MakeTab({
	Name = "Aliens Recalibrados",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local Section = Tab:AddSection({
	Name = "Recalibrado"
})

--------ALIENS RECALIBRADOS---------

local fogofatuo = {
    [1] = "AF",
    [2] = "swampfire",
    [3] = 240,
    [4] = true
}


local echoecho = {
    [1] = "AF",
    [2] = "echoecho",
    [3] = 240,
    [4] = true
}


local enormossauro = {
    [1] = "AF",
    [2] = "humungosaur",
    [3] = 240,
    [4] = true
}


local arraiajato = {
    [1] = "AF",
    [2] = "jetray",
    [3] = 240,
    [4] = true
}


local friagem = {
    [1] = "AF",
    [2] = "bigchill",
    [3] = 240,
    [4] = true
}


local cromatico = {
    [1] = "AF",
    [2] = "chromastone",
    [3] = 240,
    [4] = true
}


local artropode = {
    [1] = "AF",
    [2] = "brainstorm",
    [3] = 240,
    [4] = true
}


local macacoaranha = {
    [1] = "AF",
    [2] = "spidermonkey",
    [3] = 240,
    [4] = true
}


local gosma = {
    [1] = "AF",
    [2] = "goop",
    [3] = 240,
    [4] = true
}


local estrelapolar = {
    [1] = "AF",
    [2] = "lodestar",
    [3] = 240,
    [4] = true
}


local rath = {
    [1] = "AF",
    [2] = "rath",
    [3] = 240,
    [4] = true
}


local nanomech = {
    [1] = "AF",
    [2] = "nanomech",
    [3] = 240,
    [4] = true
}





-------tranformar recalibrado---------

Tab:AddButton({
	Name = "Fogo FÃ¡tuo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(fogofatuo))
         

	end    
})


Tab:AddButton({
	Name = "Eco Eco",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(echoecho))
         

	end    
})


Tab:AddButton({
	Name = "Enormossauro",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(enormossauro))
         

	end    
})


Tab:AddButton({
	Name = "Arraia Ajato",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(arraiajato))
         

	end    
})


Tab:AddButton({
	Name = "Friagem",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(friagem))
         

	end    
})


Tab:AddButton({
	Name = "CromÃ¡tico",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(cromatico))
         

	end    
})


Tab:AddButton({
	Name = "ArtrÃ³pode",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(artropode))
         

	end    
})


Tab:AddButton({
	Name = "Macaco-Aranha",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(macacoaranha))
         

	end    
})


Tab:AddButton({
	Name = "Gosma",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(gosma))
         

	end    
})


Tab:AddButton({
	Name = "EstrelaPolar",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(estrelapolar))
         

	end    
})


Tab:AddButton({
	Name = "Rath",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(rath))
         

	end    
})


Tab:AddButton({
	Name = "Nanomech",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(nanomech))
         

	end    
})


---------ultratrix-----------


local Tab = Window:MakeTab({
	Name = "Ultratrix",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local Section = Tab:AddSection({
	Name = "Ultratrix"
})


local fogofatuos = {
    [1] = "UA",
    [2] = "uswampfire",
    [3] = 360,
    [4] = true
}


local ecoecos = {
    [1] = "UA",
    [2] = "uechoecho",
    [3] = 360,
    [4] = true
}


local enormossauros = {
    [1] = "UA",
    [2] = "uhumungosaur",
    [3] = 360,
    [4] = true
}


local arraiajatos = {
    [1] = "UA",
    [2] = "ujetray",
    [3] = 360,
    [4] = true
}


local friagems = {
    [1] = "UA",
    [2] = "ubigchill",
    [3] = 360,
    [4] = true
}


local cromaticos = {
    [1] = "UA",
    [2] = "uchromastone",
    [3] = 360,
    [4] = true
}


local artropodes = {
    [1] = "UA",
    [2] = "ubrainstorm",
    [3] = 360,
    [4] = true
}


local gosmas = {
    [1] = "UA",
    [2] = "ugoop",
    [3] = 360,
    [4] = true
}


-------transformar ultratrix---------
Tab:AddButton({
	Name = "Fogo FÃ¡tuo Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(fogofatuos))
 
	end    
})


Tab:AddButton({
	Name = "Eco Eco Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(ecoecos))
 
	end    
})


Tab:AddButton({
	Name = "Enormossauro Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(enormossauros))
 
	end    
})


Tab:AddButton({
	Name = "Arraia Ajato Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(arraiajatos))
 
	end    
})


Tab:AddButton({
	Name = "Friagem Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(friagems))
 
	end    
})


Tab:AddButton({
	Name = "CromÃ¡tico Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(cromaticos))
 
	end    
})


Tab:AddButton({
	Name = "ArtrÃ³pode Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(artropodes))
 
	end    
})


Tab:AddButton({
	Name = "Gosma Supremo",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(gosmas))
 
	end    
})


------alienx-------

local Tab = Window:MakeTab({
	Name = "Sapien Celestial",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local Section = Tab:AddSection({
	Name = "AlienX"
})

--------------------------


local alienx = {
    [1] = "AF",
    [2] = "alienx",
    [3] = 240,
    [4] = true
}


Tab:AddButton({
	Name = "Alien X",
	Callback = function()
      		game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(alienx))
 
	end    
})


local Tab = Window:MakeTab({
	Name = "Teleporte",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Teleport omnitrix"
})



local plr = game.Players.LocalPlayer
local char = plr.Character

---------Omnitrix Teleport----------

Tab:AddButton({
Name = "Omnitrix",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-392, -44, -4353)))

end
})

Tab:AddButton({ 	Name = "Raid Ultratrix Direto", 	Callback = function() 		game:GetService("TeleportService"):Teleport(16091658541) 	end })

Tab:AddButton({
Name = "Omnitrix Recalibrado e resetar classe",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(419, 35290, 244)))

end
})

---------Castelo-----------
local Section = Tab:AddSection({
	Name = "Teleport Castelo"
})


Tab:AddButton({
Name = "Raid do Castelo",
Callback = function()

game:GetService("TeleportService"):Teleport(16129091908)
end
})

--------raid alien x---------
Tab:AddButton({
Name = "Teleport Raid Alien X",
Callback = function()
 
game:GetService("TeleportService"):Teleport(16029997375)


end})

-------super omnitrix--------
local Section = Tab:AddSection({
	Name = "Teleport Bracelete e NÃºcleo Ultratrix"
})


Tab:AddButton({
Name = "Bracelete Ultratrix",
Callback = function()
  
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-5091, 6, -8426)))

end
})


Tab:AddButton({
Name = "NÃºcleo Ultratrix",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(89046, -272, -42247)))

end
})

--------plataforma----------
local Section = Tab:AddSection({
	Name = "Plataforma"
})

Tab:AddButton({
Name = "Plataforma",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(0, 100000, 0)))

local platform = Instance.new("Part")
platform.Size = Vector3.new(100, 1, 100) -- 2
platform.Position = character.PrimaryPart.Position - Vector3.new(0, 5, 0)
platform.Anchored = true
platform.Parent = game.Workspace

end})


---------auto kill e auto save----------
local Tab = Window:MakeTab({
	Name = "Auto kill, Auto Save e Auto Raid",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Auto Kill, Auto save e Auto Raid"
})


Tab:AddButton({
	Name = "Auto Kill",
	Callback = function()
      		
while wait() do
   game:GetService("ReplicatedStorage").Remotes.PunchDummy:FireServer(150,999)

end

end
})

---------auto save----------
Tab:AddButton({
	Name = "Auto Save",
	Callback = function()
while wait(5) do
   game:GetService("ReplicatedStorage").Remotes.SaveAll:FireServer()

end

end
})


---------auto kill raid eternos-----------
local Section = Tab:AddSection({
	Name = "Auto Raid"
})

local contratempo = {
    [1] = "OS",
    [2] = "clockwork",
    [3] = 120,
    [4] = true
}


Tab:AddButton({
Name = "Auto Raid Eternos",
Callback = function()
  
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()


character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-52, -280, 131)))

local platform = Instance.new("Part")
platform.Size = Vector3.new(10, 1, 10) -- 2
platform.Position = character.PrimaryPart.Position - Vector3.new(0, 5, 0)
platform.Anchored = true
platform.Parent = game.Workspace


wait(1)

game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(contratempo))
     

  while wait(2) do

game:GetService("ReplicatedStorage").AliensPowerRemotes.clockwork.timeexplosion:FireServer()
--[[character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-52, -280, 131)))]]

  
  end
  

end})

Tab:AddButton({
	Name = "Auto Raid Diagon",
	Callback = function()
      		if game.PlaceId == 16365412402 then
  
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()


character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-2992, 1409, -875)))

local platform = Instance.new("Part")
platform.Size = Vector3.new(10, 1, 10) -- 2
platform.Position = character.PrimaryPart.Position - Vector3.new(0, 5, 0)
platform.Anchored = true
platform.Parent = game.Workspace

local AlienX = {
    [1] = "OS",
    [2] = "alienx",
    [3] = 240,
    [4] = true
}


wait(1)

game:GetService("ReplicatedStorage").Remotes.AlienMorph:FireServer(unpack(AlienX))
     

  while wait(5) do

game:GetService("ReplicatedStorage").AliensPowerRemotes.alienx.Explos:FireServer()

  
  end
  
end
  	end    
})

--------anti afk-----------
local Section = Tab:AddSection({
	Name = "Anti AFK e Reset"
})


Tab:AddButton({
  Name = "Anti AFK",
  Callback = function()

wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,370,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by luca#5432"
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Active"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="Roblox tried kicking you buy I didnt let them!"wait(2)ab.Text="Status : Active"end)


local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
while wait(5) do
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(0, 100005, 0)))

end
  end
})

Tab:AddButton({
  Name = "Reset",
  Callback = function()
    game:GetService("ReplicatedStorage").Remotes.LoadCHCopy:FireServer()

end})


---------rejoin e infinityeld
local Tab = Window:MakeTab({
	Name = "Rejoin e InfinitYeld",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Rejoin e InfinitYeld"
})

Tab:AddButton({
  Name = "Rejoin",
  Callback = function()

local TeleportService = game:GetService("TeleportService")
local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer

local Rejoin = coroutine.create(function()
    local Success, ErrorMessage = pcall(function()
        TeleportService:Teleport(game.PlaceId, LocalPlayer)
    end)
    if ErrorMessage and not Success then
        warn(ErrorMessage)
    end
end)

coroutine.resume(Rejoin)
end})


Tab:AddButton({
  Name = "InfinitYield",
  Callback = function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()


end})


---------server hop-----------
local Tab = Window:MakeTab({
	Name = "Server com pouco player",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Server Hop"
})


Tab:AddButton({
  Name = "Procurar servidor com pouco player",
  Callback = function()

local Http = game:GetService("HttpService")
local TPS = game:GetService("TeleportService")
local Api = "https://games.roblox.com/v1/games/"

local _place = game.PlaceId
local _servers = Api.._place.."/servers/Public?sortOrder=Asc&limit=100"
function ListServers(cursor)
   local Raw = game:HttpGet(_servers .. ((cursor and "&cursor="..cursor) or ""))
   return Http:JSONDecode(Raw)
end

local Server, Next; repeat
   local Servers = ListServers(Next)
   Server = Servers.data[1]
   Next = Servers.nextPageCursor
until Server

TPS:TeleportToPlaceInstance(_place,Server.id,game:GetService('Players').LocalPlayer)


end
})

local Tab = Window:MakeTab({
	Name = "Teleport Geral",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Diagon"
})

Tab:AddButton({
	Name = "Teleport Lugar Raid Diagon",
	Callback = function()
Teleportplayer1(-7185, -1162, -4509)	
  	end    
})

Tab:AddButton({
	Name = "Teleport Direto Raid Diagon",
	Callback = function()
game:GetService("TeleportService"):Teleport(16365412402)
  	end    
})

Tab:AddButton({
Name = "Castelo",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(2453, 299, -6988)))

end
})

local Section = Tab:AddSection({
	Name = "PeÃ§as Alien X"
})

Tab:AddButton({
Name = "PeÃ§a 1",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-1916, -895, 933)))

end
})

Tab:AddButton({
Name = "PeÃ§a 2",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(-743, -193, -73714)))
end
})


Tab:AddButton({
Name = "PeÃ§a 3",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(94, 144, 92835)))
end
})


Tab:AddButton({
Name = "Cubo Alien X",
Callback = function()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- 1
character:SetPrimaryPartCFrame(CFrame.new(Vector3.new(101218, 1251, -1666)))
end
})

local Tab = Window:MakeTab({
	Name = "Misc",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Creditos",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Creditos.",
	Content = "Script de Junin (Kryp Developer)",
	Image = "rbxassetid://4483345998",
	Time = 15
})

  	end    
})

Tab:AddButton({ 	Name = "Discord", 	Callback = function() 	 setclipboard("https://discord.com/invite/2vGDDGdC")
end })

Tab:AddSlider({
	Name = "Velocidade",
	Min = 1,
	Max = 120,
	Default = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid").WalkSpeed,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "Speed",
	Callback = function(Value)
		game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = Speed
	end    
})

Tab:AddButton({
	Name = "Resetar(nÃ£o usa na raid",
	Callback = function()
      		game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid").Health = 0
  	end    
})

-- Adicionando um color picker


Tab:AddButton({
	Name = "Fly",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
  	end    
})

OrionLib:Init()
