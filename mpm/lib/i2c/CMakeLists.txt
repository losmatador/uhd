#
# Copyright 2018 Ettus Research, a National Instruments Company
#
# SPDX-License-Identifier: GPL-3.0-or-later
#
SET(I2C_SOURCES
    ${CMAKE_CURRENT_SOURCE_DIR}/i2cdev_iface.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/i2c_regs_iface.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/i2cdev.c
)

USRP_PERIPHS_ADD_OBJECT(i2c ${I2C_SOURCES})
