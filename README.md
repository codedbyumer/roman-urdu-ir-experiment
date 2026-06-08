# Roman Urdu IR Experiment

Tested roman-urdu-mt5-mmarco model on real social media Roman Urdu queries.

## Findings
- Model achieved 80% accuracy on relevance detection
- Gap found: model struggles with colloquial queries containing brand names (olx, daraz)
- This suggests out-of-domain generalization issue

## Based On
Butt et al. (2025) - "Roman Urdu as a Low-Resource Language: Building the First IR Dataset and Baseline"

## Models Used
- Mavkif/roman-urdu-mt5-mmarco
- Dataset: Mavkif/roman-urdu-msmarco-dataset
