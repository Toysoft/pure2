SUBDIRS = fonts extensions keymaps skin_default countries defaults

dist_pkgdata_DATA = \
	skin_default.xml \
	skin.xml \
	prev.png \
	encoding.conf \
	keymap.xml \
	keytranslation.xml \
	menu.xml \
	black.mvi \
	radio.mvi \
	rcpositions.xml \
	setup.xml \
	skin_subtitles.xml \
	startwizard.xml \
	userinterfacepositionerwizard.xml \
	videowizard.xml \
	freesat.t1 \
	freesat.t2 \
	unicable.xml \
	overscan.mvi \
	distro-logo.png


if HAVE_TEXTLCD
if HAVE_7SEGMENT
SUBDIRS += 7segment
else
if SPARK
SUBDIRS += displaydualtext
else
SUBDIRS += displaytext
endif
endif
endif

if HAVE_COLORLCD3
SUBDIRS += display128dm
endif

if HAVE_COLORLCD2
SUBDIRS += display96
endif

if HAVE_COLORLCD1
SUBDIRS += display128
endif

if HAVE_COLORLCD220
SUBDIRS += display220 lcd_220
endif

if HAVE_COLORLCD390
SUBDIRS += display390
endif

if HAVE_COLORLCD400
SUBDIRS += display400 lcd_400
endif

if HAVE_COLORLCD480
SUBDIRS += display480
endif

if HAVE_COLORLCD720
SUBDIRS += display720
endif

if HAVE_COLORLCD800
SUBDIRS += display800
endif

if HAVE_BWLCD255
SUBDIRS += vfd255
endif

if HAVE_BWLCD140
SUBDIRS += vfd140
endif

if HAVE_BWLCD128
SUBDIRS += vfd128
endif

if HAVE_GRAUTEC8000
SUBDIRS += grautec8000
endif

if HAVE_GRAUTEC70X0
SUBDIRS += grautec70x0
endif

