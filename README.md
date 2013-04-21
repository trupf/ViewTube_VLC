ViewTube_VLC
============

This patch is made to improve performance of the ViewTube userscript from Sebaro 
(http://isebaro.com/viewtube/) in firefox.
It is specially aimed at use with the VLC plugin but should not break compatibiliy with other plugins
and probably improve totem performance the same way as VLCs (not tested by me).

You need to disable cookies in your browser on Dailymotion to make this site work!

Fixes:

- remove the 'Alt' option and decide browser dependent instead
- make VLC plugin work with Vimeo without delay in Firefox 
- make VLC plugin work with Vimeo in Chrome and Chromium with Tampermonkey
  (this special constellation does not work with Sebaro's version)


2013/04/08: Initial release against ViewTube 2013-04-06

2013/04/17: updated patch 2013-04-10

2013/04/20: added patch for ViewTubePlus

