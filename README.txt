
# Reaver-wpc-maker-and-pingen-3W-Offline-

Reaver wpc session file maker, with MAC numers and 3W Offline pingen algorithms.

Primally we filter the network.
wash -i <iface>

Enter accordingly -> Choose vendor from the list (multiple vendors can be used).
<BSSID> <Vendor> <Vendor>
exaple:
1A:2B:3C:4D:5E:6F Realtek D-Link
  
Opened 3W Offline browser -> CLICK Get All and copy.

Optional choose:
Generate digits method -> h/c (hashcat, or crunch reverse method)
Subtract identical digits -> y/n (0000-1111-etc. 000-111-etc.)

* 2.0 plus modes added !!!
Specify location a previous .wpc session file for subtraction. -> y/n
example:
/var/lib/reaver/XXXXXXXXXXXX.wpc

Multiple MACs can be developed one after the other.

---------------------------------------------------
Install:

https://github.com/OutsiderLost/Reaver-wpc-maker-pingen

cd Reaver-wpc-maker-pingen

(optional unzip)
unzip 3W_wps-pin_offline.zip && rm 3W_wps-pin_offline.zip && chmod +x *.sh
(if don't work "FIRE", just use "OTHER")

(run)
./wpc-maker.sh
(or)
./wpc-maker2.sh
---------------------------------------------------
