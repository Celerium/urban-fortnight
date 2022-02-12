---
name: "\U0001F41B Bug Report"
about: "If something isn't working as expected \U0001F914."
title: ''
labels: 'bug: bug, i: needs triage'
assignees: ''

---

### **Steps to reproduce`:`**

Describe the steps to reproduce the issue.

### **Actual behavior`:`**

Describe the actual behavior

### **Expected behavior`:`**

A clear and concise description of what you expected to happen. Please include a screenshot if you can.

### **Possible Solution`:`**
<!--- Only if you have suggestions on a fix for the bug -->

If you have suggestions on a fix for the bug, please describe it here.

---

## Environment

Please share additional details about your environment.

* PowerShell | MyITProcessAPI | Operating System

```posh
$PSversionTable

Get-Package -Name MyITProcessAPI | Select-Object Name,Version,Source,ProviderName

Get-ComputerInfo -Property @(
        'OsName',
        'OsOperatingSystemSKU',
        'OSArchitecture',
        'WindowsVersion',
        'WindowsBuildLabEx',
        'OsLanguage',
        'OsMuiLanguages'
    )

```