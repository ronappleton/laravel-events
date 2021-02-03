# Redis Events
[Official Repo](https://github.com/laravel/framework/tree/6.x/src/Illuminate/Redis/Events)

## CommandExecuted

## Available Properties

    time (float)
    command (string)
    parameters (array)
    connection (\Illuminate\Redis\Connections\Connection)
    connectionName (string) (pulled from connection object)

