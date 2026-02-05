# 01_foundation - Basic raytracing foundation
#
# This sample demonstrates the basic setup for Vulkan raytracing without any
# additional common sources or special shader requirements.

# Basic setup without RT common sources (foundation sample)
setup_rt_tutorial_sample(
    USE_FOUNDATION_SHADER
    EXTRA_SHADER_INCLUDES 
        ${TUTO_DIR} 
        ${CMAKE_CURRENT_LIST_DIR}/shaders
    EXTRA_COPY_DIRECTORIES 
        ${COMMON_DIR}/shaders
)
