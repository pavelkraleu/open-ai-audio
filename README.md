# Analysis of OpenAI Text-to-speech APIs

## Input text

Inout text is snippet from Czech constitution.

```
My, občané České republiky v Čechách, na Moravě a ve Slezsku,
v čase obnovy samostatného českého státu,
věrni všem dobrým tradicím dávné státnosti zemí Koruny české i státnosti československé,
odhodláni budovat, chránit a rozvíjet Českou republiku
v duchu nedotknutelných hodnot lidské důstojnosti a svobody
```

## Generated Audio
Please see directory [output](https://github.com/pavelkraleu/open-ai-audio/tree/main/output) where are generated MP3 files.

## API response time
Sometime HD models can take very long to response 

![](timing.png)

## Length of generated audio
Generated tracks are not exactly same every time, but their difference is only around 0.5s

![](length.png)
