-- Gui to Lua
-- Version: 3.2

-- Instances:

local GG = Instance.new("ScreenGui")
local King = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local UIListLayout = Instance.new("UIListLayout")
local Frame_2 = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local UICorner_7 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UICorner_9 = Instance.new("UICorner")

--Properties:

GG.Name = "GG"
GG.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
GG.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

King.Name = "King"
King.Parent = GG
King.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
King.BorderColor3 = Color3.fromRGB(0, 0, 0)
King.BorderSizePixel = 0
King.Position = UDim2.new(0.353398055, 0, 0.346389443, 0)
King.Size = UDim2.new(0, 196, 0, 181)
King.Visible = false

UICorner.Parent = King

TextLabel.Parent = King
TextLabel.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
TextLabel.BackgroundTransparency = 0.100
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 196, 0, 23)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "ВЕЗDАРНОСЬТЬ "
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

UICorner_2.Parent = TextLabel

Frame.Parent = King
Frame.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0524953716, 0, 0.140969127, 0)
Frame.Size = UDim2.new(0, 178, 0, 147)

UICorner_3.Parent = Frame

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0315789469, 0, 0.0322580636, 0)
TextButton.Size = UDim2.new(0, 177, 0, 42)
TextButton.Font = Enum.Font.DenkOne
TextButton.Text = "ESP"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_4.Parent = TextButton

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.036842104, 0, 0.276284397, 0)
TextButton_2.Size = UDim2.new(0, 177, 0, 42)
TextButton_2.Font = Enum.Font.DenkOne
TextButton_2.Text = "Custom Day"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

UICorner_5.Parent = TextButton_2

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0315789469, 0, 0.533452928, 0)
TextButton_3.Size = UDim2.new(0, 177, 0, 42)
TextButton_3.Font = Enum.Font.DenkOne
TextButton_3.Text = "Legit Hit Box"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

UICorner_6.Parent = TextButton_3

UIListLayout.Parent = Frame
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(0, 10)

Frame_2.Parent = GG
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BackgroundTransparency = 0.500
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.360851943, 0, 0.292723328, 0)
Frame_2.Size = UDim2.new(0, 286, 0, 174)

TextBox.Parent = Frame_2
TextBox.BackgroundColor3 = Color3.fromRGB(94, 94, 94)
TextBox.BackgroundTransparency = 0.350
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.214983717, 0, 0.255924165, 0)
TextBox.Size = UDim2.new(0, 170, 0, 39)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 14.000

UICorner_7.Parent = TextBox

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
TextButton_4.BackgroundTransparency = 0.300
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.14816305, 0, 0.577191234, 0)
TextButton_4.Size = UDim2.new(0, 200, 0, 50)
TextButton_4.Font = Enum.Font.Fantasy
TextButton_4.Text = "Key up"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 20.000

UICorner_8.Parent = TextButton_4

UICorner_9.Parent = Frame_2

-- Scripts:

local function YYSAO_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		local BoxESP = {}
		function BoxESP.Create(Player)
			local Box = Drawing.new("Square")
			Box.Visible = false
			Box.Color = Color3.fromRGB(255, 2, 213)
			Box.Filled = false
			Box.Transparency = 1
			Box.Thickness = 1
	
			local Updater
	
			local function UpdateBox()
				if Player and Player:IsA("Model") and Player:FindFirstChild("HumanoidRootPart") and Player:FindFirstChild("Head") then
					local Target2dPosition, IsVisible = workspace.CurrentCamera:WorldToViewportPoint(Player.HumanoidRootPart.Position)
					local scale_factor = 1 / (Target2dPosition.Z * math.tan(math.rad(workspace.CurrentCamera.FieldOfView * 0.5)) * 2) * 100
					local width, height = math.floor(40 * scale_factor), math.floor(62 * scale_factor)
					Box.Visible = IsVisible
					Box.Size = Vector2.new(width, height)
					Box.Position = Vector2.new(Target2dPosition.X - Box.Size.X / 2, Target2dPosition.Y - Box.Size.Y / 2)
				else
					Box.Visible = false
					if not Player then
						Box:Remove()
						Updater:Disconnect()
					end
				end
			end
	
			Updater = game:GetService("RunService").RenderStepped:Connect(UpdateBox)
	
			return Box
		end
	
		local Boxes = {}
	
		local function EnableBoxESP()
			for _, Player in pairs(game:GetService("Workspace"):GetChildren()) do
				if Player:IsA("Model") and Player:FindFirstChild("HumanoidRootPart") and Player:FindFirstChild("Head") then
					local Box = BoxESP.Create(Player)
					table.insert(Boxes, Box)
				end
			end
		end
	
		game.Workspace.DescendantAdded:Connect(function(i)
			if i:IsA("Model") and i:FindFirstChild("HumanoidRootPart") and i:FindFirstChild("Head") then
				local Box = BoxESP.Create(i)
				table.insert(Boxes, Box)
			end
		end)
	
		EnableBoxESP()
	end)
end
coroutine.wrap(YYSAO_fake_script)()
local function NMZXKD_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		getgenv().Lighting = game:GetService'Lighting'
		getgenv().RunService = game:GetService'RunService'
		local ColorCorrection = false
		local Correction = false
		local SunRays = false
		Skybox = Instance.new("Sky", Lighting)
		Skybox.SkyboxBk = "rbxassetid://15502324143"
		Skybox.SkyboxDn = "rbxassetid://15502324962"
		Skybox.SkyboxFt = "rbxassetid://15502325676"
		Skybox.SkyboxLf = "rbxassetid://15502326432"
		Skybox.SkyboxRt = "rbxassetid://15502327161"
		Skybox.SkyboxUp = "rbxassetid://15502328272"
	
		RunService.Stepped:Connect(function()
			if Lighting then
				if Lighting:FindFirstChild"ColorCorrection" then
					if not ColorCorrection then
						Lighting:WaitForChild"ColorCorrection":Destroy()
					else
						return nil
					end
				elseif Lighting:FindFirstChild"Correction" then
					if not Correction then
						Lighting:WaitForChild"Correction":Destroy()
					else
						return nil
					end
				elseif Lighting:FindFirstChildOfClass"SunRaysEffect" then
					if not SunRays then
						Lighting:WaitForChild"SunRaysEffect":Destroy()
					else
						return nil
					end
				end
			end
		end)
	end)
end
coroutine.wrap(NMZXKD_fake_script)()
local function XAYAUSW_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		local SelectPart = "Head"
		local HBSizeX = 7
		local HBSizeY = 7
		local HBSizeZ = 7
		local HBTrans = 0.5
	
		local PurpleColor = BrickColor.new("Really red")
	
		local hitboxlist1 = {}
	
		local RunService = game:GetService("RunService")  
	
		task.spawn(function ()
			while wait(0.1) do
				for v, i in pairs(workspace:GetChildren()) do
					if i:FindFirstChild("HumanoidRootPart") and not i:FindFirstChild("Fake1") then
						local FakeHead = Instance.new("Part", i)
						FakeHead.CFrame = i.Head.CFrame
						FakeHead.Name = SelectPart
						FakeHead.Size = Vector3.new(HBSizeX, HBSizeY, HBSizeZ)
						FakeHead.Anchored = true
						FakeHead.CanCollide = false
						FakeHead.Transparency = HBTrans
						FakeHead.BrickColor = PurpleColor 
						local subndom = Instance.new("Part", i)
						subndom.Name = "Fake1"
						table.insert(hitboxlist1, FakeHead)
						table.insert(hitboxlist1, subndom)
						for d, obj in ipairs(hitboxlist1) do
							print(i, obj) 
						end
					end
				end
			end
		end)
	end)
end
coroutine.wrap(XAYAUSW_fake_script)()
local function BZCH_fake_script() -- King.Drag 
	local script = Instance.new('LocalScript', King)

	local parent: Frame = script.Parent
	parent.Draggable = true
	parent.Selectable = true
	parent.Active = true
end
coroutine.wrap(BZCH_fake_script)()
local function SDJDLC_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.TextBox.Text == "KeyHackMB" then
			script.Parent.Parent.Parent.King.Visible = true
			script.Parent.Parent.Parent.Frame:Destroy()
			script.Parent.Parent.Parent.Frame:Destroy()
		else
			script.Parent.Parent.TextBox.Text = "Wrong Key!"
		end
	end)
end
coroutine.wrap(SDJDLC_fake_script)()
