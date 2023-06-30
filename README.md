# note
Note

```
# Written in tcsh

# Send terminal to other host (sender -> receiver):
setenv HOSTNAME_of_receiver <Host name of receiver of the terminal>
( setenv DISPLAY ${HOSTNAME_of_receiver}:0 ; xterm & )

# You can also send other types of terminals
# Mate terminal
( setenv DISPLAY ${HOSTNAME_of_receiver}:0 ; mate-terminal & )

#  Konsole (KDE terminal)
( setenv DISPLAY ${HOSTNAME_of_receiver}:0 ; konsole & )

# Gnome terminal
( setenv DISPLAY ${HOSTNAME_of_receiver}:0 ; gnome-terminal & )

```
