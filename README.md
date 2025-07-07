# Coding and Thematic Analysis

Created by [Matt Artz](https://www.mattartz.me/) — Advancing AI Anthropology through computational approaches to qualitative research.

## What This Tool Does

This notebook analyzes qualitative data by coding it using both deductive and inductive approaches, and then building those codes up into themes. Rather than manually applying codes to hundreds of text segments and then building themes iteratively, you receive coded data as well as suggested themes.

Building on the foundations established by the Qualitative Codebook Builder and Interview Transcript Semantic Chunker, the notebook processes chunked text by applying the pre-defined deductive codes while inductively identifying emergent codes, and then it constructs themes from both approaches.

## Key Features

- **Data Integration**: Imports codebooks and transcripts from other AI Anthropology Toolkit notebooks
- **Three Coding Approaches**: Choose between deductive, inductive, or hybrid coding methodologies
- **Code Application**: Uses Claude AI for coding across text segments
- **Theme Construction**: Builds hierarchical themes from coded data
- **Export Options**: Produces Excel workbooks and formatted Word documents with themes


## Workflow

1. Import deductive codebook from Qualitative Codebook Builder (CSV format)
2. Import interview chunks from Interview Transcript Processor (CSV format)
3. Configure analysis parameters including coding approach and AI model
4. Apply deductive codes using predefined codes (if selected)
5. Discover inductive codes emerging from the data (if selected)
6. Integrate codes and build themes
7. Generate visualizations and export results

## Applications

This tool supports qualitative research from dissertation fieldwork to applied research projects. It's particularly useful for computational analysis using the tools in my AI Anthropology Toolkit, enabling researchers to maintain rigor while working at scale.

## Methodological Positioning

This represents "computational anthropology" - using AI to enhance rather than replace traditional qualitative methods. The tool handles the time-intensive coding and thematic analysis process of interpretation and meaning-making. 

**Important:** AI can assist with pattern recognition and consistency, but human expertise remains essential for contextual understanding.

## Target Audience

Designed for anthropologists and qualitative researchers working with qualitative data—from graduate students managing thesis interviews to research teams processing large datasets for applied projects.

## Technical Approach

Combines natural language processing with anthropological coding principles, using Claude AI to apply codes consistently while discovering emergent patterns through computational analysis.

## Contributing to AI Anthropology

This notebook contributes to the emerging field of AI Anthropology—which combines studying AI as cultural artifact, using AI to enhance ethnographic research, and applying anthropological insights to AI development (Artz, forthcoming). By open-sourcing these tools, this work advances the collective capacity of anthropologists to work effectively with computational methods.

## AI Anthropology Toolkit

This tool is part of a growing suite of computational resources for anthropological research:

- **[Qualitative Codebook Builder](https://github.com/MattArtzAnthro/Qualitative_Codebook_Builder)** - AI-assisted development of qualitative coding frameworks
- **[Interview Transcript Semantic Chunker](https://github.com/MattArtzAnthro/Interview_Transcript_Semantic_Chunker)** - AI-assisted segmentation of interview transcripts
- **[Coding and Thematic Analysis](https://github.com/MattArtzAnthro/Coding_and_Thematic_Analysis)** (this tool) - AI-assisted coding and thematic analysis of qualtiative data

*Additional tools will be added to this toolkit as they are developed.*


<br>

---

<br>

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license. You may remix, adapt, and build upon the material for non-commercial purposes, provided you credit Matt Artz and link to the repository.

**Full license details**: https://creativecommons.org/licenses/by-nc/4.0/

## Attribution   

If you use or adapt this project in your work, please cite:


> Built with the Coding and Thematic Analysis (Matt Artz, 2025) — https://github.com/MattArtzAnthro/Coding_and_Thematic_Analysis


## Citation

If you use this tool in your academic research, please cite:


> Artz, Matt. 2025. Coding and Thematic Analysis. Software.
Zenodo. https://doi.org/10.5281/zenodo.15832611

## Refrences
Artz, Matt. Forthcoming. “AI Anthropology: The Future of Applied Anthropological Practice.” In Routledge Handbook of Applied Anthropology, edited by Christina Wasson, Edward B. Liebow, Karine L. Narahara, Ndukuyakhe Ndlovu, and Alaka Wali. New York: Routledge.
