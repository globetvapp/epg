
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

**Example:**  
```
https://raw.githubusercontent.com/globetvapp/epg/main/France/guide.xml
```

Replace `globetvapp`, `epg`, `main`, `France`, and `guide.xml` with the appropriate values for your use case.

### 3. Updating EPG Data

**The EPG files are updated every day at 3:00 AM UTC.** To get the latest data, always use the latest version from the repository.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have improvements or new EPG sources to add.

## License

This project is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE) for details.

---

**EPG data provided by [globetv.app](https://globetv.app).**  
If you appreciate this project, please consider donating: [https://ko-fi.com/m3u8player](https://ko-fi.com/m3u8player)
