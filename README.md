# OfficeJS Initialization Bug

```
npm install
npm start
```
Then navigate to https://localhost:3000 via the provided manifest in Word.

## Context

We have a few documents that cannot load our add-in.

## The Bug

This is pretty simple: when a document's name contains one or more apostrophes, OfficeJS fails to load successfully.

## Versions

```
Word 2016 on Windows Version 1910 (Build 12112.20000 Click-to-Run), Office Insider [Microsoft Word for Office 365 MSO (16.0.12112.20000)]

Windows 10 Version 1903 (OS Build 18362.356)

Browser:
Edge, version 44.18362.329.0, EdgeHTML 18.18362
```
