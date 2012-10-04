if ENABLE_VAPIGEN
-include $(VAPIGEN_MAKEFILE)

gst-rtsp-server-1.0.vapi: $(top_srcdir)/gst/rtsp-server/GstRtspServer-1.0.gir

VAPIGEN_VAPIS = gst-rtsp-server-1.0.vapi

gst_rtsp_server_1_0_vapi_DEPS = gstreamer-1.0 gio-2.0
gst_rtsp_server_1_0_vapi_FILES = $(top_srcdir)/gst/rtsp-server/GstRtspServer-1.0.gir
gst_rtsp_server_1_0_vapi_METADATADIRS = $(srcdir)

vapidir = $(datadir)/vala/vapi
vapi_DATA = $(VAPIGEN_VAPIS) $(VAPIGEN_VAPIS:.vapi=.deps)
endif

EXTRA_DIST = gst-rtsp-server-1.0.vapi gst-rtsp-server-1.0.deps GstRtspServer-1.0.metadata
