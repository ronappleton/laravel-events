#Cache Events 
[Official Repo](https://github.com/laravel/framework/tree/6.x/src/Illuminate/Cache/Events)

##CacheEvent

    key (string)
    tags (array)

###Available Methods

    setTags($tags) (array)

###Available Properties

##CacheHit

###Available Properties

    key (string) (inherited)
    tags (array) (inherited)
    value (mixed)

###Methods Available

    setTags($tags) (array) (inherited)

##CacheMissed

###Available Properties

    key (string) (inherited)
    tags (array) (inherited)

###Methods Available

    setTags($tags) (array) (inherited)

##KeyForgotten

###Available Properties

    key (string) (inherited)
    tags (array) (inherited)

###Methods Available

    setTags($tags) (array) (inherited)

##KeyWritten

###Available Properties

    key (string) (inherited)
    tags (array) (inherited)
    value (mixed)
    seconds (int|null)

###Methods Available

    setTags($tags) (array) (inherited)
