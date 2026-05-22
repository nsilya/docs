Если PyCharm не запускается (ошибка Start Failed, stale lock):

pkill -f /app/pycharm/jbr/bin/java
rm -f ~/.var/app/com.jetbrains.PyCharm-Community/config/JetBrains/PyCharmCE2024.3/.lock

Потом запустить заново:
flatpak run com.jetbrains.PyCharm-Community
