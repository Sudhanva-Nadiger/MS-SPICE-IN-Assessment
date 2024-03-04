# MS-SPICE-IN-Assessment
Microsoft Research India - SPICE-IN Lens - Technical Assessment submission

## What this script does.
- Downloads IMF's Latest Working Paper series
- [Link to the site](https://www.imf.org/en/Publications/Search#sort=%40imfdate%20descending&f:series=[WRKNGPPRS])

## Install and Run the script

#### Requirements

- Install the IDE command line runner.
- [Selenium IDE](https://www.selenium.dev/selenium-ide/)
- [Selenium side runner](https://www.seleniumhq.org/selenium-ide/docs/en/introduction/command-line-runner/)

#### Install Locally and Run the script
- Install

```bash
git clone https://github.com/Sudhanva-Nadiger/MS-SPICE-IN-Assessment.git
```
```bash
cd MS-SPICE-IN-Assessment
```

- Run
```bash
selenium-side-runner imf_download_latest_working_paper.side
```

### Further Improvements
- Handling Popups: Currently, the script assumes that no popups will appear during the file download process. To improve robustness, consider implementing logic to handle popups gracefully if they do occur.

- Dynamic Wait Time: The wait time for the file download is currently hard-coded, which may lead to incomplete downloads if the file size is large or the download speed is slow. Implement dynamic wait times based on factors such as file size or download speed to ensure complete downloads under varying conditions.(Its hard to record with selenium ide. With code we can impliment thise easily)

### Thanks