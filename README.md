# UI KAYLIS

# Creating the Window

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
