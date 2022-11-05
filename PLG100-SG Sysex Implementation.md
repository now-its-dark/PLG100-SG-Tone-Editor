| <付表3> SG Native Part Parameter |   |   |   |   |   |   |   |   |   |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| `Parameter Address High 50h` |   |   |   |   |   |   |   |   |   |
| `Parameter Address Mid 0ph p:part number` |   |   |   |   |   |   |   |   |   |
| Parameter Address Low # #:show below |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| &num;(h) | Size | Data (h) Parameter | Parameter name | Range / Description | Default value | Example | Other useful functions |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 00 | 2 | 00-FF | **NasalFreqShift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 02 | 2 | 00-FF | **FormantFreq1Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 04 | 2 | 00-FF | **FormantFreq2Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 06 | 2 | 00-FF | **FormantFreq3Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 08 | 2 | 00-FF | **FormantFreq4Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 0A | 2 | 00-FF | **FormantFreq5Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 0C | 2 | 00-FF | **FormantFreq6Shift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 0E | 2 | 00-FF | **BuzzBarFreqShift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   | Low:F0 43 10 5D 50 PP 0E 00 00 F7 |   |   | PP= part number— 00 for part 1, 01 for part 2 etc |
|   |   |   |   |   |   | High:F0 43 10 5D 50 PP 0E 0F 0F F7 |   |   |   |
| ~~10~~ | 2 |   | Reserved |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 12 | 2 | 00-FF | **AllFormantFreqShift** | &plus;1280 – +1270 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
| 14 | 1 | 00-7F | **NasalLevShift** | &plus;64 – +63 |   |   |   |   |   |
| 15 | 1 | 00-7F | **VFormantLev1Shift** | &plus;64 – +63 |   |   |   |   |   |
| 16 | 1 | 00-7F | **VFormantLev2Shift** | &plus;64 – +63 |   |   |   |   |   |
| 17 | 1 | 00-7F | **VFormantLev3Shift** | &plus;64 – +63 |   |   |   |   |   |
| 18 | 1 | 00-7F | **VFormantLev4Shift** | &plus;64 – +63 |   |   |   |   |   |
| 19 | 1 | 00-7F | **VFormantLev5Shift** | &plus;64 – +63 |   |   |   |   |   |
| 1A | 1 | 00-7F | **VFormantLev6Shift** | &plus;64 – +63 |   |   |   |   |   |
| 1B | 1 | 00-7F | **BuzzBarLevShift** | &plus;64 – +63 |   |   |   |   |   |
| ~~1C~~ | 1 |   | Reserved |   |   |   |   |   |   |
| 1D | 1 | 00-7F | **AllVFormantLevShift** | &plus;64 – +63 |   |   |   |   |   |
| 1E | 1 |   | Reserved |   |   |   |   |   |   |
| 1F | 1 | 00-7F | **UFormantLev1Shift** | &plus;64 – +63 |   |   |   |   |   |
| 20 | 1 | 00-7F | **UFormantLev2Shift** | &plus;64 – +63 |   |   |   |   |   |
| 21 | 1 | 00-7F | **UFormantLev3Shift** | &plus;64 – +63 |   |   |   |   |   |
| 22 | 1 | 00-7F | **UFormantLev4Shift** | &plus;64 – +63 |   |   |   |   |   |
| 23 | 1 | 00-7F | **UFormantLev5Shift** | &plus;64 – +63 |   |   |   |   |   |
| 24 | 1 | 00-7F | **UFormantLev6Shift** | &plus;64 – +63 |   |   |   |   |   |
| 25 | 1 |   | Reserved |   |   |   |   |   |   |
| 26 | 1 |   | Reserved |   |   |   |   |   |   |
| 27 | 1 | 00-7F | **AllUFormantLevShift** | &plus;64 – +63 |   |   |   |   |   |
| 28 | 1 |   | Reserved |   |   |   |   |   |   |
| 29 | 1 |   | Reserved |   |   |   |   |   |   |
| 2A | 1 |   | Reserved |   |   |   |   |   |   |
| 2B | 1 |   | Reserved |   |   |   |   |   |   |
| 2C | 1 |   | Reserved |   |   |   |   |   |   |
| 2D | 1 |   | Reserved |   |   |   |   |   |   |
| 2E | 1 |   | Reserved |   |   |   |   |   |   |
| 2F | 1 |   | Reserved |   |   |   |   |   |   |
| 30 | 1 | 00-7F | **U/V Balance** | &plus;64 – +63 |   |   |   |   |   |
| 31 | 1 | 00-7F | **PitchDurTime** | &plus;64 – +63 |   |   |   |   |   |
| 32 | 1 | 00-7F | **CoartTimeCompRatio** | &plus;64 – +63 |   |   |   |   |   |
| 33 | 1 | 00-7F | **ConsCompRatio** | &plus;64 – +63 |   |   |   |   |   |
| 34 | 1 | 00-7F | **PhoneMorphRatio** | &plus;64 – +63 |   |   |   |   |   |
| 35 | 1 | 00-7F | **CoartMorphRatio** | &plus;64 – +63 |   |   |   |   |   |
| 36 | 1 | 00-06 | **LFO_EFX_WAVE** | sin,tri,saw+,saw-,squ,l/l,s&h |   |   |   |   |   |
| 37 | 1 | 00-01 | **LFO_EFX_TYPE** | 0 / 1 |   |   |   |   |   |
| 38 | 1 | 00-7F | **LFO_EFX_DELAY** | 0 – 127 |   |   |   |   |   |
| 39 | 1 | 00-7F | **LFO_EFX_Speed** | 0 – 127 |   |   |   |   |   |
| 3A | 1 | 00-7F | **LFO_EFX_Fade** | 0 – 127 |   |   |   |   |   |
| 3B | 1 | 00-7F | **LFO_EFX_SusLev** | 0 – 127 |   |   |   |   |   |
| 3C | 1 | 00-01 | **LFO_EFX_Sync** | 0:OFF / 1:ON |   |   |   |   |   |
| 3D | 1 | 39-47 | **LFO_EFX_Offset** | &plus;7 – +7 |   |   |   |   |   |
| 3E | 1 | 00-7F | **LFO_EFX_SpdKsBP** | C2 – G8 |   |   |   |   |   |
| 3F | 1 | 00-7F | **LFO_EFXSpdKsDepth** | &plus;64 – +63 |   |   |   |   |   |
| 40 | 1 | 00-7F | **LFO_EFX_FlutSpeed** | 0 – 127 |   |   |   |   |   |
| 41 | 1 | 00-7F | **LFO_EFX_FlutDepth** | 0 – 127 |   |   |   |   |   |
| 42 | 1 | 00-7F | **LFO_EFX_PmodDepth** | 0 – 127 |   |   |   |   |   |
| 43 | 1 | 00-7F | **LFO_EFX_AmodDepth** | 0 – 127 |   |   |   |   |   |
| 44 | 1 | 00-7F | **LFO_EFX_FmodDepth** | 0 – 127 |   |   |   |   |   |
| ~~45~~ | 1 |   | Reserved |   |   |   |   |   |   |
| ~~46~~ | 1 |   | Reserved |   |   |   |   |   |   |
| 47 | 1 | 00-07 | **PMS** | 0 – 7 |   |   |   |   |   |
| 48 | 1 | 00-07 | **NasalFms** | 0 – 7 |   |   |   |   |   |
| 49 | 1 | 00-07 | **Formant1Fms** | 0 – 7 |   |   |   |   |   |
| 4A | 1 | 00-07 | **Formant2Fms** | 0 – 7 |   |   |   |   |   |
| 4B | 1 | 00-07 | **Formant3Fms** | 0 – 7 |   |   |   |   |   |
| 4C | 1 | 00-07 | **Formant4Fms** | 0 – 7 |   |   |   |   |   |
| 4D | 1 | 00-07 | **Formant5Fms** | 0 – 7 |   |   |   |   |   |
| 4E | 1 | 00-07 | **Formant6Fms** | 0 – 7 |   |   |   |   |   |
| 4F | 1 |   | Reserved |   |   |   |   |   |   |
| 50 | 1 |   | Reserved |   |   |   |   |   |   |
| 51 | 1 |   | Reserved |   |   |   |   |   |   |
| 52 | 1 | 00-07 | **NasalAms** | 0 – 7 |   |   |   |   |   |
| 53 | 1 | 00-07 | **VFormant1Ams** | 0 – 7 |   |   |   |   |   |
| 54 | 1 | 00-07 | **VFormant2Ams** | 0 – 7 |   |   |   |   |   |
| 55 | 1 | 00-07 | **VFormant3Ams** | 0 – 7 |   |   |   |   |   |
| 56 | 1 | 00-07 | **VFormant4Ams** | 0 – 7 |   |   |   |   |   |
| 57 | 1 | 00-07 | **VFormant5Ams** | 0 – 7 |   |   |   |   |   |
| 58 | 1 | 00-07 | **VFormant6Ams** | 0 – 7 |   |   |   |   |   |
| 59 | 1 | 00-07 | **BuzzBarAms** | 0 – 7 |   |   |   |   |   |
| 5A | 1 |   | Reserved |   |   |   |   |   |   |
| 5B | 1 |   | Reserved |   |   |   |   |   |   |
| 5C | 1 |   | Reserved |   |   |   |   |   |   |
| 5D | 1 | 00-07 | **UFormant1Ams** | 0 – 7 |   |   |   |   |   |
| 5E | 1 | 00-07 | **UFormant2Ams** | 0 – 7 |   |   |   |   |   |
| 5F | 1 | 00-07 | **UFormant3Ams** | 0 – 7 |   |   |   |   |   |
| 60 | 1 | 00-07 | **UFormant4Ams** | 0 – 7 |   |   |   |   |   |
| 61 | 1 | 00-07 | **UFormant5Ams** | 0 – 7 |   |   |   |   |   |
| 62 | 1 | 00-07 | **UFormant6Ams** | 0 – 7 |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | Assign to part: |   |   |
|   |   |   |   |   |   |   | 1-16 |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 00 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 01 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 02 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 03 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 04 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 05 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 06 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 07 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 09 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 09 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0A F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0B F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0C F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0D F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0E F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 4C 70 01 00 0F F7 |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | Define Init Phoneme: |   |   |
|   |   |   |   |   |   |   | ahh, ihh, uhh, ehh, ohh, rha, wha, rhu |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 00 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 01 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 02 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 03 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 04 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 05 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 06 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 0A 07 F7 |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | Sustain Timeout: |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | OFF |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 08 00 F7 |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   | 0-100 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 08 01 F7 |   |   |
|   |   |   |   |   |   |   | F0 43 10 5D 00 00 08 64 F7 |   |   |