SET(SOURCES components/ui_comp_btn1.c
    components/ui_comp.c
    screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.cpp)

add_library(ui ${SOURCES})
