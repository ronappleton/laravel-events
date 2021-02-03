# Notification Events
[Official Repo](https://github.com/laravel/framework/tree/7.x/src/Illuminate/Notifications/Events)

## BroadcastNotificationCreated

### Available Properties

    data (array)
    notifiable (mixed)
    notification (\Illuminate\Notifications\Notification)

### Available Methods

    broadcastOn() (Get the channels the event should broadcast on)
    broadcastWith() (Get the data that should be sent with the broadcasted event)
    broadcastType() (Get the type of the notification being broadcast)

## NotificationFailed

### Available Properties

    data (array)
    channel (string)
    notifiable (mixed)
    notification (\Illuminate\Notifications\Notification)

## NotificationSending

### Available Properties

    channel (string)
    notifiable (mixed)
    notification (\Illuminate\Notifications\Notification)

## NotificationSent

### Available Properties

    channel (string)
    response (mixed)
    notifiable (mixed)
    notification (\Illuminate\Notifications\Notification)
