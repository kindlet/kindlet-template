# Kindlet Template
## A simple template for creating Kindlets for Kindle Keyboards (3/3G/Paperwhite, etc)

## Important Notices

* You'll need the Java 8 JDK. I initially was using the Java 17 JDK and it gave an error.
* **DO NOT** change the build target!!! This will mess up the build!

## Making a Kindlet

Here's the actual part about programming it in Java. Warning: maybe don't start programming until you can get the Hello World to run on your Kindle. It's harder than you think.

### Kindlet KDK Documentation

The Kindle KDK documentation was taken down sometime around 2019. See: [Forum: "Does anyone have an archive of the KDK (Kindle Development Kit) Developer Docs?"](https://www.mobileread.com/forums/showthread.php?t=353046). Unfortunately, Archive.org does not seem to have a copy of the documentation (only the homepage/overview).

Fortunately, there seems to be a KDK emulator with the source files. Although this isn's as good as documentation, all the UI classes seem to be there.

[View KDK Emulator](https://github.com/kindlet/kdk-emulator/tree/master/src/main/java/com/amazon/kindle/kindlet/ui)

## Useful Resources

DISCLAIMER: I do not endorse any of these links.

Almost all of these come from the [MobileRead Forums](https://www.mobileread.com/forums/) or the MobileRead Wiki. If you're going to make a Kindlet, I highly recommend signing up for the MobileRead forum as it is essentially the only place you'll be able to get help making your Kindlet these days.

* [Forum: "Font, ScreenSaver & USBNetwork Hacks for Kindle 2.x, 3.x & 4.x"](https://www.mobileread.com/forums/showthread.php?t=88004)
* [Wiki: "Official Kindlet Index"](https://wiki.mobileread.com/wiki/Kindlet_Index)
* [Wiki: "Official Kindlet Tutorial (outdated)" - Very helpful in creating a new Kindlet](https://wiki.mobileread.com/wiki/Kindlet_Developer_HowTo)
* [Forum: "How to make a new Kindlet?" - Contains useful files and information](https://www.mobileread.com/forums/showthread.php?t=352953)
* [Forum: "How to create a BIN update file from a developer keystore?"](https://www.mobileread.com/forums/showthread.php?t=353045)
* [Forum: "Does anyone have an archive of the KDK (Kindle Development Kit) Developer Docs?"](https://www.mobileread.com/forums/showthread.php?t=353046)
* [Forum: "Merged Developer Keystore"](https://www.mobileread.com/forums/showthread.php?t=152294)

## Interesting KDK-Related Links

DISCLAIMER: I do not endorse any of these links.

* [@umjammer/vavi-games-tetris-kdk](https://github.com/umjammer/vavi-games-tetris-kdk)
* [@umjammer/kdk-emulator](https://github.com/umjammer/kdk-emulator)

## Credits

* [evilReader](https://www.mobileread.com/forums/member.php?u=333976)
* [AABBox](https://www.mobileread.com/forums/member.php?u=334018)
* [encol](https://www.mobileread.com/forums/member.php?u=272794)
