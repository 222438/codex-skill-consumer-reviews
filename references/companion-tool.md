# Companion collector and analyzer

The executable collector and analyzer are intentionally maintained separately from this skill so the code project and the skill-design lab have distinct GitHub repositories.

- Repository: <https://github.com/222438/consumer-review-collector>
- Collector: `scripts/collect_reviews.py`
- Analyzer: `scripts/analyze_reviews.py`
- Offline fixture and tests: `examples/` and `tests/`

Clone it once into a local workspace when collection or script-based analysis is needed:

```powershell
git clone https://github.com/222438/consumer-review-collector.git
```

Then set `$tool` to the cloned folder and run the commands in `SKILL.md`. The scripts have no third-party Python dependencies.
