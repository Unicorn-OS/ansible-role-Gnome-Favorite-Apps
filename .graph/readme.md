get(){
#gsettings list-recursively | grep -i favorite-apps

return `gsettings get org.gnome.shell favorite-apps`
}
