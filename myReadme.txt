


---------------------------------------------------------
#readall

ebusctl f > output.txt
cat output.txt |  sed -r 's/(^[^ ]*) *([^ ]+) .*$/ebusctl r -c \1 \2 /'


-----------------------------------------------------------
#ebus info

address 00: master #1
address 03: master #11
address 05: slave #1, scanned "MF=Vaillant;ID=VR921;SW=2801;HW=5703"
address 08: slave #11, scanned "MF=Vaillant;ID=HMU00;SW=0517;HW=5103", loaded "vaillant/08.hmu00.csv"
address 0a: slave, scanned "MF=Vaillant;ID=PMW00;SW=0117;HW=4402", loaded "vaillant/0a.pmw.hwc.csv"
address 10: master #2
address 12: slave, scanned "MF=Vaillant;ID=PMW00;SW=0117;HW=4402"
address 13: master #12
address 15: slave #2, scanned "MF=Vaillant;ID=70000;SW=0613;HW=6903", loaded "vaillant/15.700.csv"
address 18: slave #12, scanned "MF=Vaillant;ID=V32;SW=0117;HW=9802"
address 26: slave, scanned "MF=Vaillant;ID=VR_71;SW=0104;HW=0503", loaded "vaillant/26.vr_71.csv"
address 31: master #8, ebusd
address 36: slave #8, ebusd
address 71: master #9
address 76: slave #9, scanned "MF=Vaillant;ID=VWZ00;SW=0517;HW=5103"
address f7: master #20
address fc: slave #20, scanned "MF=Vaillant;ID=PMW00;SW=0117;HW=4402"


