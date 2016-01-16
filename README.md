# androsmex
a PACE implementation for android smartphones with NFC capabilities. 

# introduction

androsmex is an implementation of the PACE protocol (see BSI TR-03110) for Android phones with NFC support. At this very early Alpha status it is possible to perform PACE with the new German ID card (neuer Personalausweis) and log the communication.

# known issues

The new German ID card uses a lot of cryptographic algorithms which need sometimes more energy than the RF field of the android phone can support. So the communication aborts sometimes. Just try different positions for the card.

# requirements

androsmex uses <a href="https://github.com/rtyley/spongycastle">spongycastle</a> instead of bouncycastle

The protocols PACE, TA and CA also are implemented in the project <a href="https://github.com/tsenger/animamea">animamea</a>. New features will be first implemented in animamea an then later be ported to androsmex. 
