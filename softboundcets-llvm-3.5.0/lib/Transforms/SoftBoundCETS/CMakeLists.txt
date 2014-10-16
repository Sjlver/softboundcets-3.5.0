add_llvm_library(LLVMSoftBoundCETS
    FixByValAttributesPass.cpp
    InitializeSoftBoundCETS.cpp
    InitializeSoftBoundCETSMPX.cpp
    InitializeSoftBoundMPX.cpp
    SoftBoundCETS.cpp
    SoftBoundCETSMPX.cpp
    SoftBoundMPX.cpp
  )

add_dependencies(LLVMSoftBoundCETS intrinsics_gen)
