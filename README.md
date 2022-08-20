# Unexpected behavior of Vimium with closed custom elements

In normal `textarea` and `textarea` in open custom elements, shortcuts defined in Vimium are disabled and I can input these keys. However, in `textarea` in closed custom elements, shortcuts are handled by Vimium and I cannot input these keys.

Expected:

I can input keys defined as shortcuts to `textarea` in closed custom elements.

## How to test

1. Start a server
    - e.g. `python3 -m http.server --bind localhost 8080`
2. Open `http://localhost:8080/`

## Tested on

- Microsoft Edge 104.0.1293.54 and Vimium 1.67
- Google Chrome 104.0.5112.102 and Vimium 1.67
