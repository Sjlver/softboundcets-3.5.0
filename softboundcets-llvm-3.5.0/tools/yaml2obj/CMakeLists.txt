set(LLVM_LINK_COMPONENTS
  MC
  Object
  Support
  )

add_llvm_utility(yaml2obj
  yaml2obj.cpp
  yaml2coff.cpp
  yaml2elf.cpp
  )
