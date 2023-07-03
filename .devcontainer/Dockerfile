FROM mcr.microsoft.com/windows/servercore:ltsc2019

RUN powershell -Command \
    Add-WindowsFeature Web-Server; \
    Remove-Item -Recurse C:\inetpub\wwwroot\*
