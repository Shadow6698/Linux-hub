-- Rayfield Load
local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

-- Janela Principal
local Window = Rayfield:CreateWindow({
    Name = "🐧 Linux Hub",
    LoadingTitle = "🐧 Linux Hub V3",
    LoadingSubtitle = "by Nightmare",
    ConfigurationSaving = {
        Enabled = true,
        FolderName = nil,
        FileName = "🐧 Linux Hub"
    },
    Discord = {
        Enabled = false,
        Invite = "noinvitelink",
        RememberJoins = true
    },
    KeySystem = false,
    KeySettings = {
        Title = "Untitled",
        Subtitle = "Key System",
        Note = "No method of obtaining the key is provided",
        FileName = "Key",
        SaveKey = true,
        GrabKeyFromSite = false,
        Key = {"Hello"}
    }
})

-- Criação das Abas
local ScriptsTab = Window:CreateTab("📜 Scripts 🐧", nil)
local AdminTab = Window:CreateTab("👑 Admin 🐧", nil)
local ScriptsNovosTab = Window:CreateTab("✨ Scripts Novos 🐧", nil)
local BrookhavenTab = Window:CreateTab("🏘️ Brookhaven 🐧", nil)
local TrollTab = Window:CreateTab("😈 Troll 🐧", nil)
local ExtrasTab = Window:CreateTab("🎯 Extras 🐧", nil)
local FarmsTab = Window:CreateTab("🌾 Farms 🐧", nil)
local ToolsTab = Window:CreateTab("🔧 Tools 🐧", nil)
local ImunesTab = Window:CreateTab("🛡️ Imunes 🐧", nil)
local PlayersTab = Window:CreateTab("👤 Players 🐧", nil)

-- Seções de Cada Aba
local ScriptsSection = ScriptsTab:CreateSection("Principais Scripts")
local AdminSection = AdminTab:CreateSection("Comandos Admin")
local ScriptsNovosSection = ScriptsNovosTab:CreateSection("Scripts Novos")
local BrookhavenSection = BrookhavenTab:CreateSection("Scripts Brookhaven")
local TrollSection = TrollTab:CreateSection("Scripts de Troll")
local ExtrasSection = ExtrasTab:CreateSection("Scripts Extras")
local FarmsSection = FarmsTab:CreateSection("Scripts de Farm")
local ToolsSection = ToolsTab:CreateSection("Ferramentas e Armas")
local ImunesSection = ImunesTab:CreateSection("Proteções e Imunidades")
local PlayersSection = PlayersTab:CreateSection("Métodos")

-- Notificação Inicial
Rayfield:Notify({
    Title = "🐧 Linux Hub Carregado! 🐧",
    Content = "Bem-vindo ao 🐧 Linux Hub V3",
    Duration = 6.5,
    Image = nil,
    Actions = {
        Ignore = {
            Name = "OK",
            Callback = function()
                print("🐧 Linux Hub iniciado com sucesso!")
            end
        },
    },
})

-- Scripts Principais
ScriptsTab:CreateButton({
    Name = "Fê Emotes",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Ghost Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end,
})



ScriptsTab:CreateButton({
    Name = "Pesquisar Scripts",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/ScriptSearcher"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "R4D",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Rael Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Save Servers",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Sabe-servers/main/Main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Nameless Admin",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ltseverydayyou/Nameless-Admin/main/Source.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Sander X",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "System Broken",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/H20CalibreYT/SystemBroken/main/script"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "View Itens",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/View-itens/main/main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "View Players",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/View/main/main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Void",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Void-fe/main/main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "freeze emotes",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Lockemotes/main/Main.txt"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Tiger Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/balintTheDevX/Tiger-X-V3/main/Tiger%20X%20V3.5%20Fixed"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Aimbot",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/qtZt0Nzb"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Hub Universal",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubekitten/SCRIPTHUBV3/main/SCRIPTHUBV3"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Salvatore",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RFR-R1CH4RD/Loader/main/Salvatore.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Draw FE",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Affexter/Programs/refs/heads/main/scripts/tooldrawFE.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Multiplicar Tools",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/kigredns/NeonDuplicator/refs/heads/main/Script.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Chaos Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Venom-devX/ChaosHub/main/loader.lua"))()
    end,
})

ScriptsTab:CreateButton({
    Name = "Rebobination",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/rebobination/main/Main.txt"))()
    end,
})

-- Comandos Admin
AdminTab:CreateButton({
    Name = "Nameless Admin",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ltseverydayyou/Nameless-Admin/main/Source.lua"))()
    end,
})

AdminTab:CreateButton({
    Name = "Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end,
})

AdminTab:CreateButton({
    Name = "Reviz Admin",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/Caniwq2N"))()
    end,
})

AdminTab:CreateButton({
    Name = "CMD-X",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source"))()
    end,
})

AdminTab:CreateButton({
    Name = "Fates Admin",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
    end,
})

AdminTab:CreateButton({
    Name = "Angel Cmds",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/angel-commands/main/Main.txt"))()
    end,
})

AdminTab:CreateButton({
    Name = "AntKick",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/antkick/main/Main.txt"))()
    end,
})

AdminTab:CreateButton({
    Name = "/helpadm",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/spawngenio/main/Main.txt"))()
    end,
})

AdminTab:CreateButton({
    Name = "helpbiel",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/helpbiel/main/Main.txt"))()
    end,
})

AdminTab:CreateButton({
    Name = "helpangel",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/helpangel/main/Main.txt"))()
    end,
})

AdminTab:CreateButton({
    Name = "helpgeison",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/helpgeison/main/Main.txt"))()
    end,
})

-- Scripts Novos
ScriptsNovosTab:CreateButton({
    Name = "Combo Universal",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub"))()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Combo de Brookhaven",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JaozinScripts/Gumball-Hub/refs/heads/main/GumballHubRetorn2.1.1.1.lua"))()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt"))()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Combo de Vazar KK",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Void-fe/main/main.txt"))()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Speed-2/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "TP Magic",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/doctorestranho/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "CopyHub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/copychat/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "HeadSitHub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/headsit/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Bot",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/bot/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Ping",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/fpsgui/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Hub de Utilidades",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/utilidades/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "MagoByte Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/hubsecrety/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Hub Games",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/hubofhubs/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Rochips Scripts",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/rochipshub-v3-/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Bug Players",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Glitch-fe-44756"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Realistic FX",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-BrookHaven-UltraFX-44718"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Spam Chat [No Abuse]",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/spam/main/Main.txt"))()
    end,
})

ScriptsNovosTab:CreateButton({
    Name = "Unban House",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Main.txt/main/Main.txt"))()
    end,
})

-- Scripts Brookhaven
BrookhavenTab:CreateButton({
    Name = "Gumball Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JaozinScripts/Gumball-Hub/refs/heads/main/GumballHubRetorn2.1.1.1.lua"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Sander X",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Sander-XY-35845"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Chaos Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Venom-devX/ChaosHub/main/loader.lua"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Rael Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Shadow Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/realgengar/scripts/refs/heads/main/Gui%20Version.Lua"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "IceHub (Precisa de Key)",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Orbit-x-IceHub-Loads-of-features-31605"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Speed Wave",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/vheiclespeed/main/Main.txt"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Duplicator Carros",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/kigredns/Flame-Object/refs/heads/main/script.lua"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Coquette Hub",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Coquette-Hub-41921"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Yin Hub (executa Ayla Hub)",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Yin-Hub-21835"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "SP Hub",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-SP-Hub-New-Uptade-1o3v-33364"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Brutus Hub",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-BRUTUS-HUB-REUPLOUD-44098"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Nytherune Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/wx-sources/spacecomm/refs/heads/main/nytheruneplus"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Demon Hub [só presta as abas com português]",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-DemoV-46268"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "Jeon Hub",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Jeon-26588"))()
    end,
})

BrookhavenTab:CreateButton({
    Name = "UwU Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Execute666j/TESTE/refs/heads/main/zinac%20luraph.txt"))()
    end,
})

-- Scripts de Troll
TrollTab:CreateButton({
    Name = "ChatSpy",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/spychat/main/Main.txt"))()
    end,
})

TrollTab:CreateButton({
    Name = "Glue",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/gluegui/main/Main.txt"))()
    end,
})

-- Scripts Extras
ExtrasTab:CreateButton({
    Name = "God Mode",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/godmode/main/Main.txt"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Evade",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/evade/main/Main.txt"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Modo Gigante",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-FE-BIG-AVATAR-43381"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Virar Bola KKJ",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fe-ball-rolL-9835"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "c00lkid Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/COOLKIDHUB/main/Main.txt"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Dia Infinito",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/time-lock/main/README.md"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Angel Executor",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Executor-script/main/Main.txt"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Sky Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/FE%20Trolling%20GUI.luau"))()
    end,
})

ExtrasTab:CreateButton({
    Name = "Rejoin",
    Callback = function()
        game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
    end,
})

ExtrasTab:CreateButton({
    Name = "Server Hop",
    Callback = function()
        local Http = game:GetService("HttpService")
        local TPS = game:GetService("TeleportService")
        local Api = "https://games.roblox.com/v1/games/"

        local _place = game.PlaceId
        local _servers = Api.._place.."/servers/Public?sortOrder=Asc&limit=100"
        
        function ListServers(cursor)
            local Raw = game:HttpGet(_servers .. ((cursor and "&cursor="..cursor) or ""))
            return Http:JSONDecode(Raw)
        end

        local Server, Next; repeat
            local Servers = ListServers(Next)
            Server = Servers.data[1]
            Next = Servers.nextPageCursor
        until Server

        TPS:TeleportToPlaceInstance(_place,Server.id,game.Players.LocalPlayer)
    end,
})

ExtrasTab:CreateButton({
    Name = "Speed",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Speed-2/main/Main.txt"))()
    end,
})

-- Scripts de Farm
FarmsTab:CreateButton({
    Name = "Farm Ballon",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/ballonfarm/main/Main.txt"))()
    end,
})

FarmsTab:CreateButton({
    Name = "AutoTickets",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/farmbrookhaven/main/Main.txt"))()
    end,
})

FarmsTab:CreateButton({
    Name = "RealzX Hub (HubFarms)",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-RealzXHub-New-Event-44226"))()
    end,
})

-- Tools Scripts
ToolsTab:CreateButton({
    Name = "Arma de Portais",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Arma-de-portais-/main/Main.txt"))()
    end,
})

ToolsTab:CreateButton({
    Name = "Portal Gun",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Portal-gun-/main/Main.txt"))()
    end,
})

ToolsTab:CreateButton({
    Name = "Buraco Negro Tool",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-Blackhole-Tool-Control-Unanc*d-Parts-27791"))()
    end,
})

ToolsTab:CreateButton({
    Name = "Gravity Gun",
    Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Telekinesis-12332"))()
    end,
})

ToolsTab:CreateButton({
    Name = "Ioio da Ladybug",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/ladybug/main/Main.txt"))()
    end,
})

-- Scripts Imunes
ImunesTab:CreateButton({
    Name = "Ant Coquette Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/antbug/main/main.txt"))()
    end,
})

ImunesTab:CreateButton({
    Name = "ant chaos hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/removeplayers/main/Main.txt"))()
    end,
})

-- Players > Métodos
PlayersTab:CreateButton({
    Name = "Bring",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Bring/main/Main.txt"))()
    end,
})

PlayersTab:CreateButton({
    Name = "Kill Players",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/Kill/main/main.txt"))()
    end,
})

PlayersTab:CreateButton({
    Name = "Hub de Espionar",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/guiview/main/Main.txt"))()
    end,
})

PlayersTab:CreateButton({
    Name = "Player Informations",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Shadow6698/informations/main/Main.txt"))()
    end,
})

print("🐧 Linux Hub V3 carregado com sucesso! - Criado por Nightmare")
