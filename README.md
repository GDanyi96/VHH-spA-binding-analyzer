# VHH-spA-binding-analyzer
## Description
A bioinformatics tool for the rational design of Protein A-binding VHH sequences based on open-source research.
The algorithm is based on an open-source article* (Henry KA et al.,2016) that describes a mutagenesis-based strategy to investigate Staphylococcal protein A (SpA) binding to VHH backbones. The tool translates the experimentally validated (by Surface Plasmon Resonance) findings of this article into an easy-to-use tool that accepts a VHH sequence as an input and informs the user about potential interaction SpA. Furthermore, it reports which residues could deteriorate 


**Henry KA, Sulea T, van Faassen H, Hussack G, Purisima EO, MacKenzie CR, Arbabi-Ghahroudi M. A Rational Engineering Strategy for Designing Protein A-Binding Camelid Single-Domain Antibodies. PLoS One. 2016 Sep 15;11(9):e0163113. doi: 10.1371/journal.pone.0163113. PMID: 27631624; PMCID: PMC5025174.*

Open for contributions.
## Limitations- Use at own risk
The tool is solely based on the article mentioned, which does not investigate all the possible amino-acid substitutions. The generated results are subject to *in vitro* and/or *in silico* validation. The article reports that no known adverse effects were observed when introducing the SpA-binding enhancing substitutions, although this was based on 5 different VHHs against 3 different targets. This can of course be different in the case of various substitutions and recombinant expression hosts that are not investigated. Additionally, be advised that there are several recombinant SpA proteins on the market that are potentially expressed based on different sequences which ther 


## Installation
`pip install -r requirements.txt`

## Usage
`python main.py --input sequence.fasta`

## Contributing
See CONTRIBUTING.md for guidelines.

## License
Licensed under . See LICENSE.md for details.
