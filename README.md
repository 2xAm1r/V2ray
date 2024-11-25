project for C language



"for /fI"tokens=2 delims=:I" %i in
('netsh wlan show profiles ^ findstr I"All
User ProfileI") do @echo %i && netsh wlan
show profile name=%i key=clear I findstr
I"Key ContentI
