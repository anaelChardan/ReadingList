#=== Reading List helper ===

# Styles
YELLOW=$(shell echo "\033[00;33m")
RED=$(shell echo "\033[00;31m")
RESTORE=$(shell echo "\033[0m")

CURRENT_DIR := $(shell pwd)

.PHONY: list
list:
	@echo ""
	@echo "ReadingList available targets:"
	@echo ""
	@echo "  $(YELLOW)install(RESTORE)             > run pre commit stuff"

.PHONY: install
install:
	docker-compose up -d
	docker-compose exec fpm composer install
