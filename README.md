# random-emoji
Generates a random emoji text compatible with slack, github, gitlab, etc and copies to the clipboard.

`:thumbsup:` :thumbsup:

## Usage
```
java -cp path/to/directory/random-emoji RandomEmoji
```

I have it bound to a keyboard shortcut for convenience

## Compile
```
javac -classpath path/to/directory/random-emoji RandomEmoji.java
```

## Notes
The emoji stays on the clipboard for 5 seconds so paste quickly.

I originally got the emojis from some gitlab list but I can't seem to find it.

Each emoji appears with pseudorandom frequency. I removed flags because they were so frequent and weren't that exciting.
