# Squirrel Lolbin
### Description

Detects Possible Squirrel Packages Manager as Lolbin.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on update.exe being run with --processStart or --createShortcut parameters.

-------------------

### Possible causes of false positives

    - 1Clipboard
    - Beaker Browser
    - Caret
    - Collectie
    - Discord
    - Figma
    - Flow
    - Ghost
    - GitHub Desktop
    - GitKraken
    - Hyper
    - Insomnia
    - JIBO
    - Kap
    - Kitematic
    - Now Desktop
    - Postman
    - PostmanCanary
    - Rambox
    - Simplenote
    - Skype
    - Slack
    - SourceTree
    - Stride
    - Svgsus
    - WebTorrent
    - WhatsApp
    - WordPress.com
    - atom
    - gitkraken
    - slack
    - teams


-------------------
### References

    - http://www.hexacorn.com/blog/2019/03/30/sqirrel-packages-manager-as-a-lolbin-a-k-a-many-electron-apps-are-lolbins-by-default/  

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
