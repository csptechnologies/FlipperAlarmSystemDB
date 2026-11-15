# FlipperAlarmSystemDB
This is a community database of captured security alarm system sensors that can be used with alarm systems for testing.
## Directory Structure

```text
FlipperAlarmSystemDB/(Frequency)/(Brand)/(Type)/(TXID)/(Open or Close).sub
```

## Contributing

- Only submit signals that are read as RAW.
- Do not submit files with other sensors going off at the same time.
- Place each capture in the correct frequency, brand, device type, and transmitter ID directory. You may create new directories for different sensor types, brand, and frequencies.
- Follow the filename naming scheme found in existing files.
- Add a `readme.md` in the transmitter ID directory when details about the device, capture conditions, or supported actions would help others.
- Verify that the capture works as documented before submitting it, and explain any limitations or uncertainty.
- Create a pull request to add the sensor in.

## AI Use Declaration

AI assistance was used to draft and edit this README. The project maintainer reviewed the resulting content and is responsible for its final wording. Contributions to the database should still be reviewed by their authors for accuracy, safety, and authorization.
