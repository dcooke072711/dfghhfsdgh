**This is the notification script!**
*+This is the LocalScript(inside StarterGui)**


local StarterGui = game:GetService("StarterGui")

local Notifications = {
    "PolarWareAPI Injected",
}

local TimeBetweenNotifications = 6

while true do
    for i = 1, #Notifications do
        local Notification = Notifications[i]

        StarterGui:SetCore("SendNotification", {
            Title = "Message",
            Text = Notification,
            Duration = 3
        })

        wait(TimeBetweenNotifications)
    end
end
