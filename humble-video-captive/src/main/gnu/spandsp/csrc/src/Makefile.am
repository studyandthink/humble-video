##
## SpanDSP - a series of DSP components for telephony
##
## Makefile.am - Process this file with automake to produce Makefile.in
##
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU Lesser General Public License version 2.1,
## as published by the Free Software Foundation.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU Lesser General Public License for more details.
##
## You should have received a copy of the GNU Lesser General Public
## License along with this program; if not, write to the Free Software
## Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

AM_CFLAGS = $(COMP_VENDOR_CFLAGS)
AM_LDFLAGS = $(COMP_VENDOR_LDFLAGS)

MAINTAINERCLEANFILES = Makefile.in

DISTCLEANFILES = $(srcdir)/at_interpreter_dictionary.h \
                 $(srcdir)/math_fixed_tables.h \
                 $(srcdir)/v17_v32bis_rx_fixed_rrc.h \
                 $(srcdir)/v17_v32bis_rx_floating_rrc.h \
                 $(srcdir)/v17_v32bis_tx_fixed_rrc.h \
                 $(srcdir)/v17_v32bis_tx_floating_rrc.h \
                 $(srcdir)/v22bis_rx_1200_fixed_rrc.h \
                 $(srcdir)/v22bis_rx_2400_fixed_rrc.h \
                 $(srcdir)/v22bis_rx_1200_floating_rrc.h \
                 $(srcdir)/v22bis_rx_2400_floating_rrc.h \
                 $(srcdir)/v22bis_tx_fixed_rrc.h \
                 $(srcdir)/v22bis_tx_floating_rrc.h \
                 $(srcdir)/v27ter_rx_2400_fixed_rrc.h \
                 $(srcdir)/v27ter_rx_4800_fixed_rrc.h \
                 $(srcdir)/v27ter_rx_2400_floating_rrc.h \
                 $(srcdir)/v27ter_rx_4800_floating_rrc.h \
                 $(srcdir)/v27ter_tx_2400_fixed_rrc.h \
                 $(srcdir)/v27ter_tx_4800_fixed_rrc.h \
                 $(srcdir)/v27ter_tx_2400_floating_rrc.h \
                 $(srcdir)/v27ter_tx_4800_floating_rrc.h \
                 $(srcdir)/v29rx_fixed_rrc.h \
                 $(srcdir)/v29rx_floating_rrc.h \
                 $(srcdir)/v29tx_fixed_rrc.h \
                 $(srcdir)/v29tx_floating_rrc.h

EXTRA_DIST = floating_fudge.h \
             libspandsp.dsp \
             libspandsp.2005.sln \
             libspandsp.2008.sln \
             libspandsp.2005.vcproj \
             libspandsp.2008.vcproj \
             libtiff.2005.vcproj \
             libtiff.2008.vcproj \
             filter_tools.c \
             make_at_dictionary.c \
             make_math_fixed_tables.c \
             make_modem_filter.c \
             msvc/config.h \
             msvc/Download_TIFF.2005.vcproj \
             msvc/Download_TIFF.2008.vcproj \
             msvc/getopt.c \
             msvc/gettimeofday.c \
             msvc/inttypes.h \
             msvc/make_at_dictionary.2005.vcproj \
             msvc/make_at_dictionary.2008.vcproj \
             msvc/make_modem_filter.2005.vcproj \
             msvc/make_modem_filter.2008.vcproj \
             msvc/msvcproj.head \
             msvc/msvcproj.foot \
             msvc/spandsp.h \
             msvc/tgmath.h \
             msvc/tiff/cleancount \
             msvc/unistd.h \
             msvc/util.vbs \
             msvc/vc8proj.foot \
             msvc/vc8proj.head \
             msvc/vc9proj.foot \
             msvc/vc9proj.head \
             msvc/sys/time.h \
             spandsp/private/README \
             spandsp/version.h.in

AM_CPPFLAGS = -I$(top_builddir)

lib_LTLIBRARIES = libspandsp.la

libspandsp_la_SOURCES = ademco_contactid.c \
                        adsi.c \
                        async.c \
                        at_interpreter.c \
                        awgn.c \
                        bell_r2_mf.c \
                        bert.c \
                        bit_operations.c \
                        bitstream.c \
                        complex_filters.c \
                        complex_vector_float.c \
                        complex_vector_int.c \
                        crc.c \
                        dds_float.c \
                        dds_int.c \
                        dtmf.c \
                        echo.c \
                        fax.c \
                        fax_modems.c \
                        fsk.c \
                        g711.c \
                        g722.c \
                        g726.c \
                        gsm0610_decode.c \
                        gsm0610_encode.c \
                        gsm0610_long_term.c \
                        gsm0610_lpc.c \
                        gsm0610_preprocess.c \
                        gsm0610_rpe.c \
                        gsm0610_short_term.c \
                        hdlc.c \
                        ima_adpcm.c \
                        image_translate.c \
                        logging.c \
                        lpc10_analyse.c \
                        lpc10_decode.c \
                        lpc10_encode.c \
                        lpc10_placev.c \
                        lpc10_voicing.c \
                        math_fixed.c \
                        modem_echo.c \
                        modem_connect_tones.c \
                        noise.c \
                        oki_adpcm.c \
                        playout.c \
                        plc.c \
                        power_meter.c \
                        queue.c \
                        schedule.c \
                        sig_tone.c \
                        silence_gen.c \
                        super_tone_rx.c \
                        super_tone_tx.c \
                        swept_tone.c \
                        t4_rx.c \
                        t4_tx.c \
                        t30.c \
                        t30_api.c \
                        t30_logging.c \
                        t31.c \
                        t35.c \
                        t38_core.c \
                        t38_gateway.c \
                        t38_non_ecm_buffer.c \
                        t38_terminal.c \
                        testcpuid.c \
                        time_scale.c \
                        timezone.c \
                        tone_detect.c \
                        tone_generate.c \
                        v17rx.c \
                        v17tx.c \
                        v18.c \
                        v22bis_rx.c \
                        v22bis_tx.c \
                        v27ter_rx.c \
                        v27ter_tx.c \
                        v29rx.c \
                        v29tx.c \
                        v42.c \
                        v42bis.c \
                        v8.c \
                        vector_float.c \
                        vector_int.c

libspandsp_la_LDFLAGS = -version-info @SPANDSP_LT_CURRENT@:@SPANDSP_LT_REVISION@:@SPANDSP_LT_AGE@ $(COMP_VENDOR_LDFLAGS)

nobase_include_HEADERS = spandsp/ademco_contactid.h \
                         spandsp/adsi.h \
                         spandsp/async.h \
                         spandsp/arctan2.h \
                         spandsp/at_interpreter.h \
                         spandsp/awgn.h \
                         spandsp/bell_r2_mf.h \
                         spandsp/bert.h \
                         spandsp/biquad.h \
                         spandsp/bit_operations.h \
                         spandsp/bitstream.h \
                         spandsp/crc.h \
                         spandsp/complex.h \
                         spandsp/complex_filters.h \
                         spandsp/complex_vector_float.h \
                         spandsp/complex_vector_int.h \
                         spandsp/dc_restore.h \
                         spandsp/dds.h \
                         spandsp/dtmf.h \
                         spandsp/echo.h \
                         spandsp/fast_convert.h \
                         spandsp/fax.h \
                         spandsp/fax_modems.h \
                         spandsp/fir.h \
                         spandsp/fsk.h \
                         spandsp/g168models.h \
                         spandsp/g711.h \
                         spandsp/g722.h \
                         spandsp/g726.h \
                         spandsp/gsm0610.h \
                         spandsp/hdlc.h \
                         spandsp/ima_adpcm.h \
                         spandsp/image_translate.h \
                         spandsp/logging.h \
                         spandsp/lpc10.h \
                         spandsp/math_fixed.h \
                         spandsp/modem_echo.h \
                         spandsp/modem_connect_tones.h \
                         spandsp/noise.h \
                         spandsp/oki_adpcm.h \
                         spandsp/playout.h \
                         spandsp/plc.h \
                         spandsp/power_meter.h \
                         spandsp/queue.h \
                         spandsp/saturated.h \
                         spandsp/schedule.h \
                         spandsp/stdbool.h \
                         spandsp/sig_tone.h \
                         spandsp/silence_gen.h \
                         spandsp/super_tone_rx.h \
                         spandsp/super_tone_tx.h \
                         spandsp/swept_tone.h \
                         spandsp/t30.h \
                         spandsp/t30_api.h \
                         spandsp/t30_fcf.h \
                         spandsp/t30_logging.h \
                         spandsp/t31.h \
                         spandsp/t35.h \
                         spandsp/t38_core.h \
                         spandsp/t38_gateway.h \
                         spandsp/t38_non_ecm_buffer.h \
                         spandsp/t38_terminal.h \
                         spandsp/t4_rx.h \
                         spandsp/t4_tx.h \
                         spandsp/t4_t6_decode.h \
                         spandsp/t4_t6_encode.h \
                         spandsp/telephony.h \
                         spandsp/time_scale.h \
                         spandsp/timezone.h \
                         spandsp/timing.h \
                         spandsp/tone_detect.h \
                         spandsp/tone_generate.h \
                         spandsp/v17rx.h \
                         spandsp/v17tx.h \
                         spandsp/v18.h \
                         spandsp/v22bis.h \
                         spandsp/v27ter_rx.h \
                         spandsp/v27ter_tx.h \
                         spandsp/v29rx.h \
                         spandsp/v29tx.h \
                         spandsp/v42.h \
                         spandsp/v42bis.h \
                         spandsp/v8.h \
                         spandsp/vector_float.h \
                         spandsp/vector_int.h \
                         spandsp/version.h \
                         spandsp/private/ademco_contactid.h \
                         spandsp/private/adsi.h \
                         spandsp/private/async.h \
                         spandsp/private/at_interpreter.h \
                         spandsp/private/awgn.h \
                         spandsp/private/bell_r2_mf.h \
                         spandsp/private/bert.h \
                         spandsp/private/bitstream.h \
                         spandsp/private/dtmf.h \
                         spandsp/private/echo.h \
                         spandsp/private/fax.h \
                         spandsp/private/fax_modems.h \
                         spandsp/private/fsk.h \
                         spandsp/private/g711.h \
                         spandsp/private/g722.h \
                         spandsp/private/g726.h \
                         spandsp/private/gsm0610.h \
                         spandsp/private/hdlc.h \
                         spandsp/private/ima_adpcm.h \
                         spandsp/private/image_translate.h \
                         spandsp/private/logging.h \
                         spandsp/private/lpc10.h \
                         spandsp/private/modem_connect_tones.h \
                         spandsp/private/modem_echo.h \
                         spandsp/private/noise.h \
                         spandsp/private/oki_adpcm.h \
                         spandsp/private/queue.h \
                         spandsp/private/schedule.h \
                         spandsp/private/sig_tone.h \
                         spandsp/private/silence_gen.h \
                         spandsp/private/super_tone_rx.h \
                         spandsp/private/super_tone_tx.h \
                         spandsp/private/swept_tone.h \
                         spandsp/private/t30.h \
                         spandsp/private/t30_dis_dtc_dcs_bits.h \
                         spandsp/private/t31.h \
                         spandsp/private/t38_core.h \
                         spandsp/private/t38_gateway.h \
                         spandsp/private/t38_non_ecm_buffer.h \
                         spandsp/private/t38_terminal.h \
                         spandsp/private/t4_rx.h \
                         spandsp/private/t4_tx.h \
                         spandsp/private/t4_t6_decode.h \
                         spandsp/private/t4_t6_encode.h \
                         spandsp/private/time_scale.h \
                         spandsp/private/timezone.h \
                         spandsp/private/tone_detect.h \
                         spandsp/private/tone_generate.h \
                         spandsp/private/v17rx.h \
                         spandsp/private/v17tx.h \
                         spandsp/private/v18.h \
                         spandsp/private/v22bis.h \
                         spandsp/private/v27ter_rx.h \
                         spandsp/private/v27ter_tx.h \
                         spandsp/private/v29rx.h \
                         spandsp/private/v29tx.h \
                         spandsp/private/v42.h \
                         spandsp/private/v42bis.h \
                         spandsp/private/v8.h \
                         spandsp/expose.h

nodist_include_HEADERS = spandsp.h

noinst_HEADERS = cielab_luts.h \
                 faxfont.h \
                 filter_tools.h \
                 gsm0610_local.h \
                 lpc10_encdecs.h \
                 mmx_sse_decs.h \
                 t30_local.h \
                 t4_t6_decode_states.h \
                 v17_v32bis_rx_constellation_maps.h \
                 v17_v32bis_tx_constellation_maps.h \
                 v29tx_constellation_maps.h

make_at_dictionary$(EXEEXT): $(top_srcdir)/src/make_at_dictionary.c
	$(CC_FOR_BUILD) -o make_at_dictionary$(EXEEXT) $(top_srcdir)/src/make_at_dictionary.c  -DHAVE_CONFIG_H -I$(top_builddir)/src

make_math_fixed_tables$(EXEEXT): $(top_srcdir)/src/make_math_fixed_tables.c
	$(CC_FOR_BUILD) -o make_math_fixed_tables$(EXEEXT) $(top_srcdir)/src/make_math_fixed_tables.c  -DHAVE_CONFIG_H -I$(top_builddir)/src -lm

make_modem_filter$(EXEEXT): $(top_srcdir)/src/make_modem_filter.c $(top_srcdir)/src/filter_tools.c
	$(CC_FOR_BUILD) -o make_modem_filter$(EXEEXT) $(top_srcdir)/src/make_modem_filter.c $(top_srcdir)/src/filter_tools.c -DHAVE_CONFIG_H -I$(top_builddir)/src -lm

# We need to run make_at_dictionary, so it generates the
# at_interpreter_dictionary.h file

at_interpreter.$(OBJEXT): at_interpreter_dictionary.h

at_interpreter.lo: at_interpreter_dictionary.h

at_interpreter_dictionary.h: make_at_dictionary$(EXEEXT)
	./make_at_dictionary$(EXEEXT) >at_interpreter_dictionary.h

math_fixed.$(OBJEXT): math_fixed_tables.h

math_fixed.lo: math_fixed_tables.h

math_fixed_tables.h: make_math_fixed_tables$(EXEEXT)
	./make_math_fixed_tables$(EXEEXT) >math_fixed_tables.h

t4_rx.$(OBJEXT): spandsp/version.h

t4_rx.lo: spandsp/version.h

V17_V32BIS_RX_INCL = v17_v32bis_rx_fixed_rrc.h \
                     v17_v32bis_rx_floating_rrc.h

v17rx.$(OBJEXT): ${V17_V32BIS_RX_INCL}

v17rx.lo: ${V17_V32BIS_RX_INCL}

v17_v32bis_rx_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.17 -i -r >v17_v32bis_rx_fixed_rrc.h

v17_v32bis_rx_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.17 -r >v17_v32bis_rx_floating_rrc.h

V17_V32BIS_TX_INCL = v17_v32bis_tx_fixed_rrc.h \
                     v17_v32bis_tx_floating_rrc.h

v17tx.$(OBJEXT): ${V17_V32BIS_TX_INCL}

v17tx.lo: ${V17_V32BIS_TX_INCL}

v17_v32bis_tx_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.17 -i -t >v17_v32bis_tx_fixed_rrc.h

v17_v32bis_tx_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.17 -t >v17_v32bis_tx_floating_rrc.h

V22BIS_RX_INCL = v22bis_rx_1200_fixed_rrc.h \
                 v22bis_rx_2400_fixed_rrc.h \
                 v22bis_rx_1200_floating_rrc.h \
                 v22bis_rx_2400_floating_rrc.h

v22bis_rx.$(OBJEXT): ${V22BIS_RX_INCL}

v22bis_rx.lo: ${V22BIS_RX_INCL}

v22bis_rx_1200_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis1200 -i -r >v22bis_rx_1200_fixed_rrc.h

v22bis_rx_2400_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis2400 -i -r >v22bis_rx_2400_fixed_rrc.h

v22bis_rx_1200_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis1200 -r >v22bis_rx_1200_floating_rrc.h

v22bis_rx_2400_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis2400 -r >v22bis_rx_2400_floating_rrc.h

V22BIS_TX_INCL = v22bis_tx_fixed_rrc.h \
                 v22bis_tx_floating_rrc.h

v22bis_tx.$(OBJEXT): ${V22BIS_TX_INCL}

v22bis_tx.lo: ${V22BIS_TX_INCL}

v22bis_tx_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis -i -t >v22bis_tx_fixed_rrc.h

v22bis_tx_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.22bis -t >v22bis_tx_floating_rrc.h

V27_RX_INCL = v27ter_rx_2400_fixed_rrc.h \
              v27ter_rx_4800_fixed_rrc.h \
              v27ter_rx_2400_floating_rrc.h \
              v27ter_rx_4800_floating_rrc.h

v27ter_rx.$(OBJEXT): ${V27_RX_INCL}

v27ter_rx.lo: ${V27_RX_INCL}

v27ter_rx_2400_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter2400 -i -r >v27ter_rx_2400_fixed_rrc.h

v27ter_rx_4800_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter4800 -i -r >v27ter_rx_4800_fixed_rrc.h

v27ter_rx_2400_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter2400 -r >v27ter_rx_2400_floating_rrc.h

v27ter_rx_4800_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter4800 -r >v27ter_rx_4800_floating_rrc.h

V27TER_TX_INCL = v27ter_tx_2400_fixed_rrc.h \
                 v27ter_tx_4800_fixed_rrc.h \
                 v27ter_tx_2400_floating_rrc.h \
                 v27ter_tx_4800_floating_rrc.h

v27ter_tx_.$(OBJEXT): ${V27TER_TX_INCL}

v27ter_tx.lo: ${V27TER_TX_INCL}

v27ter_tx_2400_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter2400 -i -t >v27ter_tx_2400_fixed_rrc.h

v27ter_tx_4800_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter4800 -i -t >v27ter_tx_4800_fixed_rrc.h

v27ter_tx_2400_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter2400 -t >v27ter_tx_2400_floating_rrc.h

v27ter_tx_4800_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.27ter4800 -t >v27ter_tx_4800_floating_rrc.h

V29_RX_INCL = v29rx_fixed_rrc.h \
              v29rx_floating_rrc.h

v29rx.$(OBJEXT): ${V29_RX_INCL}

v29rx.lo: ${V29_RX_INCL}

v29rx_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.29 -i -r >v29rx_fixed_rrc.h

v29rx_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.29 -r >v29rx_floating_rrc.h

V29_TX_INCL = v29tx_fixed_rrc.h \
              v29tx_floating_rrc.h

v29tx.$(OBJEXT): ${V29_TX_INCL}

v29tx.lo: ${V29_TX_INCL}

v29tx_fixed_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.29 -i -t >v29tx_fixed_rrc.h

v29tx_floating_rrc.h: make_modem_filter$(EXEEXT)
	./make_modem_filter$(EXEEXT) -m V.29 -t >v29tx_floating_rrc.h

DSP = libspandsp.dsp
VCPROJ8 = libspandsp.2005.vcproj
VCPROJ9 = libspandsp.2008.vcproj

WIN32SOURCES = $(libspandsp_la_SOURCES) .\\msvc\\gettimeofday.c
WIN32HEADERS = $(nobase_include_HEADERS) spandsp.h

DSPOUT = | awk '{printf("%s\r\n", $$0)}' >> $(DSP)
VCPROJOUT8 = | awk '{printf("%s\r\n", $$0)}' >> $(VCPROJ8)
VCPROJOUT9 = | awk '{printf("%s\r\n", $$0)}' >> $(VCPROJ9)

$(DSP): msvc/msvcproj.head msvc/msvcproj.foot Makefile.am
	echo "creating $(DSP)"
	@(cp $(srcdir)/msvc/msvcproj.head $(DSP); \
	echo "# Begin Group \"Source Files\"" $(DSPOUT); \
	for file in $(WIN32SOURCES); do \
	echo "# Begin Source File" $(DSPOUT); \
	echo "" $(DSPOUT); \
	echo "SOURCE=.\\"$$file $(DSPOUT); \
	echo "# End Source File" $(DSPOUT); \
	done; \
	echo "# End Group" $(DSPOUT); \
	echo "# Begin Group \"Header Files\"" $(DSPOUT); \
	for file in $(WIN32HEADERS); do \
	echo "# Begin Source File" $(DSPOUT); \
	echo "" $(DSPOUT); \
	echo "SOURCE=.\\"$$file $(DSPOUT); \
	echo "# End Source File" $(DSPOUT); \
	done; \
	echo "# End Group" $(DSPOUT); \
	cat $(srcdir)/msvc/msvcproj.foot $(DSPOUT) )

$(VCPROJ8): msvc/vc8proj.head msvc/vc8proj.foot Makefile.am
	echo "creating $(VCPROJ8)"
	@(cp $(srcdir)/msvc/vc8proj.head $(VCPROJ8); \
	for file in $(WIN32SOURCES); do \
		echo "<File RelativePath=\""$$file"\"></File>" $(VCPROJOUT8); \
	done; \
	echo "</Filter><Filter  Name=\"Header Files\">" $(VCPROJOUT8); \
	for file in $(WIN32HEADERS); do \
		echo "<File RelativePath=\""$$file"\"></File>" $(VCPROJOUT8); \
	done; \
	cat $(srcdir)/msvc/vc8proj.foot $(VCPROJOUT8) )

$(VCPROJ9): msvc/vc9proj.head msvc/vc9proj.foot Makefile.am
	echo "creating $(VCPROJ9)"
	@(cp $(srcdir)/msvc/vc9proj.head $(VCPROJ9); \
	for file in $(WIN32SOURCES); do \
		echo "<File RelativePath=\""$$file"\"></File>" $(VCPROJOUT9); \
	done; \
	echo "</Filter><Filter  Name=\"Header Files\">" $(VCPROJOUT9); \
	for file in $(WIN32HEADERS); do \
		echo "<File RelativePath=\""$$file"\"></File>" $(VCPROJOUT9); \
	done; \
	cat $(srcdir)/msvc/vc9proj.foot $(VCPROJOUT9) )

$(srcdir)/msvc/spandsp.h: spandsp.h.in
	echo "creating $(srcdir)/msvc/spandsp.h"
	@sed -e "s/#define _SPANDSP_H_/#define _SPANDSP_H_\n\n#define __inline__ __inline\n#pragma warning(disable:4200)/" \
	     -e "s/\@SPANDSP_USE_FIXED_POINT\@/#undef SPANDSP_USE_FIXED_POINT/" \
	     -e "s/\@SPANDSP_MISALIGNED_ACCESS_FAILS\@/#undef SPANDSP_MISALIGNED_ACCESS_FAILS/" \
	     -e "s/\@SPANDSP_USE_EXPORT_CAPABILITY\@/#define SPANDSP_USE_EXPORT_CAPABILITY 1/" \
	     -e "s/\@INSERT_INTTYPES_HEADER\@/#include <msvc\/inttypes.h>/" \
	     -e "s/\@INSERT_MATH_HEADER\@/#include <math.h>/" $(srcdir)/spandsp.h.in > $(srcdir)/msvc/spandsp.h

dist-hook: spandsp/version.h

spandsp/version.h:
	mkdir -p $(@D)
	NOWDATE=`date --utc +"%Y%m%d"` ; \
	NOWTIME=`date --utc +"%H%M%S"` ; \
	sed 's/$$SPANDSP_RELEASE_DATE/'$$NOWDATE'/;s/$$SPANDSP_RELEASE_TIME/'$$NOWTIME'/' \
		<$(srcdir)/spandsp/version.h.in >$@
