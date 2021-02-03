# Console Events
[Official Repo](https://github.com/laravel/framework/tree/7.x/src/Illuminate/Console/Events)

## ArtisanStarting

### Available Properties

    artisan (\Illuminate\Console\Application)

## CommandFinished

### Available Properties

    input (\Symfony\Component\Input\InputInterface)
    output (\Symfony\Component\Output\OutputInterface)
    command (string)
    exitCode (int)

## CommandStarting

### Available Properties

    input (\Symfony\Component\Input\InputInterface)
    output (\Symfony\Component\Output\OutputInterface)
    command (string)

## ScheduledTaskFailed

### Available Properties

    task (\Illuminate\Console\Scheduling\Event)
    exception (\Throwable)

## ScheduledTaskFinished

### Available Properties

    task (\Illuminate\Console\Scheduling\Event)
    runtime (float)

## ScheduledTaskSkipped

### Available Properties

    task (\Illuminate\Console\Scheduling\Event)

## ScheduledTaskStarting

### Available Properties

    task (\Illuminate\Console\Scheduling\Event)
