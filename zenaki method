local Zenaki = false

function onKeyPress(inputObject, gameProcessedEvent)
    if inputObject.KeyCode == Enum.KeyCode.Y and gameProcessedEvent == false then
     if Zenaki == false then
       Zenaki = true

     elseif Zenaki == true then
       Zenaki = false
    
       
     end
   end
end
 
game:GetService("UserInputService").InputBegan:connect(onKeyPress)


    game:GetService("RunService").RenderStepped:Connect(function()
    if Zenaki == true then
 game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.lookVector * 14
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(0, math.rad(3.50), 0)
    end
    
end)
loadstring(game:HttpGet("https://gist.githubusercontent.com/murderspree/84309f4b27fc481923f1a647c204826d/raw/a1134751b9ab8cdae1b4fbc7db9230516d8d0eca/gistfile1.txt"))()
