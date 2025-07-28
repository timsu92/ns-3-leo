build_lib_example(
  NAME leo-orbit
  SOURCE_FILES leo-circular-orbit-tracing-example.cc
  LIBRARIES_TO_LINK
    ${libcore}
    ${libleo}
    ${libmobility}
)

build_lib_example(
  NAME leo-delay
  SOURCE_FILES leo-delay-tracing-example.cc
  LIBRARIES_TO_LINK
    ${libcore}
    ${libleo}
    ${libmobility}
    ${libaodv}
    ${libepidemic-routing}
)

build_lib_example(
  NAME leo-bulk-send
  SOURCE_FILES leo-bulk-send-example.cc
  LIBRARIES_TO_LINK
    ${libcore}
    ${libleo}
    ${libmobility}
    ${libaodv}
    ${libepidemic-routing}
)
