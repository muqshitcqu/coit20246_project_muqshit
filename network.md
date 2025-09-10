# 4.1 Network Design — Truelec (Sydney HQ + Newcastle Branch)

> My Student ID: 12308682 (IP addressing uses first octet **82** per spec).

## 4.1.1 Assumptions
- **Headquarters city**: Sydney (also my study campus), acting as the administrative and ICT hub for Truelec. 65 staff across project management, marketing, leadership and ICT.
- **Branch cities**: Perth, Canberra and Newcastle (design below focuses on **Newcastle** as the chosen branch). A new location in **Melbourne** is planned but out of scope for Part 1.
- **Service posture**: Most core services (web, HR, accounting, CRM, booking app) are hosted at HQ; branches rely on HQ over secure WAN.
- **Design philosophy**: Keep components covered in-unit, prioritise availability and straightforward justification; avoid exotic features beyond unit scope.
- **WAN**: Commercial business Internet at each site with static IPv4 and site-to-site VPN between sites.
- **Cabling**: Cat6 to desks; fibre or copper uplinks as supported by chosen switches.
- **Power**: Key racks protected by UPS at each site.
