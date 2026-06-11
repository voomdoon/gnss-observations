# GNSS Observations

Personal GNSS recordings and notes from consumer devices, collected for technical discussion and later comparison with public interference reports.

These recordings may contain reception gaps, bad fixes, timestamp anomalies, implausible altitude values, map/app artifacts, or other receiver behavior. They are not certified navigation data, aircraft avionics logs, or authoritative evidence of interference by themselves.

## Repository Structure

```text
cases/
  YYYY-MM-DD_identifier/
    README.md
    data/
    screenshots/
    maps/
```

Each case folder should document:

- device/app context, where known
- recording date and approximate route or location
- observed anomalies or artifacts
- files included and any privacy edits
- notes on screenshots, map backgrounds, and third-party app UI

## Data Notes

Raw GNSS files are provided for inspection and reproducibility of the observations. They may include inaccurate positions, timestamps, speed, altitude, satellite counts, or application-specific fields.

Screenshots are included only as supporting context. App interfaces, map data, imagery, and other third-party content remain subject to their respective owners' terms.

## License

Unless otherwise noted, written analysis, derived tables, and scripts in this repository may be used under the MIT License.

Raw GNSS recordings created by me may be used, copied, modified, and redistributed without restriction.

Screenshots are provided for reference and technical discussion only. Third-party app UI, map data, and imagery visible in screenshots remain subject to their respective owners' terms.
