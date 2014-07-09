COMMAND    := linux mac raspbian

LN     := ln -s

.PHONY: usage
usage:
	@echo 'usage: make $(patsubst %,[%],$(COMMAND))'

.PHONY: $(COMMAND)
$(COMMAND):
	@for i in $@/*; do $(LN) "$$i" `basename "$$i"`; done
