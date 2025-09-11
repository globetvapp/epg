
# EPG – Free Electronic Program Guide by Country

Welcome to the **EPG** repository, a comprehensive collection of free Electronic Program Guide (EPG) listings, organized by country. This project aims to provide easy access to EPG data for developers, hobbyists, and IPTV enthusiasts worldwide.

## About

- **Project Source:** [https://globetv.app](https://globetv.app)
- **Donations:** If you find this project useful, please consider supporting us: [https://ko-fi.com/m3u8player](https://ko-fi.com/m3u8player)

## Repository Structure

The repository is organized by country, with each directory containing EPG data relevant to that region. For example:

```
Albania/
Argentina/
Australia/
Austria/
...
```

Each folder contains raw EPG files that can be used directly or processed for your application.

## How to Use

### 1. Accessing EPG Data

You can browse and download EPG files directly from this GitHub repository. To get the latest raw EPG data:

- Navigate to the desired country folder.
- Download the relevant EPG file(s) (usually in XML or gzipped XML format).


**Example:**  
To get the EPG for France, go to `France/` and download the file you need.

### 2. Using EPG Data in Your Application

Most IPTV players and applications support importing EPG data in XMLTV format. Simply provide the URL to the raw file on GitHub, or download and host it yourself.


**Direct Raw File Access:**  
To use the raw file directly from GitHub, use the following URL pattern:

```
https://raw.githubusercontent.com/<username>/<repository>/<branch>/<country>/<filename>
```

**Example (Australia):**
```
https://raw.githubusercontent.com/globetvapp/epg/main/Australia/australia1.xml
```

Replace `globetvapp`, `epg`, `main`, `Australia`, and `australia1.xml` with the appropriate values for your use case.
## Filename Structure

EPG files for each country follow a consistent naming convention. For example, for Australia:

- `australia1.xml`
- `australia2.xml`
- `australia3.xml`
- `australia4.xml`

Each file represents a different set of channels or regions within the country. The number in the filename (e.g., `1`, `2`, `3`, `4`) distinguishes between different channel groups or sources. This filename structure will remain the same for future updates.

## Commit Message Format for EPG Files

The last commit messages for EPG files follow this pattern:

```
Update australiaX.xml - <N> channels - <timestamp> UTC
```

- `australiaX.xml`: The filename, where `X` is the group number.
- `<N> channels`: The number of channels included in that file.
- `<timestamp> UTC`: The date and time when the file was last updated.

This message indicates that the EPG file was updated with the specified number of channels at the given time.

### 3. Updating EPG Data

**The EPG files are updated every day at 3:00 AM UTC.** To get the latest data, always use the latest version from the repository.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have improvements or new EPG sources to add.

## License

This project is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE) for details.

---

**EPG data provided by [globetv.app](https://globetv.app).**  
If you appreciate this project, please consider donating: [https://ko-fi.com/m3u8player](https://ko-fi.com/m3u8player)
