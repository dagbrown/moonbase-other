
  OPTS+=" -DwxWidgets_CONFIG_EXECUTABLE=/usr/bin/wx-config" &&
#  CXXFLAGS+=" -Wall -DNDEBUG" &&
  default_cmake_build &&

    # Desktop menu entry
  cat > ${MODULE}.desktop << EOF  &&
[Desktop Entry]
Type=Application
Name=wxMaxima
Comment=A computer algebra system
Exec=/usr/bin/wxmaxima
Icon=/usr/share/wxMaxima/wxmaxima.png
Categories=Science;Application;;
EOF

  install -D -m644 ${MODULE}.desktop /usr/share/applications/${MODULE}.desktop
