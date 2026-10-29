# Study Protocol and Session Record (beta)

A browser form for electroencephalography (EEG) and optically pumped magnetometer magnetoencephalography (OPM-MEG) studies.

Open the form at https://www.yufang-yang.com/EEG_protocol_YANG/

## What it does

The form has two parts.

1. In the protocol part, you declare the study, the planned recording and the planned preprocessing before any data are collected. You then lock the form, which adds a timestamp.
2. In the session record part, you record at each recording session whether each step was done as planned, done differently or not done. You also give the actual value or the reason it differed.

You choose the method at the top of the form. The options are EEG, OPM-MEG with a Cerca Magnetics system, OPM-MEG with a FieldLine system, or another OPM system. For Cerca and FieldLine, the form starts with the settings described in the OPM-FLUX preprint. The record then shows every value that differs from these starting settings.

The OPM fields include degaussing, field nulling, the empty room recording, sensor tuning, the helmet, landmarks, and co-registration, either by a three-dimensional camera scan with and without the helmet or by a Polhemus digitiser. Where possible, each field is tagged with the matching OPM-FLUX section and Brain Imaging Data Structure (BIDS) key. The fields follow ARTEM-IS and COBIDAS-MEEG.

The record can be downloaded as JSON or saved as a PDF. The form runs entirely in your browser, and nothing is uploaded.

## Status

This is a beta version. The fields are still being developed with the EEG and OPM-MEG communities.

## Contributing

Contributions are welcome. You can suggest a field, report a problem or propose a change by opening an issue in this repository, or by writing to yu-fang.yang@fu-berlin.de.

## Licence

Released under the MIT licence. See [LICENSE](LICENSE).

© 2026 Yu-Fang Yang
