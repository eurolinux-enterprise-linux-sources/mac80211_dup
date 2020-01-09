obj-m += mac80211_dup.o

# mac80211 objects
mac80211_dup-y := \
	main.o status.o \
	sta_info.o \
	wep.o \
	wpa.o \
	scan.o offchannel.o \
	ht.o agg-tx.o agg-rx.o \
	vht.o \
	ibss.o \
	iface.o \
	rate.o \
	michael.o \
	tkip.o \
	aes_ccm.o \
	aes_cmac.o \
	cfg.o \
	ethtool.o \
	rx.o \
	spectmgmt.o \
	tx.o \
	key.o \
	util.o \
	wme.o \
	event.o \
	chan.o \
	trace.o mlme.o \
	tdls.o \
	ocb.o \
	led.o \
	pm.o \
	rc80211_minstrel.o \
	rc80211_minstrel_ht.o

mac80211-$(CONFIG_MAC80211_MESH) += \
	mesh.o \
	mesh_pathtbl.o \
	mesh_plink.o \
	mesh_hwmp.o \
	mesh_sync.o \
	mesh_ps.o

CFLAGS_trace.o := -I$(src)

ccflags-y += -D__CHECK_ENDIAN__ -DDEBUG
