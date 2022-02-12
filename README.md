_G.AutoFarm = true
while _G.AutoFarm do wait()
game:GetService("Players").LocalPlayer.ninjaEvent:FireServer("swingKatana")
wait(.1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(70.166915893555, 20.502925872803, -48.203414916992)
end
