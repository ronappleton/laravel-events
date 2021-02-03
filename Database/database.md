# Database Events

## ConnectionEvent

### Available Properties

    connection (\Illuminate\Database\Connection)
    connectionName (string)

## DatabaseRefreshed

### Available Properties

    none

## MigrationEnded

### Available Properties

    method (string) (inherited)
    migration (\Illuminate\Database\Migrations\Migration) (inherited)

## MigrationEvent

### Available Properties

    method (string)
    migration (\Illuminate\Database\Migrations\Migration)

## MigrationStarted

### Available Properties

    method (string)
    migration (\Illuminate\Database\Migrations\Migration)

## MigrationsEnded

### Available Properties

    none

## MigrationsStarted

### Available Properties

    none

## NoPendingMigrations

### Available Properties

    method (string)

## QueryExecuted

### Available Properties

    sql (string)
    time (float|null)
    bindings (array)
    connection (\Illuminate\Database\Connection)
    connectionName (string) (pulled from the connection)

## SchemaDumped

### Available Properties

    connection (\Illuminate\Database\Connection)
    connectionName (string) (pulled from the connection)
    path (string)

## SchemaLoaded

### Available Properties

    connection (\Illuminate\Database\Connection)
    connectionName (string) (pulled from the connection)
    path (string)

## StatementPrepared

### Available Properties

    statement (\PDOStatement)
    connection (\Illuminate\Database\Connection)

## TransactionBeginning

### Available Properties

    connection (\Illuminate\Database\Connection) (inherited)
    connectionName (string) (inherited and pulled from the connection)

## TransactionCommitted

### Available Properties

    connection (\Illuminate\Database\Connection) (inherited)
    connectionName (string) (inherited and pulled from the connection)

## TransactionRolledBack

### Available Properties

    connection (\Illuminate\Database\Connection) (inherited)
    connectionName (string) (inherited and pulled from the connection)
