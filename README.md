# free-spoken-digit

A simple audio/speech dataset consisting of recordings of spoken digits in `wav` files at 8kHz. The recordings are trimmed so that they have near minimal silence at the beginnings and ends.

FSDD is an open dataset, which means it will grow over time as data is contributed. Thus in order to enable reproducibility and accurate citation in scientific journals the dataset is versioned using `git tags`.

### Current status
- 3 speakers
- 1,500 recordings (50 of each digit per speaker)
- English pronunciations

### Organization
Files are named in the following format:
`{digitLabel}_{speakerName}_{index}.wav`
Example: `7_jackson_32.wav`

### Contributions
Please contribute your homemade recordings. All recordings should be mono 8kHz `wav ` files and be trimmed to have minimal silence. Don't forget to update `metadata.py` with the speaker meta-data.

### Contriutor
* Yu Xia

