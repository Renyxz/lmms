INCLUDE(BuildPlugin)

BUILD_PLUGIN(bassbooster BassBooster.cpp BassBoosterControls.cpp BassBoosterControlDialog.cpp MOCFILES BassBoosterControls.h BassBoosterControlDialog.h EMBEDDED_RESOURCES "${CMAKE_CURRENT_SOURCE_DIR}/*.png")
