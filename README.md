## The FMDB Mailing List:
http://groups.google.com/group/

## Read the SQLite FAQ:
http://www.sqlite.org/faq.html

Since FMDB is built on top of SQLite, you're going to want to read this page top to bottom at least once.  And while you're there, make sure to bookmark the SQLite Documentation page: http://www.sqlite.org/docs.html

## Contributing
Do you have an awesome idea that deserves to be in FMDB?  You might consider pinging ccgus first to make sure he hasn't already ruled it out for some reason.  Otherwise pull requests are great, and make sure you stick to the local coding conventions.  However, please be patient and if you haven't heard anything from ccgus for a week or more, you might want to send a note asking what's up.

## Installing

### CocoaPods

[![Dependency Status](https://www.versioneye.com/objective-c/fmdb/2.3/badge.svg?style=flat)](https://www.versioneye.com/objective-c/fmdb/2.3)
[![Reference Status](https://www.versioneye.com/objective-c/fmdb/reference_badge.svg?style=flat)](https://www.versioneye.com/objective-c/fmdb/references)

FMDB can be installed using [CocoaPods](https://cocoapods.org/).

If you haven't done so already, you might want to initialize the project, to have it produce a `Podfile` template for you:

```
$ pod init
```

Then, edit the `Podfile`, adding `FMDB`:

```ruby
# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'MyApp' do
    # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
    use_frameworks!

    # Pods for MyApp2

    pod 'FMDB'
    # pod 'FMDB/FTS'   # FMDB with FTS
    # pod 'FMDB/standalone'   # FMDB with latest SQLite amalgamation source
    # pod 'FMDB/standalone/FTS'   # FMDB with latest SQLite amalgamation source and FTS
    # pod 'FMDB/SQLCipher'   # FMDB with SQLCipher
end
```
####www.baidu.com####
