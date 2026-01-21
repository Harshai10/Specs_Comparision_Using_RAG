## Specification Comparator with Basic RAG
<hr>

### Compare technical specifications between two PDF documents using OpenAI GPT models and display them in a clean d format. Export results to Excel for further analysis.
<hr> 

Features

  - Upload two PDF datasheets for comparison

  - Extracts key specifications using OpenAI GPT

  - Compares values for each specification side by side

  - Displays results in an interactive table in Streamlit

  - Download comparison results as an Excel file

  - Handles missing or incomplete data gracefully

  <hr>

<img width="1846" height="737" alt="Screenshot 2026-01-20 192630" src="https://github.com/user-attachments/assets/26af651b-42a0-48cc-a30f-c822160b61a1" />

<hr>

Output in Streamlit is like:

<table>Specification Comparator with Basic RAG
Upload First PDF

iph16specs.pdf
Drag and drop file here
Limit 200MB per file • PDF
iph16specs.pdf
171.6KB
Upload Second PDF

Samsung Galaxy S24 Ultra Specifications.pdf
Drag and drop file here
Limit 200MB per file • PDF
Samsung Galaxy S24 Ultra Specifications.pdf
131.4KB


Comparison Table:
 

Specification

File 1

File 2

0

company

Apple

Samsung

1

product/Model Number

iPhone 16

Galaxy S24 Ultra

2

NETWORK Technology

GSM / CDMA / HSPA / EVDO / LTE / 5G

GSM / CDMA / HSPA / EVDO / LTE / 5G

3

LAUNCH Announced

2024, September 09

N/A

4

LAUNCH Status

Available. Released 2024, September 20

Release 2024, January 24

5

BODY Dimensions

147.6 x 71.6 x 7.8 mm

162.3 x 79 x 8.6 mm

6

BODY Weight

170 g

232 g or 233 g

7

BODY Build

Glass front (Corning-made glass), glass back (Corning-made glass), aluminum frame

Glass front (Gorilla Glass Armor), glass back (Gorilla Glass), titanium frame

8

BODY SIM

Nano-SIM and eSIM - International

Nano-SIM and eSIM/ Dual eSIM or Dual SIM (2 Nano-SIMs and eSIM, dual stand-by)

9

BODY IP Rating

IP68 dust/water resistant (up to 6m for 30 min)

IP68 dust/water resistant (up to 1.5m for 30 min)</table>

<code>
</code>
