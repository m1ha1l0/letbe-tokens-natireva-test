# letbe-tokens-natireva-test

Test host for the **Natireva** letbe-ds theme, so a Figma library can import its
tokens **from a URL** (a re-fetchable source) instead of a file/paste import.

Why this exists: the letbe-tokens Figma plugin records how a library got its
tokens. `paste` and `upload` (file) sources exist only on the maintainer's
machine at import time, so files that CONSUME the library can show token names
and apply them, but cannot load the theme for the explorer and contrast proof.
A URL source can be re-fetched by every consumer.

Raw URL for the plugin (Settings → Tokens in → URL):

    https://raw.githubusercontent.com/m1ha1l0/letbe-tokens-natireva-test/main/tokens/source-tokens.json

Disposable — delete once the embedded-JSON approach lands in the plugin.
