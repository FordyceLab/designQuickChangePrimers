# designQuickChangePrimers
Batch design of any number of QuickChange primers, including hairpin Tm calculator (using primer3-py).

In practice for each library of mutants, we perform two runs. In the first, using QuickChange_mutagenesis_no_hairpin_optimization.nb, we determine the optimum primer pair to generate each mutant and its hairpin Tm. In the second run (using QuickChange_mutagenesis_with_Primer3hairpinTm.nb) we perform an additional hairpin Tm optimization for primers having a high calculatd hairpin (Tm >50C).
