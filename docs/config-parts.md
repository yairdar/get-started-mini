# Configs parts

## SDK Man

`curl -s "https://beta.sdkman.io" | bash`

```yaml
title: import-sdk-paker
kind: shell.config.part
content: |-
    #THIS MUST BE AT THE END OF THE FILE FOR SDKMAN TO WORK!!!
    export SDKMAN_DIR="$HOME/.sdkman"
    [[ -s "$HOME/.sdkman/bin/sdkman-init.sh" ]] && source "$HOME/.sdkman/bin/sdkman-init.sh"
placement:
    location:
        - end-of-file:
    targets:
        - ~/.zshrc
        - ~/.bashrc
```

```
# 8.0.312
sdk install java 8.0.312-zulu
sdk use java 8.0.312-zulu
sdk default java 8.0.312-zulu

sdk install maven
sdk install clojure
```