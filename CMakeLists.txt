#
# Copyright (c) 2021 Panasonic Industrial Devices Europe GmbH
#
# SPDX-License-Identifier: BSD-3-Clause
#

cmake_minimum_required(VERSION 3.20.0)

find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(immunity_firmware)

target_sources(app PRIVATE src/main.c)
