# Generated from qsvgrenderer.pro.

#####################################################################
## tst_qsvgrenderer Test:
#####################################################################

qt_add_test(tst_qsvgrenderer
    SOURCES
        tst_qsvgrenderer.cpp
    DEFINES
        SRCDIR=\\\"${CMAKE_CURRENT_SOURCE_DIR}/\\\"
    PUBLIC_LIBRARIES
        Qt::Gui
        Qt::GuiPrivate
        Qt::Svg
        Qt::Widgets
)

# Resources:
set(resources_resource_files
    "heart.svgz"
)

qt_add_resource(tst_qsvgrenderer "resources"
    PREFIX
        "/"
    FILES
        ${resources_resource_files}
)

