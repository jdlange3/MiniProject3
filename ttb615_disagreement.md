# Disagreement Examples — ttb615 (validator) & amart170 (author)

25 of the 50 validated records for amart170's Miniproject2 disagreed before discussion (HasRecovered 2, WhyRecovered 5, ActivityPattern 8, RecentThemes 10). All 25 were resolved as ValidatorKept after amart170 reviewed the commit evidence; see `ttb615_disagreement_resolution.csv`.

## Example 1: glotzerlab/fresnel (WhyRecovered)
**Parties:** Author amart170, Validator ttb615  
**Author:** Modernization for newer OptiX/Embree backends, Pybind11 upgrades, and CI build fixes.  
**Validator:** Build/CI/packaging stabilization (conda recipe, CircleCI/Jenkins), then feature development.  
**Reason:** The longest gap was Sep–Dec 2017 (2017-08-10 to 2018-01-19). The commits right after it are 'Use hints for tbb search', 'Update circleci config to modern standards', 'Fix conda recipe' and 'Test optix builds on Jenkins', so the author's reason described later work, not this gap.  
**Resolution:** ValidatorKept.

## Example 2: ebi-pf-team/interproscan (WhyRecovered)
**Parties:** Author amart170, Validator ttb615  
**Author:** Scheduled pipeline update and Java build updates.  
**Validator:** End-of-support notices and warnings (project wind-down).  
**Reason:** The only commits after the June–September 2026 gap are 'include end of support notice', 'End of support notice' and 'add warning'. None are pipeline or Java updates.  
**Resolution:** ValidatorKept.

## Example 3: uwdata/falcon (HasRecovered)
**Parties:** Author amart170, Validator ttb615  
**Author:** Yes (maintenance releases and dependency syncing).  
**Validator:** No.  
**Reason:** Ignoring the initial 2016 commit, the longest gap is Dec 2025–Jun 2026. The only commits after it are two dependabot version bumps, and the last human commit was 2025-07-30. Automated bumps are not resumed development.  
**Resolution:** ValidatorKept.

## Example 4: edzer/spacetime (ActivityPattern)
**Parties:** Author amart170, Validator ttb615  
**Author:** cyclical.  
**Validator:** declining.  
**Reason:** Commits per year fell from 92, 76 and 105 (2013–2015) to 0–8 per year afterward, with only sporadic CRAN-driven fixes. That shows no repeating fixed-interval cycle.  
**Resolution:** ValidatorKept.
