# New Hebrew dictation interface

[Open the hosted demonstration](https://twerdster.github.io/hebrew-speech-ipad/).

## Local use

From the repository root, use Python 3 and a browser:

```sh
python3 -m http.server --bind 127.0.0.1 --directory updated/demo
```

Open <http://127.0.0.1:8000/>. No dependency installation or build is required. Camera/microphone APIs require localhost or HTTPS and explicit permission.

## Controls

Load the new Hebrew sample, edit its right-to-left text, and save a UTF-8 text file. Optional dictation requests the browser speech service; audio may be processed by the browser vendor. Read aloud is a new addition using a locally installed Hebrew voice (`localService`), if available.

## Verification and limitations

No original recognizer or research method is implemented. Live microphone recognition, Hebrew recognition accuracy and iPad operation remain untested. Actual sample editing, word count and byte-exact UTF-8 export were checked. A sample paragraph is not recognition output.

Actual Chrome checks on 2026-11-17 exercised the controls and 390-pixel/desktop layouts without JavaScript page errors or horizontal overflow. A narrow viewport is not a physical-device test; Safari/Firefox and physical phone input were not checked. Detailed current checks are in [VALIDATION.json](VALIDATION.json).

New demo source: Aaron Wetzler with agent assistance, 2026, under the scoped [MIT license](LICENSE). Original materials and supplied data retain their separate terms.
