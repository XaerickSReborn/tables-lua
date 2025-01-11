local fruit={
	banana=1,
	apple=1,
	orange=1
}

local Banana = game.Workspace.Fruits.Banana
local Apple = game.Workspace.Fruits.Apple
local Orange = game.Workspace.Fruits.Orange

local msg = game.Workspace.Fruits.Message


Banana.Touched:Connect(function(toco)
	if toco.Parent:FindFirstChild("Humanoid") then
		fruit["banana"]=fruit["banana"]+5
		Banana:Destroy()
	end
end)

Apple.Touched:Connect(function(toco)
	if toco.Parent:FindFirstChild("Humanoid") then
		fruit["apple"]=fruit["apple"]+5
		Apple:Destroy()
	end
end)

Orange.Touched:Connect(function(toco)
	if toco.Parent:FindFirstChild("Humanoid") then
		fruit["orange"]=fruit["orange"]+5
		Orange:Destroy()
	end
end)


msg.Touched:Connect(function(toco)
	if toco.Parent:FindFirstChild("Humanoid") then
		print("Tienes: ".. fruit["banana"]..", "..fruit["apple"]..", "..fruit["orange"])
	end
end)
