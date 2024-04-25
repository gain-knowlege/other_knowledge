
- Official doc: https://mermaid.js.org/intro/
- Support some kinds of chart
  - Flowchart
  - Sequence diagram
  - Gantt diagram
  - Class diagram
  - Git graph
  - Entity Relationship Diagram - ❗ experimental
  - User Journey Diagram
  - Quadrant Chart
  - XY Chart

```mermaid
flowchart LR
  start((start))-->disable{disable}-- No -->isEnd(isEnd)-- Yes -->disableMap((disableMap))
	start((start))-->disable{disable}-- No -->isEnd(isEnd)-- No --> notHighlight{highlightType != none}-- No --> disableMap((disableMap))

	start((start))-->disable{disable}-- Yes -->isEnd2(isEnd)

```