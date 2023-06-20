# Introduction and proteins

- Proteins 10nm, amino-acids 1nm.
- Amino acids have an amino and a carboxyl terminal group, distinguished by a residue on the $\alpha$-carbon (different chemical and physical properties).

# Proteins' geometry

- **The peptide bond**: carboxylic end and an amino react losing a water molelcule. A carbon is bonded to the oxygen in the carboxylic group and a nitrogen bond happens in the amino group. The $\alpha$-carbon is linked to the nitrogen in the amino group of another amino-acid. The carbon and nitrogen display *sp2* hybridization: the peptide bond is planar. Rotation of the plane is allowed only around one axis.
- The carbon atom of the carboxylic group and nitrogen are bonded to a different $\alpha$-carbon: trans or cis configuration. The Lennard Jones potential computes the Van der Waals repulsive forces between atoms. Decreasing the distance below a minimum requires lots of energy and poses strain to the molecule. Because of this the cis conformation is not favourable.
- **Ramachandran angles**: they are the $\phi$ and $\psi$ angles formed between the two planes formed by a peptide bond. In particular $\phi$ describes the rotation around its bond with the nitrogen, $\psi$ the rotation around its bond with the carboxylic group. Because the N atoms have a lower minimum distance, rotations around the $\psi$ angle are easier. There can be cases where the protein forces the amino acid to assume strange conformations.
- **Contact map of proteins**: maps all the contact betweena amino acids. It is symmetric with diagonal elements $1$ and two parallel diagonals for the neighbouring amino acids. $\alpha$-helices are represented by a line parallel to the diagonal ($i$ interacts with $i+4$). $\beta$-strands: parallel a parallel line to the diagonal, for anti-parallel is anti parallel. The contact is defined as teh distance between $\alpha$ carbon or the tail of the residue and an $\alpha$-carbon with a treshold.
- **Topology diagram**: $\beta$-strands as arrows $\alpha$-helices as small cylinder. Visualization of how the secondary structures interact between one another.
- **Coordinates**: described in *pdb* file, which contains some data.
- **Protein centre of mass** average position of the protein centre weighted by the mass of the atom.
- **Radius of gyration**: measures the size of the prtoein as if it was a sphere. It indicates elongating behaviour. Used to check whether a protein is goind toward equilibrium.
- **Comparing protein structures**: Select common regions (1-1 correspondence between amino acids). Align the two structures, traslating them so that the centre of masses coincide. Finding the opritmal rotation that superimpose the two structures. Compute the *root mean square deviation RMSD* also for a single protein in time, plateau is an equilibrium, jumping to different plateau means to be in a meta-stable state (or more stable states). The refernce is the initial configuration. Not sufficient for equilibrium.
- **Native state** The functional state of a protein (not crystallized), an ensemble in space and time of structure, all compatible with the conditions (constant temperature and pressure).
- **RMSF**: The flexibility of each amino acid (movement with respect to one another), a scaled of the *B* or *Debye-Waller* factors.

# Semi-empirical force fields
