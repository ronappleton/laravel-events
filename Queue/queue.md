# Queue Events

## JobExceptionOccurred

### Available Properties

    job (\Illuminat\Contracts\Queue\Job)
    exception (\Throwable)
    connectionName (string)

## JobFailed

### Available Properties

    job (\Illuminat\Contracts\Queue\Job)
    exception (\Throwable)
    connectionName (string)

## JobProcessed

### Available Properties

    job (\Illuminat\Contracts\Queue\Job)
    connectionName (string)

## JobProcessing

### Available Properties

    job (\Illuminat\Contracts\Queue\Job)
    connectionName (string)

## JobQueued

### Available Properties

    connectionName (string)
    id (string|int|null)
    job (\Closure|string|object)

## Looping

### Available Properties

    queue (string)
    connectionName (string)

## WorkerStopping

### Available Properties

    status (int)
