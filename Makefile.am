AUTOMAKE_OPTIONS = foreign

ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = bin/neunet

bin_neunet_SOURCES = src/main.c src/nn_algo.c src/nn_objects.c src/nn_fileIO.c src/nn_metrics.c src/nn_args.c src/nn_string.c src/nn_hash.c src/nn_matrix.c include/nn_algo.h include/nn_objects.h include/nn_fileIO.h include/nn_metrics.h include/nn_args.h include/nn_string.h include/nn_limits.h include/nn_hash.h include/nn_matrix.h
bin_neunet_CFLAGS = -I $(srcdir)/include

man_MANS = doc/neunet.1 doc/neunet-learn.1 doc/neunet-solve.1
EXTRA_DIST = $(man_MANS)
