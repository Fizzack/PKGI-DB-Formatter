# PKGI DB Formatter

## 💡 Introduction

This script transform .tsv file to PKGI DB Format

From:
```
Title ID	Region	Name	PKG direct link	RAP	Content ID	Last Modification Date	Download .RAP file	File Size	SHA256
```
To:
```
Content ID,0,Name,Description,.RAP file,File Size,SHA256
```

## 💻 Commands

Convert command:
```
PKGI-Formatter.py c <source> <dest>
```
Merge command:
```
PKGI-Formatter.py m <source0> <source1> <dest>
```