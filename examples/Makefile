CAMLP4=
OCAMLC_OPTS=-w '@f@p@u@s@40'
OCAMLOPT_OPTS=$(OCAMLC_OPTS)

NON_LIB_MODULES=$(wildcard *.ml)

EXTERNAL_DEPS=

BYTE_TARGETS=$(NON_LIB_MODULES:%.ml=%.byte_ex)
NATIVE_TARGETS=$(NON_LIB_MODULES:%.ml=%.native_ex)

.PHONY: all native-code byte-code test clean

all: native-code byte-code

# Dependencies
include ../lib/Ocamlrules.mk.in
