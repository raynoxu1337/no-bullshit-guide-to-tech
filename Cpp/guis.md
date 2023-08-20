# GUI tools overview
You can have two types of GUI's obviously. Immediate mode and the normal one, whatever it's called. Immediate mode is rendering every frame in open GL, direct X or whatever. If you're using c++ probably you want speed so probably all those browser JS gui's are out of the question.

# Immediate mode
## ImGUI
Best option it to use DearIMGui, you can use themes for it and use ImPlot, which are great addons.
ImGUI is awesome and supports every rendering API and yuo can export it to WASM with emscripten.

*[ImGui Themes](https://github.com/Patitotective/ImThemes)
*[ImGui](https://github.com/ocornut/imgui)
*[ImPlot](https://github.com/epezent/implot)

## SDL
You can can use SDL or similar libs, with an ability to export to WASM with emscripten if ever needed. IDK why you'd use SDL tho when you can use ImGUI.
# The old way
So there is shitton of frameworks. Qt is industry standard. But wxWidgets is free and doesnt have stupid licences, so use Wx, it also has Glade, an editor for your GUI's.
*[WxWidgets](https://github.com/wxWidgets)
*[WxGlade](https://wxglade.sourceforge.net/)