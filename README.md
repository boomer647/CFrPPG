# LrPPG
Detailed implementation settings of CFrPPG

![Figure 1.](https://user-images.githubusercontent.com/3102772/28667872-f392f46a-72ff-11e7-935b-933d33011583.png)

The 3 local regions for template training are defined based on the landmark index in Figure 1 as follows: 
ROI.template(1).ptsIdx = [0 1 2 3 4 48 49 50 51 33 30 29 28 27 39 40 41 36];
ROI.template(2).ptsIdx = [27 28 29 30 33 51 62 63 54 12 13 14 15 16 45 46 47 42];
ROI.template(3).ptsIdx = [3 4 5 6 7 8 9 10 11 12 13 75 74 33 73 72];

The 9 local regions for feature construction are defined based on the landmark index in Figure 1 as follows: 
ROI.feature(1).ptsIdx = [0 1 2 3 72 73 33 30 29 28 27 39 40 41 36];
ROI.feature(2).ptsIdx = [36 68 72 73 33 74 75 71 45 46 47 42 27 39 40 41];
ROI.feature(3).ptsIdx = [27 28 29 30 33 74 75 13 14 15 16 45 46 47 42];
ROI.feature(4).ptsIdx = [1 2 3 4 48 61 62 33 30 69 68];
ROI.feature(5).ptsIdx = [68 72 48 61 62 63 54 75 71 70 30 69];
ROI.feature(6).ptsIdx = [30 33 51 62 63 54 12 13 14 15 71 70];
ROI.feature(7).ptsIdx = [3 4 5 6 7 8 66 62 33 73 72];
ROI.feature(8).ptsIdx = [72 48 50 6 7 8 9 10 55 54 75 74 33 73];
ROI.feature(9).ptsIdx = [33 62 57 8 9 10 11 12 13 75 74];


![Figure 2.](https://user-images.githubusercontent.com/3102772/28668093-e258c85e-7300-11e7-8c24-8700070140c6.png)


