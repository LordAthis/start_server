# start_server
Első lépések friss szerveren

# Első körben megnézzük, vannak-e frissítések a rendszerre, vagy az összetevőire, a későbbi problémák elkerülése végett!
# Telepítés elött ez mindig leyen az első!
sudo apt update
sudo apt upgrade -y


# Komolyabb frissítés esetén nem árt egy újraindítás, ha nem történt semmi, kihagyható!
sudo reboot


# A git feltelepítése, hogy minden mást lehessen a lehetőségekhez mérten legjobban automatizálni!
sudo apt-get install git -y
