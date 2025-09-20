# Actionfile examples and tests


Examples and testcases for Actionfile excutor implementations


### info

This file is a basic Actionfile that contains testcases.


### basic
```sh
action basic.md
```

    Hello, World!


### config
```sh
action config.md
```

    Hello, World!


### `override test`
```sh
action test.md --arg TEST_TEXT="Cruel world!"
```

    Cruel world!


### `override config`
```sh
action config.md --arg TEST_TEXT="Cruel world!"
```

    Cruel world!


### default run
```sh
echo "This is the default action for this actionfile. Others are:"
action . --list-actions
```

    This is the default action for this actionfile. Others are:
    basic
    config
    override test
    override config
    default
    run

