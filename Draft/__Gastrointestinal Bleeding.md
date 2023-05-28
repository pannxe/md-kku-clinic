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
title: GI Bleeding Approach
---
flowchart TB;
subgraph Localization
	direction TB;
	05("
		- NG tube for gastric lavage 
		R/O UGIB
		- DRE & proctoscore R/O LGIB
	") --> 1 & 2 
	1("Really GI bleed?")
		1b("
		- Epitaxis
		- Food or drug color
		- Systemic Bleed
		")
	15("
		Initial Management
		- NPO
		- Foley for I/O record
		- Keep urine >0.5 mL/kg/hr
		- NG irrigation (also R/O UGIB)
	")
	
	2("Lower or Upper GI?")
		2a["Upper GI Bleeding"]
			2aa["Varicial Bleeding"]:::internal-link
			2ab["Non-varicial GI Bleeding"]:::internal-link
		2b["Lower GI Bleeding"]:::internal-link
	
	1 -- "GI Bleed" --> 15 --> 2
	1 -- "
		Non-bleed
		Non-GI
	" --> 1b
	2 -- " 
		Hematemesis
		Coffee-ground vomiting
		Melena
		+ve gastric lavage
	" --> 2a
	
	2 -- "
		Hematochezia
		Melena (if slow)
		-ve gastric lavage
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
end

2aa --> vbmed["
	Octreotide 50 mcg IV 
	→ 50 mcg/hr for 5 d.
	(x5 dose ico
	Somatostatin)
"]
2ab --> nvbmed["
	- Controloc
	80 mg IV stat
	- NSS 100 mL IV drip
	8 mg/hr for 72 hr
"]

initInvest["
	Initial Investigation
	- CBC
	- Coagulogram
	- BUN/Cr
	- Glucose level
	- E'lyte
	- OCBT
	- Blood typing & Cross match
"]
initTx["
	Correct initial problems
	- Isotonic resuscitation
	- Blood transfusion
	- Correct coagulopathy
"]	

0["Suspected GI Bleeding"]
0 --> initInvest --> initTx
initTx -- "History and Symptoms" --> 1
initTx -- "Further Investigation" --> 05

linkStyle default text-align: left, stroke-width:2px;
classDef default text-align: left;
```

