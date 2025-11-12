# LimeSDR Mini GSM-R Repeater

Bare-metal Python control of LimeSDR Mini for GSM-R repeater application.

## Setup

1. Activate venv: `source .venv/bin/activate`
2. Run tests: `pytest tests/`

## Hardware

- LimeSDR Mini (LMS7002M chip)
- Frequency: 100 MHz - 3.8 GHz
- GSM-R: 380-390 MHz

## Development

Direct register access via liblimeapi.so - NO high-level abstractions.
