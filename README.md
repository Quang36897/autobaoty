_G.Config = {
    WebHook = "", -- Discord Webhook
    Team = "Pirate", -- Pirate, Marine
    Time = 120,
    InvisFromKen = true,
    NoStun = true,
    Invisible = false, -- Please use bundle: https://www.roblox.com/bundles/238/Man,
    TpBypass = false,
    Melee = {
        Use = true,
        Z = {
            Use = true,
            Hold = 0.2
        },
        X = {
            Use = true,
            Hold = 0.2
        },
        C = {
            Use = true,
            Hold = 0.2
        }
    },
    Sword = {
        Use = false,
        Z = {
            Use = false,
            Hold = 0.2
        },
        X = {
            Use = false,
            Hold = 0.2
        }
    },
    Gun = {
        Use = false,
        Z = {
            Use = false,
            Hold = 0.1
        },
        X = {
            Use = false,
            Hold = 0.1
        }
    },
    Fruit = {
        Use = true,
        Z = {
            Use = true,
            Hold = 0.2
        },
        X = {
            Use = true,
            Hold = 0.3
        },
        C = {
            Use = false,
            Hold = 0.3
        },
        V = {
            Use = true,
            Hold = 0.3
        },
        F = {
            Use = false,
            Hold = 0.1
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/AlongNgu/AloneHub/main/Bounty%20Beta.lua", true))()
