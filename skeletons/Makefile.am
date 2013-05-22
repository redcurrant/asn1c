
SUBDIRS = standard-modules tests

dist_pkgdata_DATA =				\
		$(srcdir)/*.[ch]		\
		$(srcdir)/file-dependencies

uninstall-local:
	-@echo -n " "
	-rm -f -r $(DESTDIR)$(pkgdatadir)

lib_LTLIBRARIES=libASN1.la

libASN1_la_SOURCES=\
	ANY.c\
	BIT_STRING.c\
	BMPString.c\
	BOOLEAN.c\
	ENUMERATED.c\
	GeneralString.c\
	GeneralizedTime.c\
	GraphicString.c\
	IA5String.c\
	INTEGER.c\
	ISO646String.c\
	NULL.c\
	NativeEnumerated.c\
	NativeInteger.c\
	NativeReal.c\
	NumericString.c\
	OBJECT_IDENTIFIER.c\
	OCTET_STRING.c\
	ObjectDescriptor.c\
	PrintableString.c\
	REAL.c\
	RELATIVE-OID.c\
	T61String.c\
	TeletexString.c\
	UTCTime.c\
	UTF8String.c\
	UniversalString.c\
	VideotexString.c\
	VisibleString.c\
	asn_SEQUENCE_OF.c\
	asn_SET_OF.c\
	asn_codecs_prim.c\
	ber_decoder.c\
	ber_tlv_length.c\
	ber_tlv_tag.c\
	constr_CHOICE.c\
	constr_SEQUENCE.c\
	constr_SEQUENCE_OF.c\
	constr_SET.c\
	constr_SET_OF.c\
	constr_TYPE.c\
	constraints.c\
	der_encoder.c\
	per_decoder.c\
	per_encoder.c\
	per_support.c\
	xer_decoder.c\
	xer_encoder.c\
	xer_support.c

libASN1_la_CFLAGS = -Wall -D_REENTRANT -pedantic $(GLIB_CFLAGS)
libASN1_la_LDFLAGS = $(GLIB_LDFLAGS)

libASN1_la_LIBADD = -lm

