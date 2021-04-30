# pihole-unbound

Es wird docker + docker-compose benötigt, und das Docker macvlan Netzwerk verwendet.
Weiterhin wird der DNS Cache unbound anstand des DNS Upstream Server verwendet (reduziert die DNS Anfragen, was sich positiv auf den Datenschutz auswirkt) weiterhin werden bereits besuchte Domain viel schneller aufgelöst.
