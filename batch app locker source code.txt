@echo off
:unlocked
cls
set /p password= password: 
if %password% == (your password here) goto wow
if not %password% == (your password here) goto unlocked

:wow
(app directory here)