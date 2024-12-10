
# Notizen

- https://people.freebsd.org/~gallatin/talks/euro2019.pdf
- https://blog.jcole.us/2010/09/28/mysql-swap-insanity-and-the-numa-architecture/
- Der Cluster-index (primary key) bestimmt die Reihenfolge der Daten auf der Plate
- INFORMATION_SCHEMA will korrekte Daten zeigen und blockt daher Tables
-- viele Tabellen sind im SQL-Standard f
-- Abfrage auf einer Prod-DB kann einem daher die DB killen

- PERFORMANCE_SCHEMA wird nur alle 2 Minuten aktiviert und blockt nicht.

- Redolog 

- IO-Capa
-- 200 -> rotierende Platten
-- 8000 -> SSD
-- 80.000 -> NVME, aber nicht konfigurieren, weil so viel Commits noch werden

