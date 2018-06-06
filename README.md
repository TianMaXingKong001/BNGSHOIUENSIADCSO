
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
####(http://www.baidu.com)####
