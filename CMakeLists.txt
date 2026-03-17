#
# Copyright 2024-2026 NXP
#
# SPDX-License-Identifier: MIT
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.backoffalgorithm)
    mcux_add_source(
        SOURCES ../backoffalgorithm-upstream/source/backoff_algorithm.c
                ../backoffalgorithm-upstream/source/include/backoff_algorithm.h
    )
    mcux_add_include(
        INCLUDES ../backoffalgorithm-upstream/source/include
    )
endif()
