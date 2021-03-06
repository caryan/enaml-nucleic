Enaml Release Notes
===================

0.8.9 - 11/25/2013
------------------
- Add ability to query window minimized/maximized state. 713feb85952a_
- Implement 'always_on_top' window flag. 3ac3e6955579_
- A handful of bug fixes.

.. _713feb85952a: https://github.com/nucleic/enaml/commit/713feb85952ab93094d6f06a8af457871355207c
.. _3ac3e6955579: https://github.com/nucleic/enaml/commit/3ac3e6955579595c1c2ce2a74e79c1f96fe4a21e

0.8.8 - 11/7/2013
-----------------
- Add a task dialog mini-framework and a MessageBox stlib component. 5583808f293a_

.. _5583808f293a: https://github.com/nucleic/enaml/commit/5583808f293a881ea52b00907fd3d85cc2b3e7b0

0.8.7 - 11/4/2013
-----------------
- Add an alerting api for dock items in a dock area. ba766d773090_

.. _ba766d773090: https://github.com/nucleic/enaml/commit/ba766d7730908c7370727da8713a74f7d1380ed2

0.8.6 - 10/30/2013
------------------
- Add 'limit_width' and 'limit_height' virtual constraints. 8722be90844e_

.. _8722be90844e: https://github.com/nucleic/enaml/commit/8722be90844ed68809de792b818cd399bbb8bfa2

0.8.5 - 10/29/2013
------------------
- Add support for style sheets to the DockArea. 5e38c591ad55_

.. _5e38c591ad55: https://github.com/nucleic/enaml/commit/5e38c591ad55683d367b652460f70b75f3f087b2

0.8.4 - 10/28/2013
------------------
- Add a size hint mode switch to Notebook and Stack. 330c7a337c32d_

.. _330c7a337c32d: https://github.com/nucleic/enaml/commit/330c7a337c32d1b15a8d8d50acfc4ea208fd5330

0.8.3 - 10/25/2013
------------------
- Add support for style sheets. 77e2a0afbd56_
- Fix a bug with a null widget and the notebook selected tab. 64cfe8789838_

.. _77e2a0afbd56: https://github.com/nucleic/enaml/commit/77e2a0afbd56489fe457c13c0b3e12e0187393ce
.. _64cfe8789838: https://github.com/nucleic/enaml/commit/64cfe87898382b9a76a0450914d40272b6fa6d02

0.8.2 - 10/11/2013
------------------
- Add a DynamicTemplate declarative object. ede76a778a86_
- Add 'window' mode to PopupView. f37263fd7b7d_
- Add 'selected_tab' attribute to the Notebook. 45ca092e7222_
- Overhaul of the docs and doc build system.
- Various bug fixes and performance improvements.

.. _ede76a778a86: https://github.com/nucleic/enaml/commit/ede76a778a864dbb79636f38a15fd6b24e975228
.. _f37263fd7b7d: https://github.com/nucleic/enaml/commit/f37263fd7b7db22c0a404660ccaea3f444b8a171
.. _45ca092e7222: https://github.com/nucleic/enaml/commit/45ca092e722209163c4dad81741d2f09595efade

0.8.1 - 09/25/2013
------------------
- Update the PopupView to automatically reposition on-screen. 3225683f9411_
- Minor bug fixes.
- Added an ImageView example.

.. _3225683f9411: https://github.com/nucleic/enaml/commit/3225683f9411266d98b050be252440c7f5a1e892

0.8.0 - 09/20/2013
------------------
- Added templates to the language.
- Added aliases to the language.
- Removed the compatibility code scheduled for removal.
- Added a completely new declarative expression engine.

0.7.20 - 08/12/2013
-------------------
- Bugfix area layout traversal. 308164fd5134_
- Allow alpha hex colors. d9605cc55bb5_
- Add a declarative Timer object. 13259258e6fd_
- Added a Scintilla widget.
- Added the applib sub-package.
- Added live editor components to the applib.
- Added an 'auto_sync' submit trigger to Field. 1926cde5e64b_

.. _308164fd5134: https://github.com/nucleic/enaml/commit/308164fd513416ffb52a38db9b5b7039942e32f2
.. _d9605cc55bb5: https://github.com/nucleic/enaml/commit/d9605cc55bb546f1a2593df0865687678de182f1
.. _13259258e6fd: https://github.com/nucleic/enaml/commit/13259258e6fdb62181a26b24cef9d69f70c37ac3
.. _1926cde5e64b: https://github.com/nucleic/enaml/commit/1926cde5e64ba3b4227886268869b10e755d5c0b

0.7.19 - 07/22/2013
-------------------
- Added dock layout ops for extending/retracting from dock bars. 00ee34a102f_
- Added methods for manipulating window geometry. bebba0a82fa_

.. _00ee34a102f: https://github.com/nucleic/enaml/commit/00ee34a102fd28c1861a82f784699844c5537c6c
.. _bebba0a82fa: https://github.com/nucleic/enaml/commit/bebba0a82face4000a28bdff73e4df71fcbeb356

0.7.18 - 07/20/2013
-------------------
- Production release of dock area toolbars.
- Updates to dock layout specification with compatibility env setting.
- Resizable slide-out dock bar items.
- Pin buttons on dock items.
- Improved procedural dock layout modification api.
- Added a base Frame class which supplies borders for subclasses. d1316f40248_
- Fixed container ref-cycle issue on widget destruction. 03a5e53038f_

.. _d1316f40248: https://github.com/nucleic/enaml/commit/d1316f40248eaef807705ccc9954f43eebece954
.. _03a5e53038f: https://github.com/nucleic/enaml/commit/03a5e53038f2aac1d187d9bb2c27c86c2b1d9caf

0.7.17 - 07/03/2013
-------------------
- Added easier to use operator hooks. 2aaf3c96fc8_
- Added support for PySide. 0d18a21754e_
- Add cursor anchor mode to PopupView. 74ddd47197e_
- Initial feedback release of dock area toolbars.

.. _2aaf3c96fc8: https://github.com/nucleic/enaml/commit/2aaf3c96fc89bc064e52a83ef416c752a5bbedf5
.. _0d18a21754e: https://github.com/nucleic/enaml/commit/0d18a21754ee9b071b0986289ddfdb380ab016fc
.. _74ddd47197e: https://github.com/nucleic/enaml/commit/74ddd47197ef9330e69cf9cb137aeb45a0204d07

0.7.16 - 06/19/2013
-------------------
- Add a more useful file dialog as FileDialogEx. 390868cccb_
- Add a color selection dialog as ColorDialog. d722a876e9_
- Persist the linked state of floating dock items in a saved layout. adc9dec8db_
- Add a right click event to the dock item title bar. 812e97aebcf_
- Make the dock item title user editable. 54b68881529_
- Make the visibility of the dock item title bar configurable. 54b68881529_
- Toggle the maximized state of a dock item on title bar double click. 4ffe9d6b68e_
- Add a RawWidget widget to easily embed external widgets into Enaml. e9d25a29e77_

.. _390868cccb: https://github.com/nucleic/enaml/commit/390868cccb718dc33b48d2943d7150826daf0886
.. _d722a876e9: https://github.com/nucleic/enaml/commit/d722a876e9309bff81b78324c6553e73a4b5c6ab
.. _adc9dec8db: https://github.com/nucleic/enaml/commit/adc9dec8dbf562f1e365573739532ca7bdd1dda4
.. _812e97aebcf: https://github.com/nucleic/enaml/commit/812e97aebcf2e06142b516383097d5fb51d8872b
.. _54b68881529: https://github.com/nucleic/enaml/commit/54b688815295b3d1181986a6b91784ff68e9ae72
.. _4ffe9d6b68e: https://github.com/nucleic/enaml/commit/4ffe9d6b68ed55496ef9491aa13d62805aa59543
.. _e9d25a29e77: https://github.com/nucleic/enaml/commit/e9d25a29e77c7177cef3dd85733867faddb6eac1

0.7.15 - 06/12/2013
-------------------
- Fix a bug in parsing elif blocks. e25363b005_

.. _e25363b005: https://github.com/nucleic/enaml/commit/e25363b00581ece64aad02fee369119e8393b5ce

0.7.14 - 06/05/2013
-------------------
- Make the translucent background of PopupView configurable. 0731314117_
- Add a 'live_drag' flag to the DockArea. 0cd6889b2c_

.. _0731314117: https://github.com/nucleic/enaml/commit/0731314117c2c9cbd29f7e285b487f6cb30754e0
.. _0cd6889b2c: https://github.com/nucleic/enaml/commit/0cd6889b2c0b9c086605fce5322c07c7ee92e448

0.7.13 - 05/31/2013
-------------------
- Feature improvements and fixes to snappable dock frames. 693a6f363a_
- Add a 'link_activated' event to the Label widget. 269b386639_

.. _693a6f363a: https://github.com/nucleic/enaml/commit/693a6f363a6be6751734c64e1e1c0454dcdc1325
.. _269b386639: https://github.com/nucleic/enaml/commit/269b3866397ed126dd11083f1be99ba6296d5892

0.7.12 - 05/29/2013
-------------------
- Make floating dock windows snappable and linkable. de3ced381e_

.. _de3ced381e: https://github.com/nucleic/enaml/commit/de3ced381e3b4dde88bb59fdab5399eb7173ceba

0.7.11 - 05/28/2013
-------------------
- Claw back the direct exposure of the Qt stylesheets. 947760ebcd_

.. _947760ebcd: https://github.com/nucleic/enaml/commit/947760ebcd68f351f268913ebbd396a6da24f06d

0.7.10 - 05/26/2013
-------------------
- Expose the Qt stylesheet directly for the dock area. 5877335bcf_
- Add the ability to style the various dock area buttons. 5877335bcf_

.. _5877335bcf: https://github.com/nucleic/enaml/commit/5877335bcf8fd09c9d066a17905b4d92ca24de8d

0.7.9 - 05/24/2013
------------------
- Make the close button on dock items configurable. d839fb0c2b_
- Expose a public api for manipulating the dock layout. e269adbdb2_
- Expose user configurable dock area styles. 4c05d5953f_

.. _4c05d5953f: https://github.com/nucleic/enaml/commit/4c05d5953fd0cbefdb66ca502ff662d259955ee1
.. _e269adbdb2: https://github.com/nucleic/enaml/commit/e269adbdb23ecfd6c6728af3ca8857e20d40415f
.. _d839fb0c2b: https://github.com/nucleic/enaml/commit/d839fb0c2bd096a6580d8ab887dfc6787928bcd5

0.7.8 - 05/20/2013
------------------
- Add support for maximizing a docked item within a DockArea. a051862ce5_
- Update the popup view to use a 45 degree angled arrow. f3edc88fe1_
- Miscellaneous updates and bug fixes to the DockArea.

.. _a051862ce5: https://github.com/nucleic/enaml/commit/a051862ce5dbe2240295c4ae9fc19187554a928f
.. _f3edc88fe1: : https://github.com/nucleic/enaml/commit/f3edc88fe163cbe02b08b5215f78de0fbd1ac61b

0.7.7 - 05/09/2013
------------------
- Add support for floating "dock rafts" in the DockArea. 402330dcaf_
- Add a PopupView widget to support transparent popups and growl-style notifications. a5117121bf_

.. _402330dcaf: https://github.com/nucleic/enaml/commit/402330dcafefaf8470db74bf632d58f039fc4a4f
.. _a5117121bf: https://github.com/nucleic/enaml/commit/a5117121bf5e553a6d5953685605494d676d1661

0.7.6 - 04/25/2013
------------------
- Add an advanced DockArea widget. 3ed122b110_
- Add popup() functionality to the Menu widget. 5363a56f33_

.. _3ed122b110: https://github.com/nucleic/enaml/commit/3ed122b11050ee72383aa0ef08ca2537ec7eb841
.. _5363a56f33: https://github.com/nucleic/enaml/commit/5363a56f336e7302d6c2876e0b630794b9f751ae

0.7.5 - 04/09/2013
------------------
- Fix a bug in the Wx main window implementation. 39f6baee49_

.. _39f6baee49: https://github.com/nucleic/enaml/commit/39f6baee49ddb601f8fde5b222fadf4053075a73

0.7.4 - 04/04/2013
------------------
- Add border support for Container on the Qt backend. 505662d5f1_
- Workaround a logic bug in Wx's handling of modal windows. 56a1e00112_
- Workaround a Wx segfault during window destruction. a8525788c9_

.. _505662d5f1: https://github.com/nucleic/enaml/commit/505662d5f1ad0bdf50a4439873a252c2367dc418
.. _56a1e00112: https://github.com/nucleic/enaml/commit/56a1e001127f12ea971b11343e58711466af1895
.. _a8525788c9: https://github.com/nucleic/enaml/commit/a8525788c9a8ccf50c657fefc85db66d0a78abf9

0.7.3 - 04/03/2013
------------------
- Added support for adding/removing models in a ViewTable. 5bc1809340_
- Added an ObjectCombo control which is a more flexible combo box. 51f3a3c6d3_
- Emit useful error messages when a backend does not implement a control. b264b3b927_

.. _5bc1809340: https://github.com/nucleic/enaml/commit/5bc1809340543aa7184a96cd7a1da3daa37c19dd
.. _51f3a3c6d3: https://github.com/nucleic/enaml/commit/51f3a3c6d3e6fe8c076a8baa26c33ada895beb18
.. _b264b3b927: https://github.com/nucleic/enaml/commit/b264b3b927b979fb83766e82656f70d0023c6a48

0.7.2 - 04/02/2013
------------------
- Added first real cut at a model-viewer grid-based control. de0d8e35ae_
- Fix a bug in size hinting during complex relayouts. 963cee88d0_
- Added hooks for proxy-specific customization. 3e045dfb18_

.. _de0d8e35ae: https://github.com/nucleic/enaml/commit/de0d8e35aee42d5eda63ad0bef0b8eb0adf299f5
.. _963cee88d0: https://github.com/nucleic/enaml/commit/963cee88d09e2e0ff0c9c4d41b2ac2e8ee6f4ab6
.. _3e045dfb18: https://github.com/nucleic/enaml/commit/3e045dfb18ee74000106c7559626449102930010

0.7.1 - 03/28/2013
------------------
- Updated compiler infrastructure to produce more extensible parse trees.
- Various bug fixes.

0.7.0 - 03/20/2013
------------------
- First release under new nucleic org.
- Rewrite of entire framework to sit on top of Atom instead of Traits.
- Vastly improved backend architecture.
- Improved compile-time operator binding.

0.6.8 - 02/14/2013
------------------
- Added ability to change the Z order of a window and a flag to make it stay on top. d6f618101f_
- Added a multiline text entry widget. dde4bd3409_
- Bugfix when ImageView is used in a ScrollArea. 67133d3fec_

.. _d6f618101f: https://github.com/enthought/enaml/commit/d6f618101f281aec8fd124fc5d7faf51066ffc99
.. _dde4bd3409: https://github.com/enthought/enaml/commit/dde4bd34097c59d982ebf5121e0a111b88c1a3f8
.. _67133d3fec: https://github.com/enthought/enaml/commit/67133d3fec03c567dab38aa9123002cab4f6215b


0.6.7 - 01/23/2013
------------------
- Added a `root_object()` method on the `Object` class which returns the root of the object tree. d9b4830963_
- Properly handle window modality on the Qt backend. 28f2433814_
- Add a `destroy_on_close` flag to the `Window` class. 2a63e8cefd_
- Prevent Wx from destroying top-level windows by default. 8e298e768e_
- Add support for adding windows to a session at run-time. c090c0fad6_
- Fix the lifetime bug with the `FileDialog`. 8e354de858_

.. _d9b4830963: https://github.com/enthought/enaml/commit/d9b48309631ed315b67ddf9c4222a2efcf4858ee
.. _28f2433814: https://github.com/enthought/enaml/commit/28f243381439ce1ce263cad2672b62a96bc87a0c
.. _2a63e8cefd: https://github.com/enthought/enaml/commit/2a63e8cefde29416291536ec6c02a05b612e11b1
.. _8e298e768e: https://github.com/enthought/enaml/commit/8e298e768eb45248cc98f682c9cc3b3f473b2a29
.. _c090c0fad6: https://github.com/enthought/enaml/commit/c090c0fad64a30936fc79774f8e851dca46076b6
.. _8e354de858: https://github.com/enthought/enaml/commit/8e354de858a6ee5deeda96dafa6322579c5514a6


0.6.6 - 01/10/2013
------------------
- Fix the broken unittests and make them Python 2.6 safe. 2c1d7f01d_

.. _22c1d7f01d: https://github.com/enthought/enaml/commit/22c1d7f01d844979c166e2f156d18a553f2c0152


0.6.5 - 01/10/2013
------------------
- Add a stretch factor to the Splitter widget. c2272cf1ef_
- Fix bugs in the Wx splitter implementation. dfa542ba3d_

.. _c2272cf1ef: https://github.com/enthought/enaml/commit/c2272cf1eff3e667c6ea1d255cc9c13c14745872
.. _dfa542ba3d: https://github.com/enthought/enaml/commit/dfa542ba3d36d6b968bffb1dcd1e0ed96ddbcf3b


0.6.4 - 01/07/2013
------------------
- Add support for icons on notebook pages on the Qt backend. b6426b7ae9_
- Add support for popup menus in the Wx backend (Qt is already supported). 153f3124b2_
- Add simpler way of building the optional C++ extensions. 4eebd59ae5_
- Update enaml-run to play nice with ETS_TOOLKIT. f864975a87_

.. _f864975a87: https://github.com/enthought/enaml/commit/f864975a872189a76dc8a2cf9e2469a78320a906
.. _4eebd59ae5: https://github.com/enthought/enaml/commit/4eebd59ae51df08d255ffe3860db821781f40579
.. _153f3124b2: https://github.com/enthought/enaml/commit/153f3124b2c62f2a5e7695e7ea1a8dff067f2fc5
.. _b6426b7ae9: https://github.com/enthought/enaml/commit/b6426b7ae9bcab9f8549fa635216c6cfd39ee29b


0.6.3 - 12/11/2012
------------------
- Fix critical bug related to traits Disallow and the `attr` keyword. 25755e2bbd_

.. _25755e2bbd: https://github.com/enthought/enaml/commit/25755e2bbd5e2e38e42d30776e1864d52c992af3


0.6.2 - 12/11/2012
------------------
- Fix critical bug for broken dynamic scoping. a788869ab0_

.. _a788869ab0: https://github.com/enthought/enaml/commit/a788869ab0a410c478cbe4cc066fc8ee35b266b8


0.6.1 - 12/10/2012
------------------
- Fix critical bug in compiler and expression objects. dfb6f648a1_

.. _dfb6f648a1: https://github.com/enthought/enaml/commit/dfb6f648a15370249b0a57433b8839a4caba7d35


0.6.0 - 12/10/2012
------------------
- Add Icon and Image support using a lazy loading resource sub-framework. 77d5ca3b01_
- Add a traitsui support via the TraitsItem widget (care of Steven Silvester). 9cb9126da1_
- Add matplotlib support via the MPLCanvas widget (care of Steven Silvester). eaa6294566_
- Updated Session api which is more intuitive and easier to use.
- Updated Object api which is more intuitive and easier to use.
- Object lifecycle reflected in a `state` attribute.
- Huge reduction in memory usage when creating large numbers of objects.
- Huge reduction in time to create large numbers of objects.
- New widget registry make it easier to register custom widgets. cc791a52d7_
- Better and faster code analysis via code tracers. 4eceb09f70_
- Fix a parser bug related to relative imports. 3e43e73e90_
- Various other tweaks, bugfixes, and api cleanup.

.. _77d5ca3b01: https://github.com/enthought/enaml/commit/77d5ca3b0135fa982663d4ce9cf801119617c611
.. _eaa6294566: https://github.com/enthought/enaml/commit/eaa62945663fa9c96aee822c9f31ef966c88fd62
.. _9cb9126da1: https://github.com/enthought/enaml/commit/9cb9126da1e590814ad6dbee9a732c9add185ed6
.. _cc791a52d7: https://github.com/enthought/enaml/commit/cc791a52d772b07c7482427b5b60dcff9d5436c1
.. _4eceb09f70: https://github.com/enthought/enaml/commit/4eceb09f707e7795182013b9f874abf0afbaab41
.. _3e43e73e90: https://github.com/enthought/enaml/commit/3e43e73e90bd392a63a1faa53f821672fdb8c44f


0.5.1 - 11/19/2012
------------------
- Fix a method naming bug in QSingleWidgetLayout. 7a4c9de7e6_
- Fix a test height computation bug in QFlowLayout. a962d2ae78_
- Invalidate the QFlowLayout on layout request. 1e91a54245_
- Dispatch child events immediately when possible. e869f7124f_
- Destroy child widgets after the children change event is emitted. c695ae35ee_
- Add a preliminary WebView widget. 27faa381dc_

.. _27faa381dc: https://github.com/enthought/enaml/commit/27faa381dc5dd6c5cc41a0826df35b71339d3e7e
.. _c695ae35ee: https://github.com/enthought/enaml/commit/c695ae35ee9fcf35964df88831de0d3b30883f78
.. _e869f7124f: https://github.com/enthought/enaml/commit/e869f7124f0e13bea7f35d5f5a91bc89dc1dcd4e
.. _1e91a54245: https://github.com/enthought/enaml/commit/1e91a542452662ebd3dfe9d5a854ec2277f4415d
.. _a962d2ae78: https://github.com/enthought/enaml/commit/a962d2ae78488398cbe50d4ad16bd1cd90a1060b
.. _7a4c9de7e6: https://github.com/enthought/enaml/commit/7a4c9de7e6342b65efd6e3e841be0adfad286d99


0.5.0 - 11/16/2012
------------------
- Merge the feature-async branch into mainline. f86dad8f6e_
- First release with release notes. 8dbed4b9cd_

.. _8dbed4b9cd: https://github.com/enthought/enaml/commit/8dbed4b9cd16d8c9f71ea63dfd92494176fdf753
.. _f86dad8f6e: https://github.com/enthought/enaml/commit/f86dad8f6e3fe0bf07a2cf59765aaa3b934fa233

