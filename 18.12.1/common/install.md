wget http://downloads.asterisk.org/pub/telephony/asterisk/asterisk-18.12.1.tar.gz -O - | gzip -dc | tar -xvf -

./contrib/scripts/live_ast configure --with-jansson-bundled

./contrib/scripts/live_ast install

./contrib/scripts/live_ast run -fc
