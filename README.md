local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("BEAR X HUB", "Sentinel")


local Tab = Window:NewTab("Blox Fruits")
local Section = Tab:NewSection("Blox Fruits")


Section:NewButton("Open Script", "Open Script", function()
    getgenv().Color = Color3.fromRGB(0, 128, 255)
loadstring(game:HttpGet("https://raw.githubusercontent.com/StormSKz12/StirkeHub1/main/Gameincluded"))()
end)


---2


local Tab = Window:NewTab("King Legacy")
local Section = Tab:NewSection("King Legacy")


Section:NewButton("Open Script", "Open Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/King%20Leagacy"))()

end)


---3


local Tab = Window:NewTab("Last Pirates")
local Section = Tab:NewSection("Last Pirates")


Section:NewButton("Open Script", "Open Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/rayrei0112/Lua/main/Last%20Pirates"))()
end)


---4


local Tab = Window:NewTab("Two Piece")
local Section = Tab:NewSection("Two Piece")


Section:NewButton("Open Script", "Open Script", function()
    pcall(function()
   loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
end)
end)


