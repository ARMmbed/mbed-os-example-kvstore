# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

add_library(gen_config INTERFACE)

# Anybody linking to gen_config needs to include the current source directory
target_include_directories(gen_config
    INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}
)
