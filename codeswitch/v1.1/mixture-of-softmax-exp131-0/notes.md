* Observation 1: Some undesirable ranking of switched text (top candidates of bin1&2 in step 1200).
* Observation 2: Precision and recall is artificially good by repeating in-reference words.
* Observation 3: I should be doing unconstrained beam search or fraction L2 fraction constrained beam search for INTVN, because it's not symmetric anymore and the bins produces by switching count is not as natural.
