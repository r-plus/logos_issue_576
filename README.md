```
$ gmake
> Making all for tweak test…
==> Preprocessing Tweak.x…
Tweak.x:2: error: fell off the face of the planet when we found a '}'
gmake[3]: *** [/opt/theos/makefiles/instance/rules.mk:258: /private/tmp/test/.theos/obj/debug/arm64/Tweak.x.m] Error 255
==> Preprocessing Tweak.x…
Tweak.x:2: error: fell off the face of the planet when we found a '}'
gmake[3]: *** [/opt/theos/makefiles/instance/rules.mk:258: /private/tmp/test/.theos/obj/debug/armv7/Tweak.x.m] Error 255
rm /private/tmp/test/.theos/obj/debug/arm64/Tweak.x.m
rm /private/tmp/test/.theos/obj/debug/armv7/Tweak.x.m
gmake[2]: *** [/opt/theos/makefiles/instance/library.mk:52: /private/tmp/test/.theos/obj/debug/armv7/test.dylib] Error 2
gmake[2]: *** Waiting for unfinished jobs....
gmake[2]: *** [/opt/theos/makefiles/instance/library.mk:52: /private/tmp/test/.theos/obj/debug/arm64/test.dylib] Error 2
==> Preprocessing Tweak.x…
Tweak.x:2: error: fell off the face of the planet when we found a '}'
gmake[3]: *** [/opt/theos/makefiles/instance/rules.mk:258: /private/tmp/test/.theos/obj/debug/arm64e/Tweak.x.m] Error 255
rm /private/tmp/test/.theos/obj/debug/arm64e/Tweak.x.m
gmake[2]: *** [/opt/theos/makefiles/instance/library.mk:52: /private/tmp/test/.theos/obj/debug/arm64e/test.dylib] Error 2
gmake[1]: *** [/opt/theos/makefiles/instance/library.mk:37: internal-library-all_] Error 2
gmake: *** [/opt/theos/makefiles/master/rules.mk:117: test.all.tweak.variables] Error 2
```
