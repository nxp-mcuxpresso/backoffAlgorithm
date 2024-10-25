#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.backoffalgorithm)
    mcux_add_source(
        SOURCES source/backoff_algorithm.c source/include/backoff_algorithm.h
    )
    mcux_add_include(
        INCLUDES source/include
    )
endif()
