![Europa Lang](./images/europa.png)
[Discord Server](https://discord.gg/csdaFGd5K9)

# Europa Lang

This language aims to be simple, minimal, and compact. There will not be any classes whatsoever, and importing other files should be painless.

## Example

```europa
use Math;
use Io;

Io.println("Hello, World!");
var input = Io.stdin.readline();
Io.println("You said: " + input);

Io.println("Random Number 0..1: " + Math.random());

var map = {{
    a_map = 'strings can look like this too';
    [1 + 1] = 'expression keys';
}};

Io.println(map['a_map']);
Io.println(map.a_map);
Io.println(map[2]);

fn add_two(a, b) {
    return a + b;
}

var a = true;
var b = true;

while true {
    if a == b {
        break;
    } elif a != b {
        continue;
    } else {
        break;
    }
}

var array = [1, 2, 3];
for i in array {
    Io.println(i);
}
```

## Usage

```sh
cargo run -- [file]
```

## Credits

- @justamirror and Dart for name and language design suggestions.
- @CoolCoderSJ for creating the discord server, along with language design suggestions!
- @SixBeeps for designing the Europa logo!
