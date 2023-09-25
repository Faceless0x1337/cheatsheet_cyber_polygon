Сканирование устройств ICS/SCADA
nmap -Pn -sT --scan-delay 1s --max-parallelism 1 \
    -p
    80,102,443,502,530,593,789,1089-1091,1911,1962,2222,2404,4000,4840,4843,4911,9600,19999,20000,20547,34962-34964,34980,44818,46823,46824,55000-55003 \
    <target>
Каждый из этих портов соответствует известному протоколу ICS SCADA.
More:
https://github.com/gnebbia/nmap_tutorial/blob/master/sections/ics_scada.md