# Auth Events
[Official Repo](https://github.com/laravel/framework/tree/7.x/src/Illuminate/Auth/Events)

## Attempting

### Available Properties

    guard (string)
    remember (bool)
    credentials (array)

## Authenticated

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)

## CurrentDeviceLogout

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)

## Failed

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)
    credentials (array)

## Lockout

### Available Properties

    request (\Illuminate\Http\Request)

## Login

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)
    remember (bool)

## Logout

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)

## OtherDeviceLogout

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)

## PasswordReset

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)

## Registered

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)

## Validated

### Available Properties

    user (\Illuminate\Contracts\Auth\Authenticatable)
    guard (string)

## Verified

### Available Properties

    user (\Illuminate\Contracts\Auth\MustVerifyEmail)
