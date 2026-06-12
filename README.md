[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000239-blue)](https://doi.org/10.82901/nemar.nm000239)

# P-ary m-sequence-based c-VEP dataset from Martínez-Cagigal et al. (2023)

P-ary m-sequence-based c-VEP dataset from Martínez-Cagigal et al. (2023)

## Dataset Overview

- **Code**: MartinezCagigal2023Parycvep
- **Paradigm**: cvep
- **DOI**: https://doi.org/10.71569/025s-eq10
- **Subjects**: 16
- **Sessions per subject**: 5
- **Events**: 0.0=100, 1.0=101, 2.0=102, 3.0=103, 4.0=104, 5.0=105, 6.0=106, 7.0=107, 8.0=108, 9.0=109, 10.0=110
- **Trial interval**: (0, 1) s
- **Runs per session**: 8

## Acquisition

- **Sampling rate**: 256.0 Hz
- **Number of channels**: 16
- **Channel types**: eeg=16
- **Montage**: standard_1005
- **Line frequency**: 50.0 Hz

## Participants

- **Number of subjects**: 16
- **Health status**: healthy

## Experimental Protocol

- **Paradigm**: cvep
- **Number of classes**: 11
- **Class labels**: 0.0, 1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0

## HED Event Annotations

Schema: HED 8.4.0 | Browse: https://www.hedtags.org/hed-schema-browser

```
  0.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_0_0

  1.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_1_0

  2.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_2_0

  3.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_3_0

  4.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_4_0

  5.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_5_0

  6.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_6_0

  7.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_7_0

  8.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_8_0

  9.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_9_0

  10.0
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/intensity_10_0

```
## Documentation

- **DOI**: 10.71569/025s-eq10
- **Associated paper DOI**: 10.1016/j.eswa.2023.120815
- **License**: CC-BY-NC-SA-4.0
- **Investigators**: Víctor Martínez-Cagigal, Eduardo Santamaría-Vázquez, Sergio Pérez-Velasco, Diego Marcos-Martínez, Selene Moreno-Calderón, Roberto Hornero
- **Senior author**: Roberto Hornero
- **Contact**: victor.martinez@gib.tel.uva.es
- **Institution**: University of Valladolid
- **Department**: Biomedical Engineering Group, ETSIT
- **Address**: Paseo de Belén, 15, 47011, Valladolid, Spain
- **Country**: ES
- **Repository**: U Valladoid
- **Data URL**: https://doi.org/10.71569/025s-eq10
- **Publication year**: 2023
- **Funding**: Ministerio de Ciencia e Innovación/Agencia Estatal de Investigación and ERDF (TED2021-129915B-I00, RTC2019-007350-1, PID2020-115468RB-I00); CIBER-BBN through Instituto de Salud Carlos III
- **Ethics approval**: Approved by the local ethics committee; all participants provided informed consent
- **Acknowledgements**: This study was partially funded by Ministerio de Ciencia e Innovación/Agencia Estatal de Investigación and ERDF, and CIBER-BBN through Instituto de Salud Carlos III.
- **How to acknowledge**: Please cite: Martínez-Cagigal et al. (2023). Non-binary m-sequences for more comfortable brain-computer interfaces based on c-VEPs. Expert Systems With Applications, 232, 120815. https://doi.org/10.1016/j.eswa.2023.120815

## References

Martínez-Cagigal, V., Santamaría-Vázquez, E., Pérez-Velasco, S., Marcos-Martínez, D., Moreno-Calderón, S., & Hornero, R. (2023). Non-binary m-sequences for more comfortable brain-computer interfaces based on c-VEPs. *Expert Systems with Applications, 232*, 120815. https://doi.org/10.1016/j.eswa.2023.120815

Martínez-Cagigal, V., Thielen, J., Santamaría-Vázquez, E., Pérez-Velasco, S., Desain, P., & Hornero, R. (2021). Brain-computer interfaces based on code-modulated visual evoked potentials (c-VEP): A literature review. *Journal of Neural Engineering*, 18(6), 061002. https://doi.org/10.1088/1741-2552/ac38cf

Martínez-Cagigal, V. (2025). Dataset: Non-binary m-sequences for more comfortable brain-computer interfaces based on c-VEPs. https://doi.org/10.35376/10324/70945

Santamaría-Vázquez, E., Martínez-Cagigal, V., Marcos-Martínez, D., Rodríguez-González, V., Pérez-Velasco, S., Moreno-Calderón, S., & Hornero, R. (2023). MEDUSA©: A novel Python-based software ecosystem to accelerate brain-computer interface and cognitive neuroscience research. *Computer Methods and Programs in Biomedicine, 230*, 107357. https://doi.org/10.1016/j.cmpb.2023.107357

Notes

Although the dataset was recorded in a single session, each condition is stored as a separate session to match the MOABB structure. Within each session, eight runs are available (six for training, two for testing).

.. versionadded:: 1.2.0
Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M., Mikulan, E., Tavabi, K., Hochenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E., Gramfort, A. and Jas, M. (2019). MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis. Journal of Open Source Software 4: (1896). https://doi.org/10.21105/joss.01896

Pernet, C. R., Appelhoff, S., Gorgolewski, K. J., Flandin, G., Phillips, C., Delorme, A., Oostenveld, R. (2019). EEG-BIDS, an extension to the brain imaging data structure for electroencephalography. Scientific Data, 6, 103. https://doi.org/10.1038/s41597-019-0104-8

---
Generated by MOABB 1.5.0 (Mother of All BCI Benchmarks)
https://github.com/NeuroTechX/moabb
