# Opsims

This directory holds the opsims that are being considered in the
simulation. The size of the opsim databases are too large to be
hosted on github; to download them, run the following:

```bash
#!/bin/bash
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.1/baseline/baseline_v2.1_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_3.0/baseline/baseline_v3.0_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/dd6/dd6_v2.99_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/draft/draft_connected_v2.99_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/draft2/draft2_rw0.9_v2.99_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/draft2/draft2_rw0.9_uz_v2.99_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.2/galplane/galplane_priority_blue_agg_level1.5_v2.2_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/low_gp/low_gp_v2.99_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.2/rolling/noroll_v2.2_10yrs.db
wget http://astro-lsst-01.astro.washington.edu:8080/fbs_db/fbs_2.99/roll_early/roll_early_v2.99_10yrs.db
```

Note that you can download any other opsim runs and include those
opsims in the analysis by adding them to the opsim list in the
code. Happy analyzing!
