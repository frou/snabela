CAMLP4=

OCAMLDEP_OPTS=
OCAMLC_OPTS=$(OCAMLDEP_OPTS) -w '@f@p@u@s@40'
OCAMLOPT_OPTS=$(OCAMLDEP_OPTS)

LIB_MODULES=
NON_LIB_MODULES=

BYTE_TARGETS=
NATIVE_TARGETS=

.PHONY: all test install

all: native-code byte-code

test:

install: all

# Dependencies
include ../Ocamlrules.mk.in
