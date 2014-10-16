set(LLVM_LINK_COMPONENTS bitreader bitwriter asmparser irreader instrumentation scalaropts objcarcopts ipo vectorize codegen softboundcets )

add_llvm_tool(softboundcets
    main.cpp
  )
