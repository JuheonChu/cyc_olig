## Project Tasks List

Day 01:
- Read [ProteinMPNN](https://www.biorxiv.org/content/10.1101/2022.06.03.494563v1) and [Cyclic peptide structure prediction and design using AlphaFold
](https://www.biorxiv.org/content/10.1101/2023.02.25.529956v1.full) for understanding project backgrounds.
- Project Literature Review

Day 02:
- Increase proficiency with the RFDiffusion model by generating hundreds of protein structures.
- Attempt to generate cyclic oligomer.
- Review Gram-Schmidt which is principle to maintain the cyclic property of the oligomer structure.

Day 03: 
- Find the best setting for icosahedral & octahedral structures by manipulating guiding potential values (e.g. weight_intra, weight_inter, guide_scale). This ended up that other guiding potentials did not contribute hugely in changing the icosahedron structures. To see the clear difference, we have to change `weight_inter` and `weight_intra`.
- Call for Proposal First Draft (Complete)
### Resources:
- [Artificial Neural Network](https://www.turing.com/kb/necessity-of-bias-in-neural-networks)
- Review  [probabilistic diffusion model](https://arxiv.org/pdf/2006.11239.pdf).
- Learn [Classifier-Free Guidance](https://arxiv.org/abs/2207.12598).

Day 04: 
- Call for Proposal First Draft (Revised Draft based on David's feedback)
- Compute average distances between C_a atoms and amino acid chains. Check David's parser file which returns data dictionary whose key is `x,y,z` and includes 60 2-D matrices that denote the coordinates that correspond to each amino acid.
- Analyze Professor Gaurav's code.
