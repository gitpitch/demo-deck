[drag=50 10, drop=0 5, set=front-9]
Diagrams-as-Code

@cloud[drag=50 100, drop=0](src/demo.py)

@mermaid[drag=55 100, drop=right, width=1200, theme=forest](src/demo.mmd)

[drag=50 10, drop=0 -5, set=front-9]
Mermaid Flowcharts
---

[drag=100 10, drop=top, set=front-9]
PlantUML Diagrams

@plantuml[drop=left, pad=30px, width=1000px](src/graph-1.puml)


@plantuml[drop=topright, pad=10px, width=500px](src/graph-2.puml)

[drop=bottomright, pad=10px, width=500px]

<canvas data-chart="line">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[65,59,80,81,56,55,40],
    "label":"Sample Data X",
    "backgroundColor":"rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"Sample Data Y",
    "backgroundColor":"rgba(120,220,0,.8)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>

