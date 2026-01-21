## Specification Comparator with Basic RAG
<hr>
#### Compare technical specifications between two PDF documents using OpenAI GPT models and display them in a clean tabular format. Export results to Excel for further analysis.
<hr> 

Features

  - Upload two PDF datasheets for comparison

  - Extracts key specifications using OpenAI GPT

  Compares values for each specification side by side

  Displays results in an interactive table in Streamlit

  Download comparison results as an Excel file

  Handles missing or incomplete data gracefully

  <hr>

<img width="1846" height="737" alt="Screenshot 2026-01-20 192630" src="https://github.com/user-attachments/assets/26af651b-42a0-48cc-a30f-c822160b61a1" />

<hr>

Output in Streamlit is like:

<code>Specification Comparator with Basic RAG
Upload First PDF

No file chosen
Drag and drop file here
Limit 200MB per file • PDF
iph16specs.pdf
171.6KB
Upload Second PDF

No file chosen
Drag and drop file here
Limit 200MB per file • PDF
Samsung Galaxy S24 Ultra Specifications.pdf
131.4KB


Comparison Results:

{
"company":[
0:"Apple"
1:"Samsung"
]
"product/Model Number":[
0:"iPhone 16"
1:"Galaxy S24 Ultra"
]
"NETWORK Technology":[
0:"GSM / CDMA / HSPA / EVDO / LTE / 5G"
1:"GSM / CDMA / HSPA / EVDO / LTE / 5G"
]
"LAUNCH Announced":[
0:"2024, September 09"
1:"N/A"
]
"LAUNCH Status":[
0:"Available. Released 2024, September 20"
1:"Release 2024, January 24"
]
"BODY Dimensions":[
0:"147.6 x 71.6 x 7.8 mm"
1:"162.3 x 79 x 8.6 mm"
]
"BODY Weight":[
0:"170 g"
1:"232 g or 233 g"
]
"BODY Build":[
0:"Glass front (Corning-made glass), glass back (Corning-made glass), aluminum frame"
1:"Glass front (Gorilla Glass Armor), glass back (Gorilla Glass), titanium frame"
]
"BODY SIM":[
0:"Nano-SIM and eSIM - International, Dual eSIM with multiple numbers - USA, Dual SIM (Nano-SIM, dual stand-by) - China"
1:"Nano-SIM and eSIM/ Dual eSIM or Dual SIM (2 Nano-SIMs and eSIM, dual stand-by)"
]
"BODY IP Rating":[
0:"IP68 dust/water resistant (up to 6m for 30 min)"
1:"IP68 dust/water resistant (up to 1.5m for 30 min)"
]
"DISPLAY Type":[
0:"Super Retina XDR OLED, HDR10, Dolby Vision"
1:"Dynamic LTPO AMOLED 2X, 120Hz, HDR10+"
]
"DISPLAY Size":[
0:"6.1 inches"
1:"6.8 inches"
]
"DISPLAY Resolution":[
0:"1179 x 2556 pixels"
1:"1440 x 3120 pixels"
]
"DISPLAY Protection":[
0:"Ceramic Shield glass (2024 gen)"
1:"Corning Gorilla Glass Armor"
]
"PLATFORM OS":[
0:"iOS 18"
1:"Android 14, One UI 6.1"
]
"PLATFORM Chipset":[
0:"Apple A18 (3 nm)"
1:"Qualcomm SM8650-AC Snapdragon 8 Gen 3 (4 nm)"
].......
</code>
