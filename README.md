# ATF-54143 ADS Power Amplifier Model

This repository contains an ADS design of a 5.8 GHz Class A power amplifier using a fully reconstructed Curtice II model of the discontinued ATF-54143 transistor.

## Contents
- Rebuilt Curtice II model (`.dsn` / `.sch`)
- Biasing setup for Class A operation (60 mA @ 3V)
- S-parameter simulation showing ~15 dB gain at 5.8 GHz
- Stability analysis and matching network

## Background
The ATF-54143 model was made unavailable after Avago was acquired by Broadcom. This project recreates the model from legacy documentation and Avago datasheets, ensuring long-term accessibility.

## License
MIT – feel free to use, modify, or improve.
