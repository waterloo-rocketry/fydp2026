# FYDP 2026 Electrical & Software

Sisyphus is a regeneratively cooled, 3D-printed liquid rocket engine. There are threee main electrical projects that support this system: Automedon, Achilles, and Theseus

## Automedon
Automedon is a repackaging of the team's existing EGSE stack (namely RLCS, DAQ, and GSPD) within two fully enclosed NEMA panels and with a redesigned power architecture. This vastly improves the robustness and utility of the system
Design doc: https://docs.google.com/document/d/1RASc9nuHLxcU_nNqpzqdATsLbMFS-u7HsDOORrnuTvM/edit?tab=t.0#heading=h.aovynwwb2h1r

## Achilles
Achilles, like its namesake, is designed to be an unkillable DAQ module that retains good analog performance. Unlike the team's previous COTS solutions, the system supports up to 30V common mode and differential signals, and is protected up to +/- 60V at the inputs.
DAQ v2 Design Doc (for context): https://docs.google.com/document/d/1antcjPh_7nqCMTjgXxEhXMyPKeuij0gU7g0J603f2qo/edit?tab=t.0#heading=h.4f9eymtkxact

## Theseus
Theseus is the third iteration on the team's integrated propulsion avionics PCB. It is designed to read from pressure transducers, Hall sensors, and RTDs (which are very necessary for regen testing), as well as actuating solenoid valves
