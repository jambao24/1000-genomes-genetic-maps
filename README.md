Genetic maps for the 1000 Genomes Project variants
=====

These directories contain interpolated genetic map positions for the 1000 Genomes variants obtained at ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/ The genome build is hg19.

We only interpolated from maps generated from European populations for the moment.

In interpolated_from_hapmap are the interpolated map positions from the CEU genetic map generated by the HapMap 2 Project and lifted over to hg19, this map was generated by Adam Auton and is available at ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/technical/working/20110106_recombination_hotspots/

In interpolated_OMNI are the interpolated map positions from the CEU genetic map generated by the 1000 Genomes Project using OMNI arrays. This map was generated by Adam Auton and is available at ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130507_omni_recombination_rates/

For all files, the format is: [id] [physical position] [genetic position (cumulative)]

NB: for variants beyond the limits of the genetic map used for interpolation, the genetic position was set to a constant (either 0 for those as the beginnning of the chromosome or the maxmimum input genetic position for those at the end of a chromosome) rather than extrapolating beyond the map.

