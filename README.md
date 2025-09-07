repeat wait() until game:IsLoaded() and game.Players.LocalPlayer

getgenv().KaitunLegendary = {
    ["Hide UI"] = true,

    ["FPS Boost"] = {
        ["Enable"] = true,
        ["FPS Cap"] = 30,
    },

    ["Fast Attack"] = {
        ["Speed Attack"] = 0.1,
        ["Attack Duration"] = 5,
        ["Speed Attack if Cooldown"] = 0.2,
        ["Attack Cooldown"] = 6,
    },

    ["Auto Farm"] = {
        ["Enabled"] = true,
        ["Farm Mastery"] = true,
        ["Weapons"] = {"Cursed Dual Katana", "Soul Guitar", "GodHuman"},
        ["Mastery Health (%)"] = 40,
        ["Farm Bone Get x2 Exp"] = true,
        ["Farm Boss Drops"] = true,
        ["Farm Boss Drops When X2 Expired"] = true,
    },

    ["Auto Quest"] = {
        ["Enabled"] = true,
        ["Hop if Near Farm Area"] = true,
        ["First Farm At Sky"] = true,
    },

    ["Auto Race"] = {
        ["Auto Evo Race"] = true,
        ["Auto Race V2-V3"] = true,
        ["Race Snipping"] = true,
        ["Race Choosen"] = {["Human"] = true},
    },

    ["Auto Awakening"] = {
        ["Awaken Fruit"] = true,
        ["Auto Awaken Fruit"] = true,
        ["Auto Pull Lever"] = true,
        ["Auto Get Mirror Fractal"] = true,
        ["Mirage Puzzle"] = true,
    },

    ["Auto Items"] = {
        ["Auto Saber"] = true,
        ["Auto Pole"] = true,
        ["Soul Guitar"] = true,
        ["Shark Anchor"] = true,
        ["Cursed Dual Katana"] = true,
        ["Buy Stuffs"] = true,
        ["Buy Haki"] = {
            ["Enhancement"] = true,
            ["Skyjump"] = true,
            ["Flash Step"] = true,
            ["Observation"] = true,
        },
        ["Buy Haki Color Legendary"] = true,
    },

    ["Fruit System"] = {
        ["Fruit Snipping"] = true,
        ["Fruit Eating"] = true,
        ["Fruit Choosen"] = {
            ["Dragon-Dragon"] = true,
            ["Leopard-Leopard"] = true,
            ["Dough-Dough"] = true,
            ["Spirit-Spirit"] = true,
            ["Kitsune-Kitsune"] = true,
        },
        ["Hop Fruit 1M Quest Third Sea"] = true,
    },

    ["Hop System"] = {
        ["Enable"] = true,
        ["Hop Player Near"] = true,
        ["High Ping Hop"] = true,
        ["Select Hop"] = {
            ["Hop Find Rip Indra Get Valkyrie Helm"] = true,
            ["Hop Find Full Moon Soul Guitar"] = true,
            ["Hop Find Rip Indra Get Tushita"] = true,
            ["Hop Find Cake Queen [CDK]"] = true,
            ["Hop Find Soul Reaper [CDK]"] = true,
            ["Hop Find Darkbeard [SG]"] = true,
            ["Hop Find Mirage"] = true,
        },
    },

    ["Misc"] = {
        ["Lock Fragment"] = {
            ["Enabled"] = true,
            ["Fragments"] = 30000,
        },
        ["Switch Melee"] = true,
        ["Eat Fruit"] = "",
        ["Snipe Fruit"] = "",
        ["Webhook"] = {
            ["Enabled"] = false,
            ["WebhookUrl"] = "",
        },
    }
}

loadstring(game:HttpGet("https://starlighthub.onrender.com/Kaitun.lua"))()
