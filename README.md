# **Project Summary** 

The following code describes the sequence processing steps used to analyze **ITS2** data generated for the **Sphaerulina musiva soil inoculations** project. Data comes from DNA extracted from soils. Soils were collected from pots that were amended with either a l non-autoclaved forest soil or an autoclaved forest soil. After soil amendments, *Populus trichocarpa* (black cottonwood) was planted in a subset of pots. The two different strains of *Sphaerulina musiva* were added to pots. One strain was determined to be high virulence and the other was determined to be low virulence. Soils were collected from three different locations within the pots. 

**Treatments**

**Inoculum Type**

1. **No Sphaerulia** == NoSept
2. **High Virulence Sphaerulina** == Mn5
3. **Low Virulence Sphaeulina** == SARM07

**Sampling Date**

1. **Day 10** == D10
2. **Day 25** == D25

**Soil Amendment Type**

1. **Autoclaved/Reduced Soil Community** == A
2. **Not-Autoclaved/Full Community** == NA

**Plant Presence**

1. **No Plant in Pot** == NP
2. **Plant in Pot** == P

**Soil Collection Location**

1. **Near Root** == NR (only in plant treatments)
2. **Middle of Pot** == MoP (only in non-plant treatments)
3. **Edge of Pot** == EoP

Extracted DNA was amplified and sequenced on the Illumina MiSeq platform (2x250 bp). **Samples were sequenced by sampling date and as a result initial sequence processing steps prior to chimera detection were completed in batches by sequencing run**.  

The sequence processing steps outlined below are based on the [dada2 pipeline](https://benjjneb.github.io/dada2/tutorial.html).
