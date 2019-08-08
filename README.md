# BoxStarterConfigs
Contains BoxStarter scripts for various machine configurations


Todo

Set-ExecutionPolicy RemoteSigned

. { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force

Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/arvesv/BoxStarterConfigs/master/U4BW-Escrow
