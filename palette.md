 # Structure vide
 ```json
"palettes": {  
    "data": [],
    "ui": [] 
 }
  ```

 # Exemple structure palette
```json
 "palettes": {
        "data": [
            {
                "name": "Calm & Neutral",
                "translation": "",
                "propertyValue": "ca5nr",
                "type": "row",
                "scale": [
                    "#97958F",
                    "#774741",
                    "#A7816A",
                    "#CCA59D",
                    "#BF7C4C",
                    "#E1C189",
                    "#788F8F",
                    "#727352",
                    "#BDB894",
                    "#90B1D4",
                    "#CBD3D7",
                    "#5C5E60",
                    "#CABDB1",
                    "#D0C9CF",
                    "#CCCCCC"
                ]
            },
            {
                "name": "QS Breeze",
                "translation": "",
                "propertyValue": "n2gij",
                "type": "row",
                "scale": [
                    "#138185",
                    "#26A0A7",
                    "#65D3DA",
                    "#70BA6E",
                    "#578B60",
                    "#CBE989",
                    "#F9EC86",
                    "#ECC43D",
                    "#EC983D",
                    "#FF8080",
                    "#A54343"
                ]
            }
        ],
        "ui": [
            {
                "name": "Calm & neutral",
                "colors": [
                    "#97958F",
                    "#774741",
                    "#A7816A",
                    "#CCA59D",
                    "#BF7C4C",
                    "#E1C189",
                    "#788F8F",
                    "#727352",
                    "#BDB894",
                    "#90B1D4",
                    "#CBD3D7",
                    "#5C5E60",
                    "#CABDB1",
                    "#D0C9CF",
                    "#E4E1DD",
                    "#CCCCCC",
                    "#eeeeee",
                    "#ffffff",
                    "#000000"
                ]
            },
            {
                "name": "QS Breeze",
                "colors": [
                    "#B0AFAE",
                    "#7B7A78",
                    "#A54343",
                    "#FF8080",
                    "#EC983D",
                    "#ECC43D",
                    "#F9EC86",
                    "#CBE989",
                    "#70BA6E",
                    "#578B60",
                    "#79D69F",
                    "#26A0A7",
                    "#138185",
                    "#65D3DA",
                    "#ffffff",
                    "#000000"
                ]
            }
        ]
    }
   ```
    
    
  # Scales exemple
  
  ```json
    "scales": [
  {
    "name": "Light colors sequential gradient",
    "translation": "Light colors sequential gradient",
    "type": "gradient",
    "propertyValue": "sg",
    "scale": [ "#8C8C8C", "#FBFBFB" ]
  },
  {
    "name": "Light colors sequential classes",
    "translation": "Light colors sequential classes",
    "propertyValue": "sc",
    "type": "class",
    "scale": [ "#8C8C8C", "#FBFBFB" ]
  },
  {
    "name": "Dark colors diverging gradient",
    "translation": "Dark colors diverging gradient",
    "propertyValue": "dg",
    "type": "gradient",
    "scale": [ "#737373", "#0D0D0D" ]
  },
  {
    "name": "Dark colors diverging classes",
    "translation": "Dark colors diverging classes",
    "propertyValue": "dc",
    "type": "class",
    "scale": [ "#737373", "#0D0D0D" ]
  }
]
 ```

# Full code palettes exemple
    
  ```json
    {
  "_inherit": false,
  "_variables" : {
    "@grayscale-100" : "#FFFFFF",
    "@grayscale-98" : "#FBFBFB",
    "@grayscale-95" : "#F2F2F2",
    "@grayscale-90" : "#E6E6E6",
    "@grayscale-85" : "#D9D9D9",
    "@grayscale-80" : "#CCCCCC",
    "@grayscale-75" : "#BFBFBF",
    "@grayscale-70" : "#B3B3B3",
    "@grayscale-65" : "#A6A6A6",
    "@grayscale-60" : "#999999",
    "@grayscale-55" : "#8C8C8C",
    "@grayscale-50" : "#808080",
    "@grayscale-45" : "#737373",
    "@grayscale-40" : "#666666",
    "@grayscale-35" : "#595959",
    "@grayscale-30" : "#4D4D4D",
    "@grayscale-28" : "#474747",
    "@grayscale-25" : "#404040",
    "@grayscale-20" : "#333333",
    "@grayscale-15" : "#262626",
    "@grayscale-10" : "#1A1A1A",
    "@grayscale-5" : "#0D0D0D",
    "@grayscale-0" : "#000000",
    "@text" : "13px"
  },
  "color": "@grayscale-20",
  "fontSize": "@text",
  "backgroundColor": "@grayscale-95",
  "dataColors": {
    "primaryColor": "@grayscale-28",
    "othersColor": "@grayscale-55",
    "errorColor": "@grayscale-90",
    "nullColor": "@grayscale-85"
  },
  "palettes" : {
    "data" : [
      {
        "name": "Dark colors",
        "translation": "Dark colors",
        "propertyValue": "12",
        "type": "row",
        "scale": [
          "#808080",
          "#737373",
          "#666666",
          "#595959",
          "#4D4D4D",
          "#474747",
          "#404040",
          "#333333",
          "#262626",
          "#1A1A1A",
          "#0D0D0D",
          "#000000"
        ]
      },
      {
        "name": "Light colors",
        "translation": "Light colors",
        "propertyValue": "11",
        "type": "row",
        "scale": [
          "#FFFFFF",
          "#FBFBFB",
          "#F2F2F2",
          "#E6E6E6",
          "#D9D9D9",
          "#CCCCCC",
          "#BFBFBF",
          "#B3B3B3",
          "#A6A6A6",
          "#999999",
          "#8C8C8C"
        ]
      }
    ],
    "ui": [
      {
        "name": "Palette",
        "colors": [
          "#FFFFFF",
          "#FBFBFB",
          "#F2F2F2",
          "#D9D9D9",
          "#BFBFBF",
          "#A6A6A6",
          "#8C8C8C",
          "#808080",
          "#737373",
          "#595959",
          "#474747",
          "#404040",
          "#262626",
          "#0D0D0D",
          "#000000"
        ]
      }
    ]
  },
  "scales": [
    {
      "name": "Light colors sequential gradient",
      "translation": "Light colors sequential gradient",
      "type": "gradient",
      "propertyValue": "sg",
      "scale": [ "#8C8C8C", "#FBFBFB" ]
    },
    {
      "name": "Light colors sequential classes",
      "translation": "Light colors sequential classes",
      "propertyValue": "sc",
      "type": "class",
      "scale": [ "#8C8C8C", "#FBFBFB" ]
    },
    {
      "name": "Dark colors diverging gradient",
      "translation": "Dark colors diverging gradient",
      "propertyValue": "dg",
      "type": "gradient",
      "scale": [ "#737373", "#0D0D0D" ]
    },
    {
      "name": "Dark colors diverging classes",
      "translation": "Dark colors diverging classes",
      "propertyValue": "dc",
      "type": "class",
      "scale": [ "#737373", "#0D0D0D" ]
    }
  ]
}
