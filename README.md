# LrPPG
Detailed implementation settings of LrPPG and MS-LrPPG

![Figure 1.](https://user-images.githubusercontent.com/3102772/28667872-f392f46a-72ff-11e7-935b-933d33011583.png)

The 22 unit local regions is defined based on the landmark index in “Csiro face analysis sdk" as follows: (1 37 69 2); (37 42 41 40 70 69); (40 28 31 70); (28 43 71 31); (43 48 47 46 72 71); (46 17 16 72); (2 69 73 4 3); (69 70 74 73); (70 30 34 74); (30 71 75 34); (71 72 76 75); (72 16 15 14 76); (4 73 49 5); (73 74 62 49); (74 34 63 62); (34 75 64 66); (75 76 55 64); (76 14 13 55); (5 49 68 7 6); (68 67 58 9 8 7); (67 66 11 10 9 58); (66 55 13 12 11).

![Figure 2.](https://user-images.githubusercontent.com/3102772/28667933-3915c0c6-7300-11e7-9f44-84a41a446d8b.png)


Finally, every 4 unit neighbor (Figure 6) REGION OF INTERESTs are combined to form 15 overlapped local REGION OF INTERESTs. As such, local region of interests are defined along the index of the 22 local unit regions. The details are listed as follows, (1 2 7 8); (2 3 8 9); (3 4 9 10); (4 5 10 11); (5 6 11 12); (7 8 13 14); (8 9 14 15); (9 10 15 16); (10 11 16 17); (11 12 17 18); (13 14 19); (14 15 19 20); (15 16 20 21); (16 17 21 22); (17 18 20).
