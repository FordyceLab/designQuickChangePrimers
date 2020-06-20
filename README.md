# designQuickChangePrimers
Batch design of any number of QuickChange primers, including hairpin Tm calculator (using primer3-py).

In practice for each library of mutants, we perform two runs, for convenience each in a separate notebook. In the first, using QuickChange_mutagenesis_no_hairpin_optimization.nb, we determine the optimum primer pair to generate each mutant and its hairpin Tm. In the second run (using QuickChange_mutagenesis_with_Primer3hairpinTm.nb) we perform an additional hairpin Tm optimization for primers from the first round having a high calculatd hairpin (Tm >50C).
