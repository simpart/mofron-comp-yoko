# mofron-comp-yoko
[mofron](https://mofron.github.io/mofron/) is module based frontend framework.

yoko input component

this source based on the codrops: https://github.com/codrops/TextInputEffects


# Install
```
npm install mofron mofron-comp-yoko
```

# Sample
```html
<setting>
    <tag load="mofron-comp-yoko">Input</tag>
</setting>

<Input label="yoko input">
    <size>2rem,0.7rem</size>
    <color>#6a7989,#f0e6fa,#ad473c</color>
</Input>
```

# Parameter

| Short<br>Form | Parameter Name | Type | Description |
|:-------------:|:---------------|:-----|:------------|
| | label | mixed | string: label text |
| | | | mofron-comp-text: text component for label |
| | | | undefined: call as getter |
| | width | string (size) | input width |
| | | | undefined: call as getter |
| | | key-value | style option |
| | height | string (size) | input height |
| | | | undefined: call as getter |
| | | key-value | style option |
| | mainColor | mixed (color) | string: label color, #hex |
| | | | array: [red, green, blue, (alpha)] |
| | baseColor | mixed (color) | string: background color, #hex |
| | | | array: [red, green, blue, (alpha)] |
| | accentColor | mixed (color) | string: border color, #hex |
| | | | array: [red, green, blue, (alpha)] |

