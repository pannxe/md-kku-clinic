# Definition
Cut off at **ligament of Treitz**
- Prox. → **Upper** GI bleed
- Dist. → **Lower** GI bleed

> ![[Pasted image 20230527093509.png]]
> Ligament of Treitz ~ **Duofeno-jejunal flexure**; do not confuse with foregut-midgut cut-off point

ico cannot determine site of bleed → **obscure GI bleed**

# Approach

```mermaid
---
title: GI Bleed Approach
---

flowchart TB

	1("1. Really GI bleed?")
	1b("
	Epitaxis
	Food or drug color
	Systemic Bleed")
	2("2. Lower or Upper GI?")
	2a["Upper GI Bleeding"]
	2b["Lower GI Bleeding"]
	2aa["Varicial Bleeding"]
	2ab["Non-varicial GI Bleeding"]
	ddx["3. DDx"]
	
	1 -- "GI Bleed" --> 2
	1 -- "
		Non-bleed
		Non-GI
	" --> 1b
	2 -- " 
		Hematemesis
		Coffee-ground vomiting
		Melena
	" --> 2a
	
	2 -- "
		Hematochezia
		Melena (if slow)
	" ---> 2b
	2a -- "
		Painless
		Hematemesis
		Hemodynamic unstable
		U/D liver disease
	" --> 2aa
	2a -- "
		Painful
		Coffee-ground vomiting
		Melena
		U/D PUD, NSAIDs use
	" --> 2ab
	2b & 2aa & 2ab --> ddx

linkStyle default text-align: left, stroke:-width:2px;
```

# Differential Diagnosis
