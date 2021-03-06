# Chrome Apps for Ruby

![Chrome Apps logo](images/chrome_apps.png)

## Installation

### 1. Clone this repository and see its contents.
Open a terminal give the following command:

```bash
$ git clone https://github.com/enogrob/ChromeApps_Ruby.git
```

As we can see a subdirectory is created for each Ruby app.

```bash
$ ls -la
total 40
drwxr-xr-x@   8 enogrob  staff   272B Apr  1 16:24 ./
:
drwxr-xr-x   28 enogrob  staff   952B Apr  1 16:35 ChromeApss_Ruby/
-rw-r--r--    1 enogrob  staff   137B Apr  1 16:24 today_data.yaml

$ tree -L 1 ChromeApps_Ruby/
ChromeApps_Ruby/
├── README.md
├── Ruby-API
├── Ruby-Awesome
├── Ruby-Bundler
├── Ruby-GoogleGroups
├── Ruby-Homepage
├── Ruby-IronRuby
├── Ruby-MacRuby
├── Ruby-MagLev
├── Ruby-MobiRuby
├── Ruby-Opal
├── Ruby-Pry
├── Ruby-RVM
├── Ruby-Rubinius
├── Ruby-Ruboto
├── Ruby-Rubular
├── Ruby-RubyBench
├── Ruby-RubyCentral
├── Ruby-RubyConf2014
├── Ruby-RubyDoc.org
├── Ruby-RubyFLOW
├── Ruby-RubyGems
├── Ruby-RubyMine
├── Ruby-RubyMineTV
├── Ruby-RubyWeekly
├── Ruby-RubyWikipedia
├── Ruby-Toolbox
├── Ruby-TryRuby
├── Ruby-mruby
└── images

29 directories, 1 file

$
```

### 2. Open Chrome with the following url:
In order to load the `Chrome Apps` for Ruby, check `Developer Mode` and press `Load unpacked extension...` to load each App selecting its corresponding directory inside `ChromeApps_Ruby` e.g. `Ruby-MRI`, and then repeat that for the other apps.

```
chrome://extensions/
```

![Chrome screenshot](images/chrome_screenshot1.png)

### 3. After load all the Chrome Apps for Ruby, Chrome will look like the screenshot below:

![Chrome screenshot](images/chrome_screenshot2.png)