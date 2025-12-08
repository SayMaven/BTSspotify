# BTSspotify
(SCRIPT1)



[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/SayMaven/BTSspotify/refs/heads/main/SayMavenContribution.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify"


(SCRIPT2)



iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SayMaven/BTSspotify/refs/heads/main/run.ps1)') } -new_theme"
# Copy text diatas dan paste di powershell
