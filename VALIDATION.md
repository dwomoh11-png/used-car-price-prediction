# Validation

Validated on 27 October 2026 using Python 3.12.14 and the supplied original dataset.

- All 60 retained Python code cells executed in sequence without errors.
- Outputs were regenerated from the current code, including tables and charts.
- No original absolute Windows dataset paths remain.
- The original source dataset was copied into `data/` only for execution, then excluded from the public package.
- Package versions used for analysis are recorded in requirements.txt.

Execution used a lightweight Python runner that evaluates cells in order and captures explicit displays, final expressions and Matplotlib figures. A Jupyter kernel and fresh pip installation were not tested in this environment. The `jupyterlab` frontend requirement is specified separately and was not installed here.

After validation, a presentation-only cleanup removed a redundant NumPy import. This did not change the analytical logic or saved results.

This validates reproducible execution against the supplied data. It does not validate deployment performance, causal conclusions or unseen future data.
