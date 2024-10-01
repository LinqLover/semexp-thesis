# The Semantic Workspace: Augmenting Exploratory Programming with Integrated Generative AI Tools

Master's thesis by Christoph Thiede.  
Supervised by [Robert Hirschfeld](https://github.com/roberthirschfeld), [Marcel Taeumel](https://github.com/marceltaeumel), and [Lukas Böhme](https://github.com/boehmchen).

Read the thesis here: **[💾 PDF (twoside)](https://github.com/LinqLover/semexp-thesis/releases/download/submission/semexp-thesis.pdf)** or **[💾 PDF (oneside)](https://github.com/LinqLover/semexp-thesis/releases/download/submission/semexp-thesis-oneside.pdf)**

**Available artifacts:**
- https://github.com/hpi-swa-lab/SemanticSqueak
- https://github.com/hpi-swa-lab/Squeak-SemanticText

## Abstract

> In the exploratory programming practice, programmers iteratively ask questions and run experiments to understand and develop software systems.
> However, traditional exploratory programming workflows often lead to distractions and information overload, as programmers need to handle numerous implementation artifacts.
> Meanwhile, semantic technologies—text generation using large language models (LLMs) and semantic retrieval using embeddings—are establishing themselves in other development practices to assist in writing and searching code.
> 
> We propose an augmented exploratory programming workflow that integrates semantic technologies into programming systems, allowing programmers to interact with them through more conceptual interfaces.
> Our semantic workspace introduces three semantic programming tools for augmenting and automating exploration:
> semantic suggestions anticipate the intentions of programmers and recommend possible experiments, semantic completions continue their plans through contextualized suggestions, and semantic conversations enable high-level, natural-language questions about objects.
>
> Our semantic exploration kernel uses semantic technologies to power these tools with a suggestion engine for recommending and contextualizing artifacts, and with an exploratory programming agent for autonomous experiments and conversations with programmers.
> We explore embedding- and term-based strategies for searching and ranking artifacts, and we design prompts and system interfaces for an agent based on the GPT-4o model.
> 
> We successfully used a prototype of the semantic workspace for Squeak/Smalltalk to augment different exploratory activities.
> From our experience, semantic tools show promise in streamlining the exploratory programming workflow, but they must be further optimized to master exploratory practices and semantic understanding and to reduce time and resource consumption.
> We believe that our work is an important step toward a new era of semantic exploratory programming, where programmers and deeply intelligent agents collaborate effectively to comprehend and extend large systems.

## Citing

Short version:

```bib
@thesis{thiede2024semantic,
	title = {The Semantic Workspace: Augmenting Exploratory Programming with Integrated Generative AI Tools},
	author = {Christoph Thiede},
	year = {2024},
	month = {9},
	day = {30},
	institution = {Hasso Plattner Institute},
	address = {Potsdam, Germany},
	type = {Master's Thesis},
	keywords = {exploratory programming, semantic technologies, generative AI, LLMs, semantic retrieval, document embeddings, Squeak, Smalltalk, GPT},
	url = {https://github.com/LinqLover/semexp-thesis/releases/download/submission/semexp-thesis.pdf},
}
```

Long version:

<details>
<summary>Citation</summary>
<pre><code>@thesis{thiede2024semantic,
	title = {The Semantic Workspace: Augmenting Exploratory Programming with Integrated Generative AI Tools},
	author = {Christoph Thiede},
	year = {2024},
	month = {9},
	day = {30},
	institution = {Hasso Plattner Institute},
	address = {Potsdam, Germany},
	type = {Master's Thesis},
	abstract = {In the exploratory programming practice, programmers iteratively ask questions and run experiments to understand and develop software systems. However, traditional exploratory programming workflows often lead to distractions and information overload, as programmers need to handle numerous implementation artifacts. Meanwhile, semantic technologies—text generation using large language models (LLMs) and semantic retrieval using embeddings—are establishing themselves in other development practices to assist in writing and searching code.

We propose an augmented exploratory programming workflow that integrates semantic technologies into programming systems, allowing programmers to interact with them through more conceptual interfaces. Our semantic workspace introduces three semantic programming tools for augmenting and automating exploration: semantic suggestions anticipate the intentions of programmers and recommend possible experiments, semantic completions continue their plans through contextualized suggestions, and semantic conversations enable high-level, natural-language questions about objects.

Our semantic exploration kernel uses semantic technologies to power these tools with a suggestion engine for recommending and contextualizing artifacts, and with an exploratory programming agent for autonomous experiments and conversations with programmers. We explore embedding- and term-based strategies for searching and ranking artifacts, and we design prompts and system interfaces for an agent based on the GPT-4o model.

We successfully used a prototype of the semantic workspace for Squeak/Smalltalk to augment different exploratory activities. From our experience, semantic tools show promise in streamlining the exploratory programming workflow, but they must be further optimized to master exploratory practices and semantic understanding and to reduce time and resource consumption. We believe that our work is an important step toward a new era of semantic exploratory programming, where programmers and deeply intelligent agents collaborate effectively to comprehend and extend large systems.},
	keywords = {exploratory programming, semantic technologies, generative AI, LLMs, semantic retrieval, document embeddings, Squeak, Smalltalk, GPT},
	url = {https://github.com/LinqLover/semexp-thesis/releases/download/submission/semexp-thesis.pdf},
}</code></pre>
</details>

## Building

Uses the [swathesis](https://github.com/krono/swathesis) template (plus many customizations).

```bash
swth clean && swth go
```

Worked on my machine with pdfTeX, Version 3.141592653-2.6-1.40.22 (TeX Live 2022/dev/Debian). It is also possible to substitute `swth` by latexmk (version 4.76), even though multiple reruns might be required after changing the bibliography.

Figures were created with PowerPoint 365 Online (not recommended to try at home), inspired by Marcel Taeumel's fantastic drawing style (Segoe Print, sketchy lines - freehand and scribble).
