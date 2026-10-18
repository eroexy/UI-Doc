# Window
    local Window = kaylis:CreateWindow({
        Title = "I love kay!",
        SubTitle = "Made by X3D!",
        ToggleKey = Enum.KeyCode.RightShift,
        CompactLeftSide = false, -- Changes the Width of the TabSide
        WindowSize = UDim2.fromOffset(500, 370),
        WindowCornerSize = UDim.new(0, 12),
        EnableHubImage = true,
        HubImage = "rbxassetid://82795327169782",
    })

    Window Functions

    Window:SetVisible(boolean)

    Window:Destroy()

# Tab
    
    Home = win:CreateTab({Text = "Home", Icon = "house"})

    Tab Functions

    Home:SetActive()
    
    Home:SetVisible(boolean)

    Home:SetText("string")

    Home:SetIcon("swords")

    Better use of tabs is using tables

    local Tabs = {}
    Tabs.Home = win:CreateTab({Text = "Home", Icon = "house"})
