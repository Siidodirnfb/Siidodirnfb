local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("OxyHub", "Midnight")
local Tab = Window:NewTab("Teleports")
local Section = Tab:NewSection("Teleports")
Section:NewButton("Rocks", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = 117.9976806640625
local y = 2347.939697265625
local z = 17.54490852355957

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
Section:NewButton("Middle Of The Map", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = 63.92826843261719
local y = 2313.124755859375
local z = -336.85369873046875

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
Section:NewButton("Rocks 2", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = -463.5323181152344
local y = 2566.656005859375
local z = -874.6510009765625

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
Section:NewButton("Tree", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = 462.71087646484375
local y = 2597.93994140625
local z = -76.40318298339844

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
Section:NewButton("Tree2", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = 454.09539794921875
local y = 2469.052490234375
local z = 130.99513244628906

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
Section:NewButton("Tree3", "ButtonInfo", function()
local player = game.Players.LocalPlayer
local x = 477.1802978515625
local y = 2469.4189453125
local z = -469.3216552734375

player.Character.HumanoidRootPart.CFrame = CFrame.new(x, y, z)
    print("Clicked")
end)
local Tab = Window:NewTab("Fast Character Change")
local Section = Tab:NewSection("Fast Character Change")
Section:NewButton("Goku", "ButtonInfo", function()
local args = {
    [1] = {
        [1] = "Low-Class Warrior",
        [2] = "\2"
    }
}

game:GetService("ReplicatedStorage").BridgeNet2.dataRemoteEvent:FireServer(unpack(args))

    print("Clicked")
end)
Section:NewButton("Vegeta", "ButtonInfo", function()
local args = {
    [1] = {
        [1] = "Proud Prince",
        [2] = "\2"
    }
}

game:GetService("ReplicatedStorage").BridgeNet2.dataRemoteEvent:FireServer(unpack(args))
    print("Clicked")
end)
Section:NewButton("Broly", "ButtonInfo", function()
local args = {
    [1] = {
        [1] = "Legendary Warrior",
        [2] = "\2"
    }
}

game:GetService("ReplicatedStorage").BridgeNet2.dataRemoteEvent:FireServer(unpack(args))
    print("Clicked")
end)
Section:NewButton("Gohan", "ButtonInfo", function()
local args = {
    [1] = {
        [1] = "The Great Hero",
        [2] = "\2"
    }
}

game:GetService("ReplicatedStorage").BridgeNet2.dataRemoteEvent:FireServer(unpack(args))
    print("Clicked")
end)
Section:NewButton("Black Goku", "ButtonInfo", function()
local args = {
    [1] = {
        [1] = "Corrupted Vigilante",
        [2] = "\2"
    }
}

game:GetService("ReplicatedStorage").BridgeNet2.dataRemoteEvent:FireServer(unpack(args))

    print("Clicked")
end)
