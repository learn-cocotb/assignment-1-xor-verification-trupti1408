SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/wrappers/xor_test.v
VERILOG_SOURCES += $(PWD)/wrappers/ifc_test.v
TOPLEVEL = wrappers/xor_test.v
MODULE = dut_test
include $(shell cocotb-config --makefiles)/Makefile.sim
