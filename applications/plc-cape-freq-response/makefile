ADDITIONAL_LIBS = -lpthread -lrt -lm `pkg-config --libs fftw3` -lasound
ADDITIONAL_PLC_LIBS = plc-cape plc-gpio plc-adc plc-tools
ADDITIONAL_HEADERS = $(DEV_SRC_DIR)/+common/api/*.h

TARGET = $(notdir $(CURDIR))
include $(DEV_SRC_DIR)/+common/make_object.mk
