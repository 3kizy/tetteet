-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Main = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TextButton_9 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextButton_10 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextButton_11 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextButton_12 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local TextButton_13 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TextButton_14 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_17 = Instance.new("UICorner")
local TextButton_15 = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local TextButton_16 = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local TextButton_17 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local shadowHolder = Instance.new("Frame")
local umbraShadow = Instance.new("ImageLabel")
local penumbraShadow = Instance.new("ImageLabel")
local ambientShadow = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Credits = Instance.new("Frame")
local UICorner_21 = Instance.new("UICorner")
local TextButton_18 = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local TextButton_19 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local TextButton_20 = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local TextButton_21 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local TextButton_22 = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local TextButton_23 = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local Information = Instance.new("Frame")
local UICorner_28 = Instance.new("UICorner")
local TextButton_24 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local TextButton_25 = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local TextButton_26 = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local TextButton_27 = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local TextButton_28 = Instance.new("TextButton")
local UICorner_33 = Instance.new("UICorner")
local TextButton_29 = Instance.new("TextButton")
local UICorner_34 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_35 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local UICorner_36 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Global

Frame.Parent = ScreenGui


UICorner.CornerRadius = UDim.new(0, 3)
UICorner.Parent = Frame

Main.Name = "Main"
Main.Parent = Frame
Main.BackgroundColor3 = Color3.fromRGB(1000, 36, 36)
Main.Position = UDim2.new(0.00142349559, 0, 0.274297148, 0)
Main.Size = UDim2.new(0, 0, 0, 0)

UICorner_2.CornerRadius = UDim.new(0, 3)
UICorner_2.Parent = Main

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextButton.Position = UDim2.new(0, 800, 50, 70)
TextButton.Size = UDim2.new(0, 213, 0, 70)
TextButton.Font = Enum.Font.GothamBlack
TextButton.Text = "UFA BIGFOOT"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 20.000

UICorner_3.Parent = TextButton



TextButton_17.Parent = Frame_2
TextButton_17.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_17.Position = UDim2.new(0.1593981631, 0, 0.30107972, 0)
TextButton_17.Size = UDim2.new(0, 103, 0, 38)
TextButton_17.Font = Enum.Font.GothamBlack
TextButton_17.Text = "Information"
TextButton_17.TextColor3 = Color3.fromRGB(200, 255, 255)
TextButton_17.TextSize = 20.000

UICorner_20.CornerRadius = UDim.new(0, 3)
UICorner_20.Parent = TextButton_17

shadowHolder.Name = "shadowHolder"
shadowHolder.Parent = Frame
shadowHolder.BackgroundTransparency = 0.500
shadowHolder.Size = UDim2.new(1, 0, 0.409638554, 0)
shadowHolder.ZIndex = 5

umbraShadow.Name = "umbraShadow"
umbraShadow.Parent = shadowHolder
umbraShadow.AnchorPoint = Vector2.new(0.5, 0.5)
umbraShadow.BackgroundTransparency = 1.000
umbraShadow.Position = UDim2.new(0.5, 0, 0.5, 3)
umbraShadow.Size = UDim2.new(1, 1, 1, 3)
umbraShadow.Image = "rbxassetid://1316045217"
umbraShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
umbraShadow.ImageTransparency = 0.160
umbraShadow.ScaleType = Enum.ScaleType.Slice
umbraShadow.SliceCenter = Rect.new(10, 10, 118, 118)

penumbraShadow.Name = "penumbraShadow"
penumbraShadow.Parent = shadowHolder
penumbraShadow.AnchorPoint = Vector2.new(0.5, 0.5)
penumbraShadow.BackgroundTransparency = 1.000
penumbraShadow.Position = UDim2.new(0.5, 0, 0.5, 3)
penumbraShadow.Size = UDim2.new(1, 1, 1, 3)
penumbraShadow.Image = "rbxassetid://1316045217"
penumbraShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
penumbraShadow.ImageTransparency = 0.880
penumbraShadow.ScaleType = Enum.ScaleType.Slice
penumbraShadow.SliceCenter = Rect.new(10, 10, 118, 118)

ambientShadow.Name = "ambientShadow"
ambientShadow.Parent = shadowHolder
ambientShadow.AnchorPoint = Vector2.new(0.5, 0.5)
ambientShadow.BackgroundTransparency = 1.000
ambientShadow.Position = UDim2.new(0.501123726, 0, 0.474999994, 3)
ambientShadow.Size = UDim2.new(0.991011322, 3, 1.04999995, 3)
ambientShadow.Image = "rbxassetid://1316045217"
ambientShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
ambientShadow.ImageTransparency = 0.880
ambientShadow.ScaleType = Enum.ScaleType.Slice
ambientShadow.SliceCenter = Rect.new(10, 10, 118, 118)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.0267857146, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 94, 0, 23)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = ""
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 25.000

Credits.Name = "Credits"
Credits.Parent = Frame
Credits.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Credits.Position = UDim2.new(0, 0, 0.277108431, 0)
Credits.Size = UDim2.new(0, 543, 0, 372)
Credits.Visible = false

UICorner_21.CornerRadius = UDim.new(0, 3)
UICorner_21.Parent = Credits

TextButton_18.Parent = Credits
TextButton_18.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_18.Position = UDim2.new(0.259970695, 0, 0.0569556877, 0)
TextButton_18.Size = UDim2.new(0, 381, 0, 38)
TextButton_18.Font = Enum.Font.GothamBlack
TextButton_18.Text = "Main dev: David De Gea#4581"
TextButton_18.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_18.TextSize = 14.000

UICorner_22.Parent = TextButton_18

TextButton_19.Parent = Credits
TextButton_19.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_19.Position = UDim2.new(0.259970695, 0, 0.193665951, 0)
TextButton_19.Size = UDim2.new(0, 381, 0, 38)
TextButton_19.Font = Enum.Font.GothamBlack
TextButton_19.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_19.TextSize = 14.000

UICorner_23.Parent = TextButton_19

TextButton_20.Parent = Credits
TextButton_20.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_20.Position = UDim2.new(0.260420144, 0, 0.479643464, 0)
TextButton_20.Size = UDim2.new(0, 380, 0, 38)
TextButton_20.Font = Enum.Font.GothamBlack
TextButton_20.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_20.TextSize = 10.000

UICorner_24.Parent = TextButton_20

TextButton_21.Parent = Credits
TextButton_21.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_21.Position = UDim2.new(0.258578479, 0, 0.33613947, 0)
TextButton_21.Size = UDim2.new(0, 381, 0, 38)
TextButton_21.Font = Enum.Font.GothamBlack
TextButton_21.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_21.TextSize = 14.000

UICorner_25.Parent = TextButton_21

TextButton_22.Parent = Credits
TextButton_22.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_22.Position = UDim2.new(0.260420144, 0, 0.612421036, 0)
TextButton_22.Size = UDim2.new(0, 380, 0, 38)
TextButton_22.Font = Enum.Font.GothamBlack
TextButton_22.Text = "Join our discord! discord.gg/rj8PXHXmUe"
TextButton_22.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_22.TextSize = 10.000

UICorner_26.Parent = TextButton_22

TextButton_23.Parent = Credits
TextButton_23.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_23.Position = UDim2.new(0.260420144, 0, 0.739835024, 0)
TextButton_23.Size = UDim2.new(0, 378, 0, 38)
TextButton_23.Font = Enum.Font.GothamBlack
TextButton_23.Text = "Copy Discord Link"
TextButton_23.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_23.TextSize = 14.000

UICorner_27.Parent = TextButton_23

Information.Name = "Information"
Information.Parent = Frame
Information.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Information.Position = UDim2.new(0, 0, 0.277108431, 0)
Information.Size = UDim2.new(0, 542, 0, 371)
Information.Visible = false

UICorner_28.CornerRadius = UDim.new(0, 3)
UICorner_28.Parent = Information

TextButton_24.Parent = Information
TextButton_24.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_24.Position = UDim2.new(0.278182626, 0, 0.0569701903, 0)
TextButton_24.Size = UDim2.new(0, 379, 0, 38)
TextButton_24.Font = Enum.Font.GothamBlack
TextButton_24.Text = "Press F for AC"
TextButton_24.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_24.TextSize = 14.000

UICorner_29.Parent = TextButton_24

TextButton_25.Parent = Information
TextButton_25.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_25.Position = UDim2.new(0.278182626, 0, 0.190948814, 0)
TextButton_25.Size = UDim2.new(0, 379, 0, 38)
TextButton_25.Font = Enum.Font.GothamBlack
TextButton_25.Text = "Scripting Group: Avexcital Scripts"
TextButton_25.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_25.TextSize = 14.000


UICorner_31.Parent = TextButton_26

TextButton_27.Parent = Information
TextButton_27.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextButton_27.Position = UDim2.new(0.278182626, 0, 0.333371639, 0)
TextButton_27.Size = UDim2.new(0, 379, 0, 38)
TextButton_27.Font = Enum.Font.GothamBlack
TextButton_27.Text = "Comma (,) to close the GUI"
TextButton_27.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_27.TextSize = 14.000



UICorner_34.Parent = TextButton_29

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(-0.0267857146, 0, 0, 0)
TextLabel_2.Size = UDim2.new(0, 94, 0, 23)
TextLabel_2.Font = Enum.Font.GothamBold
TextLabel_2.Text = ""
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 25.000





-- Scripts:

local function EBAYR_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		if getgenv().MTAPIMutex~=nil then return end;local function a()if is_protosmasher_caller~=nil then return 0 end;if elysianexecute~=nil then return 1 end;if fullaccess~=nil then return 2 end;if Synapse~=nil then return 3 end;return 4 end;local function b()local c=a()if c==0 then return is_protosmasher_caller end;if c==1 or c==3 then return checkcaller end;if c==2 then return IsLevel7 end;return nil end;if a()==2 then error("mt-api: Exploit not supported")end;local d={}local e={}local f={}local g={}local h={}local i={}local j={}local k={}local function l()local m=a()local n=b()local o=getrawmetatable(game)if m==0 then make_writeable(o)elseif m==2 then fullaccess(o)else setreadonly(o,false)end;local p=o.__index;local q=o.__newindex;local r=o.__namecall;o.__index=newcclosure(function(s,t)if n()then return p(s,t)end;if d[s]and d[s][t]then local u=d[s][t]if u["IsCallback"]==true then return u["Value"](s)else return u["Value"]end end;if g[t]then local v=g[t]if v["IsCallback"]==true then return v["Value"](s)else return v["Value"]end end;if j[s]and j[s][t]then return k[s][t]end;return p(s,t)end)o.__newindex=newcclosure(function(w,x,y)if n()then return q(w,x,y)end;if e[w]and e[w][x]then local z=e[w][x]if z["Callback"]==nil then return else z["Callback"](w,y)return end end;if h[x]then local A=h[x]if A["Callback"]==nil then return else A["Callback"](w,y)return end end;if j[w]and j[w][x]then local B=j[w][x]if type(y)~=B["Type"]then error("bad argument #3 to '"..x.."' ("..B["Type"].." expected, got "..type(x)..")")end;k[w][x]=y;return end;return q(w,x,y)end)local C=isluau and isluau()or false;o.__namecall=newcclosure(function(D,...)local E={...}local F=C and getnamecallmethod()or table.remove(E)if n()then if F=="AddGetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local G=E[1]local H=E[2]local I=E[3]if type(G)~="string"then error("mt-api: Invalid hook type")end;if not d[D]then d[D]={}end;if I==true and type(H)~="function"then error("mt-api: Invalid callback function")end;d[D][G]={Value=H,IsCallback=I}local J=function()d[D][G]=nil end;return{remove=J,Remove=J}end;if F=="AddGlobalGetHook"then local K=E[1]local L=E[2]local M=E[3]if type(K)~="string"then error("mt-api: Invalid hook type")end;if M==true and type(L)~="function"then error("mt-api: Invalid callback function")end;g[K]={Value=L,IsCallback=M}local N=function()g[K]=nil end;return{remove=N,Remove=N}end;if F=="AddSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local O=E[1]local P=E[2]if type(O)~="string"then error("mt-api: Invalid hook type")end;if not e[D]then e[D]={}end;if type(P)=="function"then e[D][O]={Callback=P}else e[D][O]={Callback=nil}end;local Q=function()e[D][O]=nil end;return{remove=Q,Remove=Q}end;if F=="AddGlobalSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local R=E[1]local S=E[2]if type(R)~="string"then error("mt-api: Invalid hook type")end;if type(S)=="function"then h[R]={Callback=S}else h[R]={Callback=nil}end;local T=function()h[R]=nil end;return{remove=T,Remove=T}end;if F=="AddCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local U=E[1]local V=E[2]if type(U)~="string"then error("mt-api: Invalid hook type")end;if type(V)~="function"then error("mt-api: Invalid argument #2 (not function)")end;if not f[D]then f[D]={}end;f[D][U]={Callback=V}local W=function()f[D][U]=nil end;return{remove=W,Remove=W}end;if F=="AddGlobalCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local X=E[1]local Y=E[2]if type(X)~="string"then error("mt-api: Invalid hook type")end;if type(Y)~="function"then error("mt-api: Invalid argument #2 (not function)")end;i[X]={Callback=Y}local Z=function()i[X]=nil end;return{remove=Z,Remove=Z}end;if F=="AddPropertyEmulator"then if#E<1 then error("mt-api: Invalid argument count")end;local _=E[1]if type(_)~="string"then error("mt-api: Invalid hook type")end;local a0=p(D,_)local a1=type(a0)if not j[D]then j[D]={}end;if not k[D]then k[D]={}end;j[D][_]={Type=a1}k[D][_]=p(D,_)local a2=function()j[D][_]=nil;k[D][_]=nil end;return{remove=a2,Remove=a2}end;return r(D,...)end;if f[D]and f[D][F]then local a3=f[D][F]return a3["Callback"](p(D,F),unpack(E))end;if i[F]then local a4=i[F]return a4["Callback"](D,p(D,F),unpack(E))end;return r(D,...)end)if m==0 then make_readonly(o)elseif m==2 then else setreadonly(o,true)end end;l()getgenv().MTAPIMutex=true
	
		game.Players.LocalPlayer.Character["Right Leg"]:AddPropertyEmulator("Size")
		wait(0.5)
		game.Players.LocalPlayer.Character["Right Leg"].Massless = true
		game.Players.LocalPlayer.Character["Right Leg"].Size = Vector3.new (12.3, 2.11, 10.2)
		game.Players.LocalPlayer.Character["Right Leg"].Transparency = 0.9
	end)
end
coroutine.wrap(EBAYR_fake_script)()
local function DTNR_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		if getgenv().MTAPIMutex~=nil then return end;local function a()if is_protosmasher_caller~=nil then return 0 end;if elysianexecute~=nil then return 1 end;if fullaccess~=nil then return 2 end;if Synapse~=nil then return 3 end;return 4 end;local function b()local c=a()if c==0 then return is_protosmasher_caller end;if c==1 or c==3 then return checkcaller end;if c==2 then return IsLevel7 end;return nil end;if a()==2 then error("mt-api: Exploit not supported")end;local d={}local e={}local f={}local g={}local h={}local i={}local j={}local k={}local function l()local m=a()local n=b()local o=getrawmetatable(game)if m==0 then make_writeable(o)elseif m==2 then fullaccess(o)else setreadonly(o,false)end;local p=o.__index;local q=o.__newindex;local r=o.__namecall;o.__index=newcclosure(function(s,t)if n()then return p(s,t)end;if d[s]and d[s][t]then local u=d[s][t]if u["IsCallback"]==true then return u["Value"](s)else return u["Value"]end end;if g[t]then local v=g[t]if v["IsCallback"]==true then return v["Value"](s)else return v["Value"]end end;if j[s]and j[s][t]then return k[s][t]end;return p(s,t)end)o.__newindex=newcclosure(function(w,x,y)if n()then return q(w,x,y)end;if e[w]and e[w][x]then local z=e[w][x]if z["Callback"]==nil then return else z["Callback"](w,y)return end end;if h[x]then local A=h[x]if A["Callback"]==nil then return else A["Callback"](w,y)return end end;if j[w]and j[w][x]then local B=j[w][x]if type(y)~=B["Type"]then error("bad argument #3 to '"..x.."' ("..B["Type"].." expected, got "..type(x)..")")end;k[w][x]=y;return end;return q(w,x,y)end)local C=isluau and isluau()or false;o.__namecall=newcclosure(function(D,...)local E={...}local F=C and getnamecallmethod()or table.remove(E)if n()then if F=="AddGetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local G=E[1]local H=E[2]local I=E[3]if type(G)~="string"then error("mt-api: Invalid hook type")end;if not d[D]then d[D]={}end;if I==true and type(H)~="function"then error("mt-api: Invalid callback function")end;d[D][G]={Value=H,IsCallback=I}local J=function()d[D][G]=nil end;return{remove=J,Remove=J}end;if F=="AddGlobalGetHook"then local K=E[1]local L=E[2]local M=E[3]if type(K)~="string"then error("mt-api: Invalid hook type")end;if M==true and type(L)~="function"then error("mt-api: Invalid callback function")end;g[K]={Value=L,IsCallback=M}local N=function()g[K]=nil end;return{remove=N,Remove=N}end;if F=="AddSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local O=E[1]local P=E[2]if type(O)~="string"then error("mt-api: Invalid hook type")end;if not e[D]then e[D]={}end;if type(P)=="function"then e[D][O]={Callback=P}else e[D][O]={Callback=nil}end;local Q=function()e[D][O]=nil end;return{remove=Q,Remove=Q}end;if F=="AddGlobalSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local R=E[1]local S=E[2]if type(R)~="string"then error("mt-api: Invalid hook type")end;if type(S)=="function"then h[R]={Callback=S}else h[R]={Callback=nil}end;local T=function()h[R]=nil end;return{remove=T,Remove=T}end;if F=="AddCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local U=E[1]local V=E[2]if type(U)~="string"then error("mt-api: Invalid hook type")end;if type(V)~="function"then error("mt-api: Invalid argument #2 (not function)")end;if not f[D]then f[D]={}end;f[D][U]={Callback=V}local W=function()f[D][U]=nil end;return{remove=W,Remove=W}end;if F=="AddGlobalCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local X=E[1]local Y=E[2]if type(X)~="string"then error("mt-api: Invalid hook type")end;if type(Y)~="function"then error("mt-api: Invalid argument #2 (not function)")end;i[X]={Callback=Y}local Z=function()i[X]=nil end;return{remove=Z,Remove=Z}end;if F=="AddPropertyEmulator"then if#E<1 then error("mt-api: Invalid argument count")end;local _=E[1]if type(_)~="string"then error("mt-api: Invalid hook type")end;local a0=p(D,_)local a1=type(a0)if not j[D]then j[D]={}end;if not k[D]then k[D]={}end;j[D][_]={Type=a1}k[D][_]=p(D,_)local a2=function()j[D][_]=nil;k[D][_]=nil end;return{remove=a2,Remove=a2}end;return r(D,...)end;if f[D]and f[D][F]then local a3=f[D][F]return a3["Callback"](p(D,F),unpack(E))end;if i[F]then local a4=i[F]return a4["Callback"](D,p(D,F),unpack(E))end;return r(D,...)end)if m==0 then make_readonly(o)elseif m==2 then else setreadonly(o,true)end end;l()getgenv().MTAPIMutex=true
	
		game.Players.LocalPlayer.Character["Right Hand"]:AddPropertyEmulator("Size")
		game.Players.LocalPlayer.Character["Left Hand"]:AddPropertyEmulator("Size")
		wait(0.5)
		game.Players.LocalPlayer.Character["Right Arm"].Size = Vector3.new(5,5,5)
		game.Players.LocalPlayer.Character["Left Arm"].Size = Vector3.new(5,5,5)
		game.Players.LocalPlayer.Character["Right Arm"].Transparency = 0.9
		game.Players.LocalPlayer.Character["Left Arm"].Transparency = 0.9
	end)
end
coroutine.wrap(DTNR_fake_script)()
local function ILVXFM_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		local Player = game.Players.LocalPlayer
		local Mouse = Player:GetMouse()
		Mouse.KeyDown:connect(function(catch)
			catch:lower()
			if catch == "f" then
				for i,balls in pairs(game.Workspace:GetDescendants()) do
					if balls.Name == "TPS" then
						balls.Position = Player.Character["HumanoidRootPart"].Position
					end
				end
			end
		end)
	end)
end
coroutine.wrap(ILVXFM_fake_script)()
local function REXTSH_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		if getgenv().MTAPIMutex~=nil then return end;local function a()if is_protosmasher_caller~=nil then return 0 end;if elysianexecute~=nil then return 1 end;if fullaccess~=nil then return 2 end;if Synapse~=nil then return 3 end;return 4 end;local function b()local c=a()if c==0 then return is_protosmasher_caller end;if c==1 or c==3 then return checkcaller end;if c==2 then return IsLevel7 end;return nil end;if a()==2 then error("mt-api: Exploit not supported")end;local d={}local e={}local f={}local g={}local h={}local i={}local j={}local k={}local function l()local m=a()local n=b()local o=getrawmetatable(game)if m==0 then make_writeable(o)elseif m==2 then fullaccess(o)else setreadonly(o,false)end;local p=o.__index;local q=o.__newindex;local r=o.__namecall;o.__index=newcclosure(function(s,t)if n()then return p(s,t)end;if d[s]and d[s][t]then local u=d[s][t]if u["IsCallback"]==true then return u["Value"](s)else return u["Value"]end end;if g[t]then local v=g[t]if v["IsCallback"]==true then return v["Value"](s)else return v["Value"]end end;if j[s]and j[s][t]then return k[s][t]end;return p(s,t)end)o.__newindex=newcclosure(function(w,x,y)if n()then return q(w,x,y)end;if e[w]and e[w][x]then local z=e[w][x]if z["Callback"]==nil then return else z["Callback"](w,y)return end end;if h[x]then local A=h[x]if A["Callback"]==nil then return else A["Callback"](w,y)return end end;if j[w]and j[w][x]then local B=j[w][x]if type(y)~=B["Type"]then error("bad argument #3 to '"..x.."' ("..B["Type"].." expected, got "..type(x)..")")end;k[w][x]=y;return end;return q(w,x,y)end)local C=isluau and isluau()or false;o.__namecall=newcclosure(function(D,...)local E={...}local F=C and getnamecallmethod()or table.remove(E)if n()then if F=="AddGetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local G=E[1]local H=E[2]local I=E[3]if type(G)~="string"then error("mt-api: Invalid hook type")end;if not d[D]then d[D]={}end;if I==true and type(H)~="function"then error("mt-api: Invalid callback function")end;d[D][G]={Value=H,IsCallback=I}local J=function()d[D][G]=nil end;return{remove=J,Remove=J}end;if F=="AddGlobalGetHook"then local K=E[1]local L=E[2]local M=E[3]if type(K)~="string"then error("mt-api: Invalid hook type")end;if M==true and type(L)~="function"then error("mt-api: Invalid callback function")end;g[K]={Value=L,IsCallback=M}local N=function()g[K]=nil end;return{remove=N,Remove=N}end;if F=="AddSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local O=E[1]local P=E[2]if type(O)~="string"then error("mt-api: Invalid hook type")end;if not e[D]then e[D]={}end;if type(P)=="function"then e[D][O]={Callback=P}else e[D][O]={Callback=nil}end;local Q=function()e[D][O]=nil end;return{remove=Q,Remove=Q}end;if F=="AddGlobalSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local R=E[1]local S=E[2]if type(R)~="string"then error("mt-api: Invalid hook type")end;if type(S)=="function"then h[R]={Callback=S}else h[R]={Callback=nil}end;local T=function()h[R]=nil end;return{remove=T,Remove=T}end;if F=="AddCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local U=E[1]local V=E[2]if type(U)~="string"then error("mt-api: Invalid hook type")end;if type(V)~="function"then error("mt-api: Invalid argument #2 (not function)")end;if not f[D]then f[D]={}end;f[D][U]={Callback=V}local W=function()f[D][U]=nil end;return{remove=W,Remove=W}end;if F=="AddGlobalCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local X=E[1]local Y=E[2]if type(X)~="string"then error("mt-api: Invalid hook type")end;if type(Y)~="function"then error("mt-api: Invalid argument #2 (not function)")end;i[X]={Callback=Y}local Z=function()i[X]=nil end;return{remove=Z,Remove=Z}end;if F=="AddPropertyEmulator"then if#E<1 then error("mt-api: Invalid argument count")end;local _=E[1]if type(_)~="string"then error("mt-api: Invalid hook type")end;local a0=p(D,_)local a1=type(a0)if not j[D]then j[D]={}end;if not k[D]then k[D]={}end;j[D][_]={Type=a1}k[D][_]=p(D,_)local a2=function()j[D][_]=nil;k[D][_]=nil end;return{remove=a2,Remove=a2}end;return r(D,...)end;if f[D]and f[D][F]then local a3=f[D][F]return a3["Callback"](p(D,F),unpack(E))end;if i[F]then local a4=i[F]return a4["Callback"](D,p(D,F),unpack(E))end;return r(D,...)end)if m==0 then make_readonly(o)elseif m==2 then else setreadonly(o,true)end end;l()getgenv().MTAPIMutex=true
	
		game.Players.LocalPlayer.Character["Head"]:AddPropertyEmulator("Size")
		wait(0.5)
		game.Players.LocalPlayer.Character["Head"].Size = Vector3.new(5,5,5)
		game.Players.LocalPlayer.Character["Head"].Transparency = 0.9
	end)
end
coroutine.wrap(REXTSH_fake_script)()
local function OAVARHV_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		local args = {
			[1] = workspace.TPS,
			[2] = CFrame.new(Vector3.new(104.05304718018, 3.7450363636017, 144.50581359863), Vector3.new(-0, -0, -1)),
			[3] = Vector3.new(20.015998840332, 31.02379989624, 32.967914581299)
		}
	
		game:GetService("ReplicatedStorage").TPBall:FireServer(unpack(args))
	end)
end
coroutine.wrap(OAVARHV_fake_script)()
local function JTYHMX_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		local args = {
			[1] = workspace.TPS,
			[2] = CFrame.new(Vector3.new(1014.05304718018, 33.7450363636017, 1444.50581359863), Vector3.new(-0, -0, -1)),
			[3] = Vector3.new(202.015998840332, 311.02379989624, 342.967914581299)
		}
	
		game:GetService("ReplicatedStorage").TPBall:FireServer(unpack(args))
	end)
end
coroutine.wrap(JTYHMX_fake_script)()
local function FRWE_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
				for i,balls in pairs(game.Lighting:GetDescendants()) do
					if balls.Name == "TPS" then
						game.ReplicatedStorage.CatchBall:FireServer(balls)
					end
		end
	end)
	
end
coroutine.wrap(FRWE_fake_script)()
local function XVKIRXB_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
				for i,balls in pairs(game.Lighting:GetDescendants()) do
			if balls.Name == "TPS" then
				while true do
					wait()
					game.ReplicatedStorage.CatchBall:FireServer(balls)
				end
			end
		end
	end)
	
end
coroutine.wrap(XVKIRXB_fake_script)()
local function IKONX_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		for i,balls in pairs(game.Lighting:GetDescendants()) do
			if balls.Name == "TPS" then
				game.ReplicatedStorage.CatchBall:FireServer(balls)
				wait()
				game.ReplicatedStorage.DropBall:FireServer(balls)
				end
			end
	end)
	
end
coroutine.wrap(IKONX_fake_script)()
local function PIEH_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		if getgenv().MTAPIMutex~=nil then return end;local function a()if is_protosmasher_caller~=nil then return 0 end;if elysianexecute~=nil then return 1 end;if fullaccess~=nil then return 2 end;if Synapse~=nil then return 3 end;return 4 end;local function b()local c=a()if c==0 then return is_protosmasher_caller end;if c==1 or c==3 then return checkcaller end;if c==2 then return IsLevel7 end;return nil end;if a()==2 then error("mt-api: Exploit not supported")end;local d={}local e={}local f={}local g={}local h={}local i={}local j={}local k={}local function l()local m=a()local n=b()local o=getrawmetatable(game)if m==0 then make_writeable(o)elseif m==2 then fullaccess(o)else setreadonly(o,false)end;local p=o.__index;local q=o.__newindex;local r=o.__namecall;o.__index=newcclosure(function(s,t)if n()then return p(s,t)end;if d[s]and d[s][t]then local u=d[s][t]if u["IsCallback"]==true then return u["Value"](s)else return u["Value"]end end;if g[t]then local v=g[t]if v["IsCallback"]==true then return v["Value"](s)else return v["Value"]end end;if j[s]and j[s][t]then return k[s][t]end;return p(s,t)end)o.__newindex=newcclosure(function(w,x,y)if n()then return q(w,x,y)end;if e[w]and e[w][x]then local z=e[w][x]if z["Callback"]==nil then return else z["Callback"](w,y)return end end;if h[x]then local A=h[x]if A["Callback"]==nil then return else A["Callback"](w,y)return end end;if j[w]and j[w][x]then local B=j[w][x]if type(y)~=B["Type"]then error("bad argument #3 to '"..x.."' ("..B["Type"].." expected, got "..type(x)..")")end;k[w][x]=y;return end;return q(w,x,y)end)local C=isluau and isluau()or false;o.__namecall=newcclosure(function(D,...)local E={...}local F=C and getnamecallmethod()or table.remove(E)if n()then if F=="AddGetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local G=E[1]local H=E[2]local I=E[3]if type(G)~="string"then error("mt-api: Invalid hook type")end;if not d[D]then d[D]={}end;if I==true and type(H)~="function"then error("mt-api: Invalid callback function")end;d[D][G]={Value=H,IsCallback=I}local J=function()d[D][G]=nil end;return{remove=J,Remove=J}end;if F=="AddGlobalGetHook"then local K=E[1]local L=E[2]local M=E[3]if type(K)~="string"then error("mt-api: Invalid hook type")end;if M==true and type(L)~="function"then error("mt-api: Invalid callback function")end;g[K]={Value=L,IsCallback=M}local N=function()g[K]=nil end;return{remove=N,Remove=N}end;if F=="AddSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local O=E[1]local P=E[2]if type(O)~="string"then error("mt-api: Invalid hook type")end;if not e[D]then e[D]={}end;if type(P)=="function"then e[D][O]={Callback=P}else e[D][O]={Callback=nil}end;local Q=function()e[D][O]=nil end;return{remove=Q,Remove=Q}end;if F=="AddGlobalSetHook"then if#E<1 then error("mt-api: Invalid argument count")end;local R=E[1]local S=E[2]if type(R)~="string"then error("mt-api: Invalid hook type")end;if type(S)=="function"then h[R]={Callback=S}else h[R]={Callback=nil}end;local T=function()h[R]=nil end;return{remove=T,Remove=T}end;if F=="AddCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local U=E[1]local V=E[2]if type(U)~="string"then error("mt-api: Invalid hook type")end;if type(V)~="function"then error("mt-api: Invalid argument #2 (not function)")end;if not f[D]then f[D]={}end;f[D][U]={Callback=V}local W=function()f[D][U]=nil end;return{remove=W,Remove=W}end;if F=="AddGlobalCallHook"then if#E<2 then error("mt-api: Invalid argument count")end;local X=E[1]local Y=E[2]if type(X)~="string"then error("mt-api: Invalid hook type")end;if type(Y)~="function"then error("mt-api: Invalid argument #2 (not function)")end;i[X]={Callback=Y}local Z=function()i[X]=nil end;return{remove=Z,Remove=Z}end;if F=="AddPropertyEmulator"then if#E<1 then error("mt-api: Invalid argument count")end;local _=E[1]if type(_)~="string"then error("mt-api: Invalid hook type")end;local a0=p(D,_)local a1=type(a0)if not j[D]then j[D]={}end;if not k[D]then k[D]={}end;j[D][_]={Type=a1}k[D][_]=p(D,_)local a2=function()j[D][_]=nil;k[D][_]=nil end;return{remove=a2,Remove=a2}end;return r(D,...)end;if f[D]and f[D][F]then local a3=f[D][F]return a3["Callback"](p(D,F),unpack(E))end;if i[F]then local a4=i[F]return a4["Callback"](D,p(D,F),unpack(E))end;return r(D,...)end)if m==0 then make_readonly(o)elseif m==2 then else setreadonly(o,true)end end;l()getgenv().MTAPIMutex=true
	
		game.Players.LocalPlayer.Character["Left Leg"]:AddPropertyEmulator("Size")
		wait(0.5)
		game.Players.LocalPlayer.Character["Left Leg"].Massless = true
		game.Players.LocalPlayer.Character["Left Leg"].Size = Vector3.new (12.3, 2.11, 10.2)
		game.Players.LocalPlayer.Character["Left Leg"].Transparency = 0.9
	end)
	
end
coroutine.wrap(PIEH_fake_script)()
local function TXGR_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", true))()
	end)
	
end
coroutine.wrap(TXGR_fake_script)()
local function FNFNDRH_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		local RunService = game:GetService("RunService")
		RunService.RenderStepped:connect(function()
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 22
		end)
		local e = game:GetService("\82\117\110\83\101\114\118\105\99\101") e.RenderStepped:connect(function() local c = game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.Start.Points.StaminaBar c.Size = UDim2.new(0,200,0,3) c.Name = "" end)
	end)
	
end
coroutine.wrap(FNFNDRH_fake_script)()
local function LVXMBYW_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		local RunService = game:GetService("RunService")
		RunService.RenderStepped:connect(function()
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 22
		end)
		local e = game:GetService("\82\117\110\83\101\114\118\105\99\101") e.RenderStepped:connect(function() local c = game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.Start.Points.StaminaBar c.Size = UDim2.new(0,200,0,3) c.Name = "" end)
	end)
	
end
coroutine.wrap(LVXMBYW_fake_script)()
local function LZZTXN_fake_script() -- TextButton_14.LocalScript 
	local script = Instance.new('LocalScript', TextButton_14)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
	
	
	button.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/KNUzQPYS", true))()
	end)
	
end
coroutine.wrap(LZZTXN_fake_script)()
local function EMTKDD_fake_script() -- TextButton_15.LocalScript 
	local script = Instance.new('LocalScript', TextButton_15)
script.Parent.ZIIndex = 10
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Main.Visible = true
		script.Parent.Parent.Parent.Credits.Visible = false
		script.Parent.Parent.Parent.Information.Visible = false
	end)
end
coroutine.wrap(EMTKDD_fake_script)()
local function SBMLZ_fake_script() -- TextButton_16.LocalScript 
	local script = Instance.new('LocalScript', TextButton_16)
script.Parent.ZIIndex = 10

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Main.Visible = false
		script.Parent.Parent.Parent.Credits.Visible = true
		script.Parent.Parent.Parent.Information.Visible = false
	end)
end
coroutine.wrap(SBMLZ_fake_script)()
local function VWOX_fake_script() -- TextButton_17.LocalScript 
	local script = Instance.new('LocalScript', TextButton_17)
script.Parent.ZIIndex = 10
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Main.Visible = false
		script.Parent.Parent.Parent.Credits.Visible = false
		script.Parent.Parent.Parent.Information.Visible = true
	end)
end
coroutine.wrap(VWOX_fake_script)()
local function RHGICX_fake_script() -- TextButton_18.LocalScript 
	local script = Instance.new('LocalScript', TextButton_18)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(RHGICX_fake_script)()
local function TEQIBW_fake_script() -- TextButton_19.LocalScript 
	local script = Instance.new('LocalScript', TextButton_19)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(TEQIBW_fake_script)()
local function AMOM_fake_script() -- TextButton_20.LocalScript 
	local script = Instance.new('LocalScript', TextButton_20)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
end
coroutine.wrap(AMOM_fake_script)()
local function SVMRX_fake_script() -- TextButton_21.LocalScript 
	local script = Instance.new('LocalScript', TextButton_21)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(40, 50, 20)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(SVMRX_fake_script)()
local function SSWUOAQ_fake_script() -- TextButton_22.LocalScript 
	local script = Instance.new('LocalScript', TextButton_22)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(200, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(SSWUOAQ_fake_script)()
local function EDJZFA_fake_script() -- TextButton_23.LocalScript 
	local script = Instance.new('LocalScript', TextButton_23)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	button.MouseButton1Click:Connect(function()
		
	end)
end
coroutine.wrap(EDJZFA_fake_script)()
local function XEHZL_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	script.Parent.Active = true
	script.Parent.Selectable = true
	script.Parent.Draggable = true
	
	
	game:GetService("UserInputService").InputBegan:Connect(function(K,g)
		if g then return end
		if K.KeyCode == Enum.KeyCode.Comma then
			if script.Parent.Visible == true then
				script.Parent.Visible = false
			else
				script.Parent.Visible = true
			end
		end
	end)
	
end
coroutine.wrap(XEHZL_fake_script)()
local function BGJZVR_fake_script() -- TextButton_24.LocalScript 
	local script = Instance.new('LocalScript', TextButton_24)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(BGJZVR_fake_script)()
local function PWBN_fake_script() -- TextButton_25.LocalScript 
	local script = Instance.new('LocalScript', TextButton_25)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(PWBN_fake_script)()
local function HLSAD_fake_script() -- TextButton_26.LocalScript 
	local script = Instance.new('LocalScript', TextButton_26)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	
end
coroutine.wrap(HLSAD_fake_script)()
local function GURYDXZ_fake_script() -- TextButton_27.LocalScript 
	local script = Instance.new('LocalScript', TextButton_27)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(GURYDXZ_fake_script)()
local function YNRBEM_fake_script() -- TextButton_28.LocalScript 
	local script = Instance.new('LocalScript', TextButton_28)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
end
coroutine.wrap(YNRBEM_fake_script)()
local function WJLOTGU_fake_script() -- TextButton_29.LocalScript 
	local script = Instance.new('LocalScript', TextButton_29)

	local button = script.Parent
	local ts = game:GetService("TweenService")
	local ti = TweenInfo.new(0.5, Enum.EasingStyle.Sine, Enum.EasingDirection.In) --you can set that to anything you want
	local tIn = {BackgroundColor3 = Color3.fromRGB(255, 255, 255), TextColor3 = Color3.fromRGB(43, 43, 43)} --colors are up to you
	local tOut = {BackgroundColor3 = Color3.fromRGB(43, 43, 43), TextColor3 = Color3.fromRGB(255, 255, 255)} --colors are up to you
	local createIn = ts:Create(button, ti, tIn) --when mouse ENTERS button
	local createOut = ts:Create(button, ti, tOut) --when mouse LEAVES button
	
	button.MouseEnter:Connect(function()
	
		createIn:Play()
	
	end)
	
	button.MouseLeave:Connect(function()
	
		createOut:Play()
	
	end)
	
	button.MouseButton1Click:Connect(function()
		setclipboard(discord.gg/rj8PXHXmUe)
	end)
end
coroutine.wrap(WJLOTGU_fake_script)()
