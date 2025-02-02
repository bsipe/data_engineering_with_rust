# Makefile for Rust project

# Variables
CARGO := cargo
PROJECT_NAME := my_rust_project

# Targets
.PHONY: all format build test run clean

all: format build test run

format:
	@$(CARGO) fmt --all

build:
	@$(CARGO) build

test:
	@$(CARGO) test

run:
	@$(CARGO) run

clean:
	@$(CARGO) clean