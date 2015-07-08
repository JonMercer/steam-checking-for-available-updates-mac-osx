# steam-checking-for-available-updates-mac-osx

## The problem
In my mac OSX 10.10.4, a fresh install of Steam gets stuck at `checking for available updates...`

The steam version I had was

```
Built: Jun 4 2015, at 10:30:12
Steam API: v017
Steam package versions: 1433441742
```

I'll paste the log files below for google SEO.

## Solution
With my second mac that had steam installed already, I copied all the files form `/Applications/Steam.app/Contents/MacOS/package` and pasted them into my other mac where steam won't download.

I've pasted the `package` contents in the folder above.

## Logs
filepath of log file: ~/Library/Application Support/Steam/logs/bootstrap_log.txt

```
[2015-07-07 20:11:30] Startup - updater built Feb 24 2014 13:14:14
[2015-07-07 20:11:30] Verifying installation...
[2015-07-07 20:11:30] Unable to read and verify install manifest
/Applications/Steam.app/Contents/MacOS/package/steam_client_osx.installed
[2015-07-07 20:11:30] Verification complete
[2015-07-07 20:11:30] Downloading update...
[2015-07-07 20:11:30] Checking for available updates...
[2015-07-07 20:12:30] Download failed: http error 0
[2015-07-07 20:12:31] Package file
tenfoot_misc_all.zip.0f55f659f9339a1ed0c85f0c591607e4b8dfbc5e missing or
incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_dicts_all.zip.e818f4aaa4d9d8ad025659d9bc85cdc4fbe58eba missing or
incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_fonts_all.zip.vz.07635fc6a446b4cd80b7eb45c45a919098c7a710_12063303
missing or incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_ambientsounds_all.zip.20ccff954777943069dd2c57576216f5f1db7389
missing or incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_sounds_all.zip.vz.7a3cc0ba5f5309183bca660227b8e0afa9922629_1223056
missing or incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_images_all.zip.vz.46b4c32f51ec58ad26de485acd3d26b77204fdab_12090519
missing or incorrect size
[2015-07-07 20:12:31] Package file
tenfoot_all.zip.vz.7d6b68f774a46db03473c53c210b4de79baf9c8d_1168644 missing
or incorrect size
[2015-07-07 20:12:31] Package file
resources_misc_all.zip.vz.5b8f09b1f407d80780688930b071e340fe22600d_2028216
missing or incorrect size
[2015-07-07 20:12:31] Package file
resources_all.zip.vz.7d426284d781ec94b48770b1629566599bf25317_4828669
missing or incorrect size
[2015-07-07 20:12:31] Package file
strings_en_all.zip.dc314d241338b13188ab3ae835e639dccb96c712 missing or
incorrect size
[2015-07-07 20:12:31] Package file
strings_all.zip.vz.d6d75f14ee8ea56c301037030e43987d7edf1d4d_1892172 missing
or incorrect size
[2015-07-07 20:12:31] Package file
remoteui_all.zip.vz.9ab82b54e0fa29fd7bff0bb3fe6cd379ccd3989e_141165 missing
or incorrect size
[2015-07-07 20:12:31] Package file
public_all.zip.vz.8d6f2b8450d850c6bd2adda6403bf2393ded3f67_767727 missing
or incorrect size
[2015-07-07 20:12:31] Package file
bins_osx.zip.vz.e675b9fc79ea56edd08d8e86f9e6348edec74e4d_16307111 missing
or incorrect size
[2015-07-07 20:12:31] Package file
bins_client_osx.zip.vz.8dcd79eac79509ebdb904da29c595480ea9a9e66_8837904
missing or incorrect size
[2015-07-07 20:12:31] Package file
bins_codecs_osx.zip.a2cbcc611212252db3b0ab19d9386c13264a1639 missing or
incorrect size
[2015-07-07 20:12:31] Package file
bins_misc_osx.zip.b44007e469d335b40a20fa68d49e55555d9f6914 missing or
incorrect size
[2015-07-07 20:12:31] Package file
bins_panorama_osx.zip.vz.6ac9f5e3eb0fd9fbcce4eb5ebb78bf0f5c2917b8_2709337
missing or incorrect size
[2015-07-07 20:12:31] Package file
sdl2_osx.zip.vz.17ae2c993c584a816e1cb997cd633864fca473c8_559191 missing or
incorrect size
[2015-07-07 20:12:31] Package file
webhelpers_osx.zip.vz.e07bfe3a6415ef6f65c4f20a4bf419f3234fa8bd_517749
missing or incorrect size
[2015-07-07 20:12:31] Package file
webkit_osx.zip.vz.c7be47ec82729f5be60fa8f5a5f4b84f5db9759a_26252610 missing
or incorrect size
[2015-07-07 20:12:31] Package file
breakpad_osx.zip.vz.b607af16653ed9a3e56df897c78fac8ed8bf87c9_298945 missing
or incorrect size
[2015-07-07 20:12:31] Package file
miles_osx.zip.vz.af6a19400b5e0554c4f56393522fc699c99ad182_249228 missing or
incorrect size
[2015-07-07 20:12:31] Package file
res2x_osx.zip.vz.0be5ccb01843666d2b83fa8c8caa2fc5287d8a7d_34212 missing or
incorrect size
[2015-07-07 20:12:31] Package file
steam_osx.zip.vz.3bf2162bebf8e6c06934005bed542b0634283940_1178072 missing
or incorrect size
[2015-07-07 20:12:31] Downloading update (0 of 122,073 KB)...
[2015-07-07 20:13:31] Error: Download of package (tenfoot_fonts_all) failed
after 0 bytes (0).
[2015-07-07 20:13:31] Error: Download of package (tenfoot_dicts_all) failed
after 0 bytes (0).
[2015-07-07 20:13:31] Error: Download of package (tenfoot_misc_all) failed
after 0 bytes (0).
[2015-07-07 20:14:32] Error: Download of package (tenfoot_images_all)
failed after 0 bytes (0).
[2015-07-07 20:14:32] Error: Download of package (tenfoot_sounds_all)
failed after 0 bytes (0).
[2015-07-07 20:14:32] Error: Download of package
(tenfoot_ambientsounds_all) failed after 0 bytes (0).
[2015-07-07 20:15:32] Error: Download of package (resources_all) failed
after 0 bytes (0).
[2015-07-07 20:15:32] Error: Download of package (resources_misc_all)
failed after 0 bytes (0).
[2015-07-07 20:15:32] Error: Download of package (tenfoot_all) failed after
0 bytes (0).
[2015-07-07 20:16:40] Error: Download of package (remoteui_all) failed
after 0 bytes (0).
[2015-07-07 20:16:40] Error: Download of package (strings_all) failed after
0 bytes (0).
[2015-07-07 20:16:40] Error: Download of package (strings_en_all) failed
after 0 bytes (0).
[2015-07-07 20:17:43] Error: Download of package (public_all) failed after
0 bytes (0).
[2015-07-07 20:17:43] Error: Download of package (bins_client_osx) failed
after 0 bytes (0).
[2015-07-07 20:17:43] Error: Download of package (bins_osx) failed after 0
bytes (0).
[2015-07-07 20:18:25] Shutdown


[2015-07-07 20:18:29] Startup - updater built Feb 24 2014 13:14:14
[2015-07-07 20:18:29] Verifying installation...
[2015-07-07 20:18:29] Unable to read and verify install manifest
/Applications/Steam.app/Contents/MacOS/package/steam_client_osx.installed
[2015-07-07 20:18:29] Verification complete
[2015-07-07 20:18:29] Downloading update...
[2015-07-07 20:18:29] Checking for available updates...
[2015-07-07 20:19:29] Download failed: http error 0
[2015-07-07 20:19:29] Package file
tenfoot_misc_all.zip.0f55f659f9339a1ed0c85f0c591607e4b8dfbc5e missing or
incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_dicts_all.zip.e818f4aaa4d9d8ad025659d9bc85cdc4fbe58eba missing or
incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_fonts_all.zip.vz.07635fc6a446b4cd80b7eb45c45a919098c7a710_12063303
missing or incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_ambientsounds_all.zip.20ccff954777943069dd2c57576216f5f1db7389
missing or incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_sounds_all.zip.vz.7a3cc0ba5f5309183bca660227b8e0afa9922629_1223056
missing or incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_images_all.zip.vz.46b4c32f51ec58ad26de485acd3d26b77204fdab_12090519
missing or incorrect size
[2015-07-07 20:19:29] Package file
tenfoot_all.zip.vz.7d6b68f774a46db03473c53c210b4de79baf9c8d_1168644 missing
or incorrect size
[2015-07-07 20:19:29] Package file
resources_misc_all.zip.vz.5b8f09b1f407d80780688930b071e340fe22600d_2028216
missing or incorrect size
[2015-07-07 20:19:29] Package file
resources_all.zip.vz.7d426284d781ec94b48770b1629566599bf25317_4828669
missing or incorrect size
[2015-07-07 20:19:29] Package file
strings_en_all.zip.dc314d241338b13188ab3ae835e639dccb96c712 missing or
incorrect size
[2015-07-07 20:19:29] Package file
strings_all.zip.vz.d6d75f14ee8ea56c301037030e43987d7edf1d4d_1892172 missing
or incorrect size
[2015-07-07 20:19:29] Package file
remoteui_all.zip.vz.9ab82b54e0fa29fd7bff0bb3fe6cd379ccd3989e_141165 missing
or incorrect size
[2015-07-07 20:19:29] Package file
public_all.zip.vz.8d6f2b8450d850c6bd2adda6403bf2393ded3f67_767727 missing
or incorrect size
[2015-07-07 20:19:29] Package file
bins_osx.zip.vz.e675b9fc79ea56edd08d8e86f9e6348edec74e4d_16307111 missing
or incorrect size
[2015-07-07 20:19:29] Package file
bins_client_osx.zip.vz.8dcd79eac79509ebdb904da29c595480ea9a9e66_8837904
missing or incorrect size
[2015-07-07 20:19:29] Package file
bins_codecs_osx.zip.a2cbcc611212252db3b0ab19d9386c13264a1639 missing or
incorrect size
[2015-07-07 20:19:29] Package file
bins_misc_osx.zip.b44007e469d335b40a20fa68d49e55555d9f6914 missing or
incorrect size
[2015-07-07 20:19:29] Package file
bins_panorama_osx.zip.vz.6ac9f5e3eb0fd9fbcce4eb5ebb78bf0f5c2917b8_2709337
missing or incorrect size
[2015-07-07 20:19:29] Package file
sdl2_osx.zip.vz.17ae2c993c584a816e1cb997cd633864fca473c8_559191 missing or
incorrect size
[2015-07-07 20:19:29] Package file
webhelpers_osx.zip.vz.e07bfe3a6415ef6f65c4f20a4bf419f3234fa8bd_517749
missing or incorrect size
[2015-07-07 20:19:29] Package file
webkit_osx.zip.vz.c7be47ec82729f5be60fa8f5a5f4b84f5db9759a_26252610 missing
or incorrect size
[2015-07-07 20:19:29] Package file
breakpad_osx.zip.vz.b607af16653ed9a3e56df897c78fac8ed8bf87c9_298945 missing
or incorrect size
[2015-07-07 20:19:29] Package file
miles_osx.zip.vz.af6a19400b5e0554c4f56393522fc699c99ad182_249228 missing or
incorrect size
[2015-07-07 20:19:29] Package file
res2x_osx.zip.vz.0be5ccb01843666d2b83fa8c8caa2fc5287d8a7d_34212 missing or
incorrect size
[2015-07-07 20:19:29] Package file
steam_osx.zip.vz.3bf2162bebf8e6c06934005bed542b0634283940_1178072 missing
or incorrect size
[2015-07-07 20:19:29] Downloading update (0 of 122,073 KB)...
[2015-07-07 20:20:29] Error: Download of package (tenfoot_fonts_all) failed
after 0 bytes (0).
[2015-07-07 20:20:29] Error: Download of package (tenfoot_dicts_all) failed
after 0 bytes (0).
[2015-07-07 20:20:29] Error: Download of package (tenfoot_misc_all) failed
after 0 bytes (0).
[2015-07-07 20:21:10] Shutdown


[2015-07-07 20:21:12] Startup - updater built Feb 24 2014 13:14:14
[2015-07-07 20:21:12] Verifying installation...
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
bin/panorama/etc/fonts/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
bin/panorama/etc/fonts/conf.d/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/20-aliases-default-win.conf is -1 bytes,
expected 748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/20-fix-cantarell.conf is -1 bytes, expected
391
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/21-aliases-wine-win7-inf.conf is -1 bytes,
expected 949
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/30-non-latin-inf-win.conf is -1 bytes,
expected 3599
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/41-repl-os-win.conf is -1 bytes, expected 9210
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/42-repl-global.conf is -1 bytes, expected 1126
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/43-repl-tt-traced-bitmap.conf is -1 bytes,
expected 2565
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/44-repl-corrective.conf is -1 bytes, expected
1218
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/50-base-rendering-win7-winxp.conf is -1
bytes, expected 967
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/60-group-non-tt-fonts.conf is -1 bytes,
expected 94923
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/60-group-tt-fonts.conf is -1 bytes, expected
66644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/61-group-non-tt-rendering-inf-7-xp-lin.conf
is -1 bytes, expected 1144
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/61-group-tt-rendering-inf-7-xp.conf is -1
bytes, expected 485
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/62-tt-monospace-rendering.conf is -1 bytes,
expected 3921
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/62-tt-traced-bitmap-rendering.conf is -1
bytes, expected 7663
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/65-override.conf is -1 bytes, expected 1390
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/70-forced-synthetic.conf is -1 bytes,
expected 3011
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/80-selective-rendering-inf-7-xp.conf is -1
bytes, expected 1119
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/80-selective-rendering-inf-win-lin.conf is -1
bytes, expected 5717
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/81-final-rendering-inf-7-xp.conf is -1 bytes,
expected 1107
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/90-no-synthetic.conf is -1 bytes, expected
2270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/conf.d/90-reject.conf is -1 bytes, expected 687
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/fonts/fonts.conf is -1 bytes, expected 4584
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
bin/panorama/etc/pango/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/panorama/etc/pango/pango.modules is -1 bytes, expected 78
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
bin/shaders/tenfoot/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/glfancyquadshaders.cfg is -1 bytes, expected 112
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/fancyquaduber.frag is -1 bytes, expected 9001
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/fancyquaduber.vert is -1 bytes, expected 1549
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/orthographic2d.vert is -1 bytes, expected 669
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/tex2dblur.frag is -1 bytes, expected 1714
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/tex2dparticle.frag is -1 bytes, expected 742
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/vrdistort.frag is -1 bytes, expected 4587
[2015-07-07 20:21:12] BVerifyInstalledFiles:
bin/shaders/tenfoot/opengl/vrdistort.vert is -1 bytes, expected 488
[2015-07-07 20:21:12] BVerifyInstalledFiles: chromehtml.dylib is -1 bytes,
expected 1725268
[2015-07-07 20:21:12] BVerifyInstalledFiles: CodeResources is -1 bytes,
expected 743
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory controller_base/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/app_generic.vdf is -1 bytes, expected 2241
[2015-07-07 20:21:12] BVerifyInstalledFiles: controller_base/bigpicture.vdf
is -1 bytes, expected 232
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/bigpicture_daisywheel.vdf is -1 bytes, expected 232
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/bigpicture_mouseon.vdf is -1 bytes, expected 710
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/gamepad_generic.vdf is -1 bytes, expected 1920
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/steamdesktop.vdf is -1 bytes, expected 2327
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
controller_base/templates/
[2015-07-07 20:21:12] BVerifyInstalledFiles: controller_base/templates/dual
stick.vdf is -1 bytes, expected 2312
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/templates/gamepad+mouse.vdf is -1 bytes, expected 2293
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/templates/gamepad.vdf is -1 bytes, expected 2016
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/templates/mouse.vdf is -1 bytes, expected 1373
[2015-07-07 20:21:12] BVerifyInstalledFiles:
controller_base/templates/wasd.vdf is -1 bytes, expected 2543
[2015-07-07 20:21:12] BVerifyInstalledFiles: crashhandler.dylib is -1
bytes, expected 317656
[2015-07-07 20:21:12] BVerifyInstalledFiles: filesystem_stdio.dylib is -1
bytes, expected 179624
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Breakpad is 160768 bytes, expected
157616
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Headers/Breakpad.h is 14266 bytes,
expected 14548
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Headers/BreakpadDefines.h is 3826
bytes, expected 3898
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/breakpadUtilities.dylib
is 195208 bytes, expected 207804
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Info.plist
is 1423 bytes, expected 1470
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/MacOS/crash_report_sender
is 149304 bytes, expected 149852
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/Breakpad.nib
is 12507 bytes, expected 12724
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/da.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/da.lproj/Localizable.strings
is 2428 bytes, expected 2478
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/de.lproj/InfoPlist.strings
is 192 bytes, expected 196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/de.lproj/Localizable.strings
is 2746 bytes, expected 2796
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/English.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/English.lproj/Localizable.strings
is 2428 bytes, expected 2478
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/es.lproj/InfoPlist.strings
is 184 bytes, expected 188
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/es.lproj/Localizable.strings
is 2578 bytes, expected 2628
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/fr.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/fr.lproj/Localizable.strings
is 2694 bytes, expected 2744
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/it.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/it.lproj/Localizable.strings
is 2590 bytes, expected 2640
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/ja.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/ja.lproj/Localizable.strings
is 1792 bytes, expected 1842
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/nl.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/nl.lproj/Localizable.strings
is 2546 bytes, expected 2596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/no.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/no.lproj/Localizable.strings
is 2484 bytes, expected 2534
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/sl.lproj/InfoPlist.strings
is 184 bytes, expected 188
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/sl.lproj/Localizable.strings
is 2632 bytes, expected 2682
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/sv.lproj/InfoPlist.strings
is 156 bytes, expected 160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/sv.lproj/Localizable.strings
is 2588 bytes, expected 2638
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/tr.lproj/InfoPlist.strings
is 168 bytes, expected 172
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/crash_report_sender.app/Contents/Resources/tr.lproj/Localizable.strings
is 2430 bytes, expected 2480
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/Info.plist is 1101
bytes, expected 1138
[2015-07-07 20:21:12] BVerifyInstalledFiles:
Frameworks/Breakpad.framework/Versions/A/Resources/Inspector is 53940
bytes, expected 64032
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Chromium Embedded Framework is -1 bytes, expected
62549244
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Libraries/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Libraries/ffmpegsumo.so is -1 bytes, expected 2412484
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Libraries/PDF.plugin/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Libraries/PDF.plugin/Contents/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Libraries/PDF.plugin/Contents/Info.plist is -1 bytes,
expected 1535
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Libraries/PDF.plugin/Contents/MacOS/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Libraries/PDF.plugin/Contents/MacOS/PDF is -1 bytes,
expected 11818412
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/am.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/am.lproj/locale.pak is -1 bytes, expected
21368
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ar.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ar.lproj/locale.pak is -1 bytes, expected
23411
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/bg.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/bg.lproj/locale.pak is -1 bytes, expected
24974
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/bn.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/bn.lproj/locale.pak is -1 bytes, expected
30762
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ca.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ca.lproj/locale.pak is -1 bytes, expected
16556
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/cef.pak is -1 bytes, expected 2055497
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/cef_100_percent.pak is -1 bytes, expected
418566
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/cef_200_percent.pak is -1 bytes, expected
537546
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_inspector is -1 bytes, expected 57420
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Info.plist
is -1 bytes, expected 1276
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/MacOS/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/MacOS/crash_report_sender
is -1 bytes, expected 67232
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/PkgInfo is
-1 bytes, expected 8
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Resources/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Resources/Breakpad.nib
is -1 bytes, expected 12773
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Resources/crash_report_sender.icns
is -1 bytes, expected 170816
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Resources/English.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/crash_report_sender.app/Contents/Resources/English.lproj/Localizable.strings
is -1 bytes, expected 2478
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/cs.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/cs.lproj/locale.pak is -1 bytes, expected
15666
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/da.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/da.lproj/locale.pak is -1 bytes, expected
14443
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/de.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/de.lproj/locale.pak is -1 bytes, expected
15905
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/devtools_resources.pak is -1 bytes, expected
4225496
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/el.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/el.lproj/locale.pak is -1 bytes, expected
26799
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/en.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/en.lproj/locale.pak is -1 bytes, expected
13493
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/en_GB.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/en_GB.lproj/locale.pak is -1 bytes, expected
13494
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/es.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/es.lproj/locale.pak is -1 bytes, expected
16639
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/es_419.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/es_419.lproj/locale.pak is -1 bytes, expected
16098
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/et.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/et.lproj/locale.pak is -1 bytes, expected
14632
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/fa.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/fa.lproj/locale.pak is -1 bytes, expected
20768
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/fi.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/fi.lproj/locale.pak is -1 bytes, expected
15534
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/fil.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/fil.lproj/locale.pak is -1 bytes, expected
16428
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/fr.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/fr.lproj/locale.pak is -1 bytes, expected
16961
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/gu.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/gu.lproj/locale.pak is -1 bytes, expected
28566
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/he.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/he.lproj/locale.pak is -1 bytes, expected
17833
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/hi.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/hi.lproj/locale.pak is -1 bytes, expected
28877
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/hr.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/hr.lproj/locale.pak is -1 bytes, expected
15675
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/hu.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/hu.lproj/locale.pak is -1 bytes, expected
16378
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/icudtl.dat is -1 bytes, expected 10457856
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/id.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/id.lproj/locale.pak is -1 bytes, expected
14464
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/Info.plist is -1 bytes, expected 1487
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/it.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/it.lproj/locale.pak is -1 bytes, expected
15459
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ja.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ja.lproj/locale.pak is -1 bytes, expected
18038
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/kn.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/kn.lproj/locale.pak is -1 bytes, expected
32766
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ko.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ko.lproj/locale.pak is -1 bytes, expected
15608
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/lt.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/lt.lproj/locale.pak is -1 bytes, expected
16217
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/lv.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/lv.lproj/locale.pak is -1 bytes, expected
16539
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ml.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ml.lproj/locale.pak is -1 bytes, expected
37393
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/mr.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/mr.lproj/locale.pak is -1 bytes, expected
28838
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ms.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ms.lproj/locale.pak is -1 bytes, expected
14599
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/natives_blob.bin is -1 bytes, expected 413533
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/nb.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/nb.lproj/locale.pak is -1 bytes, expected
14761
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/nl.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/nl.lproj/locale.pak is -1 bytes, expected
15177
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/pl.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/pl.lproj/locale.pak is -1 bytes, expected
15822
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/pt_BR.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/pt_BR.lproj/locale.pak is -1 bytes, expected
15530
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/pt_PT.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/pt_PT.lproj/locale.pak is -1 bytes, expected
15663
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ro.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ro.lproj/locale.pak is -1 bytes, expected
16673
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ru.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ru.lproj/locale.pak is -1 bytes, expected
23406
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/sk.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/sk.lproj/locale.pak is -1 bytes, expected
16306
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/sl.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/sl.lproj/locale.pak is -1 bytes, expected
15025
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/snapshot_blob.bin is -1 bytes, expected 985220
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/sr.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/sr.lproj/locale.pak is -1 bytes, expected
23022
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/sv.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/sv.lproj/locale.pak is -1 bytes, expected
14475
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/sw.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/sw.lproj/locale.pak is -1 bytes, expected
14959
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/ta.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/ta.lproj/locale.pak is -1 bytes, expected
35312
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/te.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/te.lproj/locale.pak is -1 bytes, expected
33152
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/th.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/th.lproj/locale.pak is -1 bytes, expected
29159
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/tr.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/tr.lproj/locale.pak is -1 bytes, expected
15048
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/uk.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/uk.lproj/locale.pak is -1 bytes, expected
24717
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/vi.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/vi.lproj/locale.pak is -1 bytes, expected
17232
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/zh_CN.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/zh_CN.lproj/locale.pak is -1 bytes, expected
13176
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
Frameworks/Chromium Embedded Framework.framework/Resources/zh_TW.lproj/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Chromium Embedded
Framework.framework/Resources/zh_TW.lproj/locale.pak is -1 bytes, expected
13387
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory Frameworks/Steam
Helper EH.app/Contents/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam Helper
EH.app/Contents/Info.plist is -1 bytes, expected 1315
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory Frameworks/Steam
Helper EH.app/Contents/MacOS/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam Helper
EH.app/Contents/MacOS/Steam Helper EH is -1 bytes, expected 3105348
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam Helper
EH.app/Contents/PkgInfo is -1 bytes, expected 8
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory Frameworks/Steam
Helper.app/Contents/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam
Helper.app/Contents/Info.plist is -1 bytes, expected 1303
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory Frameworks/Steam
Helper.app/Contents/MacOS/
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam
Helper.app/Contents/MacOS/Steam Helper is -1 bytes, expected 3105308
[2015-07-07 20:21:12] BVerifyInstalledFiles: Frameworks/Steam
Helper.app/Contents/PkgInfo is -1 bytes, expected 8
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory friends/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/AchievementNotification.res is -1 bytes, expected 1919
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/addfriendenterdetailssubpanel.res is -1 bytes, expected 1968
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/addfriendresultsubpanel.res is -1 bytes, expected 749
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/addfriendresultsubpanel_failure.res is -1 bytes, expected 770
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/addfriendresultsubpanel_success.res is -1 bytes, expected 787
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/BlockCommunicationResultDialog.res is -1 bytes, expected 1619
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/BlockCommunicationWarningDialog.res is -1 bytes, expected 2471
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastapprovebar.res is -1 bytes, expected 1937
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastapprovenotification.res is -1 bytes, expected 2426
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastcantstartfriend.res is -1 bytes, expected 2410
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/broadcastinvitebar.res
is -1 bytes, expected 1612
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastinvitenotification.res is -1 bytes, expected 2421
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastpublicstatenotification.res is -1 bytes, expected 2063
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastrecordererrornotification.res is -1 bytes, expected 1697
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastuploaderrornotification.res is -1 bytes, expected 1701
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/broadcastviewernotification.res is -1 bytes, expected 2420
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ChatIntroductionDialog.res is -1 bytes, expected 4541
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ChatInviteNotification.res is -1 bytes, expected 2730
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ChatMsgNotification.res is -1 bytes, expected 2754
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ChatPasswordWarningDialog.res is -1 bytes, expected 2345
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/ChatRoomDlg.res is -1
bytes, expected 3966
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/ChatRoomDlgFriend.res
is -1 bytes, expected 3807
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ChatURLWarningDialog.res is -1 bytes, expected 3959
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/ClanEventDialog.res is
-1 bytes, expected 2595
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ClanEventNotification.res is -1 bytes, expected 2698
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/ClanInvitationNotification.res is -1 bytes, expected 2841
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/DialogFindBuddy.res is
-1 bytes, expected 232
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/DialogHelpIngame.res
is -1 bytes, expected 1099
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/DialogRemoveUser.res
is -1 bytes, expected 2038
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/DialogSendMessage.res
is -1 bytes, expected 1907
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/DialogSystemMessage.res is -1 bytes, expected 975
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/friendaliasesdialog.res is -1 bytes, expected 2545
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/friendgameinvitedialog.res is -1 bytes, expected 2127
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/FriendIngameNotification.res is -1 bytes, expected 2730
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/FriendInvitationNotification.res is -1 bytes, expected 2820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/friendnotificationoptionsdialog.res is -1 bytes, expected 4678
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/FriendOnlineNotification.res is -1 bytes, expected 2406
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/FriendsDialog.res is
-1 bytes, expected 7340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/friendsrefreshlogindialog.res is -1 bytes, expected 2884
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/friend_join.wav is -1
bytes, expected 487576
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/friend_online.wav is
-1 bytes, expected 267286
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/gameinvitebar.res is
-1 bytes, expected 1614
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/GameInviteNotification.res is -1 bytes, expected 2722
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/giftreceivednotification.res is -1 bytes, expected 2394
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_chatFailed.tga is
-1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_chat_activity.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_chat_idle.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_connected.tga is
-1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_connected_speaking.tga is -1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_groupchat_activity.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_groupchat_idle.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_microphone.tga is
-1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_microphone_hold.tga is -1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_microphone_off.tga is -1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_notChatting.tga
is -1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/icon_speaker.tga is -1
bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/icon_speaker_ringing.tga is -1 bytes, expected 2348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/InviteFriendResultSubPanel.res is -1 bytes, expected 751
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/InviteFriendResultSubPanel_failure.res is -1 bytes, expected 774
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/InviteFriendResultSubPanel_success.res is -1 bytes, expected 770
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/itemreceivednotification.res is -1 bytes, expected 2028
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_1.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_2.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_3.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_4.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_5.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_6.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_7.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/loop_8.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/message.wav is -1
bytes, expected 127340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/newturnsnotification.res is -1 bytes, expected 2011
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/PlayersSubRecentPlayers.res is -1 bytes, expected 660
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/rampDown_1.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/rampDown_2.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/rampUp_1.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/rampUp_2.tga is -1
bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/setnicknamedialog.layout is -1 bytes, expected 971
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/SubPanelFindBuddy.res
is -1 bytes, expected 3202
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/SubPanelFindBuddyComplete.res is -1 bytes, expected 742
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/SubPanelFindBuddyRequestAuth.res is -1 bytes, expected 601
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/SubPanelFindBuddyResults.res is -1 bytes, expected 986
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/SubPanelUserInfoDetails.res is -1 bytes, expected 4062
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/TrackerDialog.res is
-1 bytes, expected 38
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_brazilian.txt is -1 bytes, expected 200924
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_bulgarian.txt is -1 bytes, expected 201074
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_czech.txt is
-1 bytes, expected 202100
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_danish.txt
is -1 bytes, expected 198198
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_dutch.txt is
-1 bytes, expected 201842
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_english.txt
is -1 bytes, expected 93910
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_finnish.txt
is -1 bytes, expected 197746
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_french.txt
is -1 bytes, expected 204512
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_german.txt
is -1 bytes, expected 203866
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_greek.txt is
-1 bytes, expected 207270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_hungarian.txt is -1 bytes, expected 198932
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_italian.txt
is -1 bytes, expected 202906
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_japanese.txt
is -1 bytes, expected 178434
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_korean.txt
is -1 bytes, expected 176752
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_koreana.txt
is -1 bytes, expected 176752
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_norwegian.txt is -1 bytes, expected 198348
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_polish.txt
is -1 bytes, expected 202018
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_portuguese.txt is -1 bytes, expected 201260
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_romanian.txt
is -1 bytes, expected 197510
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_russian.txt
is -1 bytes, expected 198764
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_schinese.txt
is -1 bytes, expected 169148
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_spanish.txt
is -1 bytes, expected 203736
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_swedish.txt
is -1 bytes, expected 196360
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_tchinese.txt
is -1 bytes, expected 169678
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_thai.txt is
-1 bytes, expected 194054
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/trackerui_turkish.txt
is -1 bytes, expected 197632
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/trackerui_ukrainian.txt is -1 bytes, expected 199346
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/tradeinvitebar.res is
-1 bytes, expected 1966
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/tradeinvitenotification.res is -1 bytes, expected 2362
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/voicebar.res is -1
bytes, expected 833
[2015-07-07 20:21:12] BVerifyInstalledFiles:
friends/VoiceChatInviteNotification.res is -1 bytes, expected 2382
[2015-07-07 20:21:12] BVerifyInstalledFiles: friends/voice_hang_up.wav is
-1 bytes, expected 84028
[2015-07-07 20:21:12] BVerifyInstalledFiles: friendsui.dylib is -1 bytes,
expected 7700596
[2015-07-07 20:21:12] BVerifyInstalledFiles: gameoverlayrenderer.dylib is
-1 bytes, expected 639028
[2015-07-07 20:21:12] BVerifyInstalledFiles: gameoverlayui is -1 bytes,
expected 29472
[2015-07-07 20:21:12] BVerifyInstalledFiles: gameoverlayui.dylib is -1
bytes, expected 7865252
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory graphics/
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/achievementbg.tga is
-1 bytes, expected 7788
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/achievementbg_recent.tga is -1 bytes, expected 19644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/avatarBorderGolden.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/avatarBorderInGame.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/avatarBorderOffline.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/avatarBorderOnline.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/avatar_184blank.tga
is -1 bytes, expected 135468
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/avatar_32blank.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/avatar_64blank.tga is
-1 bytes, expected 16428
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/beta.tga is -1 bytes,
expected 46444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/beta_hover.tga is -1
bytes, expected 46444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/bg_security_code_entry.tga is -1 bytes, expected 41036
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/bg_security_wizard.tga is -1 bytes, expected 495404
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/BigPictureBG.tga is
-1 bytes, expected 110460
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
graphics/broadcast/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/broadcast_live_grey.png is -1 bytes, expected 1552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/broadcast_live_red.png is -1 bytes, expected 1657
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/desktop_placeholder.jpg is -1 bytes, expected 242255
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_close_default.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_close_hover.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_mic_disabled.png is -1 bytes, expected 1548
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_mic_off.png is -1 bytes, expected 1219
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_mic_on.png is -1 bytes, expected 1216
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_requests.png is -1 bytes, expected 1225
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/broadcast/icon_viewers.png is -1 bytes, expected 1433
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefBottom.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefBottomLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefBottomRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefLeft.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefRight.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefTop.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefTopLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDefTopRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisBottom.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisBottomLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisBottomRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisLeft.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisRight.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisTop.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisTopLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnDisTopRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffBottom.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/btnOvrOffBottomLeft.tga is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/btnOvrOffBottomRight.tga is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffTop.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffTopLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOffTopRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnBottom.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/btnOvrOnBottomLeft.tga is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/btnOvrOnBottomRight.tga is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnTop.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnTopLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnOvrOnTopRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelBottom.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelBottomLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelBottomRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelLeft.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelRight.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelTop.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelTopLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnSelTopRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdBottom.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdBottomLeft.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdBottomRight.tga
is -1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdLeft.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdRight.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdTop.tga is -1
bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdTopLeft.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/btnStdTopRight.tga is
-1 bytes, expected 444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkaeldis_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkIndeterminate.tga
is -1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/chkIndeterminate@2x.tga is -1 bytes, expected 7074
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelDis.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelDis@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelDown.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelDown@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkseldown_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelFocus.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelFocus@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkselfocus_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelStd.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSelStd@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkselstd_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkSomeSelStd.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselDis.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselDis@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkunseldis_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselFocus.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselFocus@2x.tga
is -1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkunselfocus_sm.tga
is -1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselStd.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkUnselStd@2x.tga is
-1 bytes, expected 7074
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chkunselstd_sm.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chk_menu_item.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/chk_menu_item@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/clienttexture2.tga is
-1 bytes, expected 815544
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/clienttexture2b.tga
is -1 bytes, expected 815544
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/clienttexture3.tga is
-1 bytes, expected 354204
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/clienttexture4.tga is
-1 bytes, expected 163144
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/clienttexture8.tga is
-1 bytes, expected 1043244
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/cloud_cloudfiles.tga
is -1 bytes, expected 15172
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/cloud_icon_down.tga
is -1 bytes, expected 764
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/cloud_icon_up.tga is
-1 bytes, expected 764
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/cloud_localfiles.tga
is -1 bytes, expected 15172
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/cloud_uhoh.tga is -1
bytes, expected 26828
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/creditcard_back.tga
is -1 bytes, expected 61544
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/creditcard_back_amex.tga is -1 bytes, expected 61844
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/downloads_bg.tga is
-1 bytes, expected 73844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/emailreminder_center.tga is -1 bytes, expected 240
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/emailreminder_close.tga is -1 bytes, expected 1196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/emailreminder_close_hover.tga is -1 bytes, expected 1196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/emailreminder_left.tga is -1 bytes, expected 632
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/emailreminder_right.tga is -1 bytes, expected 632
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/facebookLogo12.tga is
-1 bytes, expected 349
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/facebookLogo140.tga
is -1 bytes, expected 3679
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/find_icon_down.tga is
-1 bytes, expected 1124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/find_icon_down_hover.tga is -1 bytes, expected 1124
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/find_icon_up.tga is
-1 bytes, expected 1124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/find_icon_up_hover.tga is -1 bytes, expected 1124
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_bottom.tga is -1
bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_bottom_hover.tga
is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_fill_hover.tga
is -1 bytes, expected 140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_bottom.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_bottom_hover.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_left.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_left_hover.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_right.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_right_hover.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_inactive_top.tga
is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/flag_inactive_top_hover.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_left.tga is -1
bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_left_hover.tga
is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_right.tga is -1
bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_right_hover.tga
is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_top.tga is -1
bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/flag_top_hover.tga is
-1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/FriendsListSlantBG.tga is -1 bytes, expected 5804
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/friendslist_header2.tga is -1 bytes, expected 44960
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/FriendsPanelLeftBG.tga is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/FriendsPanelLeftBG_Down.tga is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/FriendsPanelLeftBG_Over.tga is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/FriendsPanelRightBG.tga is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/friends_icon.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/gift_wizard_friends.tga is -1 bytes, expected 45836
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/gift_wizard_heart.tga
is -1 bytes, expected 48764
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/gridview_mask.tga is
-1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/grid_btm_focus2.tga
is -1 bytes, expected 42364
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/grid_top_focus2.tga
is -1 bytes, expected 42364
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/html_lock.tga is -1
bytes, expected 1260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/html_lock_broken.tga
is -1 bytes, expected 1260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/html_lock_disabled.tga is -1 bytes, expected 15172
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/html_lock_ev.tga is
-1 bytes, expected 764
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_addFriend.tga is
-1 bytes, expected 528
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_back.tga
is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_disabled.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_disabled@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_down.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_down@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_over.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_back_over@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_detail.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_detail_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_detail_down.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_detail_over.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_disabled.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_disabled@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_down.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_down@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_over.tga is -1 bytes, expected 4012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_forward_over@2x.tga is -1 bytes, expected 15916
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_friends.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_friends_mousedown.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_friends_mouseover.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen.tga is -1 bytes, expected 23596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen@2x.tga is -1 bytes, expected 94252
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_disabled.tga is -1 bytes, expected 23596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_disabled@2x.tga is -1 bytes, expected 94252
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_down.tga is -1 bytes, expected 23596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_down@2x.tga is -1 bytes, expected 94252
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_over.tga is -1 bytes, expected 23596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_fullscreen_over@2x.tga is -1 bytes, expected 94252
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_grid.tga
is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_gridl_disabled.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_grid_down.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_grid_over.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_home.tga
is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_home_down.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_home_over.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_list.tga
is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_list_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_list_down.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_list_over.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_news.tga
is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_news_mousedown.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_news_mouseover.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload_disabled@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload_down.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload_down@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload_over.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_reload_over@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search@2x.tga is -1 bytes, expected 5228
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_disabled@2x.tga is -1 bytes, expected 5228
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_down.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_down@2x.tga is -1 bytes, expected 5228
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_over.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_search_over@2x.tga is -1 bytes, expected 5228
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_servers.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_servers_mousedown.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_servers_mouseover.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_settings.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_settings_mousedown.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_settings_mouseover.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_button_stop.tga
is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_disabled.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_disabled@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_down.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_down@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_over.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_stop_over@2x.tga is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_support.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_support_mousedown.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_button_support_mouseover.tga is -1 bytes, expected 20844
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_buy.tga is -1
bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_buy@2x.tga is -1
bytes, expected 4124
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_buy_down.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_buy_hover.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_click_for_details.tga is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_close.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_close_hover.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_collapse.tga is
-1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_collapse_friends.tga is -1 bytes, expected 548
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_collapse_osx.tga
is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_collapse_over.tga is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_collapse_over_osx.tga is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm.tga is -1 bytes, expected 1164
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm@2x.tga is -1 bytes, expected 4524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_disabled.tga is -1 bytes, expected 1164
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_disabled@2x.tga is -1 bytes, expected 4524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_down.tga is -1 bytes, expected 1164
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_down@2x.tga is -1 bytes, expected 4524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_over.tga is -1 bytes, expected 1164
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_controller_bpm_over@2x.tga is -1 bytes, expected 4524
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_details.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_details_hover.tga is -1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_disk_activity_busy.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_disk_activity_idle.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_download.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_download_hover.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_down_default.tga
is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_down_disabled.tga is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_down_focus.tga
is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_down_hover.tga
is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_emoticon.png is
-1 bytes, expected 1297
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_emoticon_hover.png is -1 bytes, expected 1326
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_expand.tga is -1
bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_expand_friends.tga is -1 bytes, expected 548
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_expand_osx.tga
is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_expand_over.tga
is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_expand_over_osx.tga is -1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_friends.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_info_sm.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_install.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_install@2x.tga
is -1 bytes, expected 4124
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_install_down.tga
is -1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_install_hover.tga is -1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_left_default.tga
is -1 bytes, expected 720
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_left_hover.tga
is -1 bytes, expected 720
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_meterOff.tga is
-1 bytes, expected 140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_meterOn.tga is
-1 bytes, expected 140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_moderatorstar.tga is -1 bytes, expected 620
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_music_player.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_music_player_hover.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_music_player_selected.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_officerStar.tga
is -1 bytes, expected 620
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_pause.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_pause_hover.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_play.tga is -1
bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_play@2x.tga is
-1 bytes, expected 4124
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_play_down.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_play_hover.tga
is -1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_right_default.tga is -1 bytes, expected 720
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_right_hover.tga
is -1 bytes, expected 720
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_scroll_handle.tga is -1 bytes, expected 332
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_scroll_handle_horiz.tga is -1 bytes, expected 396
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_scroll_handle_over.tga is -1 bytes, expected 332
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_scroll_handle_over_horiz.tga is -1 bytes, expected 396
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_fair.tga is -1 bytes, expected 2748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_good.tga is -1 bytes, expected 2748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_junk.tga is -1 bytes, expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_security_key.tga
is -1 bytes, expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_locked.tga is -1 bytes, expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_poor.tga is -1 bytes, expected 2748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_steam.tga is -1 bytes, expected 8352
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_twofactor.tga is -1 bytes, expected 2748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_unknown.tga is -1 bytes, expected 2748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_security_unlocked.tga is -1 bytes, expected 10796
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_status_bigpic.png is -1 bytes, expected 3052
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_status_bigpic_ingame.png is -1 bytes, expected 3052
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_status_mobile.png is -1 bytes, expected 2884
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_status_mobile_ingame.png is -1 bytes, expected 2883
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_status_web.png
is -1 bytes, expected 3096
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_status_web_ingame.png is -1 bytes, expected 3096
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_toast_gift.tga
is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_toast_item.tga
is -1 bytes, expected 6444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_toast_newturns.tga is -1 bytes, expected 2816
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_topofqueue.tga
is -1 bytes, expected 940
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_topofqueue_hover.tga is -1 bytes, expected 940
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_up_default.tga
is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_up_disabled.tga
is -1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_up_hover.tga is
-1 bytes, expected 260
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/icon_workshop.tga is
-1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/icon_workshop_hover.tga is -1 bytes, expected 1064
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_async_game.tga
is -1 bytes, expected 472
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_async_game_invite.tga is -1 bytes, expected 472
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_comment.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_gift.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_invite.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_item.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_moderatormessage.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification@2x.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_disabled.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_disabled@2x.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_inactive.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_inactive@2x.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_inactive_disabled.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_notification_inactive_disabled@2x.tga is -1 bytes, expected
4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/inbox_offlinemessage.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/inbox_trade.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/keybg.tga is -1
bytes, expected 146684
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/logo4.tga is -1
bytes, expected 103244
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/logo6.tga is -1
bytes, expected 19084
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/logo6@2x.tga is -1
bytes, expected 76204
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/logo7.tga is -1
bytes, expected 10684
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_1.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_2.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_3.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_4.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_5.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_6.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_7.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/loop_8.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mega_btn_off.png is
-1 bytes, expected 3045
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mega_btn_on.png is -1
bytes, expected 3075
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber01.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber02.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber03.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber04.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber05.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber06.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber07.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber08.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber09.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber10.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber11.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/minithrobber12.tga is
-1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/minithrobberinactive.tga is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mini_expand.tga is -1
bytes, expected 2564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/mini_expand_mouseover.tga is -1 bytes, expected 2564
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mini_shrink.tga is -1
bytes, expected 2564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/mini_shrink_mouseover.tga is -1 bytes, expected 2564
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mnuSepCenter.tga is
-1 bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mnuSepLeft.tga is -1
bytes, expected 84
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/mnuSepRight.tga is -1
bytes, expected 84
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/music_background.tga
is -1 bytes, expected 49484
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_0.png is -1 bytes, expected 8407
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_1.png is -1 bytes, expected 231422
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_2.png is -1 bytes, expected 231808
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_3.png is -1 bytes, expected 196774
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_4.png is -1 bytes, expected 185997
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_5.png is -1 bytes, expected 193571
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_6.png is -1 bytes, expected 188173
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_7.png is -1 bytes, expected 191031
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_8.png is -1 bytes, expected 195633
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_background_9.png is -1 bytes, expected 187474
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_browse_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_browse_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_browse_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_details_mask.png is -1 bytes, expected 8407
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_details_mask.tga is -1 bytes, expected 4194348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_pause_default.tga is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_pause_disabled.tga is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/music_pause_hover.tga
is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album.tga is -1 bytes, expected 129644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album0.png is -1 bytes, expected 5031
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album1.png is -1 bytes, expected 215956
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album1_50.png is -1 bytes, expected 215956
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album2.png is -1 bytes, expected 189385
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album2_50.png is -1 bytes, expected 189385
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album3.png is -1 bytes, expected 162748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album3_50.png is -1 bytes, expected 162748
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album4.png is -1 bytes, expected 211708
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album4_50.png is -1 bytes, expected 211708
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album5.png is -1 bytes, expected 180854
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album5_50.png is -1 bytes, expected 180854
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album6.png is -1 bytes, expected 170061
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album6_50.png is -1 bytes, expected 170061
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album7.png is -1 bytes, expected 126979
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album7_50.png is -1 bytes, expected 126979
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album8.png is -1 bytes, expected 195766
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album8_50.png is -1 bytes, expected 195766
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album9.png is -1 bytes, expected 193035
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_placeholder_album9_50.png is -1 bytes, expected 193035
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/music_player_bg.tga
is -1 bytes, expected 3392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_player_placeholder_album.tga is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_player_placeholder_album_400.tga is -1 bytes, expected 640044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_play_default.tga is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_play_disabled.tga is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/music_play_hover.tga
is -1 bytes, expected 10044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat1_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat1_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat1_enabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat1_enabled_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat_enabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat_enabled_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_repeat_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_shuffle_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_shuffle_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_shuffle_enabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_shuffle_enabled_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_shuffle_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackback_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackback_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackback_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackfwd_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackfwd_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_trackfwd_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_mute_default.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_mute_disabled.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/music_volume_mute_hover.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/nav2_highlight_selected.tga is -1 bytes, expected 14444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/nav_highlight_selected.tga is -1 bytes, expected 38132
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_button.tga is -1
bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_button_danish.tga
is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_button_french.tga
is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_button_german.tga
is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_button_hover.tga
is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_danish.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_french.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_german.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_italian.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_norwegian.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_spanish.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_hover_swedish.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_italian.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_norwegian.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_spanish.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/new_button_swedish.tga is -1 bytes, expected 64044
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/new_tab.tga is -1
bytes, expected 300
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_def.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_def@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_down.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_down@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_hov.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_close_hov@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_def.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_def@2x.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_down.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_down@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_hov.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_max_hov@2x.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_def.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_def@2x.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_down.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_down@2x.tga
is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_hov.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_min_hov@2x.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_win_dis.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/osx_win_dis@2x.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelDis.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelDis@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelDown.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelDown@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelFocus.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelFocus@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelStd.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radSelStd@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselDis.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselDis@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselFocus.tga is
-1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselFocus@2x.tga
is -1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselStd.tga is -1
bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/radUnselStd@2x.tga is
-1 bytes, expected 7100
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampDown_1.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampDown_2.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampDown_3.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampDown_4.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampUp_1.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampUp_2.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampUp_3.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/rampUp_4.tga is -1
bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/resizer.tga is -1
bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/resizer_over.tga is
-1 bytes, expected 828
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrBottom.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrBottomLeft.tga is
-1 bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrBottomRight.tga is
-1 bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrEnds.tga is -1
bytes, expected 884
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrLeft.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrRight.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrTop.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrTopLeft.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/scrTopRight.tga is -1
bytes, expected 108
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/shadowBottom.tga is
-1 bytes, expected 64
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/shadowslantTop.tga is
-1 bytes, expected 49324
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/shadowTop.tga is -1
bytes, expected 64
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/simBottom.tga is -1
bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/simTop.tga is -1
bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/streaming_intro.tga
is -1 bytes, expected 237852
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/streaming_shortcut_16.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/streaming_shortcut_32.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/stream_disconnect_notification.tga is -1 bytes, expected 71084
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/stream_notification.tga is -1 bytes, expected 71084
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_bottom.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_bottom_hover.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/support_flag_left.tga
is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_left_hover.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_right.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_right_hover.tga is -1 bytes, expected 392
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/support_flag_top.tga
is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/support_flag_top_hover.tga is -1 bytes, expected 56
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/tabSquareBottomLeft.tga is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/tabSquareBottomRight.tga is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabSquareTopLeft.tga
is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabSquareTopRight.tga
is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdBottom.tga is
-1 bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdBottomLeft.tga
is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdBottomRight.tga
is -1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdLeft.tga is -1
bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdRight.tga is -1
bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdTop.tga is -1
bytes, expected 48
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdTopLeft.tga is
-1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tabStdTopRight.tga is
-1 bytes, expected 80
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/textentry_focus.tga
is -1 bytes, expected 4736
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tiny_x_default.tga is
-1 bytes, expected 236
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/tiny_x_hover.tga is
-1 bytes, expected 236
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/win32_win_close.tga
is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/win32_win_close_disabled.tga is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/win32_win_close_hover.tga is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/win32_win_max.tga is
-1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/win32_win_max_hover.tga is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/win32_win_min.tga is
-1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/win32_win_min_hover.tga is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles: graphics/win32_win_restore.tga
is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
graphics/win32_win_restore_hover.tga is -1 bytes, expected 944
[2015-07-07 20:21:12] BVerifyInstalledFiles: Info.plist is 1770 bytes,
expected 1831
[2015-07-07 20:21:12] BVerifyInstalledFiles: ipcserver is -1 bytes,
expected 34016
[2015-07-07 20:21:12] BVerifyInstalledFiles: libaudio.dylib is -1 bytes,
expected 393660
[2015-07-07 20:21:12] BVerifyInstalledFiles: libavcodec.56.dylib is -1
bytes, expected 944688
[2015-07-07 20:21:12] BVerifyInstalledFiles: libavformat.56.dylib is -1
bytes, expected 219540
[2015-07-07 20:21:12] BVerifyInstalledFiles: libavresample.2.dylib is -1
bytes, expected 152732
[2015-07-07 20:21:12] BVerifyInstalledFiles: libavutil.54.dylib is -1
bytes, expected 162356
[2015-07-07 20:21:12] BVerifyInstalledFiles: libav_h264.56.dylib.crypt is
-1 bytes, expected 1386960
[2015-07-07 20:21:12] BVerifyInstalledFiles: libav_h264.56.dylib.md5 is -1
bytes, expected 32
[2015-07-07 20:21:12] BVerifyInstalledFiles: libfontconfig.dylib is -1
bytes, expected 677128
[2015-07-07 20:21:12] BVerifyInstalledFiles: libfreetype.dylib is -1 bytes,
expected 2024164
[2015-07-07 20:21:12] BVerifyInstalledFiles: libgio-2.0.dylib is -1 bytes,
expected 4291308
[2015-07-07 20:21:12] BVerifyInstalledFiles: libglib-2.0.dylib is -1 bytes,
expected 3337568
[2015-07-07 20:21:12] BVerifyInstalledFiles: libgmodule-2.0.dylib is -1
bytes, expected 43584
[2015-07-07 20:21:12] BVerifyInstalledFiles: libgobject-2.0.dylib is -1
bytes, expected 818148
[2015-07-07 20:21:12] BVerifyInstalledFiles: libgthread-2.0.dylib is -1
bytes, expected 24964
[2015-07-07 20:21:12] BVerifyInstalledFiles: libharfbuzz.dylib is -1 bytes,
expected 1701956
[2015-07-07 20:21:12] BVerifyInstalledFiles: libicui18n.dylib is -1 bytes,
expected 2527004
[2015-07-07 20:21:12] BVerifyInstalledFiles: libicuuc.dylib is -1 bytes,
expected 12153740
[2015-07-07 20:21:12] BVerifyInstalledFiles: libMilesX86.dylib is -1 bytes,
expected 323248
[2015-07-07 20:21:12] BVerifyInstalledFiles: libpango-1.0.dylib is -1
bytes, expected 798884
[2015-07-07 20:21:12] BVerifyInstalledFiles: libpangoft2-1.0.dylib is -1
bytes, expected 238288
[2015-07-07 20:21:12] BVerifyInstalledFiles: libSDL2-2.0.0.dylib is -1
bytes, expected 3784452
[2015-07-07 20:21:12] BVerifyInstalledFiles: libsteam.dylib is -1 bytes,
expected 3772288
[2015-07-07 20:21:12] BVerifyInstalledFiles: libswscale.3.dylib is -1
bytes, expected 366828
[2015-07-07 20:21:12] BVerifyInstalledFiles: libtier0_s.dylib is -1 bytes,
expected 418232
[2015-07-07 20:21:12] BVerifyInstalledFiles: libv8.dylib is -1 bytes,
expected 10245940
[2015-07-07 20:21:12] BVerifyInstalledFiles: libvideo.dylib is -1 bytes,
expected 4662360
[2015-07-07 20:21:12] BVerifyInstalledFiles: libvstdlib_s.dylib is -1
bytes, expected 604848
[2015-07-07 20:21:12] BVerifyInstalledFiles: libx264.142.dylib.crypt is -1
bytes, expected 884912
[2015-07-07 20:21:12] BVerifyInstalledFiles: libx264.142.dylib.md5 is -1
bytes, expected 32
[2015-07-07 20:21:12] BVerifyInstalledFiles: mssdsp.flt is -1 bytes,
expected 49664
[2015-07-07 20:21:12] BVerifyInstalledFiles: mssmixer.mix is -1 bytes,
expected 35840
[2015-07-07 20:21:12] BVerifyInstalledFiles: mssmp3.asi is -1 bytes,
expected 71168
[2015-07-07 20:21:12] BVerifyInstalledFiles: mssogg.asi is -1 bytes,
expected 41472
[2015-07-07 20:21:12] BVerifyInstalledFiles: mssvoice.asi is -1 bytes,
expected 152064
[2015-07-07 20:21:12] BVerifyInstalledFiles: panorama.dylib is -1 bytes,
expected 7434540
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/Account.html is -1
bytes, expected 1931
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/AppDownloadNotification.res is -1 bytes, expected 2355
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c1.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c10.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c11.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c12.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c13.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c14.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c15.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c16.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c17.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c18.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c19.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c2.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c20.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c3.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c4.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c5.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c6.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c7.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c8.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/c9.tga is -1 bytes,
expected 9678
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/check.ico is -1 bytes,
expected 542
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ConnectionIssuesDialog.res is -1 bytes, expected 2045
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ErrorSteamAlreadyRunningDialog.res is -1 bytes, expected 1641
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/LimitedUserDialog.res
is -1 bytes, expected 2320
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppasubpanel.res is -1
bytes, expected 1518
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_brazilian.htm is -1
bytes, expected 15668
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_english.htm is -1
bytes, expected 14264
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_french.htm is -1
bytes, expected 16029
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_german.htm is -1
bytes, expected 18636
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_italian.htm is -1
bytes, expected 15797
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_japanese.htm is -1
bytes, expected 13200
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_portuguese.htm is
-1 bytes, expected 15844
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_russian.htm is -1
bytes, expected 24652
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ppa_spanish.htm is -1
bytes, expected 16573
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/psnaccountsetupdialog.res is -1 bytes, expected 1514
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/RefreshLoginDialog.res
is -1 bytes, expected 4135
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ScreenshotErrorNotification.res is -1 bytes, expected 1172
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ScreenshotNotification.res is -1 bytes, expected 1582
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory public/ssa/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_brazilian_bigpicture.html is -1 bytes, expected 12128
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_english_bigpicture.html is -1 bytes, expected 11075
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_french_bigpicture.html is -1 bytes, expected 12486
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_german_bigpicture.html is -1 bytes, expected 13100
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_italian_bigpicture.html is -1 bytes, expected 12326
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_japanese_bigpicture.html is -1 bytes, expected 16366
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_koreana_bigpicture.html is -1 bytes, expected 12956
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_korean_bigpicture.html is -1 bytes, expected 12956
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_portuguese_bigpicture.html is -1 bytes, expected 13119
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_russian_bigpicture.html is -1 bytes, expected 22837
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_schinese_bigpicture.html is -1 bytes, expected 9642
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/eula_spanish_bigpicture.html is -1 bytes, expected 12713
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_brazilian_bigpicture.html is -1 bytes, expected 13751
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_english_bigpicture.html is -1 bytes, expected 11911
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_french_bigpicture.html is -1 bytes, expected 13920
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_german_bigpicture.html is -1 bytes, expected 16467
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_italian_bigpicture.html is -1 bytes, expected 13485
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_japanese_bigpicture.html is -1 bytes, expected 10855
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_portuguese_bigpicture.html is -1 bytes, expected 13911
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_russian_bigpicture.html is -1 bytes, expected 22343
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ppa_spanish_bigpicture.html is -1 bytes, expected 14480
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa/ssa_bigpicture.css
is -1 bytes, expected 1759
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_brazilian_bigpicture.html is -1 bytes, expected 54187
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_english_bigpicture.html is -1 bytes, expected 50089
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_french_bigpicture.html is -1 bytes, expected 56881
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_german_bigpicture.html is -1 bytes, expected 71235
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_italian_bigpicture.html is -1 bytes, expected 59565
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_japanese_bigpicture.html is -1 bytes, expected 68141
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_portuguese_bigpicture.html is -1 bytes, expected 55493
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_russian_bigpicture.html is -1 bytes, expected 95609
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/ssa/ssa_spanish_bigpicture.html is -1 bytes, expected 57196
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssadialog.res is -1
bytes, expected 2312
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssasubpanel.res is -1
bytes, expected 1433
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_brazilian.htm is -1
bytes, expected 56818
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_english.htm is -1
bytes, expected 52486
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_french.htm is -1
bytes, expected 59589
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_german.htm is -1
bytes, expected 73613
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_italian.htm is -1
bytes, expected 61988
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_japanese.htm is -1
bytes, expected 70526
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_portuguese.htm is
-1 bytes, expected 58080
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_russian.htm is -1
bytes, expected 97994
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/ssa_spanish.htm is -1
bytes, expected 59584
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_brazilian.txt is 7739 bytes, expected 7815
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_czech.txt is 7772 bytes, expected 7848
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_danish.txt is 7440 bytes, expected 7516
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_dutch.txt is 7458 bytes, expected 7536
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_english.txt is 3561 bytes, expected 3602
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_finnish.txt is 7683 bytes, expected 7762
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_french.txt is 7869 bytes, expected 7945
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_german.txt is 7808 bytes, expected 7884
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_greek.txt is 9008 bytes, expected 9085
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_hungarian.txt is 7744 bytes, expected 7820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_italian.txt is 7883 bytes, expected 7861
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_japanese.txt is 8386 bytes, expected 8462
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_korean.txt is 7825 bytes, expected 7895
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_koreana.txt is 7825 bytes, expected 7895
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_norwegian.txt is 7437 bytes, expected 7513
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_polish.txt is 7488 bytes, expected 7564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_portuguese.txt is 7603 bytes, expected 7679
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_romanian.txt is 7671 bytes, expected 7747
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_russian.txt is 8934 bytes, expected 9010
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_schinese.txt is 7225 bytes, expected 7309
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_spanish.txt is 7788 bytes, expected 7864
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_swedish.txt is 7488 bytes, expected 7564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_tchinese.txt is 7215 bytes, expected 7291
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_thai.txt is 9808 bytes, expected 10039
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_turkish.txt is 7562 bytes, expected 7638
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steambootstrapper_ukrainian.txt is 9101 bytes, expected 9177
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamclean_brazilian.txt is -1 bytes, expected 650
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_czech.txt is
-1 bytes, expected 657
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_danish.txt
is -1 bytes, expected 595
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_dutch.txt is
-1 bytes, expected 637
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_english.txt
is -1 bytes, expected 600
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_finnish.txt
is -1 bytes, expected 649
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_french.txt
is -1 bytes, expected 675
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_german.txt
is -1 bytes, expected 634
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_greek.txt is
-1 bytes, expected 383
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamclean_hungarian.txt is -1 bytes, expected 663
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_italian.txt
is -1 bytes, expected 644
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_japanese.txt
is -1 bytes, expected 655
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_korean.txt
is -1 bytes, expected 629
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamclean_norwegian.txt is -1 bytes, expected 606
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_polish.txt
is -1 bytes, expected 620
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamclean_portuguese.txt is -1 bytes, expected 665
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_romanian.txt
is -1 bytes, expected 646
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_russian.txt
is -1 bytes, expected 721
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_schinese.txt
is -1 bytes, expected 644
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_spanish.txt
is -1 bytes, expected 646
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_swedish.txt
is -1 bytes, expected 614
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_tchinese.txt
is -1 bytes, expected 615
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_thai.txt is
-1 bytes, expected 736
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamclean_turkish.txt
is -1 bytes, expected 1268
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamclean_ukrainian.txt is -1 bytes, expected 706
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/SteamLoginDialog.res is
-1 bytes, expected 9373
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_brazilian.txt
is -1 bytes, expected 1246706
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_bulgarian.txt
is -1 bytes, expected 1248556
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_czech.txt is -1
bytes, expected 1240008
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_danish.txt is
-1 bytes, expected 1220632
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_dutch.txt is -1
bytes, expected 1244608
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_english.txt is
-1 bytes, expected 579578
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_finnish.txt is
-1 bytes, expected 1219044
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_french.txt is
-1 bytes, expected 1272448
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_german.txt is
-1 bytes, expected 1270268
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_greek.txt is -1
bytes, expected 1277882
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_hungarian.txt
is -1 bytes, expected 1234058
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_italian.txt is
-1 bytes, expected 1259564
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_japanese.txt is
-1 bytes, expected 1081488
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_korean.txt is
-1 bytes, expected 1072864
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_koreana.txt is
-1 bytes, expected 1072864
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_norwegian.txt
is -1 bytes, expected 1211978
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_polish.txt is
-1 bytes, expected 1234436
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_portuguese.txt
is -1 bytes, expected 1249694
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steamui_postlogon_greek.txt is -1 bytes, expected 17926
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_romanian.txt is
-1 bytes, expected 1227042
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_russian.txt is
-1 bytes, expected 1232982
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_schinese.txt is
-1 bytes, expected 1034658
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_spanish.txt is
-1 bytes, expected 1264444
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_swedish.txt is
-1 bytes, expected 1212622
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_tchinese.txt is
-1 bytes, expected 1035032
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_thai.txt is -1
bytes, expected 1202534
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_turkish.txt is
-1 bytes, expected 1218584
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steamui_ukrainian.txt
is -1 bytes, expected 1234912
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_cloudsync.ico is
-1 bytes, expected 3942
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steam_cloudsync_posix.tga is -1 bytes, expected 65580
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_logo.tga is -1
bytes, expected 10284
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_offline.ico is -1
bytes, expected 2350
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_offline.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_offline_posix.tga
is -1 bytes, expected 65580
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_tray.ico is -1
bytes, expected 298566
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_tray.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_tray_48.tga is -1
bytes, expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_tray_mono.png is
-1 bytes, expected 5405
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_tray_posix.tga is
-1 bytes, expected 65580
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_updating.ico is
-1 bytes, expected 3942
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_updating.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steam_updating_posix.tga is -1 bytes, expected 65580
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_welcome_large.tga
is -1 bytes, expected 134444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/steam_welcome_tooltray.tga is -1 bytes, expected 131116
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_working1.tga is
-1 bytes, expected 49691
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/steam_working_large.tga
is -1 bytes, expected 89342
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/SubExtraFactorAuth.res
is -1 bytes, expected 3799
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthFail.res is -1 bytes, expected 2100
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthIntro.res is -1 bytes, expected 3507
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthNoAccess.res is -1 bytes, expected 2564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthNoEmail.res is -1 bytes, expected 2510
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthResult.res is -1 bytes, expected 1081
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorAuthSuccess.res is -1 bytes, expected 2121
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubExtraFactorRecover.res is -1 bytes, expected 2928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordAccountName.res is -1 bytes, expected 2125
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordCDKey.res is -1 bytes, expected 1149
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordEmailAddress.res is -1 bytes, expected 1183
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordGetAuthCode.res is -1 bytes, expected 1244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordGetEmailCode.res is -1 bytes, expected 1237
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordGetSmsCode.res is -1 bytes, expected 1228
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordIncorrect.res is -1 bytes, expected 425
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordOther.res is -1 bytes, expected 399
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordRecoverAuthenticatorDone.res is -1 bytes, expected
792
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordResetType.res is -1 bytes, expected 2088
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordResetType2.res is -1 bytes, expected 1650
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordSentEmail.res is -1 bytes, expected 424
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordSetNewPassword.res is -1 bytes, expected 2633
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordSuccess.res is -1 bytes, expected 419
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubForgotPasswordUserName.res is -1 bytes, expected 1161
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/subpanelchoosedefaultcachedir.res is -1 bytes, expected 1492
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccount.res is -1 bytes, expected 1199
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountAccountName.res is -1 bytes, expected
3939
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountEmail.res is -1 bytes, expected 2710
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountEmailAlreadyUsed.res is -1 bytes,
expected 7776
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountFinished.res is -1 bytes, expected 725
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountMultiple.res is -1 bytes, expected
1603
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountNameCollision.res is -1 bytes,
expected 2162
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountNames.res is -1 bytes, expected 3427
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountPassword.res is -1 bytes, expected
1853
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountPrintDetails.res is -1 bytes,
expected 287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreateNewAccountSecretQuestion.res is -1 bytes,
expected 2323
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeCreatingAccount.res is -1 bytes, expected 386
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeIntro.res is -1 bytes, expected 2344
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubPanelWelcomeRetailIntro.res is -1 bytes, expected 1995
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubRecoverAuthenticatorEmailOrSmsChoice.res is -1 bytes, expected
1339
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubRecoverAuthenticatorGetPassword.res is -1 bytes, expected 1189
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubRecoverAuthenticatorGetRecoveryCode.res is -1 bytes, expected 2480
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubRecoverAuthenticatorGetSmsCode.res is -1 bytes, expected 1229
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SubRecoverAuthenticatorGetSupportingInfo.res is -1 bytes, expected
3189
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/SupportQueryProgress.res is -1 bytes, expected 1268
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/url_list.txt is -1
bytes, expected 14779
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/UseOfflineMode.res is
-1 bytes, expected 3281
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/UseOfflineModeChosen.res is -1 bytes, expected 2046
[2015-07-07 20:21:12] BVerifyInstalledFiles: public/VACBanDialog.res is -1
bytes, expected 2585
[2015-07-07 20:21:12] BVerifyInstalledFiles:
public/WelcomeAccountCreateProgress.res is -1 bytes, expected 921
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory remoteui/static/
[2015-07-07 20:21:12] BVerifyInstalledFiles: remoteui/static/gamesList.css
is -1 bytes, expected 1000
[2015-07-07 20:21:12] BVerifyInstalledFiles: remoteui/static/headsDown.js
is -1 bytes, expected 486
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
remoteui/static/images/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_backTrack.png is -1 bytes,
expected 4148
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_backTrack_hit.png is -1 bytes,
expected 4227
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_forwardTrack.png is -1 bytes,
expected 4100
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_forwardTrack_hit.png is -1
bytes, expected 4217
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_leftSpacer.png is -1 bytes,
expected 2994
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_pauseButton.png is -1 bytes,
expected 11697
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_playButton.png is -1 bytes,
expected 12150
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_repeat.png is -1 bytes, expected
4522
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_repeat_on.png is -1 bytes,
expected 4725
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_shuffle.png is -1 bytes,
expected 4680
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_shuffle_on.png is -1 bytes,
expected 4900
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_volumeBar.png is -1 bytes,
expected 3441
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/images/remote_playControls_volumeScrubber.png is -1 bytes,
expected 3844
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
remoteui/static/libs/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
remoteui/static/libs/images/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/images/ajax-loader.gif is -1 bytes, expected 7825
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/images/icons-18-black.png is -1 bytes, expected 1968
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/images/icons-18-white.png is -1 bytes, expected 1988
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/images/icons-36-black.png is -1 bytes, expected 3859
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/images/icons-36-white.png is -1 bytes, expected 3861
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/jquery-1.9.1.min.js is -1 bytes, expected 92639
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/jquery-1.9.1.min.map is -1 bytes, expected 138758
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/jquery.mobile.ext.js is -1 bytes, expected 17538
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/libs/LICENSE.txt is -1 bytes, expected 1243
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/playerControls.css is -1 bytes, expected 2027
[2015-07-07 20:21:12] BVerifyInstalledFiles:
remoteui/static/playerControls.js is -1 bytes, expected 6533
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory resource/
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/0_star.png is -1
bytes, expected 2823
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/1_star.png is -1
bytes, expected 3423
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/2_star.png is -1
bytes, expected 3934
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/3_star.png is -1
bytes, expected 2861
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/4_star.png is -1
bytes, expected 4883
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/5_star.png is -1
bytes, expected 5291
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/battery_border.tga is
-1 bytes, expected 10684
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/battery_bright.tga is
-1 bytes, expected 8492
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/battery_dim.tga is -1
bytes, expected 10684
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/camera1.wav is -1
bytes, expected 18086
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/chatty.tga is -1
bytes, expected 102716
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/CreateTokenDialog.res
is -1 bytes, expected 2543
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/dlc_generic_header.png is -1 bytes, expected 52612
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/dlc_installed.png is
-1 bytes, expected 15675
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/dlc_overlay.png is -1
bytes, expected 5635
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/EasyNotification.res
is -1 bytes, expected 724
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/EditTokenDialog.res
is -1 bytes, expected 4073
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/familyview.png is -1
bytes, expected 1373
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/FileCopyDialog.res is
-1 bytes, expected 1757
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/FileCopyOverwritePrompt.res is -1 bytes, expected 2158
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/FileOpenDialog.res is
-1 bytes, expected 4510
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory resource/fonts/
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/fonts/marlett.ttf is
-1 bytes, expected 6136
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_blank.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_clear_field.tga
is -1 bytes, expected 914
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/icon_community_preview.tga is -1 bytes, expected 57644
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_error_red.tga is
-1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_file.tga is -1
bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_folder.tga is -1
bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_folderup.tga is
-1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/icon_folder_selected.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_gift.tga is -1
bytes, expected 9648
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_hlicon1.tga is
-1 bytes, expected 1307
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_hlicon2.tga is
-1 bytes, expected 1307
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_info.tga is -1
bytes, expected 12588
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_newfolder.tga is
-1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_password.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_steam.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/icon_steam_disabled.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/icon_trade_request.tga is -1 bytes, expected 5196
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/icon_warning.tga is
-1 bytes, expected 13968
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/icon_warning_yellow.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/invite.tga is -1
bytes, expected 7244
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory resource/layout/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/appdownloadpanel.layout is -1 bytes, expected 8630
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/app_validation_dialog.layout is -1 bytes, expected 600
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/authorizelocaldevice.layout is -1 bytes, expected 1120
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/broadcastview.layout is -1 bytes, expected 718
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/broadcast_chatbanner.layout is -1 bytes, expected 672
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/broadcast_firsttime.layout is -1 bytes, expected 2705
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/broadcast_livebanner.layout is -1 bytes, expected 1962
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/chattitlepanel.layout is -1 bytes, expected 1152
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/choosepurchaseorauthorization.layout is -1 bytes, expected
1052
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/cloud_conflict_dialog.layout is -1 bytes, expected 3354
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/debugstats.layout is -1 bytes, expected 767
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/deletecustomimagedialog.layout is -1 bytes, expected 834
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/downloadspage.layout is -1 bytes, expected 1522
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/downloadsummarypanel.layout is -1 bytes, expected 6844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/editfriendsgroups.layout is -1 bytes, expected 746
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/edittagspage.layout is -1 bytes, expected 883
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/emailreminderbar.layout is -1 bytes, expected 2464
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/friendpanel.layout is -1 bytes, expected 4307
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/friendpanel_compact.layout is -1 bytes, expected 1927
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/friendpanel_rightaligned.layout is -1 bytes, expected 870
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gameproperties_general.layout is -1 bytes, expected 2910
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gameproperties_updates.layout is -1 bytes, expected 4154
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_achievements.layout is -1 bytes, expected
1587
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_achievements_locked.layout is -1 bytes,
expected 2199
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_achievements_most_recent.layout is -1
bytes, expected 2565
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_cloud.layout is -1 bytes, expected 1337
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_cloud_file.layout is -1 bytes, expected
2009
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_communityfiles.layout is -1 bytes,
expected 966
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_community_file.layout is -1 bytes,
expected 2423
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_dlc.layout is -1 bytes, expected 1811
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_friends.layout is -1 bytes, expected 4124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_friends_list.layout is -1 bytes, expected
1969
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_gametitleheader.layout is -1 bytes,
expected 784
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_news.layout is -1 bytes, expected 1002
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_news_item.layout is -1 bytes, expected
2100
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_nonsteam.layout is -1 bytes, expected 874
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_screenshots.layout is -1 bytes, expected
1020
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_screenshots_list.layout is -1 bytes,
expected 3866
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_subheader.layout is -1 bytes, expected
8285
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_subheaderright.layout is -1 bytes,
expected 2328
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_subheaderright_labels.layout is -1 bytes,
expected 889
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_subheader_labels.layout is -1 bytes,
expected 1747
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_turnnotifications.layout is -1 bytes,
expected 1056
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_turnnotifications_item.layout is -1
bytes, expected 754
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_welcome.layout is -1 bytes, expected 1076
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_details_workshop_details.layout is -1 bytes,
expected 900
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_grid.layout is -1 bytes, expected 1781
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_grid_chrome.layout is -1 bytes, expected 2841
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_grid_loaded.layout is -1 bytes, expected 280
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_grid_loadfailed.layout is -1 bytes, expected 1670
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_grid_loading.layout is -1 bytes, expected 1653
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/gamespage_mini.layout is -1 bytes, expected 4443
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/htmlfindbar.layout is -1 bytes, expected 1672
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/htmlimebar.layout is -1 bytes, expected 780
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/htmlpopup.layout is -1 bytes, expected 3193
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/ingamefpsbanner.layout is -1 bytes, expected 531
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/joingamedialog.layout is -1 bytes, expected 2898
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/layoutdebugdialog.layout is -1 bytes, expected 618
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/layoutdebugdialog_details.layout is -1 bytes, expected 589
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musiclibrarypanel.layout is -1 bytes, expected 5786
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicpage_details_album.layout is -1 bytes, expected 5067
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicpage_details_content.layout is -1 bytes, expected 4136
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicpage_details_playlist.layout is -1 bytes, expected 3740
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicpage_details_playlistitem.layout is -1 bytes, expected
907
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicpage_details_trackitem.layout is -1 bytes, expected 904
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicplayerpanel.layout is -1 bytes, expected 7403
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/musicplayervolumepanel.layout is -1 bytes, expected 428
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaydashboard.layout is -1 bytes, expected 3169
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaydashboard_lores.layout is -1 bytes, expected 2839
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaydesktop.layout is -1 bytes, expected 3833
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaydesktop_lores.layout is -1 bytes, expected 3379
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaytaskbar.layout is -1 bytes, expected 2137
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlaywebbrowser.layout is -1 bytes, expected 4434
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_achievementsdetails.layout is -1 bytes, expected
1817
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_achievement_item.layout is -1 bytes, expected 561
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_broadcastchat.layout is -1 bytes, expected 2675
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_broadcastpanel.layout is -1 bytes, expected 1337
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_communitydiscussionspanel.layout is -1 bytes,
expected 1315
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_communityhubpanel.layout is -1 bytes, expected 1249
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_friendchangeconfirmationdialog.layout is -1 bytes,
expected 722
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_friendsdetails.layout is -1 bytes, expected 1475
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_guidespanel.layout is -1 bytes, expected 1235
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_guide_item.layout is -1 bytes, expected 909
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_microtxn_authdialog.layout is -1 bytes, expected
3078
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_newsdetails.layout is -1 bytes, expected 982
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_news_item.layout is -1 bytes, expected 832
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_playtimedetails.layout is -1 bytes, expected 1106
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/overlay_screenshotspanel.layout is -1 bytes, expected 1109
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/pagedragframe.layout is -1 bytes, expected 533
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/pagination_panel.layout is -1 bytes, expected 3035
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/parentallockdialog.layout is -1 bytes, expected 1416
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/parentalunlockdialog.layout is -1 bytes, expected 2082
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/remotecontrolauthorization.layout is -1 bytes, expected 1127
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/remotedeviceauthorization.layout is -1 bytes, expected 1367
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/requestdeviceauthorization.layout is -1 bytes, expected 1414
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotdeletedialog.layout is -1 bytes, expected 1032
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotmanager.layout is -1 bytes, expected 9110
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotspage.layout is -1 bytes, expected 1231
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotspage_full.layout is -1 bytes, expected 3418
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotspage_list.layout is -1 bytes, expected 836
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotspage_section.layout is -1 bytes, expected 459
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/screenshotsuploaddialog.layout is -1 bytes, expected 3087
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/setcustomimagedialog.layout is -1 bytes, expected 2033
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingsdialog.layout is -1 bytes, expected 1845
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingssubbroadcast.layout is -1 bytes, expected 5416
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingssubmusic.layout is -1 bytes, expected 4684
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingssubstreaming.layout is -1 bytes, expected 3034
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingssubstreaming_advanced_client.layout is -1 bytes,
expected 2056
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/settingssubstreaming_advanced_host.layout is -1 bytes,
expected 1912
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/special_survey_forwardtoweb.layout is -1 bytes, expected 371
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/special_survey_overview.layout is -1 bytes, expected 362
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog.layout is -1 bytes, expected 19819
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog_gamespage_details.layout is -1 bytes,
expected 8949
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog_gamespage_list.layout is -1 bytes, expected
307
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog_mediapage.layout is -1 bytes, expected 165
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog_musicpage_details.layout is -1 bytes,
expected 523
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/steamrootdialog_toolspage.layout is -1 bytes, expected 619
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/streamingintro.layout is -1 bytes, expected 1195
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/streamingprogress.layout is -1 bytes, expected 667
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/subpaneloptionsbrowser.layout is -1 bytes, expected 1142
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/subpaneloptionscloud.layout is -1 bytes, expected 813
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/subpaneloptionsdownloads.layout is -1 bytes, expected 4047
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/subpaneloptionsfamily.layout is -1 bytes, expected 2977
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/subpaneloptionsingame.layout is -1 bytes, expected 3774
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/toolwindow.layout is -1 bytes, expected 2508
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/twofactorcodechallenge.layout is -1 bytes, expected 2091
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/ugcdownloadpanel.layout is -1 bytes, expected 11104
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/uinavigatorpanel.layout is -1 bytes, expected 20621
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/uistatuspanel.layout is -1 bytes, expected 1282
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/layout/updatecontrollerfirmware.layout is -1 bytes, expected 876
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/LocalizationDialog.res is -1 bytes, expected 4352
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory resource/menus/
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/menus/friends.menu is
-1 bytes, expected 667
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/menus/steam.menu is
-1 bytes, expected 5692
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/mic_meter_dead.tga is
-1 bytes, expected 15404
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/mic_meter_live.tga is
-1 bytes, expected 15404
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/multiple_screenshots.tga is -1 bytes, expected 47916
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/new_badge.tga is -1
bytes, expected 7788
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/notfamilyview.png is
-1 bytes, expected 1378
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_brazilian.txt
is -1 bytes, expected 53020
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_bulgarian.txt
is -1 bytes, expected 53074
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_czech.txt is
-1 bytes, expected 52646
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_danish.txt is
-1 bytes, expected 52622
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_dutch.txt is
-1 bytes, expected 52952
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_english.txt
is -1 bytes, expected 25518
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_finnish.txt
is -1 bytes, expected 52410
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_french.txt is
-1 bytes, expected 54130
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_german.txt is
-1 bytes, expected 54060
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_greek.txt is
-1 bytes, expected 53776
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_hungarian.txt
is -1 bytes, expected 52626
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_italian.txt
is -1 bytes, expected 53608
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_japanese.txt
is -1 bytes, expected 47838
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_korean.txt is
-1 bytes, expected 47590
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_koreana.txt
is -1 bytes, expected 47590
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_norwegian.txt
is -1 bytes, expected 52276
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_polish.txt is
-1 bytes, expected 53270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/overlay_portuguese.txt is -1 bytes, expected 52888
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_romanian.txt
is -1 bytes, expected 52922
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_russian.txt
is -1 bytes, expected 52622
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_schinese.txt
is -1 bytes, expected 45868
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_spanish.txt
is -1 bytes, expected 53154
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_swedish.txt
is -1 bytes, expected 52368
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_tchinese.txt
is -1 bytes, expected 45884
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_thai.txt is
-1 bytes, expected 51684
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_turkish.txt
is -1 bytes, expected 52624
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/overlay_ukrainian.txt
is -1 bytes, expected 52154
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_brazilian.txt is -1 bytes, expected 15048
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_bulgarian.txt is -1 bytes, expected 14800
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_czech.txt is
-1 bytes, expected 14888
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_danish.txt
is -1 bytes, expected 14888
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_dutch.txt is
-1 bytes, expected 14848
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_english.txt
is -1 bytes, expected 6984
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_finnish.txt
is -1 bytes, expected 14756
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_french.txt
is -1 bytes, expected 15502
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_german.txt
is -1 bytes, expected 15338
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_greek.txt is
-1 bytes, expected 15290
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_hungarian.txt is -1 bytes, expected 14608
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_italian.txt
is -1 bytes, expected 15172
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_japanese.txt
is -1 bytes, expected 13080
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_korean.txt
is -1 bytes, expected 12886
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_koreana.txt
is -1 bytes, expected 12886
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_norwegian.txt is -1 bytes, expected 14808
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_polish.txt
is -1 bytes, expected 14696
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_portuguese.txt is -1 bytes, expected 15038
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_romanian.txt
is -1 bytes, expected 14938
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_russian.txt
is -1 bytes, expected 14882
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_schinese.txt
is -1 bytes, expected 12204
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_spanish.txt
is -1 bytes, expected 15230
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_swedish.txt
is -1 bytes, expected 14590
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_tchinese.txt
is -1 bytes, expected 12284
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_thai.txt is
-1 bytes, expected 14420
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/platform_turkish.txt
is -1 bytes, expected 14642
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/platform_ukrainian.txt is -1 bytes, expected 14672
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/registrykeys.vdf is
-1 bytes, expected 4230
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/RemoteClientConnectionNotification.res is -1 bytes, expected 2141
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/screenshots_none_selected.tga is -1 bytes, expected 61185
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/SharedLibraryNotification.res is -1 bytes, expected 1294
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/SMPStatsDialog.res is
-1 bytes, expected 3829
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/sourceinit.dat is -1
bytes, expected 155232
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/sourceinit_macos.dat
is -1 bytes, expected 78381
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/steamscheme.res is -1
bytes, expected 14528
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/steam_logo.tga is -1
bytes, expected 6700
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/steam_logo_big.tga is
-1 bytes, expected 164364
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/steam_splash_fallback.tga is -1 bytes, expected 258764
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory resource/styles/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/styles/gameoverlay.styles is -1 bytes, expected 529
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/styles/steam.styles
is -1 bytes, expected 76063
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/valve_logo.tga is -1
bytes, expected 10284
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/valve_logo_welcome.tga is -1 bytes, expected 11804
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_brazilian.txt is
-1 bytes, expected 40346
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_bulgarian.txt is
-1 bytes, expected 40236
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_czech.txt is -1
bytes, expected 40010
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_danish.txt is -1
bytes, expected 39678
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_dutch.txt is -1
bytes, expected 40112
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_english.txt is
-1 bytes, expected 18548
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_finnish.txt is
-1 bytes, expected 40156
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_french.txt is -1
bytes, expected 40872
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_german.txt is -1
bytes, expected 40684
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_greek.txt is -1
bytes, expected 40638
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_hungarian.txt is
-1 bytes, expected 39742
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_italian.txt is
-1 bytes, expected 40314
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_japanese.txt is
-1 bytes, expected 36660
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_korean.txt is -1
bytes, expected 36470
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_koreana.txt is
-1 bytes, expected 36470
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_norwegian.txt is
-1 bytes, expected 39766
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_polish.txt is -1
bytes, expected 40008
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_portuguese.txt
is -1 bytes, expected 40318
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_romanian.txt is
-1 bytes, expected 39900
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_russian.txt is
-1 bytes, expected 40156
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_schinese.txt is
-1 bytes, expected 35946
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_spanish.txt is
-1 bytes, expected 40592
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_swedish.txt is
-1 bytes, expected 39616
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_tchinese.txt is
-1 bytes, expected 36042
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_thai.txt is -1
bytes, expected 39922
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_turkish.txt is
-1 bytes, expected 39380
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vgui_ukrainian.txt is
-1 bytes, expected 40074
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/voice_busy.wav is -1
bytes, expected 59948
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/voice_dialing.wav is
-1 bytes, expected 366380
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/voice_ringing.wav is
-1 bytes, expected 366380
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/vprofpanel.res is -1
bytes, expected 3158
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/warning.wav is -1
bytes, expected 137730
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/webkit.css is -1
bytes, expected 2705
[2015-07-07 20:21:12] BVerifyInstalledFiles: resource/workshop_banner.png
is -1 bytes, expected 22396
[2015-07-07 20:21:12] BVerifyInstalledFiles:
resource/workshop_minibanner.png is -1 bytes, expected 12280
[2015-07-07 20:21:12] BVerifyInstalledFiles: serverbrowser.dylib is -1
bytes, expected 4411020
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory servers/
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/AddServerGamesPage.res
is -1 bytes, expected 6564
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/DialogAddServer.res is
-1 bytes, expected 3713
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/DialogGameInfo.res is
-1 bytes, expected 8688
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/DialogGameInfo_AutoRetry.res is -1 bytes, expected 8761
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/DialogGameInfo_NonSteam.res is -1 bytes, expected 8802
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/DialogGameInfo_SinglePlayer.res is -1 bytes, expected 8833
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/DialogServerBrowser.res is -1 bytes, expected 961
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/DialogServerPassword.res is -1 bytes, expected 2712
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/game_ready.wav is -1
bytes, expected 8378
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/icon_bots.tga is -1
bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/icon_bots_column.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/icon_password.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/icon_password_column.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/icon_robotron.tga is
-1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/icon_robotron_column.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/icon_secure_deny.tga
is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/InternetGamesPage.res
is -1 bytes, expected 6094
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/InternetGamesPage_Filters.res is -1 bytes, expected 7526
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_brazilian.txt is -1 bytes, expected 42720
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_bulgarian.txt is -1 bytes, expected 42236
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_czech.txt is -1 bytes, expected 42582
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_danish.txt is -1 bytes, expected 42484
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_dutch.txt is -1 bytes, expected 42540
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_english.txt is -1 bytes, expected 20306
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_finnish.txt is -1 bytes, expected 42558
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_french.txt is -1 bytes, expected 43060
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_german.txt is -1 bytes, expected 43290
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_greek.txt is -1 bytes, expected 43934
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_hungarian.txt is -1 bytes, expected 42078
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_italian.txt is -1 bytes, expected 43338
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_japanese.txt is -1 bytes, expected 37982
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_korean.txt is -1 bytes, expected 38030
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_koreana.txt is -1 bytes, expected 38030
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_norwegian.txt is -1 bytes, expected 41992
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_polish.txt is -1 bytes, expected 42056
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_portuguese.txt is -1 bytes, expected 42856
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_romanian.txt is -1 bytes, expected 42502
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_russian.txt is -1 bytes, expected 41754
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_schinese.txt is -1 bytes, expected 36714
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_spanish.txt is -1 bytes, expected 43940
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_swedish.txt is -1 bytes, expected 42468
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_tchinese.txt is -1 bytes, expected 36696
[2015-07-07 20:21:12] BVerifyInstalledFiles: servers/serverbrowser_thai.txt
is -1 bytes, expected 42188
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_turkish.txt is -1 bytes, expected 41550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/serverbrowser_ukrainian.txt is -1 bytes, expected 42270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
servers/VACBannedConnRefusedDialog.res is -1 bytes, expected 1987
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory skins/
[2015-07-07 20:21:12] BVerifyInstalledFiles: skins/skins_readme.txt is -1
bytes, expected 15066
[2015-07-07 20:21:12] BVerifyInstalledFiles: Steam.icns is 263086 bytes,
expected 93350
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam.sh is 23085 bytes,
expected 407
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory steam/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory steam/cached/
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/aboutdialog.res
is -1 bytes, expected 2900
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/accepted_cards.tga is -1 bytes, expected 57296
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/AccountPage.res
is -1 bytes, expected 10215
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/AddShortcutDialog.res is -1 bytes, expected 2131
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/appdownloadpanel_completed.res is -1 bytes, expected 3246
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/asyncnotificationsrequesteddialog.res is -1 bytes, expected
2029
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/BackupCompletionPage.res is -1 bytes, expected 1184
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/BackupCopyFilesPage.res is -1 bytes, expected 2433
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/backuprestoregamespage.res is -1 bytes, expected 2618
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/BackupSelectDirectoryPage.res is -1 bytes, expected 3384
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/BackupSelectGamesPage.res is -1 bytes, expected 1772
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/BackupSelectOptionsPage.res is -1 bytes, expected 3740
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/backupstartpage.res is -1 bytes, expected 1626
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/CDIcon.tga is -1
bytes, expected 4844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/CDKeyLaunchDialog.res is -1 bytes, expected 2489
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/CDKeyReceipt.html
is -1 bytes, expected 1761
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/cdkeyreceipthtml.res is -1 bytes, expected 698
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/CellMap.vdf is -1
bytes, expected 52523
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/charityquestiondialog.layout is -1 bytes, expected 3340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/chatroom_locked.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/chatroom_speaking.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/chatroom_speakingdata.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/chatroom_unlocked.tga is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ChooseBetaDialog.res is -1 bytes, expected 2650
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/ClickAndBuy.tga
is -1 bytes, expected 7688
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/cloudsyncwarningdialog.res is -1 bytes, expected 2439
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ConfirmPasswordDialog.res is -1 bytes, expected 1808
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/ConsolePage.res
is -1 bytes, expected 1381
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/contentmanagmentdialog.res is -1 bytes, expected 2374
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/convertcontentdialog.res is -1 bytes, expected 2177
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/CountryList.vdf
is -1 bytes, expected 10264
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/CreditCardPreorderReceipt.html is -1 bytes, expected 2069
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/CreditCardReceipt.html is -1 bytes, expected 1870
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/DefragAppDialog.res is -1 bytes, expected 2533
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/DeleteCache.res
is -1 bytes, expected 1518
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/details_titlebg.tga is -1 bytes, expected 20204
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/DialogCheckForUpdates.res is -1 bytes, expected 2028
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/DialogCheckForUpdates_Expanded.res is -1 bytes, expected 2762
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/DialogCheckVideoDriver.res is -1 bytes, expected 1168
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/driverunknownpagedialog.res is -1 bytes, expected 5677
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/driverunsupportedpagedialog.res is -1 bytes, expected 5689
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/driverupdatepagedialog.res is -1 bytes, expected 5679
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/DuplicateCC.res
is -1 bytes, expected 1528
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/emailsubpanel.res
is -1 bytes, expected 2035
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/fav_addTo.tga is
-1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/fav_addTo_ovr.tga
is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/fav_remove.tga is
-1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/fav_remove_ovr.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/FragmentationBadWarningDialog.res is -1 bytes, expected 1536
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_betas.res is -1 bytes, expected 2687
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_dlc.res is -1 bytes, expected 1377
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_general.res is -1 bytes, expected 5478
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_language.res is -1 bytes, expected 1125
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_localfiles.res is -1 bytes, expected 2792
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gameproperties_shortcuts.res is -1 bytes, expected 3741
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/game_details_header_blue.tga is -1 bytes, expected 2252844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/game_details_header_green.tga is -1 bytes, expected 2252844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/game_details_header_mask.tga is -1 bytes, expected 2252844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/game_details_header_red.tga is -1 bytes, expected 2252844
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/GiftRevoked.res
is -1 bytes, expected 1576
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/giving_header.tga
is -1 bytes, expected 136244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_dropshadow.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/gridview_mask.tga
is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_placeholder_0.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_placeholder_1.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_placeholder_2.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_placeholder_3.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/gridview_shadow.tga is -1 bytes, expected 395644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/GuestPassAcceptError.res is -1 bytes, expected 1822
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/GuestPassAcceptOK.res is -1 bytes, expected 1909
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/GuestPassesDialog.res is -1 bytes, expected 2288
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/GuestPassRedeemed.res is -1 bytes, expected 1829
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_back_disabled_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_back_down_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_back_over_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_back_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_forward_disabled_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_forward_down_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_forward_over_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_button_forward_sm.tga is -1 bytes, expected 1340
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_conflict.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_disabled.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_dunno.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_enabled.tga is -1 bytes, expected 1540
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_enabled_dark_bg.tga is -1 bytes, expected 3485
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_outofsync.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_synced.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_cloud_syncing.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_controller.tga is -1 bytes, expected 1200
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_game_frame.tga is -1 bytes, expected 4668
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/icon_tab_placement_arrow.tga is -1 bytes, expected 440
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallDirextXDialog.res is -1 bytes, expected 1608
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallExplanationDialog.res is -1 bytes, expected 1418
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubChooseApps.res is -1 bytes, expected 3166
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubChooseApps_SingleApp.res is -1 bytes, expected 3929
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubComplete.res is -1 bytes, expected 2034
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubComplete_RetailInstall.res is -1 bytes, expected 1996
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubConvertApps.res is -1 bytes, expected 2520
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubEULA.res is -1 bytes, expected 929
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/InstallSubOptions.res is -1 bytes, expected 1566
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/LaunchEULADialog.res is -1 bytes, expected 2137
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/LaunchOptionsDialog.res is -1 bytes, expected 2255
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/LaunchParametersDialog.res is -1 bytes, expected 2223
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_icon_mask.tga is -1 bytes, expected 4140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_logo_mask.tga is -1 bytes, expected 21644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_placeholder0.tga is -1 bytes, expected 21644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_placeholder1.tga is -1 bytes, expected 21644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_placeholder2.tga is -1 bytes, expected 21644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/listview_placeholder3.tga is -1 bytes, expected 21644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/LocalizedAudioChoiceDialog.res is -1 bytes, expected 2364
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/loggedinelsewherenotification.res is -1 bytes, expected 1749
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/logo.tga is -1
bytes, expected 19084
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/managedeviceauthdialog.res is -1 bytes, expected 2685
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/MediaConfirmationDialog.res is -1 bytes, expected 1533
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/needworkshoplegalagreementacceptance.res is -1 bytes, expected
1321
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/nobigpicture.res
is -1 bytes, expected 1588
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/nobigpicturevista.res is -1 bytes, expected 1613
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/nobigpicturewin8amd.res is -1 bytes, expected 1621
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/NotifyTrayHintDialog.res is -1 bytes, expected 2241
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_english.html is -1 bytes, expected 1023
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_french.html is -1 bytes, expected 1075
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_german.html is -1 bytes, expected 1012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_italian.html is -1 bytes, expected 1009
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_korean.html is -1 bytes, expected 2124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_schinese.html is -1 bytes, expected 2090
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_spanish.html is -1 bytes, expected 1075
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/offline_tchinese.html is -1 bytes, expected 2090
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/OverlayBatteryNotification.res is -1 bytes, expected 1119
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/OverlayCDKeyDialog.res is -1 bytes, expected 1839
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/OverlayCDKeyNotification.res is -1 bytes, expected 1877
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/OverlayDashboard.res is -1 bytes, expected 1529
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/OverlaySplash.res
is -1 bytes, expected 1688
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/OverlayTaskbar.res is -1 bytes, expected 2056
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/PayPalReceipt.html is -1 bytes, expected 1877
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ProductMarketingDialog.res is -1 bytes, expected 956
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ProductMarketingDialog_Initial.res is -1 bytes, expected 1020
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ProductMarketingDialog_Preload.res is -1 bytes, expected 1020
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ProductMarketingDialog_Released.res is -1 bytes, expected 1020
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/publishcloudfilecompletionpage.res is -1 bytes, expected 1044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/publishcloudfilestartpage.res is -1 bytes, expected 1761
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/PurchaseSubExternalSignup.res is -1 bytes, expected 1138
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_AlreadyPurchased.res is -1 bytes, expected 830
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/Receipt_Blank.res
is -1 bytes, expected 43
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Alert.res is -1 bytes, expected 4910
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Declined.res is -1 bytes, expected 5149
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Declined_AVSFailure.res is -1 bytes, expected 5306
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Declined_InsufficientFunds.res is -1 bytes,
expected 5233
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Denied_FromPreorder.res is -1 bytes, expected 4493
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Preorder.res is -1 bytes, expected 5889
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Success.res is -1 bytes, expected 5492
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Success_FromPreorder.res is -1 bytes, expected 5535
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_Success_WithShipping.res is -1 bytes, expected 5534
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CC_UseLimit.res is -1 bytes, expected 5237
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_Cancelled.res is -1 bytes, expected 801
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_InvalidKey.res is -1 bytes, expected 1285
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/receipt_cdkey_mustloginps3.res is -1 bytes, expected 865
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_MustOwnOtherApp.res is -1 bytes, expected 1308
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_RateLimited.res is -1 bytes, expected 1275
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_Rejected.res is -1 bytes, expected 2124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_CDKey_Success.res is -1 bytes, expected 1861
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Contact_Support.res is -1 bytes, expected 1601
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_HardwarePromo_AlreadyPurchased.res is -1 bytes,
expected 1318
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_HardwarePromo_Success.res is -1 bytes, expected 1903
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_HardwarePromo_Used.res is -1 bytes, expected 1282
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_Declined.res is -1 bytes, expected 1887
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_InvalidShippingAddress.res is -1 bytes,
expected 1928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_Preorder.res is -1 bytes, expected 2663
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_Success.res is -1 bytes, expected 3274
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_Success_WithShipping.res is -1 bytes, expected
3267
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_UseOtherFundingSource.res is -1 bytes, expected
1926
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PayPal_UseOtherPaymentMethod.res is -1 bytes, expected
1926
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_PreorderCancelled.res is -1 bytes, expected 1550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Purchase_AccountNotVerified.res is -1 bytes, expected
1846
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Purchase_ContactProviderSupport.res is -1 bytes,
expected 1451
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Purchase_Refunded.res is -1 bytes, expected 1318
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Restricted_Country.res is -1 bytes, expected 1783
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Server_Failure.res is -1 bytes, expected 1504
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Server_RegionNotSupported.res is -1 bytes, expected
1539
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Server_Timeout.res is -1 bytes, expected 1201
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Server_Timeout_BFS.res is -1 bytes, expected 1187
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/Receipt_Server_Timeout_Steam3.res is -1 bytes, expected 1273
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/regionrestrictiondialog.res is -1 bytes, expected 1581
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/regionrestrictiondialog_activation.res is -1 bytes, expected
1596
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/regionrestrictiondialog_purchase.res is -1 bytes, expected 1581
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/RegisterHardwarePromo.res is -1 bytes, expected 1072
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/RegisterSubEnterCDKey.res is -1 bytes, expected 4700
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/RegisterSubEnterCDKey_RetailInstall.res is -1 bytes, expected
4770
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/RegisterSubEnterCDKey_RetailInstall_3x5.res is -1 bytes,
expected 3323
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/registersubintro.res is -1 bytes, expected 734
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/RetailInstallLockedDialog.res is -1 bytes, expected 1605
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SendGuestPassEnterDetailsSubPanel.res is -1 bytes, expected
3110
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SendGuestPassResultSubPanel.res is -1 bytes, expected 1196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SendGuestPassResultSubPanel_failure.res is -1 bytes, expected
1169
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SendGuestPassResultSubPanel_success.res is -1 bytes, expected
1225
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/setjumplistoptions.res is -1 bytes, expected 8470
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SettingsSubFriends.res is -1 bytes, expected 9834
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SettingsSubInterface.res is -1 bytes, expected 7095
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SettingsSubOverlay.res is -1 bytes, expected 4740
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SettingsSubVoice.res is -1 bytes, expected 7221
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/soundsystemselect.res is -1 bytes, expected 1773
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SpecialOffersDialog.res is -1 bytes, expected 1882
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SteamGuardNotifyNewMachinesCompromised.layout is -1 bytes,
expected 1274
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SteamGuardNotifyNewMachinesDialog.layout is -1 bytes, expected
1704
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SteamIDProfilePage.res is -1 bytes, expected 4967
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamrootdialog_small.res is -1 bytes, expected 2120
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamshutdowndialog.res is -1 bytes, expected 1805
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_brazilian.txt is -1 bytes, expected 16958
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_bulgarian.txt is -1 bytes, expected 16862
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_czech.txt is -1 bytes, expected 16360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_danish.txt is -1 bytes, expected 16486
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_dutch.txt is -1 bytes, expected 17202
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_english.txt is -1 bytes, expected 8128
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_finnish.txt is -1 bytes, expected 16712
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_french.txt is -1 bytes, expected 17780
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_german.txt is -1 bytes, expected 17462
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_greek.txt is -1 bytes, expected 17874
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_hungarian.txt is -1 bytes, expected 17202
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_italian.txt is -1 bytes, expected 17576
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_japanese.txt is -1 bytes, expected 13144
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_korean.txt is -1 bytes, expected 13526
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_koreana.txt is -1 bytes, expected 13526
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_norwegian.txt is -1 bytes, expected 16316
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_polish.txt is -1 bytes, expected 16800
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_portuguese.txt is -1 bytes, expected 17566
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_romanian.txt is -1 bytes, expected 16924
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_russian.txt is -1 bytes, expected 16510
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_schinese.txt is -1 bytes, expected 12632
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_spanish.txt is -1 bytes, expected 17116
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_swedish.txt is -1 bytes, expected 16410
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_tchinese.txt is -1 bytes, expected 12594
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_thai.txt is -1 bytes, expected 16074
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_turkish.txt is -1 bytes, expected 16624
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steamui_postlogon_ukrainian.txt is -1 bytes, expected 16354
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/steam_logo_onwhite.gif is -1 bytes, expected 1558
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/StorefrontDialog.res is -1 bytes, expected 1691
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/storepage.res is
-1 bytes, expected 3707
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangeContactEmailComplete.res is -1 bytes, expected 817
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangeContactEmailIntro.res is -1 bytes, expected 3207
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangeContactEmailValidated.res is -1 bytes, expected 1590
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangePasswordChangePassword.res is -1 bytes, expected 3406
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangePasswordChangeSecretQuestion.res is -1 bytes,
expected 2807
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangePasswordComplete.res is -1 bytes, expected 427
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/subchangepasswordenterpassword.res is -1 bytes, expected 1600
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/subchangepasswordintro.res is -1 bytes, expected 420
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubChangePasswordOptions.res is -1 bytes, expected 1650
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/sublockaccountdone.res is -1 bytes, expected 1573
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/sublockaccountintro.res is -1 bytes, expected 1206
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/submanagesecuritychoosename.res is -1 bytes, expected 1659
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/submanagesecuritydone.res is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/submanagesecurityintro.res is -1 bytes, expected 3775
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/submanagesecuritylock.res is -1 bytes, expected 1634
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/submanagesecurityunlock.res is -1 bytes, expected 1234
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubPanelConvertCDKeyFinished.res is -1 bytes, expected 417
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SubPanelConvertCDKeyIntro.res is -1 bytes, expected 482
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/subvalidatecontactemaildone.res is -1 bytes, expected 1615
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/subvalidatecontactemailintro.res is -1 bytes, expected 1243
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SystemInfoPage.res is -1 bytes, expected 2189
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/SystemRequirementsDialog.res is -1 bytes, expected 8805
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/tradedialog.layout is -1 bytes, expected 255
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/turn_icon_large.tga is -1 bytes, expected 3727
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/uninstallgamesdialog.res is -1 bytes, expected 1030
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/UpdateNewsDialog.res is -1 bytes, expected 2211
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ValveSurveyInternetConnection.res is -1 bytes, expected 4892
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ValveSurveyMicrophone.res is -1 bytes, expected 2118
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ValveSurveyOverview.res is -1 bytes, expected 1738
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ValveSurveyResults.res is -1 bytes, expected 823
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/cached/ValveSurveySummarizeData.res is -1 bytes, expected 1160
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/cached/windowscompat.res
is -1 bytes, expected 1446
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/220/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/220/dxsupport.cfg is -1 bytes, expected 292898
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/220/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/240/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/240/dxsupport.cfg is -1 bytes, expected 242928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/240/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/2400/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2400/dxsupport.cfg is -1 bytes, expected 129651
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2400/dxsupport_reqs.cfg is -1 bytes, expected 208
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/2410/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2410/dxsupport_reqs.cfg is -1 bytes, expected 208
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/2420/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2420/dxsupport.cfg is -1 bytes, expected 129512
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2420/dxsupport_reqs.cfg is -1 bytes, expected 208
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/2430/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2430/dxsupport.cfg is -1 bytes, expected 129512
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/2430/dxsupport_reqs.cfg is -1 bytes, expected 208
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/260/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/260/dxsupport.cfg is -1 bytes, expected 126415
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/260/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/280/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/280/dxsupport.cfg is -1 bytes, expected 292900
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/280/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/300/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/300/dxsupport.cfg is -1 bytes, expected 242928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/300/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/340/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/340/dxsupport.cfg is -1 bytes, expected 126554
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/340/dxsupport_reqs.cfg is -1 bytes, expected 209
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/380/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/380/dxsupport.cfg is -1 bytes, expected 242928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/380/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/400/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/400/dxsupport.cfg is -1 bytes, expected 293158
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/400/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/420/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/420/dxsupport.cfg is -1 bytes, expected 293158
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/420/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/440/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/440/dxsupport.cfg is -1 bytes, expected 316274
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/440/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/500/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/500/dxsupport.cfg is -1 bytes, expected 130706
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/530/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/530/dxsupport.cfg is -1 bytes, expected 130706
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/550/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/550/dxsupport.cfg is -1 bytes, expected 253499
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/590/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/590/dxsupport.cfg is -1 bytes, expected 127185
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/620/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/620/dxsupport.cfg is -1 bytes, expected 207157
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/620/dxsupport_reqs.cfg is -1 bytes, expected 129
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/8870/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/8870/dxsupport.cfg is -1 bytes, expected 336
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/9200/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/9200/dxsupport.cfg is -1 bytes, expected 204730
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
steam/drivercheck/html/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/html/DrvrUpdate_ATI1.html is -1 bytes, expected 3382
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/html/DrvrUpdate_INTEL1.html is -1 bytes, expected 3370
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/html/DrvrUpdate_NV1.html is -1 bytes, expected 3376
[2015-07-07 20:21:12] BVerifyInstalledFiles:
steam/drivercheck/html/HardwareRequirements.html is -1 bytes, expected 1864
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory steam/games/
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/Dedicated Server
Install.html is -1 bytes, expected 1968
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/Left 4 Dead
Authoring Tools install.html is -1 bytes, expected 2076
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/PlatformMenu.vdf
is -1 bytes, expected 602
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/Source Dedicated
Server install.html is -1 bytes, expected 1846
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/Source SDK
install.html is -1 bytes, expected 1957
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/games/SteamMovie.ico is
-1 bytes, expected 10134
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam/legacydepotdata.vdf is
-1 bytes, expected 219330
[2015-07-07 20:21:12] BVerifyInstalledFiles: steamclean is -1 bytes,
expected 550732
[2015-07-07 20:21:12] BVerifyInstalledFiles: steamclient.dylib is -1 bytes,
expected 57084488
[2015-07-07 20:21:12] BVerifyInstalledFiles: steamloader.dylib is -1 bytes,
expected 29384
[2015-07-07 20:21:12] BVerifyInstalledFiles: steamservice.dylib is -1
bytes, expected 3727320
[2015-07-07 20:21:12] BVerifyInstalledFiles: steamui.dylib is -1 bytes,
expected 27090644
[2015-07-07 20:21:12] BVerifyInstalledFiles: steam_osx is -1 bytes,
expected 4260992
[2015-07-07 20:21:12] BVerifyInstalledFiles: streaming_client is -1 bytes,
expected 2287124
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory tenfoot/resource/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/browser/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/browser/webkit.css is -1 bytes, expected 28
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/default_keybinds.cfg is -1 bytes, expected 1916
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/fonts/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/fonts/LICENSE_CJK.txt is -1 bytes, expected 4393
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/fonts/NotoSansCJKjp-Regular.otf is -1 bytes, expected
16426032
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/fonts/tenfoot.uifont is -1 bytes, expected 1267938
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/abutton.tga is -1 bytes, expected 11218
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/async_game.png is -1 bytes, expected 2197
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/background_alpha_mask.png is -1 bytes, expected
117347
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/betabutton4.tga is -1 bytes, expected 44044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/bg_gradient_mask.tga is -1 bytes, expected 4844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/bootstrapper.jpg is -1 bytes, expected 515467
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/broadcast/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/broadcast/broadcast_live_red.png is -1 bytes,
expected 1657
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/broadcast/live_chat.png is -1 bytes, expected 1055
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/browser/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_back.png is -1 bytes, expected 3404
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_back_mouse.png is -1 bytes,
expected 3304
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_favorite.png is -1 bytes, expected
3434
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_favorite_mouse.png is -1 bytes,
expected 3351
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_forward.png is -1 bytes, expected
3549
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_forward_mouse.png is -1 bytes,
expected 3276
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_home.png is -1 bytes, expected 3371
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_home_mouse.png is -1 bytes,
expected 3182
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_insecure.png is -1 bytes, expected
3393
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_ltab.png is -1 bytes, expected 3009
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_mask.png is -1 bytes, expected
336298
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_mousepan.png is -1 bytes, expected
8676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_reload.png is -1 bytes, expected
3553
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_reticule_middle.png is -1 bytes,
expected 7771
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_reticule_outer.png is -1 bytes,
expected 32135
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_rtab.png is -1 bytes, expected 3024
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/browser_secure.png is -1 bytes, expected
3344
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/defaultfav.png is -1 bytes, expected 116993
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/favorites_addtab.png is -1 bytes, expected
16049
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/favorites_closetab.tga is -1 bytes,
expected 57644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/favorite_added.png is -1 bytes, expected
111342
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/reticle.webm is -1 bytes, expected 28247
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/reticle_80_80.webm is -1 bytes, expected
16234
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/reticle_mask.png is -1 bytes, expected 72620
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/reticle_mask_80_80.png is -1 bytes,
expected 25818
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/browser/ReticuleLoading_00039.png is -1 bytes,
expected 3347
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/carousel_bg.png is -1 bytes, expected 1320520
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/clockface.png is -1 bytes, expected 15705
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/cog_transparent.jpg is -1 bytes, expected 86129
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/collapse.tga is -1 bytes, expected 287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/comments.png is -1 bytes, expected 3064
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/community/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/community/bg_commodity_mask.tga is -1 bytes,
expected 8294444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/community/home_map.png is -1 bytes, expected 188711
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/community/item_glow.png is -1 bytes, expected 7828
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_battery_1.png is -1 bytes, expected 3666
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_battery_2.png is -1 bytes, expected 3697
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_battery_3.png is -1 bytes, expected 3734
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_battery_4.png is -1 bytes, expected 3753
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_full.png is -1 bytes, expected
3765
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_full_storemain.png is -1 bytes,
expected 7108
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_legacy.png is -1 bytes, expected
3970
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_native.png is -1 bytes, expected
3693
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_partial.png is -1 bytes,
expected 2181
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/controller_support_partial_storemain.png is -1
bytes, expected 7521
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/critical.png is -1 bytes, expected 3532
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/cursors/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/cursors/arrow.png is -1 bytes, expected 5292
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/cursors/ibeam.png is -1 bytes, expected 832
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/downloads.png is -1 bytes, expected 3721
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/exit.png is -1 bytes, expected 3376
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/expand.tga is -1 bytes, expected 287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_bottom.png is -1 bytes, expected 2844
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_left.png is -1 bytes, expected 2842
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_left2.png is -1 bytes, expected 2856
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_right.png is -1 bytes, expected 2842
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_right2.png is -1 bytes, expected 2855
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/focus_shadow_top.png is -1 bytes, expected 2834
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/footer/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/a_button.png is -1 bytes, expected 3710
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/back_d0g.png is -1 bytes, expected 2829
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/back_xinput.png is -1 bytes, expected 3044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/b_button.png is -1 bytes, expected 3612
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/grid.png is -1 bytes, expected 15957
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/start.png is -1 bytes, expected 1126
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/x_button.png is -1 bytes, expected 3607
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/footer/y_button.png is -1 bytes, expected 3684
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/friends/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_chatactivity.tga is -1 bytes,
expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_indicator_chat.png is -1 bytes,
expected 3355
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_indicator_friendrequest.png is -1
bytes, expected 3620
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_indicator_gameinvite.png is -1
bytes, expected 4278
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_indicator_voicechat.png is -1
bytes, expected 3433
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_indicator_voicehold.tga is -1
bytes, expected 11708
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_list_item_panel_labels_mask.tga is
-1 bytes, expected 228044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_list_mask_fade_both.png is -1
bytes, expected 2823
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_list_mask_fade_bottom.png is -1
bytes, expected 2808
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_list_mask_fade_top.png is -1 bytes,
expected 2816
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_search.png is -1 bytes, expected
3635
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_start_voice_chat_start.png is -1
bytes, expected 1738
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_voicechatactivity.tga is -1 bytes,
expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_voicechat_audiolevels.tga is -1
bytes, expected 12144
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_voicechat_voicelevels.tga is -1
bytes, expected 12144
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/friends/friends_voiceholdactivity.tga is -1 bytes,
expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gamepad_digital_blank.png is -1 bytes, expected 3042
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gamepad_digital_down.png is -1 bytes, expected 1300
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gamepad_digital_left.png is -1 bytes, expected 3145
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gamepad_digital_right.png is -1 bytes, expected 3092
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gamepad_digital_up.png is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/generic.jpg is -1 bytes, expected 5610
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/generic_200.png is -1 bytes, expected 8235
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/generic_800.png is -1 bytes, expected 27338
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/gifts.png is -1 bytes, expected 3269
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/grid/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/grid/grid_0.png is -1 bytes, expected 3000
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/grid/grid_1.png is -1 bytes, expected 3001
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/grid/grid_2.png is -1 bytes, expected 2996
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/grid/grid_3.png is -1 bytes, expected 3003
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/homeglow.png is -1 bytes, expected 1444865
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/icon_folder.png is -1 bytes, expected 3287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/icon_folder_add.png is -1 bytes, expected 3315
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/icon_folder_up.png is -1 bytes, expected 3488
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/icon_picture.png is -1 bytes, expected 3444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/icon_steam_update.png is -1 bytes, expected 3880
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/inbox.png is -1 bytes, expected 1407
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/intro_movie.webm is -1 bytes, expected 4899405
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/invites.png is -1 bytes, expected 3665
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/items.png is -1 bytes, expected 3160
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/keyboard/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/keyboard/a.png is -1 bytes, expected 648
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/keyboard/b.png is -1 bytes, expected 586
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/keyboard/c.png is -1 bytes, expected 660
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/keyboard/d.png is -1 bytes, expected 564
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/library/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/add_controller_icon.png is -1 bytes,
expected 3708
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller.png is -1 bytes, expected
419841
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_backside_left.png
is -1 bytes, expected 401854
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_backside_left_d0g.png
is -1 bytes, expected 218293
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_backside_right.png
is -1 bytes, expected 401164
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_backside_right_d0g.png
is -1 bytes, expected 218696
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_0.png is -1
bytes, expected 170246
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_0_d0g.png
is -1 bytes, expected 11611
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_1.png is -1
bytes, expected 170199
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_1_d0g.png
is -1 bytes, expected 11692
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_2.png is -1
bytes, expected 169910
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_2_d0g.png
is -1 bytes, expected 11755
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_3.png is -1
bytes, expected 170379
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_button_3_d0g.png
is -1 bytes, expected 11677
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_left_bumper.png is
-1 bytes, expected 170908
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_left_bumper_d0g.png
is -1 bytes, expected 231010
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_left_trigger.png
is -1 bytes, expected 168529
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_left_trigger_d0g.png
is -1 bytes, expected 12349
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_p1.png is -1
bytes, expected 190876
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_p1_d0g.png is -1
bytes, expected 33668
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_p2.png is -1
bytes, expected 190760
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_p2_d0g.png is -1
bytes, expected 35448
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_right_bumper.png
is -1 bytes, expected 170651
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_right_bumper_d0g.png
is -1 bytes, expected 18846
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_right_trigger.png
is -1 bytes, expected 168285
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_callout_right_trigger_d0g.png
is -1 bytes, expected 13013
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_d0g.png is -1 bytes,
expected 235059
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_lines.png is -1 bytes,
expected 287165
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/alpha_controller_lines_d0g.png is -1 bytes,
expected 190970
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/click.png is -1 bytes, expected 552
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/library/controller/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/binding_list_icon.png is -1
bytes, expected 37177
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/binding_virtual_gamepad_bg.png
is -1 bytes, expected 63648
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_bg.png is -1
bytes, expected 49996
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_controller_i_a.png
is -1 bytes, expected 68507
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_controller_i_b.png
is -1 bytes, expected 68908
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_controller_i_steam.png
is -1 bytes, expected 68994
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_controller_i_x.png
is -1 bytes, expected 68932
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_controller_i_y.png
is -1 bytes, expected 68861
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_bpad_bg.png
is -1 bytes, expected 25403
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_dpad_bg.png
is -1 bytes, expected 18938
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_stick_bg.png
is -1 bytes, expected 21567
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_trackpad_rotation.png
is -1 bytes, expected 3216
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_trackpad_zone_dead.png
is -1 bytes, expected 9838
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_trackpad_zone_modifier.png
is -1 bytes, expected 21425
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_trackpad_zone_touch.png
is -1 bytes, expected 9856
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_inspector_trigger_layout.png
is -1 bytes, expected 9140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_bpad.png
is -1 bytes, expected 4079
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_bpad_focus.png
is -1 bytes, expected 4171
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_dpad.png
is -1 bytes, expected 4081
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_dpad_focused.png
is -1 bytes, expected 4174
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_pad_complex.png
is -1 bytes, expected 3972
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_pad_complex_focused.png
is -1 bytes, expected 3963
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_stick.png
is -1 bytes, expected 3808
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_config_mode_stick_focused.png
is -1 bytes, expected 3762
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/controller_small_config.png is
-1 bytes, expected 21393
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_a.png
is -1 bytes, expected 2475
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_b.png
is -1 bytes, expected 2135
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_back.png
is -1 bytes, expected 2266
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_dp.png
is -1 bytes, expected 384
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_dp_dn.png
is -1 bytes, expected 314
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_dp_lt.png
is -1 bytes, expected 314
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_dp_rt.png
is -1 bytes, expected 287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_dp_up.png
is -1 bytes, expected 319
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_lb.png
is -1 bytes, expected 2701
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_ls.png
is -1 bytes, expected 2623
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_lt.png
is -1 bytes, expected 2170
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_rb.png
is -1 bytes, expected 2735
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_rs.png
is -1 bytes, expected 2412
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_rt.png
is -1 bytes, expected 2284
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_start.png
is -1 bytes, expected 2261
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_system.png
is -1 bytes, expected 3132
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_x.png
is -1 bytes, expected 2364
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_active_y.png
is -1 bytes, expected 2382
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_a.png
is -1 bytes, expected 3493
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_b.png
is -1 bytes, expected 3273
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_back.png
is -1 bytes, expected 3173
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_dp.png
is -1 bytes, expected 1557
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_dp_dn.png
is -1 bytes, expected 446
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_dp_lt.png
is -1 bytes, expected 453
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_dp_rt.png
is -1 bytes, expected 447
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_dp_up.png
is -1 bytes, expected 495
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_lb.png
is -1 bytes, expected 3940
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_ls.png
is -1 bytes, expected 4107
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_lt.png
is -1 bytes, expected 3376
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_rb.png
is -1 bytes, expected 4707
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_rs.png
is -1 bytes, expected 4029
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_rt.png
is -1 bytes, expected 3662
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_start.png
is -1 bytes, expected 3212
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_system.png
is -1 bytes, expected 4550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_x.png
is -1 bytes, expected 3432
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_binding_gamepad_selection_y.png
is -1 bytes, expected 3349
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller.png
is -1 bytes, expected 52078
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_back.png
is -1 bytes, expected 42714
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_forward.png
is -1 bytes, expected 42718
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_lb.png
is -1 bytes, expected 42676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_lt.png
is -1 bytes, expected 42661
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_rb.png
is -1 bytes, expected 42857
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_i_rt.png
is -1 bytes, expected 42679
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_s1.png
is -1 bytes, expected 47672
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_s2.png
is -1 bytes, expected 44725
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_s3.png
is -1 bytes, expected 45145
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_controller_s4.png
is -1 bytes, expected 47537
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/cropped_controller_config_lines.png
is -1 bytes, expected 26930
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_backspace.png is
-1 bytes, expected 3078
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_brk.png is -1
bytes, expected 3460
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_down.png is -1
bytes, expected 3160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_esc.png is -1
bytes, expected 3467
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_home.png is -1
bytes, expected 3138
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_ins.png is -1
bytes, expected 3412
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_left.png is -1
bytes, expected 3106
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_print.png is -1
bytes, expected 3185
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_return.png is -1
bytes, expected 3154
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_right.png is -1
bytes, expected 3107
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_scroll_lock.png
is -1 bytes, expected 3390
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_space.png is -1
bytes, expected 2982
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_tab.png is -1
bytes, expected 3136
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_kb_up.png is -1
bytes, expected 3149
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_wrapper_gamepad.png
is -1 bytes, expected 4584
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_wrapper_gamepad_offset.png
is -1 bytes, expected 3759
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_wrapper_keyboard.png
is -1 bytes, expected 3278
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/glyph_input_wrapper_keyboard_offset.png
is -1 bytes, expected 3112
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_left_back.png
is -1 bytes, expected 3910
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_left_bumper.png
is -1 bytes, expected 4869
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_left_grip.png
is -1 bytes, expected 5166
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_left_start.png
is -1 bytes, expected 3924
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_left_trigger.png
is -1 bytes, expected 4880
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_right_bumper.png
is -1 bytes, expected 5102
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_right_grip.png
is -1 bytes, expected 5465
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_glyph_right_trigger.png
is -1 bytes, expected 5139
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_mode_bpad.png
is -1 bytes, expected 9234
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_mode_dpad.png
is -1 bytes, expected 8229
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_mode_mouse_complex.png
is -1 bytes, expected 10409
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_mode_mouse_simple.png
is -1 bytes, expected 9069
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller/input_controller_mode_stick.png
is -1 bytes, expected 9658
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/controller_icon.png is -1 bytes, expected
3696
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/details_data_mask.tga is -1 bytes, expected
379644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/double.png is -1 bytes, expected 552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/empty_star.tga is -1 bytes, expected 5820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/full_star.tga is -1 bytes, expected 5820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/game_grid_shadow.png is -1 bytes, expected
32303
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/half_star.tga is -1 bytes, expected 5820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/horizontal_mask.tga is -1 bytes, expected
1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/keyboardfade.png is -1 bytes, expected 15539
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/lettershadow.png is -1 bytes, expected
159032
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_app_details_bg_mask.png is -1
bytes, expected 24686
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_app_details_bg_wash.png is -1
bytes, expected 552239
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_a_button.png is -1 bytes, expected
4794
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_a_button_inner_mask.tga is -1
bytes, expected 47564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_downloading_button.png is -1 bytes,
expected 6393
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_grid_bg_wash.png is -1 bytes,
expected 679436
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_install_button.png is -1 bytes,
expected 6461
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_play_button.png is -1 bytes,
expected 5615
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_purchase_button.png is -1 bytes,
expected 7503
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_stream_button.png is -1 bytes,
expected 7870
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_stream_button_edges.tga is -1
bytes, expected 150380
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/library_syncing_button.png is -1 bytes,
expected 7662
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/mouse.png is -1 bytes, expected 23498
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/outer.png is -1 bytes, expected 634
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/play_action_modal_mask.png is -1 bytes,
expected 120911
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/play_action_modal_mask_background.png is -1
bytes, expected 29185
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/screenshot_grid_shadow.png is -1 bytes,
expected 24271
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/scroll_data_mask_both.tga is -1 bytes,
expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/scroll_data_mask_down.tga is -1 bytes,
expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/scroll_data_mask_right.tga is -1 bytes,
expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/scroll_data_mask_up.tga is -1 bytes,
expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/stick.png is -1 bytes, expected 395
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/stream2.png is -1 bytes, expected 53777
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/stream2b.png is -1 bytes, expected 98669
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/title_grid_shadow.png is -1 bytes, expected
10600
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library/turnoff_controller_icon.png is -1 bytes,
expected 3690
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/library_default.tga is -1 bytes, expected 296744
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/list_mask_fade_both.png is -1 bytes, expected 2826
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/list_mask_fade_bottom.png is -1 bytes, expected 942
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/list_mask_fade_top.png is -1 bytes, expected 2816
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/locked_acct.png is -1 bytes, expected 4351
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/login/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/connect.png is -1 bytes, expected 43837
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/login_bg.tga is -1 bytes, expected 1660332
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/user_join.png is -1 bytes, expected 5392
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/user_join.tga is -1 bytes, expected 283068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/user_login.png is -1 bytes, expected 43676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/login/user_login.tga is -1 bytes, expected 283068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/lower_row_mask.tga is -1 bytes, expected 1244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/lower_row_sharp_mask.tga is -1 bytes, expected 1244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mainmenu_bg_2.png is -1 bytes, expected 283388
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/messages.png is -1 bytes, expected 3766
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/mouse/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/arrowL.tga is -1 bytes, expected 28944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/arrowLdefault.tga is -1 bytes, expected 28944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/arrowR.tga is -1 bytes, expected 28944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/arrowRdefault.tga is -1 bytes, expected 28944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/scrollingRegionL.png is -1 bytes, expected
41776
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/mouse/scrollingRegionR.png is -1 bytes, expected
41939
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music.png is -1 bytes, expected 3471
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/music/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/addlibrary.png is -1 bytes, expected 3567
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/add_filebrowser.png is -1 bytes, expected 2843
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/control_bg.png is -1 bytes, expected 4232
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/empty_player_bg.png is -1 bytes, expected 4677
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_album_placeholder.png is -1 bytes,
expected 4620
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_browse.png is -1 bytes, expected 2854
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_notification.png is -1 bytes, expected
11945
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_next.png is -1 bytes, expected 3218
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_pause.png is -1 bytes, expected
3797
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_play.png is -1 bytes, expected 5615
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_previous.png is -1 bytes, expected
3199
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_repeat.png is -1 bytes, expected
3307
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_queue_shuffle.png is -1 bytes, expected
3347
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_repeat.png is -1 bytes, expected 3273
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_repeat1.png is -1 bytes, expected 3345
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_shuffle.png is -1 bytes, expected 3420
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_first.png is -1 bytes, expected
3215
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_last.png is -1 bytes, expected 3196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_next.png is -1 bytes, expected 656
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_pause.png is -1 bytes, expected
3327
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_play.png is -1 bytes, expected 375
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_previous.png is -1 bytes, expected
595
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_stop.png is -1 bytes, expected 168
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_type_placeholder.png is -1 bytes,
expected 4620
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/icon_track_volumebars.png is -1 bytes,
expected 607
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/musicdefaultfav.png is -1 bytes, expected
1083544
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/musicguide_icon.png is -1 bytes, expected 3391
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/music_grid_bg_wash.png is -1 bytes, expected
681791
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album.png is -1 bytes, expected
469298
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album1.jpg is -1 bytes, expected
29480
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album2.jpg is -1 bytes, expected
25945
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album3.jpg is -1 bytes, expected
22573
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album4.jpg is -1 bytes, expected
29390
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album5.jpg is -1 bytes, expected
25269
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album6.jpg is -1 bytes, expected
23607
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album7.jpg is -1 bytes, expected
18777
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album8.jpg is -1 bytes, expected
26917
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/placeholder_album9.jpg is -1 bytes, expected
27020
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/remove_filebrowser.png is -1 bytes, expected
2832
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/music/shadow.png is -1 bytes, expected 279481
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/offline.png is -1 bytes, expected 4869
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/overlay/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/overlay/notification_middlebutton.png is -1 bytes,
expected 7077
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/overlay/notification_steamcog.png is -1 bytes,
expected 23800
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/overlay/notification_turn.png is -1 bytes, expected
2197
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/overlay/overlay_bg_wash.png is -1 bytes, expected
178445
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/pause.png is -1 bytes, expected 3372
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/play.png is -1 bytes, expected 5711
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/profile/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/profile/activity_bg_wash.png is -1 bytes, expected
346160
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/profile/profile_bg_wash.png is -1 bytes, expected
512548
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/profile/sharp_scroll_data_mask_both.tga is -1
bytes, expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/profile/sharp_scroll_data_mask_down.tga is -1
bytes, expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/profile/sharp_scroll_data_mask_up.tga is -1 bytes,
expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings.png is -1 bytes, expected 3789
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/settings/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/alienfx_alien.png is -1 bytes, expected
3010
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/alienfx_steam.png is -1 bytes, expected
4111
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/axis_highlight.png is -1 bytes, expected
2237
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/button_highlight.png is -1 bytes, expected
2593
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/controllermap.png is -1 bytes, expected
29105
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/controller_icon.png is -1 bytes, expected
4521
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_down.tga is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_left.tga is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_middle.tga is -1 bytes, expected 16052
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_right.tga is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_speaker.png is -1 bytes, expected 3553
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_up.tga is -1 bytes, expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wired_disabled.png is -1 bytes,
expected 3069
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wired_enabled.png is -1 bytes,
expected 3193
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wireless1.png is -1 bytes, expected
1609
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wireless2.png is -1 bytes, expected
1675
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wireless3.png is -1 bytes, expected
1689
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/icon_wireless_secure.png is -1 bytes,
expected 1612
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/keybg.png is -1 bytes, expected 9540
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/stream_connected.png is -1 bytes, expected
221721
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/stream_disconnected.png is -1 bytes,
expected 50971
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/underscan1.png is -1 bytes, expected 5463
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/underscan2.png is -1 bytes, expected 4954
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/underscan3.png is -1 bytes, expected 5318
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/settings/underscan4.png is -1 bytes, expected 5140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/sharingicon.png is -1 bytes, expected 9444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/small_steam.tga is -1 bytes, expected 9388
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam.tga is -1 bytes, expected 103244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steampad_navigationtip.png is -1 bytes, expected
71170
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam_exit.tga is -1 bytes, expected 18000
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam_home.png is -1 bytes, expected 7377
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam_home_os.png is -1 bytes, expected 6361
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam_logo.tga is -1 bytes, expected 102444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/steam_tray_48.tga is -1 bytes, expected 9260
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/store/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/alipay.png is -1 bytes, expected 29219
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/amex.png is -1 bytes, expected 31867
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_amex_brazil.png is -1 bytes, expected 32141
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_aura.png is -1 bytes, expected 26684
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_bancodobrasil.png is -1 bytes, expected
18429
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_boacompragold.png is -1 bytes, expected
17191
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_boleto.png is -1 bytes, expected 16151
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_bradesco.png is -1 bytes, expected 16195
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_dinersclub_brazil.png is -1 bytes,
expected 18764
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_hipercard.png is -1 bytes, expected 14762
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_itau.png is -1 bytes, expected 15413
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_mastercard_brazil.png is -1 bytes,
expected 29469
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_pagseguro.png is -1 bytes, expected 20861
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/bp_visa_brazil.png is -1 bytes, expected 21874
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/cartebleue.png is -1 bytes, expected 39092
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/CheckoutArrow.png is -1 bytes, expected 2881
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/clickandbuy.png is -1 bytes, expected 9046
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/dankort.png is -1 bytes, expected 7635
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/direct_ebanking.png is -1 bytes, expected
16093
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/discover.png is -1 bytes, expected 19366
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/filterbg.png is -1 bytes, expected 6529
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/genre_overview.png is -1 bytes, expected
191606
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/giropay.png is -1 bytes, expected 20283
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/holidaysalebg.jpg is -1 bytes, expected 304793
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_CheckDefault.png is -1 bytes, expected
1102
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_CheckFocus.png is -1 bytes, expected 1112
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_controller_enabled.png is -1 bytes,
expected 1438
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_DropDownArrowDefault.png is -1 bytes,
expected 2969
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_DropDownArrowFocus.png is -1 bytes,
expected 2971
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_early_access.png is -1 bytes, expected
3547
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_fullcontroller.png is -1 bytes, expected
3436
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_fullcontroller_storefront.png is -1
bytes, expected 3572
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_keyboard.png is -1 bytes, expected 3473
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_keyboard_60px.png is -1 bytes, expected
6311
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_keyboard_storefront.png is -1 bytes,
expected 3501
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_legacycontroller.png is -1 bytes,
expected 3525
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_legacycontroller_storefront.png is -1
bytes, expected 3726
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_mac_storefront.png is -1 bytes, expected
3360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_notice.png is -1 bytes, expected 3611
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_partialcontroller_storefront.png is -1
bytes, expected 3739
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_platform_linux.png is -1 bytes, expected
3542
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_platform_mac.png is -1 bytes, expected
1311
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_platform_win.png is -1 bytes, expected
3137
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_RadioDefault.png is -1 bytes, expected
2983
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/Icon_RadioSelected.png is -1 bytes, expected
2992
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_singleplayer.png is -1 bytes, expected
1230
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steamcontroller.png is -1 bytes,
expected 3357
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steamcontroller_storefront.png is -1
bytes, expected 3520
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steamos_storefront.png is -1 bytes,
expected 3724
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steamplay.png is -1 bytes, expected 3973
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steamplay_full.png is -1 bytes, expected
2584
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steam_achievements.png is -1 bytes,
expected 1354
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_steam_cloud.png is -1 bytes, expected
1185
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/icon_windows_storefront.png is -1 bytes,
expected 3159
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/ideal.png is -1 bytes, expected 13476
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/input_required.png is -1 bytes, expected 4603
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/jcb.png is -1 bytes, expected 15210
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/legend_stick_left.png is -1 bytes, expected
2423
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/legend_stick_right.png is -1 bytes, expected
2590
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/mastercard.png is -1 bytes, expected 27897
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/metacritic.png is -1 bytes, expected 4637
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/moneybookers.png is -1 bytes, expected 17915
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/paypal.png is -1 bytes, expected 15356
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/paysafe.png is -1 bytes, expected 10892
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/qiwi.png is -1 bytes, expected 20263
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/recommend_bubble.png is -1 bytes, expected
2939
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/shadow.png is -1 bytes, expected 8126
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/slideshow_glow.png is -1 bytes, expected 73898
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/sofort.png is -1 bytes, expected 15109
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/store_app_bg.png is -1 bytes, expected 1284295
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/store_app_bg_mask.png is -1 bytes, expected
1954488
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/store_browse_bg.png is -1 bytes, expected
654720
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/trailer_tv.png is -1 bytes, expected 143933
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/visa.png is -1 bytes, expected 19950
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/webmoney.png is -1 bytes, expected 11554
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/store/yandex.png is -1 bytes, expected 12035
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/streaming_intro.png is -1 bytes, expected 66384
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/textinput/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/alt.tga is -1 bytes, expected 4114
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/back.tga is -1 bytes, expected 5202
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/del.tga is -1 bytes, expected 9234
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop01.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop02.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop03.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop04.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop05.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop06.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop07.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/drop08.tga is -1 bytes, expected 250044
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/forward.tga is -1 bytes, expected 5202
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/gamepad_digital_blank.tga is -1 bytes,
expected 3180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/return.tga is -1 bytes, expected 6162
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/shift.tga is -1 bytes, expected 4114
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_footer_cancel.png is -1 bytes,
expected 847
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_footer_cancel.tga is -1 bytes,
expected 10364
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_footer_start.png is -1 bytes,
expected 839
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_footer_start.tga is -1 bytes,
expected 10364
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_ls.tga is -1 bytes, expected
83036
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_paddles.png is -1 bytes,
expected 6048
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/textinput/textinput_touchpointer.tga is -1 bytes,
expected 10422
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/trade_offer.png is -1 bytes, expected 1422
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/images/transport_controls/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/Icon_ffwd.png is -1 bytes,
expected 3206
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_fullscreen.png is -1 bytes,
expected 2934
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_jump_back.png is -1 bytes,
expected 3818
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_nexttrack.png is -1 bytes,
expected 3197
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_pause.png is -1 bytes,
expected 2905
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_play.png is -1 bytes,
expected 3175
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_previoustrack.png is -1
bytes, expected 3216
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_quality.png is -1 bytes,
expected 1653
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_rwd.png is -1 bytes,
expected 3218
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_speaker.png is -1 bytes,
expected 3671
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_stop.png is -1 bytes,
expected 2887
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/Icon_VolumeBars.tga is -1 bytes,
expected 27128
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_volume_00.png is -1 bytes,
expected 1169
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_volume_01.png is -1 bytes,
expected 1520
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_volume_02.png is -1 bytes,
expected 1275
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_volume_03.png is -1 bytes,
expected 1429
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/transport_controls/icon_volume_04.png is -1 bytes,
expected 1583
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/unlocked_acct.png is -1 bytes, expected 4339
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/unlocked_acct_lg.png is -1 bytes, expected 6208
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/unlocked_acct_sm.png is -1 bytes, expected 4816
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/upper_row_mask.tga is -1 bytes, expected 2444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/voice_headset.png is -1 bytes, expected 3469
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/images/voice_mic.png is -1 bytes, expected 3429
[2015-07-07 20:21:12] BVerifyInstalledFiles: tenfoot/resource/keybinds.cfg
is -1 bytes, expected 21
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/keyboards/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_brazilian_default.txt is -1 bytes,
expected 386
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_danish_default.txt is -1 bytes, expected
350
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_dutch_default.txt is -1 bytes, expected
338
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_english_default.txt is -1 bytes, expected
352
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_english_dualtouch.txt is -1 bytes,
expected 149
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_finnish_default.txt is -1 bytes, expected
350
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_french_default.txt is -1 bytes, expected
386
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_german_default.txt is -1 bytes, expected
352
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_italian_default.txt is -1 bytes, expected
362
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_norwegian_default.txt is -1 bytes,
expected 350
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_polish_default.txt is -1 bytes, expected
374
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_portuguese_default.txt is -1 bytes,
expected 386
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_russian_default.txt is -1 bytes, expected
417
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_spanish_default.txt is -1 bytes, expected
370
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/keyboards/layout_swedish_default.txt is -1 bytes, expected
350
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/account/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/account/confirmpassword.xml is -1 bytes, expected
1023
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/add_controller.xml is -1 bytes, expected 1171
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/backgroundvideopanel.xml is -1 bytes, expected 432
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/broadcast/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/broadcast_chat.xml is -1 bytes, expected
692
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/broadcast_overlay.xml is -1 bytes,
expected 706
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/broadcast_viewer.xml is -1 bytes,
expected 491
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/notification_availabletowatch.xml is -1
bytes, expected 517
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/notification_friendjoined.xml is -1
bytes, expected 559
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/notification_viewerjoined.xml is -1
bytes, expected 456
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/broadcast/notification_viewerrequest.xml is -1
bytes, expected 580
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/carousel.xml is -1 bytes, expected 634
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/community/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/community/community_loading.xml is -1 bytes,
expected 1071
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/community/community_wrapper.xml is -1 bytes,
expected 1582
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/consolepanel.xml is -1 bytes, expected 638
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/contextmenu.xml is -1 bytes, expected 496
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debugger.xml is -1 bytes, expected 1031
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debugindividualstyle.xml is -1 bytes, expected 263
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debuginheritedstylesheader.xml is -1 bytes,
expected 275
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debugpanel.xml is -1 bytes, expected 633
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debugstyleanimation.xml is -1 bytes, expected 561
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/debugstyleblock.xml is -1 bytes, expected 331
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/downloads/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/downloads/downloads.xml is -1 bytes, expected 793
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/downloads/downloads_griditem.xml is -1 bytes,
expected 1801
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/downloads/downloads_summaryitem.xml is -1 bytes,
expected 704
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/fileselector.xml is -1 bytes, expected 1738
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/friends/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/actions.xml is -1 bytes, expected 2506
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/addfriend.xml is -1 bytes, expected 1417
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/chaturls.xml is -1 bytes, expected 935
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/community_feed_strip.xml is -1 bytes,
expected 1095
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/community_friends_strip.xml is -1 bytes,
expected 1354
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/community_main.xml is -1 bytes, expected 506
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/feeditem_details_community.xml is -1 bytes,
expected 1172
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/feeditem_menu_details.xml is -1 bytes,
expected 557
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/feeditem_menu_details_action_button.xml is
-1 bytes, expected 427
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends.xml is -1 bytes, expected 2404
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_chat_dialog.xml is -1 bytes,
expected 2066
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_details_community.xml is -1 bytes,
expected 963
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_details_friendlistitem.xml is -1
bytes, expected 779
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_details_myheader.xml is -1 bytes,
expected 551
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_indicator_container.xml is -1
bytes, expected 2175
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_loading.xml is -1 bytes, expected
884
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_profile_details.xml is -1 bytes,
expected 738
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_profile_details_action_button.xml
is -1 bytes, expected 436
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/friends_profile_details_composite_header.xml
is -1 bytes, expected 750
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/group_details_mainlistitem.xml is -1 bytes,
expected 677
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/invitetolobby.xml is -1 bytes, expected 902
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_achievement.xml is -1 bytes,
expected 533
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_chatban.xml is -1 bytes,
expected 552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_chatinvite.xml is -1 bytes,
expected 548
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_chatkick.xml is -1 bytes,
expected 552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_chatmsg.xml is -1 bytes,
expected 516
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_clanevent.xml is -1 bytes,
expected 494
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_claninvite.xml is -1 bytes,
expected 495
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_claninvites.xml is -1 bytes,
expected 613
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_friendingame.xml is -1 bytes,
expected 550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_friendinvite.xml is -1 bytes,
expected 550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_friendonline.xml is -1 bytes,
expected 549
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_friendsinvites.xml is -1
bytes, expected 618
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_gameinvite.xml is -1 bytes,
expected 552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_giftreceived.xml is -1 bytes,
expected 566
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_itemsreceived.xml is -1 bytes,
expected 528
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_newturns.xml is -1 bytes,
expected 523
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_statusupdate.xml is -1 bytes,
expected 550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_tradeinvite.xml is -1 bytes,
expected 549
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/friends/notification_voicechat.xml is -1 bytes,
expected 547
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/inbox.xml is -1 bytes, expected 3457
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/intromovie.xml is -1 bytes, expected 311
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/library/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/bodyhittestblocker.xml is -1 bytes,
expected 187
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/cdkey.xml is -1 bytes, expected 1551
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/choosebinding.xml is -1 bytes, expected
20803
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/choose_purchase_or_authorization.xml is -1
bytes, expected 1444
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/cloudconflict.xml is -1 bytes, expected 1735
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/configbrowser.xml is -1 bytes, expected 1151
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/configbutton.xml is -1 bytes, expected 524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_bindings_save.xml is -1 bytes,
expected 2463
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_binding_button.xml is -1 bytes,
expected 385
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_properties_mode.xml is -1 bytes,
expected 20949
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_abxy.xml is -1 bytes,
expected 825
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_dpad.xml is -1 bytes,
expected 813
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_joystick_camera.xml
is -1 bytes, expected 797
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_joystick_move.xml is
-1 bytes, expected 791
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_mouse.xml is -1
bytes, expected 718
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_none.xml is -1 bytes,
expected 436
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_rel_mouse.xml is -1
bytes, expected 721
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_scrollwheel.xml is -1
bytes, expected 822
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/controller_sourcemode_trigger.xml is -1
bytes, expected 646
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/externalsignup.xml is -1 bytes, expected
1270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/launcheula.xml is -1 bytes, expected 1138
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/launchoptions.xml is -1 bytes, expected 947
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library.xml is -1 bytes, expected 650
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_allgames.xml is -1 bytes, expected
1643
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_allgames_griditem.xml is -1 bytes,
expected 615
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details.xml is -1 bytes, expected
2588
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_achievements.xml is -1
bytes, expected 6582
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_controller.xml is -1 bytes,
expected 8172
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_controllerbindings.xml is
-1 bytes, expected 14535
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_controllerbindings_d0g.xml
is -1 bytes, expected 21050
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_controllerbindings_gordon.xml
is -1 bytes, expected 1876
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_controllerbindings_vkbmouse.xml
is -1 bytes, expected 18692
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_createcategory.xml is -1
bytes, expected 981
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_dlc.xml is -1 bytes,
expected 501
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_dlc_item.xml is -1 bytes,
expected 619
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_editlaunchoptions.xml is -1
bytes, expected 1125
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_editupdateoptions.xml is -1
bytes, expected 1059
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_friendpanel.xml is -1
bytes, expected 529
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_friendswhoplay.xml is -1
bytes, expected 3002
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_guides.xml is -1 bytes,
expected 4676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_linksandmore.xml is -1
bytes, expected 5534
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_playaction.xml is -1 bytes,
expected 2436
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_recentnews.xml is -1 bytes,
expected 3515
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_screenshots.xml is -1
bytes, expected 3779
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_selectbeta.xml is -1 bytes,
expected 1313
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_selectcategory.xml is -1
bytes, expected 880
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_setapplanguage.xml is -1
bytes, expected 863
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_details_workshop.xml is -1 bytes,
expected 3680
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_recent.xml is -1 bytes, expected
2498
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_recent_activateproduct.xml is -1
bytes, expected 1546
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_recent_addcontent.xml is -1 bytes,
expected 982
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_recent_addshortcut.xml is -1 bytes,
expected 524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_recent_app.xml is -1 bytes,
expected 659
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/library_shortcuts.xml is -1 bytes, expected
880
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/notification_appdownloaded.xml is -1 bytes,
expected 568
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/notification_deviceauth.xml is -1 bytes,
expected 424
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/request_device_authorization.xml is -1
bytes, expected 1338
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/screenshots_slideshow.xml is -1 bytes,
expected 980
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/screenshots_upload.xml is -1 bytes,
expected 2398
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/screenshot_browser.xml is -1 bytes,
expected 1425
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/screenshot_browser_item.xml is -1 bytes,
expected 741
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/streamingintro.xml is -1 bytes, expected
1438
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/streamoptions.xml is -1 bytes, expected 734
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/library/waitingforgames.xml is -1 bytes, expected
1136
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/login/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/agreements.xml is -1 bytes, expected 1418
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/agreements_ssa.xml is -1 bytes, expected 1381
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/cdkey.xml is -1 bytes, expected 1559
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changeemailfail.xml is -1 bytes, expected 1062
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changeemailsuccess.xml is -1 bytes, expected
752
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changepasswordfail.xml is -1 bytes, expected
1087
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changepasswordforced.xml is -1 bytes,
expected 925
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changepasswordsuccess.xml is -1 bytes,
expected 764
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changingemail.xml is -1 bytes, expected 594
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/changingpassword.xml is -1 bytes, expected 609
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/chooseresettype.xml is -1 bytes, expected 1394
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/choosesmsorrecoverycode.xml is -1 bytes,
expected 1434
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/confcode.xml is -1 bytes, expected 2038
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/contactemail.xml is -1 bytes, expected 1609
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/createaccountfail.xml is -1 bytes, expected
1076
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/createaccountsuccess.xml is -1 bytes,
expected 1632
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/creatingaccount.xml is -1 bytes, expected 604
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/credentials.xml is -1 bytes, expected 2609
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/currentpassword.xml is -1 bytes, expected 1972
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/deauthorizecomputers.xml is -1 bytes,
expected 1023
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/deauthorizesuccess.xml is -1 bytes, expected
729
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/email.xml is -1 bytes, expected 1543
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/emailtaken.xml is -1 bytes, expected 1814
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/enterauthenticatorresetinfo.xml is -1 bytes,
expected 1640
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/enterpasswordcode.xml is -1 bytes, expected
1726
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/findingaccounts.xml is -1 bytes, expected 627
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/forgotaccountfail.xml is -1 bytes, expected
1063
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/forgotaccountnametype.xml is -1 bytes,
expected 1585
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/forgotaccountsuccess.xml is -1 bytes,
expected 777
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/forgotpassword.xml is -1 bytes, expected 1570
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/join.xml is -1 bytes, expected 1128
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/joinitem.xml is -1 bytes, expected 485
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/loginhelp.xml is -1 bytes, expected 1644
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/loginuser.xml is -1 bytes, expected 3433
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/newemail.xml is -1 bytes, expected 1813
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/newpassword.xml is -1 bytes, expected 2676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/progress.xml is -1 bytes, expected 386
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/refreshlogin.xml is -1 bytes, expected 3081
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/resetauthenticatorenterpassword.xml is -1
bytes, expected 1672
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/resetauthenticatorerror.xml is -1 bytes,
expected 981
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/resetauthenticatorsuccess.xml is -1 bytes,
expected 684
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingaccountresetdetails.xml is -1 bytes,
expected 614
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingauthenticatorreset.xml is -1 bytes,
expected 593
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingauthenticatorresetsms.xml is -1 bytes,
expected 593
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingconfcode.xml is -1 bytes, expected 612
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingpasswordcode.xml is -1 bytes, expected
615
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/sendingpasswordresetsms.xml is -1 bytes,
expected 617
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/settingsteamguard.xml is -1 bytes, expected
561
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/smserror.xml is -1 bytes, expected 988
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/steamguard.xml is -1 bytes, expected 1894
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/steamguardfail.xml is -1 bytes, expected 991
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/steamguardsuccessoff.xml is -1 bytes,
expected 713
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/steamguardsuccesson.xml is -1 bytes, expected
711
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/verifyemail.xml is -1 bytes, expected 852
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/verifyemailfail.xml is -1 bytes, expected 977
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/verifyemailsuccess.xml is -1 bytes, expected
856
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/login/verifyingemail.xml is -1 bytes, expected 529
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/mainmenu.xml is -1 bytes, expected 7928
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/movie.xml is -1 bytes, expected 2664
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/moviedebug.xml is -1 bytes, expected 698
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/msgbox.xml is -1 bytes, expected 1264
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/music/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music.xml is -1 bytes, expected 612
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_album.xml is -1 bytes, expected 1870
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_album_more.xml is -1 bytes, expected
1094
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_album_trackitem.xml is -1 bytes,
expected 625
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_allmusic_plus.xml is -1 bytes, expected
509
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_artist.xml is -1 bytes, expected 814
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_artist_more.xml is -1 bytes, expected
919
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_control.xml is -1 bytes, expected 1424
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_control_more.xml is -1 bytes, expected
1600
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_control_overlay.xml is -1 bytes,
expected 601
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_control_queue_entry.xml is -1 bytes,
expected 563
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_control_transport.xml is -1 bytes,
expected 4391
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_album.xml is -1 bytes, expected
741
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_album_griditem.xml is -1 bytes,
expected 495
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_artist.xml is -1 bytes,
expected 763
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_artist_griditem.xml is -1
bytes, expected 321
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_container.xml is -1 bytes,
expected 2946
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_crawling.xml is -1 bytes,
expected 1231
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_playlist.xml is -1 bytes,
expected 775
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_playlist_griditem.xml is -1
bytes, expected 327
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_setup.xml is -1 bytes, expected
811
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_setup_add.xml is -1 bytes,
expected 747
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_library_setup_entry.xml is -1 bytes,
expected 722
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist.xml is -1 bytes, expected 1922
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlistitem_more.xml is -1 bytes,
expected 1513
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_add.xml is -1 bytes, expected
1501
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_more.xml is -1 bytes, expected
2170
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_playlistitem.xml is -1 bytes,
expected 633
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_rename.xml is -1 bytes,
expected 1522
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_selection.xml is -1 bytes,
expected 833
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_playlist_selection_entry.xml is -1
bytes, expected 366
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_queue.xml is -1 bytes, expected 574
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_queue_list_entry.xml is -1 bytes,
expected 399
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_queue_more.xml is -1 bytes, expected
1101
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_settings.xml is -1 bytes, expected 3201
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/music_track_more.xml is -1 bytes, expected
1058
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/music/notification_musicgeneric.xml is -1 bytes,
expected 654
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/notification_networkstate.xml is -1 bytes, expected
442
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/notification_remoteclientconnected.xml is -1 bytes,
expected 564
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/notification_remoteclientdisconnected.xml is -1
bytes, expected 571
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/notification_steamupdated.xml is -1 bytes, expected
594
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/oobe/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/displaysettings.xml is -1 bytes, expected 1090
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/eula.xml is -1 bytes, expected 1091
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/language.xml is -1 bytes, expected 1270
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/networksettings.xml is -1 bytes, expected 940
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/progress.xml is -1 bytes, expected 310
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/oobe/timezonesettings.xml is -1 bytes, expected 1105
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/overlay/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/async_notifications_requested.xml is -1
bytes, expected 1466
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/notification_accesswhileplaying.xml is -1
bytes, expected 592
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/notification_refreshlogin.xml is -1 bytes,
expected 538
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/notification_screenshot.xml is -1 bytes,
expected 527
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/notification_steamlinkauth.xml is -1 bytes,
expected 593
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/notification_watch_request.xml is -1 bytes,
expected 1023
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/overlay.xml is -1 bytes, expected 3558
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/overlay_first_time_broadcast.xml is -1
bytes, expected 2090
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/overlay/overlay_notifications.xml is -1 bytes,
expected 811
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/parental/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/chooseapps.xml is -1 bytes, expected 1303
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/chooseapps_grid.xml is -1 bytes, expected
1492
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/choosefeatures.xml is -1 bytes, expected
2360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/intro.xml is -1 bytes, expected 1354
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_appgrid_overlay.xml is -1 bytes,
expected 360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_disable.xml is -1 bytes, expected
919
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_griditem.xml is -1 bytes,
expected 711
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_lock.xml is -1 bytes, expected 858
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_recent_app.xml is -1 bytes,
expected 700
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_replacement_panel.xml is -1
bytes, expected 516
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/parental_unlock.xml is -1 bytes, expected
1189
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setenablecode.xml is -1 bytes, expected
1867
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setfail.xml is -1 bytes, expected 1227
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setinprogress.xml is -1 bytes, expected 665
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setpin.xml is -1 bytes, expected 2014
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setrecovery.xml is -1 bytes, expected 1858
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/parental/setsuccess.xml is -1 bytes, expected 2164
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/profile/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/profile/profile_loading.xml is -1 bytes, expected
1326
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/profile/profile_options.xml is -1 bytes, expected
1066
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/profile/profile_wrapper.xml is -1 bytes, expected
716
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/quit.xml is -1 bytes, expected 410
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/quitentries.xml is -1 bytes, expected 2785
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/search.xml is -1 bytes, expected 1687
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/search_storeresult.xml is -1 bytes, expected 747
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/search_storesection.xml is -1 bytes, expected 528
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/settings/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/settings/audio/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/audio/settings_audio_card_wiz.xml is -1
bytes, expected 1210
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/audio/settings_audio_codec_wiz.xml is -1
bytes, expected 1730
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/audio/settings_audio_port_wiz.xml is -1
bytes, expected 1591
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/audio/settings_audio_profile_wiz.xml is -1
bytes, expected 1392
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/settings/network/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_connect.xml is -1
bytes, expected 1224
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_device_wiz.xml is
-1 bytes, expected 2369
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_ipconfig.xml is
-1 bytes, expected 1582
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_ipcustomconfig.xml
is -1 bytes, expected 3257
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_list_entry.xml is
-1 bytes, expected 573
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_wap_credentials.xml
is -1 bytes, expected 1810
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_wap_custom_ssid.xml
is -1 bytes, expected 1701
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_wap_list_entry.xml
is -1 bytes, expected 570
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/network/settings_network_wap_wiz.xml is -1
bytes, expected 1962
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings.xml is -1 bytes, expected 4550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_about.xml is -1 bytes, expected
4491
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_account.xml is -1 bytes, expected
2603
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_alienfx.xml is -1 bytes, expected
5584
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_audio.xml is -1 bytes, expected
2968
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_authorize_local_device.xml is -1
bytes, expected 1722
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_broadcast.xml is -1 bytes,
expected 1626
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_diskmgmt.xml is -1 bytes,
expected 1400
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_diskmgmt_app.xml is -1 bytes,
expected 438
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_display.xml is -1 bytes, expected
2281
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_downloads.xml is -1 bytes,
expected 2452
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_family_sharing_borrower.xml is -1
bytes, expected 585
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_friends.xml is -1 bytes, expected
3144
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_gamecontroller.xml is -1 bytes,
expected 1485
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_gamecontroller_bindings.xml is -1
bytes, expected 3521
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_gamecontroller_bindrow.xml is -1
bytes, expected 600
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_gamecontroller_namedialog.xml is
-1 bytes, expected 1501
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_ingame.xml is -1 bytes, expected
3067
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_interface.xml is -1 bytes,
expected 2566
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_language.xml is -1 bytes,
expected 839
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_manage_devices.xml is -1 bytes,
expected 1360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_manage_devices_list_entry.xml is
-1 bytes, expected 749
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_network.xml is -1 bytes, expected
2670
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_parental.xml is -1 bytes,
expected 290
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_remoteclients.xml is -1 bytes,
expected 3435
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_remoteclients_advanced_client.xml
is -1 bytes, expected 3181
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_remoteclients_advanced_host.xml
is -1 bytes, expected 1431
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_remoteclients_listing.xml is -1
bytes, expected 378
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_store.xml is -1 bytes, expected
3323
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_timezone.xml is -1 bytes,
expected 1124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/settings/settings_voice.xml is -1 bytes, expected
3896
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/shutdown.xml is -1 bytes, expected 345
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/ssa.xml is -1 bytes, expected 1035
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/steamlinkauthdialog.xml is -1 bytes, expected 1061
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/store/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/age_gate.xml is -1 bytes, expected 1387
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app.xml is -1 bytes, expected 2931
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_description.xml is -1 bytes, expected 874
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_details.xml is -1 bytes, expected 4441
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_dlc.xml is -1 bytes, expected 804
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_dlcitem.xml is -1 bytes, expected 760
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_friends.xml is -1 bytes, expected 2557
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_note.xml is -1 bytes, expected 2124
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_package.xml is -1 bytes, expected 1524
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_packagegroup.xml is -1 bytes, expected 645
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_purchase.xml is -1 bytes, expected 2126
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_purchaseoptions.xml is -1 bytes, expected
799
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/app_reviews.xml is -1 bytes, expected 1068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/browsebycategory.xml is -1 bytes, expected
1325
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/browsebycategory_item.xml is -1 bytes,
expected 1701
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/cart.xml is -1 bytes, expected 1888
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/cart_lineitem.xml is -1 bytes, expected 652
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/cart_noteitem.xml is -1 bytes, expected 395
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/cart_setcoupon.xml is -1 bytes, expected 1212
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkoutcontroller.xml is -1 bytes, expected
471
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_addfunds.xml is -1 bytes, expected
1004
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_addfunds_button.xml is -1 bytes,
expected 362
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_billinginfo.xml is -1 bytes,
expected 5287
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_confirmation.xml is -1 bytes,
expected 2777
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_giftnote.xml is -1 bytes, expected
3472
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_giftrecipient.xml is -1 bytes,
expected 3788
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_giftrecipient_friend.xml is -1
bytes, expected 563
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_microtxnauth.xml is -1 bytes,
expected 2416
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_microtxnauth_lineitem.xml is -1
bytes, expected 589
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_paymentmethod.xml is -1 bytes,
expected 1505
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_paymentmethod_fields.xml is -1
bytes, expected 3011
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_review.xml is -1 bytes, expected 4677
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_review_lineitem.xml is -1 bytes,
expected 607
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_shippinginfo.xml is -1 bytes,
expected 5581
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_verifyemail.xml is -1 bytes,
expected 1382
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/checkout_verifyshippinginfo.xml is -1 bytes,
expected 1990
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/featured_category.xml is -1 bytes, expected
353
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/filterselector.xml is -1 bytes, expected 310
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/filterselectoritem.xml is -1 bytes, expected
552
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/genre_preview.xml is -1 bytes, expected 300
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/package.xml is -1 bytes, expected 1704
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/package_appoverview.xml is -1 bytes, expected
1188
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/package_purchase.xml is -1 bytes, expected
1708
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/price.xml is -1 bytes, expected 290
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/screenshotbg.xml is -1 bytes, expected 365
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/slideshow.xml is -1 bytes, expected 241
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/slideshow_image.xml is -1 bytes, expected 459
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/stackable_loading.xml is -1 bytes, expected
400
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/store.xml is -1 bytes, expected 17900
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/textdialog.xml is -1 bytes, expected 502
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/store/trailer_slideshow.xml is -1 bytes, expected
408
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/systemim.xml is -1 bytes, expected 617
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/tenfootfooterpanel.xml is -1 bytes, expected 3793
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/test/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/test/backgroundimagetest.xml is -1 bytes, expected
1400
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/test/testpanel.xml is -1 bytes, expected 751
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/testpanel.xml is -1 bytes, expected 561
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/textinput/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/textinput/text_input_daisy.xml is -1 bytes,
expected 8910
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/textinput/text_input_daisy_group.xml is -1 bytes,
expected 847
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/textinput/text_input_dualtouch.xml is -1 bytes,
expected 9997
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/textinput/text_input_fullscreen.xml is -1 bytes,
expected 484
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/tooltip.xml is -1 bytes, expected 157
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/layout/webbrowser/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webbrowser.xml is -1 bytes, expected 4272
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webbrowser_menu.xml is -1 bytes,
expected 1759
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webcontroller.xml is -1 bytes, expected
222
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webfavorites.xml is -1 bytes, expected
1145
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webfavorites_griditem.xml is -1 bytes,
expected 629
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/webbrowser/webfavorites_imagegrid.xml is -1 bytes,
expected 3249
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/layout/wizard.xml is -1 bytes, expected 446
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/localization/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_brazilian.txt is -1 bytes, expected
464350
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_bulgarian.txt is -1 bytes, expected
544476
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_czech.txt is -1 bytes, expected 450452
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_danish.txt is -1 bytes, expected
444757
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_dutch.txt is -1 bytes, expected 452261
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_english.txt is -1 bytes, expected
232671
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_finnish.txt is -1 bytes, expected
431463
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_french.txt is -1 bytes, expected
472686
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_german.txt is -1 bytes, expected
469891
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_greek.txt is -1 bytes, expected 551521
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_hungarian.txt is -1 bytes, expected
468360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_italian.txt is -1 bytes, expected
464131
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_japanese.txt is -1 bytes, expected
460437
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_korean.txt is -1 bytes, expected
430801
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_koreana.txt is -1 bytes, expected
430801
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_norwegian.txt is -1 bytes, expected
404058
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_polish.txt is -1 bytes, expected
464360
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_portuguese.txt is -1 bytes, expected
459821
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_romanian.txt is -1 bytes, expected
449460
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_russian.txt is -1 bytes, expected
537401
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_schinese.txt is -1 bytes, expected
447004
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_spanish.txt is -1 bytes, expected
469208
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_swedish.txt is -1 bytes, expected
419952
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_tchinese.txt is -1 bytes, expected
367205
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_thai.txt is -1 bytes, expected 558689
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_turkish.txt is -1 bytes, expected
462913
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/localization/tenfoot_ukrainian.txt is -1 bytes, expected
537426
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/sounds/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/activation.wav is -1 bytes, expected 147172
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/activation_change_fail.wav is -1 bytes, expected
112784
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/add_favorite.wav is -1 bytes, expected 102044
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/sounds/ambient/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_drone_01.mp3 is -1
bytes, expected 287422
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_01.mp3 is -1
bytes, expected 201785
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_02.mp3 is -1
bytes, expected 349320
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_03.mp3 is -1
bytes, expected 297096
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_04.mp3 is -1
bytes, expected 449919
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_05.mp3 is -1
bytes, expected 377002
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_06.mp3 is -1
bytes, expected 235710
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_07.mp3 is -1
bytes, expected 259768
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_08.mp3 is -1
bytes, expected 271836
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_01_09.mp3 is -1
bytes, expected 122091
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_01.mp3 is -1
bytes, expected 224416
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_02.mp3 is -1
bytes, expected 408701
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_03.mp3 is -1
bytes, expected 340345
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_04.mp3 is -1
bytes, expected 547534
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_05.mp3 is -1
bytes, expected 444031
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_06.mp3 is -1
bytes, expected 275215
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_07.mp3 is -1
bytes, expected 297180
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_08.mp3 is -1
bytes, expected 304680
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_02_09.mp3 is -1
bytes, expected 165156
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_01.mp3 is -1
bytes, expected 239579
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_02.mp3 is -1
bytes, expected 328247
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_03.mp3 is -1
bytes, expected 294240
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_04.mp3 is -1
bytes, expected 476823
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_05.mp3 is -1
bytes, expected 393896
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_06.mp3 is -1
bytes, expected 268167
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_07.mp3 is -1
bytes, expected 261847
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_08.mp3 is -1
bytes, expected 264355
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/ambient/amb_bigfoot_backing_part_03_09.mp3 is -1
bytes, expected 134882
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/focus_change.wav is -1 bytes, expected 183456
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/focus_change_fail.wav is -1 bytes, expected 74096
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/focus_change_fastscroll.wav is -1 bytes, expected
130736
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/page_scroll_left.wav is -1 bytes, expected 158056
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/page_scroll_right.wav is -1 bytes, expected 190068
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_cursor_end.wav is -1 bytes, expected 29860
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_cursor_home.wav is -1 bytes, expected 25944
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_cursor_left.wav is -1 bytes, expected 65476
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_cursor_right.wav is -1 bytes, expected 58660
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_focus.wav is -1 bytes, expected 37676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_group_defocus.wav is -1 bytes, expected 67556
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_group_focus.wav is -1 bytes, expected 37676
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_press_a.wav is -1 bytes, expected 86560
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_press_b.wav is -1 bytes, expected 154808
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_press_x.wav is -1 bytes, expected 149884
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_press_y.wav is -1 bytes, expected 120132
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_backspace.wav is -1 bytes, expected
39824
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_caps.wav is -1 bytes, expected 115476
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_extra.wav is -1 bytes, expected 152432
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_fail.wav is -1 bytes, expected 74096
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_main.wav is -1 bytes, expected 102812
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_numbers.wav is -1 bytes, expected 70604
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/txting_type_spacebar.wav is -1 bytes, expected 58132
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/volume_change.wav is -1 bytes, expected 68408
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/sounds/zoom_in.wav is -1 bytes, expected 185540
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/account/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/account/confirmpassword.css is -1 bytes, expected
2820
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/backgroundvideopanel.css is -1 bytes, expected 16293
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/broadcast/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/broadcast/broadcast.css is -1 bytes, expected 3129
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/button.css is -1 bytes, expected 1475
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/community/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/community/community.css is -1 bytes, expected 6984
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/consolepanel.css is -1 bytes, expected 2376
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/debugger.css is -1 bytes, expected 12024
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/downloads.css is -1 bytes, expected 23035
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/fileselector.css is -1 bytes, expected 10603
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/footer.css is -1 bytes, expected 11051
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/friends/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/friends/chaturls.css is -1 bytes, expected 402
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/friends/community_main.css is -1 bytes, expected
40370
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/friends/friends.css is -1 bytes, expected 42140
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/friends/friends_profile_details.css is -1 bytes,
expected 9336
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/intromovie.css is -1 bytes, expected 1262
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/keyboard.css is -1 bytes, expected 256
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/library/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/cdkey.css is -1 bytes, expected 3582
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/choose_purchase_or_authorization.css is -1
bytes, expected 1990
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/cloudconflict.css is -1 bytes, expected 541
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/controllerbindings.css is -1 bytes,
expected 49604
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/controllerbindings_d0g.css is -1 bytes,
expected 48876
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/controllerbindings_gordon.css is -1 bytes,
expected 52327
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/externalsignup.css is -1 bytes, expected 0
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/launcheula.css is -1 bytes, expected 165
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/launchoptions.css is -1 bytes, expected 171
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/library.css is -1 bytes, expected 111201
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/library_recent_activateproduct.css is -1
bytes, expected 835
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/library_recent_addshortcut.css is -1 bytes,
expected 979
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/library_screenshots_slideshow.css is -1
bytes, expected 8092
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/request_device_authorization.css is -1
bytes, expected 886
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/screenshotbrowser.css is -1 bytes, expected
6513
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/streamoptions.css is -1 bytes, expected 454
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/library/waitingforgames.css is -1 bytes, expected 78
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login.css is -1 bytes, expected 12325
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/login/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/changeemail.css is -1 bytes, expected 1290
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/changepassword.css is -1 bytes, expected 3623
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/createaccount.css is -1 bytes, expected 5234
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/join.css is -1 bytes, expected 6550
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/loginhelp.css is -1 bytes, expected 88
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/loginstyles.css is -1 bytes, expected 3671
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/loginuser.css is -1 bytes, expected 11897
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/refreshlogin.css is -1 bytes, expected 871
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/login/steamguard.css is -1 bytes, expected 2003
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/mainmenu.css is -1 bytes, expected 28268
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/mainmenu_communitybackground.css is -1 bytes,
expected 6720
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/mainmenu_librarybackground.css is -1 bytes,
expected 9595
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/mainmenu_storebackground.css is -1 bytes, expected
5764
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/mainmenu_systemmessages.css is -1 bytes, expected
16776
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/movie.css is -1 bytes, expected 10348
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/msgbox.css is -1 bytes, expected 6405
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/music/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music.css is -1 bytes, expected 3445
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_album.css is -1 bytes, expected 7511
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_artist.css is -1 bytes, expected 1003
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_control.css is -1 bytes, expected 6307
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_control_overlay.css is -1 bytes,
expected 4969
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_control_transport.css is -1 bytes,
expected 15553
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_library.css is -1 bytes, expected 28145
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_library_setup.css is -1 bytes, expected
2840
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_playlist.css is -1 bytes, expected 7636
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_playlist_add.css is -1 bytes, expected
2547
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_playlist_rename.css is -1 bytes,
expected 2548
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_playlist_selection.css is -1 bytes,
expected 3196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_queue.css is -1 bytes, expected 4975
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/music/music_settings.css is -1 bytes, expected 28
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/notifications.css is -1 bytes, expected 6772
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/oobe/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/oobe/oobe.css is -1 bytes, expected 2089
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/overlay/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/overlay/asyncnotifications.css is -1 bytes,
expected 135
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/overlay/overlay.css is -1 bytes, expected 7366
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/parental/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/parental/parental.css is -1 bytes, expected 16346
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/profile/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/profile/profile.css is -1 bytes, expected 9704
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/quit.css is -1 bytes, expected 2730
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/search.css is -1 bytes, expected 10763
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/settings.css is -1 bytes, expected 65476
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/shutdown.css is -1 bytes, expected 740
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/steamstyles.css is -1 bytes, expected 40648
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/store/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/browsebycategory.css is -1 bytes, expected
11695
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/checkout.css is -1 bytes, expected 29743
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/filterselector.css is -1 bytes, expected 4608
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/store.css is -1 bytes, expected 33893
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/storeapp.css is -1 bytes, expected 59497
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/store_setcoupon.css is -1 bytes, expected 3104
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/store/textdialog.css is -1 bytes, expected 1387
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/test/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/test/backgroundimagetest.css is -1 bytes, expected
2379
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/test/testpanel.css is -1 bytes, expected 1074
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/testpanel.css is -1 bytes, expected 902
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/textinput/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/textinput/text_input.css is -1 bytes, expected 29964
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/textinput/text_input_dualtouch.css is -1 bytes,
expected 4478
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/textinput/text_input_fullscreen.css is -1 bytes,
expected 688
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/waitingforgames.css is -1 bytes, expected 78
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/styles/webbrowser/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/webbrowser/webbrowser.css is -1 bytes, expected
13196
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/webbrowser/webbrowser_dialogs.css is -1 bytes,
expected 2493
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/webbrowser/webcontroller.css is -1 bytes, expected
864
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/webbrowser/webfavorites.css is -1 bytes, expected
11737
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/styles/wizardstyles.css is -1 bytes, expected 10542
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/window_keybinds.cfg is -1 bytes, expected 12897
[2015-07-07 20:21:12] BVerifyInstalledFiles: bad directory
tenfoot/resource/wordlists/
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/brazilian_compiled_words.dic is -1 bytes,
expected 520108
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/danish_compiled_words.dic is -1 bytes, expected
522099
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/dutch_compiled_words.dic is -1 bytes, expected
553406
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/english_compiled_words.dic is -1 bytes, expected
510012
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/finnish_compiled_words.dic is -1 bytes, expected
549450
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/french_compiled_words.dic is -1 bytes, expected
534973
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/german_compiled_words.dic is -1 bytes, expected
546740
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/italian_compiled_words.dic is -1 bytes, expected
535264
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/norwegian_compiled_words.dic is -1 bytes,
expected 521362
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/polish_compiled_words.dic is -1 bytes, expected
512142
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/portuguese_compiled_words.dic is -1 bytes,
expected 531339
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/russian_compiled_words.dic is -1 bytes, expected
634244
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/spanish_compiled_words.dic is -1 bytes, expected
528692
[2015-07-07 20:21:12] BVerifyInstalledFiles:
tenfoot/resource/wordlists/swedish_compiled_words.dic is -1 bytes, expected
526915
[2015-07-07 20:21:12] BVerifyInstalledFiles: ThirdPartyLegalNotices.css is
-1 bytes, expected 405
[2015-07-07 20:21:12] BVerifyInstalledFiles: ThirdPartyLegalNotices.doc is
-1 bytes, expected 25088
[2015-07-07 20:21:12] BVerifyInstalledFiles: ThirdPartyLegalNotices.html is
-1 bytes, expected 200227
[2015-07-07 20:21:12] BVerifyInstalledFiles: vgui2_s.dylib is -1 bytes,
expected 1589372
[2015-07-07 20:21:12] Verification complete
[2015-07-07 20:21:12] Downloading update...
[2015-07-07 20:21:12] Checking for available updates...
[2015-07-07 20:22:12] Download failed: http error 0
[2015-07-07 20:22:12] Download complete.
[2015-07-07 20:22:12] uninstalled manifest found in
/Applications/Steam.app/Contents/MacOS/package/steam_client_osx (1).
[2015-07-07 20:22:12] Extracting package...
[2015-07-07 20:22:24] Installing update...
[2015-07-07 20:22:25] Cleaning up...
[2015-07-07 20:22:25] Update complete, launching Steam...
[2015-07-07 20:22:25] Shutdown

```
