# Gruvbox Material Ports

### Kitty Terminal
```conf
background            #1d2021
foreground            #d4be98
cursor                #d4be98
cursor_text_color     #1d2021
selection_foreground  #d4be98
selection_background  #473c29

# URL underline color when hovering with mouse
url_color             #89b482

# Window Borders
active_border_color   #a9b665
inactive_border_color #32302f

# Tab Bar Colors
active_tab_foreground   #1d2021
active_tab_background   #a9b665
inactive_tab_foreground #d4be98
inactive_tab_background #3c3836

# Black
color0 #1d2021
color8 #928374

# Red
color1 #ea6962
color9 #ea6962

# Green
color2  #a9b665
color10 #a9b665

# Yellow
color3  #d8a657
color11 #d8a657

# Blue
color4  #7daea3
color12 #7daea3

# Magenta
color5  #d3869b
color13 #d3869b

# Cyan
color6  #89b482
color14 #89b482

# White
color7  #d4be98
color15 #d4be98
```

### Windows Terminal
```json
{
    "name": "Gruvbox Material Dark Hard",
    "background": "#1D2021",
    "foreground": "#D4BE98",
    "cursorColor": "#D4BE98",
    "selectionBackground": "#473C29",
    "black": "#1D2021",
    "blue": "#7DAEA3",
    "cyan": "#89B482",
    "green": "#A9B665",
    "purple": "#D3869B",
    "red": "#EA6962",
    "white": "#D4BE98",
    "yellow": "#D8A657",
    "brightBlack": "#928374",
    "brightBlue": "#7DAEA3",
    "brightCyan": "#89B482",
    "brightGreen": "#A9B665",
    "brightPurple": "#D3869B",
    "brightRed": "#EA6962",
    "brightWhite": "#D4BE98",
    "brightYellow": "#D8A657"
}
```

### SumatraPDF
```txt
# For documentation, see https://www.sumatrapdfreader.org/settings/settings3-5-1.html
Theme = Dark
FixedPageUI [
    TextColor = #D4BE98
    BackgroundColor = #1D2021
    SelectionColor = #473C29
    WindowMargin = 2 4 2 4
    PageSpacing = 4 4
    InvertColors = false
    HideScrollbars = true
]
ComicBookUI [
    WindowMargin = 0 0 0 0
    PageSpacing = 4 4
    CbxMangaMode = false
]
ChmUI [
    UseFixedPageUI = false
]

SelectionHandlers [
]
ExternalViewers [
]

ZoomLevels = 8.33 12.5 18 25 33.33 50 66.67 75 100 125 150 200 300 400 600 800 1000 1200 1600 2000 2400 3200 4800 6400
ZoomIncrement = 0

PrinterDefaults [
    PrintScale = shrink
]
ForwardSearch [
    HighlightOffset = 0
    HighlightWidth = 15
    HighlightColor = #7DAEA3
    HighlightPermanent = false
]
Annotations [
    HighlightColor = #D8A657
    UnderlineColor = #A9B665
    SquigglyColor = #D3869B
    StrikeOutColor = #EA6962
    FreeTextColor = #D4BE98
    FreeTextSize = 12
    FreeTextBorderWidth = 1
    TextIconColor = #89B482
    TextIconType = 
    DefaultAuthor = 
]

RememberOpenedFiles = false
RememberStatePerDocument = false
RestoreSession = false
UiLanguage = en
EnableTeXEnhancements = false
DefaultDisplayMode = automatic
DefaultZoom = fit page
Shortcuts [
]
EscToExit = false
ReuseInstance = false
ReloadModifiedDocuments = true

MainWindowBackground = #1D2021
FullPathInTitle = false
ShowMenubar = false
ShowToolbar = false
ShowFavorites = false
ShowToc = false
NoHomeTab = true
TocDy = 0
SidebarDx = 480
ToolbarSize = 15
TabWidth = 300
TreeFontSize = 0
TreeFontWeightOffset = 0
TreeFontName = automatic
SmoothScroll = true
ShowStartPage = true
CheckForUpdates = true
WindowState = 1
WindowPos = -7 0 974 1080
UseTabs = true
UseSysColors = false
CustomScreenDPI = 0
```

### Zathura
```zathurarc
set default-bg                  "#1D2021"
set default-fg                  "#D4BE98"

set statusbar-fg                "#D4BE98"
set statusbar-bg                "#32302F"

set inputbar-bg                 "#1D2021"
set inputbar-fg                 "#A9B665"

set notification-bg             "#1D2021"
set notification-fg             "#D4BE98"

set notification-error-bg       "#EA6962"
set notification-error-fg       "#1D2021"

set notification-warning-bg     "#D8A657"
set notification-warning-fg     "#1D2021"

set highlight-color             "rgba(125, 174, 163, 0.5)"
set highlight-active-color      "rgba(234, 105, 98, 0.5)"

set completion-bg               "#32302F"
set completion-fg               "#D4BE98"

set completion-highlight-fg     "#1D2021"
set completion-highlight-bg     "#7DAEA3"

# Recolor settings (for PDF content)
set recolor-lightcolor          "#1D2021"
set recolor-darkcolor           "#D4BE98"

set recolor                     "true"
set recolor-keephue             "true"
```
