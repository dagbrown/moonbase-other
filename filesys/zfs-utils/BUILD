OPTS+=" --with-linux=$BUILD_DIRECTORY/linux \
        --with-linux-obj=$BUILD_DIRECTORY/linux \
        --with-config=user \
        --disable-sysvinit \
        --disable-static"

default_config &&
make &&
make DESTDIR=$SOURCE_DIRECTORY/__pkg install &&
prepare_install &&
cp -rfv --remove-destination $SOURCE_DIRECTORY/__pkg/* /
