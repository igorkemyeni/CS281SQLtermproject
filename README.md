# CS281SQLtermproject
**Bilkent CS281 2021-2022 Fall Term Project**

This project is a term project of six students:
Merve Öztürk,
İsmail Görkem Yeni,
Bora Çetin,
Aysel Başa Bula,
Defne Tan,
Doruk Karakaş.

**Project Description**

You are going to implement a database system for a scooter renting company (like Martı) that rents scooters to customers. Users of this system are going to be customers, managers, repairers  and chargers. For each user, you should store a unique SSN, name and  surname. For customers, you should also store their address and phone number and credit card information. For each scooter, you should store a unique scooter id , battery level  and location. For each charger, you should store an area name and a number of scooters in his/her responsibility. Each scooter should be rented to exactly one customer and one customer can rent multiple scooters. Repairers can repair multiple scooters but each scooter can be repaired by one repairer. Each repairer gets multiple new parts from the warehouse to change broken parts. Parts are identified with a unique part number and has part name and quantity in stock. Parts can be either batteries or engines. Each repairer performs a fix operation on one scooter at a time. But the same scooter can be fixed by multiple repairers. Managers assign chargers to different areas. Each area can be assigned to multiple chargers but each charger can serve in one area only.  Chargers charge batteries in the company’s electric station. Each charger charge multiple batteries and any battery can be charged by any charger. Managers create discount offers for customers. Each created discount offer can be used by one customer once. 

**Functional Requirements To Be Implemented on SQL and PySimpleGUI Python API.**

●	Scooter Company:
○	Log in as a customer, Enter your address phone number and other relative information, View scooters available in his /her area. Rent a scooter that is available in the area, view discount offers available. use discount offers received by managers to rent the scooter (apply coupon concept) 
○	Log in as a worker, choose your type of worker(charger/repairer) for repairers view the damaged scooter in areas. Request multiple parts from the warehouse for scooters fix operations. Fix scooters in a certain area. For chargers, view the low battery scooters in a certain area. Request new charged batteries from the warehouse, charge different scooters. 
○	Log in as a manager, view repairers, chargers assigned areas and status (occupied/not occupied), add new areas to the system. Block certain users from renting scooters. Provide quantity of batteries and parts for the warehouse, create discount offers for customers. 



