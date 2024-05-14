local player = {
   "Anthonyz_ohhhhh8"
   ""
}

if game.Players.LocalPlayer.Name == unpack(player) then
local starterGui = game:GetService("StarterGui")

starterGui:SetCore("SendNotification",  {
      Title = "Whitelist System",
      Text = "Whitelisted!",
      Duration = 5
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/User999191/Easy_hub/main/s"))()

else
    local starterGui = game:GetService("StarterGui")

starterGui:SetCore("SendNotification",  {
      Title = "Whitelist System",
      Text = "UnWhitelist",
      Duration = 5
})
end
