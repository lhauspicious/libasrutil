include $(abs_top_builddir)/src/rules.mk

noinst_PROGRAMS = \
	asrutil_text_translate_test			\
	asrutil_voice_engine_test			\
	asrutil_voice_engine_test_chunked		\
	asrutil_voice_engine_test_seperate		\
	asrutil_voice_engine_test_seperate_en_2_zh 	\
	asrutil_voice_engine_test_seperate_vad		\
	asrutil_voice_engine_test_seperate_vad_chunked	\
	asrutil_voice_engine_test_seperate_zh_2_en
	
AM_CPPFLAGS = -DFUSE_USE_VERSION=26

asrutil_text_translate_test_SOURCES = asrutil_text_translate_test.c
asrutil_text_translate_test_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_SOURCES = asrutil_voice_engine_test.c
asrutil_voice_engine_test_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_chunked_SOURCES = asrutil_voice_engine_test_chunked.c
asrutil_voice_engine_test_chunked_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_seperate_SOURCES = asrutil_voice_engine_test_seperate.c
asrutil_voice_engine_test_seperate_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_seperate_en_2_zh_SOURCES = asrutil_voice_engine_test_seperate_en_2_zh.c
asrutil_voice_engine_test_seperate_en_2_zh_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_seperate_vad_SOURCES = asrutil_voice_engine_test_seperate_vad.c
asrutil_voice_engine_test_seperate_vad_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_seperate_vad_chunked_SOURCES = asrutil_voice_engine_test_seperate_vad_chunked.c
asrutil_voice_engine_test_seperate_vad_chunked_LDADD = $(ASRUTIL_BIN_LDFLAGS)

asrutil_voice_engine_test_seperate_zh_2_en_SOURCES = asrutil_voice_engine_test_seperate_zh_2_en.c
asrutil_voice_engine_test_seperate_zh_2_en_LDADD = $(ASRUTIL_BIN_LDFLAGS)
