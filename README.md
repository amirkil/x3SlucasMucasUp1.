local PlaceId = game.PlaceId

if PlaceId == 2753915549 or PlaceId == 4442272183 or PlaceId == 7449423635 then
   loadstring(game:HttpGet"https://raw.githubusercontent.com/amirkil/x3SlucasMucasUp1/main/README.md")();
elseif PlaceId == 3956818381 then
	loadstring(game:HttpGet"https://raw.githubusercontent.com/amirkil/How/main/README.md")();
else
	game.Players.LocalPlayer:kick("สคริปไม่มีเกมนี้ ไอ้เวร")
	wait(1)
	game:Shutdown()
end
