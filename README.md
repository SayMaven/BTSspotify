# BTSspotify

[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/SayMaven/BTSspotify/refs/heads/main/SayMavenContribution.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify"

# Copy text diatas dan paste di powershell
