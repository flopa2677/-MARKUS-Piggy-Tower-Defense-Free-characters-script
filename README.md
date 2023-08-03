local Library=loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window=Library.CreateLib("Piggy tower defense", "BloodTheme")
local Tab=Window:NewTab("Main(Free Characters)")
local Section=Tab:NewSection("Main(Free Characters)")
Section:NewButton("Mother", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Mother"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Father", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Father"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Giraffy", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Giraffy"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Beary", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Beary"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Mimi", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Mimi"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Doggy", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Doggy"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Pony", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Pony"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Markus", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Markus"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Poley", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Poley"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Zizzy", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Zizzy"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
Section:NewButton("Bunny", "ButtonInfo", function()
local function getHeadPosition()
local player=game.Players.LocalPlayer
local character=player.Character
if character then
local humanoid=character:FindFirstChild("Humanoid")
if humanoid then
local head=character:FindFirstChild("Head")
if head then
return head.Position
end
end
end
return nil
end
local headPosition=getHeadPosition()
if headPosition then
local A_1="Bunny"
local A_2=CFrame.new(headPosition)
local Event=game:GetService("ReplicatedStorage").Functions.SpawnTower
Event:InvokeServer(A_1, A_2)
end
end)
