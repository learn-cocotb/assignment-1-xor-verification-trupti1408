SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/wrappers/xor_test.v
VERILOG_SOURCES += $(PWD)/wrappers/ifc_test.v
VERILOG_SOURCES += $(PWD)/../hdl/ifc_or.v
VERILOG_SOURCES += $(PWD)/../hdl/FIFO1.v
VERILOG_SOURCES += $(PWD)/../hdl/FIFO2.v
TOPLEVEL = dut
MODULE = dut_test
include $(shell cocotb-config --makefiles)/Makefile.sim
