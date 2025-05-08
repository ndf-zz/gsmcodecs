# SPDX-License-Identifier: MIT
#
# GSM Codecs - Charmaps
#

JSONMAPS = gsmcharmaps.json
TARGET = ../src/gsmcodecs/charmaps.py
CSVTABLES = *_lock.csv *_shift.csv
CODEGEN = ./codegen
MKCHARMAPS = ./mkcharmaps

.PHONY: all
all: $(TARGET)

$(TARGET): $(JSONMAPS) $(CODEGEN)
	$(CODEGEN) $(TARGET)

$(JSONMAPS): $(CSVTABLES) $(MKCHARMAPS)
	$(MKCHARMAPS)

.PHONY: clean
clean:
	-rm -f gsmcharmaps.json
