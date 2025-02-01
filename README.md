-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()

-- janela principal

local Window = Fluent:CreateWindow({
    Title = "Cael Hub" .. Fluent.Version,
    SubTitle = "by Cael",
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
})

-- abas

local Tabs = {
    Main = Window:AddTab({ Title = "Descrição", Icon = "" }),
    Insta = Window:AddTab({ Title = "Instagram", Icon = "" }),
    Youtube = Window:AddTab({ Title = "YouTube", Icon = "" }),
    Insta da muie = Window:AddTab({ Title = "Instagram da minha mulher", Icon = "" }),
    Discord= Window:AddTab({ Title = "Discord", Icon = "" }),
    Brook= Window:AddTab({ Title = "Brookhaven", Icon = "" }),
    Blox = Window:AddTab({ Title = "Blox fruit", Icon = "" }),
    Emotes = Window:AddTab({ Title = "Emotes", Icon = "" }),
    Eu = Window:AddTab({ Title = "Cael Hub", Icon = "" }),
    Hora = Window:AddTab({ Title = "Script de hora", Icon = "" }),
    Settings = Window:AddTab({ Title = ".", Icon = "settings" })
}

-- notificacao

    Fluent:Notify({
        Title = "Cael Hub script executado",
        Content = "Script executado com sucesso",
        SubContent = "Cael Hub agradece", -- Optional
        Duration = 9 -- Set to nil to make the notification not disappear
    })
    Fluent:Notify({
        Title = "REDES SOCIAIS",
        Content = "Fique por dentro de tudo seguindo as redes sociais do cael",
        SubContent = "Ana Sofia Agradece", -- Optional
        Duration = 5 -- Set to nil to make the notification not disappear
    })
    Fluent:Notify({
        Title = "Instagram",
        Content = "Siga a conta da minha mulher pra ficar por dentro dos scripts dela",
        SubContent = "Cael Hub agradece👍", -- Optional
        Duration = 7 -- Set to nil to make the notification not disappear
    })

-- parágrafo

    Tabs.Main:AddParagraph({
        Title = "Cael hub",
        Content = "Como que eu comecei a criar scripts? eu tava bebendo ai me veio uma vontade de criar um script so que eu não sabia 
como que criava ai eu fui e procurei e achei ate hoje tou criando esses script"
    })
    Tabs.Insta:AddParagraph({
        Title = "Meu Instagram",
        Content = "(carlosdanielsilv708) uma foto de um caminhão com um cachorro"
    })
    Tabs.Youtube:AddParagraph({
        Title = "Meu YouTube",
        Content = "(CaelHub)"
    })
    Tabs.Insta da muie:AddParagraph({
        Title = "Insta da mulher se não acha vai tar na minha bio do insta",
        Content = "ana_gabriela_1344848"
    })
    Tabs.Blox:AddParagraph({
        Title = "Scripts de blox fruits",
        Content = "Vou por esses script depois"
    })

-- botao

BrookTab:AddButton({
    Title = "Clique-me",
    Callback = function()
        print("Botão clicado!")
    end
})
BrookTab:AddButton({
    Title = "Rael Hub",
    Callback = function()
        print("loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")()")
    end
})
EmotesTab:AddButton({
    Title = "Clique-me",
    Callback = function()
        print("Botão clicado!")
    end
})
EuTab:AddButton({
    Title = "Cael hub",
    Callback = function()
        print("loadstring(game:HttpGet"https://raw.githubusercontent.com/carlin157/Cael-hub/refs/heads/main/README.md")()")
    end
})
HoraTab:AddButton({
    Title = "Sirius",
    Callback = function()
        print("loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Sirius-7420"))()")
    end
})
BrookTab:AddButton({
    Title = "Sander X",
    Callback = function()
        print("loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))()")
    end
})
BrookTab:AddButton({
    Title = "Sander X 341",
    Callback = function()
        print("loadstring(game:HttpGet(('https://raw.githubusercontent.com/kigredns/sander341/main/sanderx341')))()")
    end
})
