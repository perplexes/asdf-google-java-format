# asdf-google-java-format

An asdf/mise plugin for [google-java-format].

## Install
```sh
mise plugin add google-java-format https://github.com/perplexes/asdf-google-java-format
mise ls-remote google-java-format
mise install google-java-format 1.28.0
mise use -g google-java-format@1.28.0
```

## Dependencies
- `java` (JRE/JDK 11+ on PATH)
- `python3` (for google-java-format-diff)
- `curl`, `awk`, `sed`, `openssl` (install-time)

## Provided commands
- `google-java-format`
- `google-java-format-diff`

