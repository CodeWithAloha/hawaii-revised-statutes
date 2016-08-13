# Hawaii Revised Statutes

This repository contains a mirror of the Hawaii Revised Statutes from the [Hawaii State Legislature's official website](http://www.capitol.hawaii.gov).


## Changelog

### [2016-08-12] 2015 update
> Download new `hrs2015` directory and updated `hrscurrent` directory


### [2015-12-08] Initial import
> Downloaded years 1999 through 2014 (and hrscurrent) via the script:
>
> ```
> #!/bin/bash
> for year in $(seq 1999 2014) hrscurrent; do
>   wget -r --no-parent http://www.capitol.hawaii.gov/hrs${year}/
> done
> ```

